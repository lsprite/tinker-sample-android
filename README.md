## 说明
build.gradle里本处使用的是VERSION_NAME来当tinkerId,详情见build.gradle文件中的设置

修改tinkerOldApkPath与tinkerApplyResourcePath，在Terminal里输入gradlew tinkerPatchDebug或gradlew tinkerPatchRelease生成补丁

若使用proguard混淆，需要保持mapping.txt文件,并设置tinkerApplyMappingPath的路径后生成补丁

## 其他
参考 https://github.com/Tencent/tinker/wiki/Tinker-接入指南


