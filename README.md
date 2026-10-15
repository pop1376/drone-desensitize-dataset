# 无人机脱敏检测训练数据集

无人机视角下行人 / 人脸 / 车辆 / 车牌检测与脱敏模型训练数据集。共 **22 个压缩包、约 7.4 GB**，全部托管于本仓库 Release v1.0，点击即下载，无需登录。

## 一、强相关（无人机/航拍/遥感/高空俯视，视角直接匹配，10 个）

| 文件名 | 大小 | 内容 | 下载 |
|---|--:|---|---|
| AI-TOD_code.zip | 2.0 MB | AI-TOD aitodtoolkit 工具 | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/AI-TOD_code.zip) |
| MOBDrone.zip | 8.5 MB | MOBDrone 无人机搜救数据集标注 | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/MOBDrone.zip) |
| AI-TOD_annotations_v2.zip | 11.3 MB | AI-TOD 无人机航拍微小目标 v2 标注 | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/AI-TOD_annotations_v2.zip) |
| HRRSD.zip | 14.4 MB | HRRSD 遥感/航空车辆标注 | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/HRRSD.zip) |
| CNRPark_patches.zip | 34.9 MB | CNRPark 高位俯视停车场 patch（busy/free） | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/CNRPark_patches.zip) |
| AI-TOD_annotations_v1.zip | 35.2 MB | AI-TOD 无人机航拍微小目标 v1 标注 | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/AI-TOD_annotations_v1.zip) |
| AerialMPT.zip | 76.9 MB | 高空航拍行人追踪数据集，DLR发布 | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/AerialMPT.zip) |
| CNRPark_EXT_patches.zip | 429 MB | CNRPark-EXT 高位俯视停车场扩展 patch | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/CNRPark_EXT_patches.zip) |
| HIT-UAV.zip | 793 MB | 无人机红外热成像，昼夜多视角 | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/HIT-UAV.zip) |
| ITCVD.zip | 1217 MB | 高分辨率机载航拍车辆（约6000×4000），有效166张 | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/ITCVD.zip) |

## 二、弱相关（地面/卡口/街景/室内监控/平视，用于车牌·人脸迁移，12 个）

| 文件名 | 大小 | 内容 | 下载 |
|---|--:|---|---|
| WIDER_FACE_annotations.zip | 3.4 MB | WIDER FACE 通用人脸 划分与标注 | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/WIDER_FACE_annotations.zip) |
| UC3M_LP.zip | 10.6 MB | UC3M-LP 街景西班牙车牌标注样例（5图） | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/UC3M_LP.zip) |
| keremberke_valid.zip | 42.8 MB | 街景车牌检测 valid 子集 | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/keremberke_valid.zip) |
| CrowdHuman_annotations.zip | 98.6 MB | CrowdHuman 街景/监控行人标注 | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/CrowdHuman_annotations.zip) |
| keremberke_train.zip | 156 MB | 街景车牌检测 train 子集 | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/keremberke_train.zip) |
| Iranis_dataset.zip | 156 MB | 伊朗车牌字符，83844张裁剪字符 | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/Iranis_dataset.zip) |
| openalpr_benchmarks.zip | 208 MB | OpenALPR 卡口/街景基准（US/EU/BR） | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/openalpr_benchmarks.zip) |
| WIDER_FACE_val.zip | 346 MB | WIDER FACE val，3226图（平视） | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/WIDER_FACE_val.zip) |
| ofeeler_LPR.zip | 394 MB | 整车图 + 车牌裁剪图（3977+3977） | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/ofeeler_LPR.zip) |
| SCUT_HEAD_hf.zip | 954 MB | SCUT-HEAD 室内监控人头（教室高位俯视） | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/SCUT_HEAD_hf.zip) |
| FDDB.zip | 1084 MB | FDDB 通用人脸（新闻/照片，平视） | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/FDDB.zip) |
| ccpd_subset_30k.zip | 1531 MB | 中国城市车牌（地面平视），30000张 | [下载](https://github.com/pop1376/drone-desensitize-dataset/releases/download/v1.0/ccpd_subset_30k.zip) |

## 三、使用说明

1. **标注缺图类**：AI-TOD、HRRSD、CrowdHuman、MOBDrone、UC3M-LP 仅含标注文件，图像需按各包内 README 另行下载，不可直接用于训练。
2. **许可**：多为学术研究用途（部分 CC BY-NC-SA）；人脸、车牌属敏感个人信息，仅在授权范围内以脱敏为目的使用，勿二次传播。
3. **本次未上传**（受单文件 2GB / 网络限制，需要可随时补传）：`WIDER_FACE_train.zip`、`WIDER_FACE_test.zip`、`VEDAI.zip`（分卷共约 2.7GB）。
4. 类别建议统一映射为 `person / face / car / license_plate` 四类后再训练。
