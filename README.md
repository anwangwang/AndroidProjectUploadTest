# AndroidProjectUploadTest
测试AS上传android项目到GitHub上时需要忽略的文件
# 测试结果
在as中项目原有的.gitignore文件中加入
```
# Built application files
*.apk
*.ap_

# Files for the ART/Dalvik VM
*.dex

# Java class files
*.class

# Generated files
bin/
gen/
out/

# Gradle files
.gradle/
build/

# Local configuration file (sdk path, etc)
local.properties

# Proguard folder generated by Eclipse
proguard/

# Log Files
*.log

# Android Studio Navigation editor temp files
.navigation/

# Android Studio captures folder
captures/

# Intellij
*.iml
*.idea

# Keystore files
*.jks

```
或者
```
*.iml
*.idea
.gradle
/local.properties
/.idea/workspace.xml
/.idea/libraries
.DS_Store
/build
/captures
.externalNativeBuild

```
可以使as上的android项目既精简，又不会影响到项目的运行
