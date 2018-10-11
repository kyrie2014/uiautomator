# uiautomator
doing uitest by uiautomator ,include usages of python API and java API
GMS版本自动化测试疑难问题解决：
1. Google引导界面设置问题
解决办法：
adb shell settings put secure user_setup_complete 1
adb shell settings put global device_provisioned 1
2. Google Play保护弹框问题
解决办法：
adb shell settings put secure package_verifier_user_consent -1
adb shell settings put global package_verifier_enable 0
adb shell settings put global upload_apk_enable 0
