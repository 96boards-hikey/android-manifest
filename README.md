This is a local android manifest repository. It is supposed to be used with android.googlesource.com to get full AOSP code stack.

# Usage
```
repo init -u https://android.googlesource.com/platform/manifest -b master
git clone https://github.com/96boards-hikey/android-manifest.git -b hikey970_v1.0-rebase-0402 .repo/local_manifests
repo sync
```

# More information
For more information, see http://www.androidenea.com/2010/06/using-localmanifestxml-file-in-repo-to.html

