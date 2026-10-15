# 无人机脱敏检测数据集

无人机视角下行人 / 人脸 / 车辆 / 车牌检测与脱敏模型训练数据集，共 25 个数据集；因 GitHub 单文件 2GB 限制，VEDAI 拆为 2 个分卷，Release 共 **26 个文件、约 13.2 GB**。

## 下载（Release v1.0）

### 01 无人机原生
| 文件 | 大小 | 下载 |
| --- | --- | --- |
| `AerialMPT.zip` | 76.9 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/AerialMPT.zip) |
| `HIT-UAV.zip` | 792.7 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/HIT-UAV.zip) |
| `ITCVD.zip` | 1.19 GB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/ITCVD.zip) |
| `VEDAI.zip.001` | 0 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/VEDAI.zip.001) |
| `VEDAI.zip.002` | 0 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/VEDAI.zip.002) |

### 02 车牌
| 文件 | 大小 | 下载 |
| --- | --- | --- |
| `ccpd_subset_30k.zip` | 1.5 GB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/ccpd_subset_30k.zip) |
| `Iranis_dataset.zip` | 155.9 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/Iranis_dataset.zip) |
| `keremberke_train.zip` | 155.7 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/keremberke_train.zip) |
| `keremberke_valid.zip` | 42.8 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/keremberke_valid.zip) |
| `ofeeler_LPR.zip` | 394.2 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/ofeeler_LPR.zip) |
| `openalpr_benchmarks.zip` | 207.6 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/openalpr_benchmarks.zip) |

### 03 人脸人头
| 文件 | 大小 | 下载 |
| --- | --- | --- |
| `FDDB.zip` | 1.06 GB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/FDDB.zip) |
| `SCUT_HEAD_hf.zip` | 954 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/SCUT_HEAD_hf.zip) |
| `WIDER_FACE_annotations.zip` | 3.4 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/WIDER_FACE_annotations.zip) |
| `WIDER_FACE_test.zip` | 0 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/WIDER_FACE_test.zip) |
| `WIDER_FACE_train.zip` | 0 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/WIDER_FACE_train.zip) |
| `WIDER_FACE_val.zip` | 345.9 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/WIDER_FACE_val.zip) |

### 04 俯视监控
| 文件 | 大小 | 下载 |
| --- | --- | --- |
| `CNRPark_EXT_patches.zip` | 428.7 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/CNRPark_EXT_patches.zip) |
| `CNRPark_patches.zip` | 34.9 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/CNRPark_patches.zip) |

### 05 仅标注_缺图（需补图像）
| 文件 | 大小 | 下载 |
| --- | --- | --- |
| `AI-TOD_annotations_v1.zip` | 35.2 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/AI-TOD_annotations_v1.zip) |
| `AI-TOD_annotations_v2.zip` | 11.3 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/AI-TOD_annotations_v2.zip) |
| `AI-TOD_code.zip` | 2 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/AI-TOD_code.zip) |
| `CrowdHuman_annotations.zip` | 98.6 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/CrowdHuman_annotations.zip) |
| `HRRSD.zip` | 14.4 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/HRRSD.zip) |
| `MOBDrone.zip` | 8.5 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/MOBDrone.zip) |
| `UC3M_LP.zip` | 10.6 MB | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/UC3M_LP.zip) |

## VEDAI 分卷合并（重要）
VEDAI 原始 2.69GB 超过 GitHub 单文件上限，拆为 `VEDAI.zip.001`（1.5GB）与 `VEDAI.zip.002`（1.19GB）。两个文件都下载后，在同目录合并为 `VEDAI.zip`：

**Windows CMD：**
```cmd
copy /b VEDAI.zip.001+VEDAI.zip.002 VEDAI.zip
```
**PowerShell：**
```powershell
$out=[IO.File]::Create('VEDAI.zip'); Get-ChildItem 'VEDAI.zip.0*' | Sort-Object Name | ForEach-Object { $i=[IO.File]::OpenRead($_.FullName); $i.CopyTo($out); $i.Close() }; $out.Close()
```
**macOS / Linux：**
```bash
cat VEDAI.zip.001 VEDAI.zip.002 > VEDAI.zip
```
合并后校验 SHA256 应为：`FC671341888EA7E263E0A0AB1B23CB1F91118AD641E84BB1C090A87FBB1C1C05`

## 说明
- `05_仅标注_缺图` 目录仅含标注文件，图像需另行下载。
- 各数据集内容、标注格式与来源见包内说明；均为学术研究用途，敏感数据（人脸/车牌）请合规使用。