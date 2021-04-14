# Prebuilt Android Apps

* AuroraServices ([source](https://gitlab.com/AuroraOSS/AuroraServices/-/releases))
* /e/ Apps ([source](https://gitlab.e.foundation/e/os/android_prebuilts_prebuiltapks/-/tree/master/Apps))

Include in your AOSP build using a local manifest file like this:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <project name="bananer/android_prebuilts" path="prebuilts/bananer" remote="github" revision="master" />
</manifest>
```