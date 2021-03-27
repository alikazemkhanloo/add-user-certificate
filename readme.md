# what is it?
This will unpack an `apk` file, and update its manifest file so it will accept user certificates in ssl connections, and of course, rebuild it.

# how to use it?
0. take a deep breath.
1. [create a keystore](https://www.google.com/search?q=create+new+keystore+cli) for signing the app and put it beside `add-certificate` file.
2. update pass and path for keystore inside `add-certificate` file.
3. add path to this repo to your `PATH` env var.
4. use `add-certificate com.org.app.apk` to generate new apk.
5. smile :)

# requirements?
1. [apktool](https://ibotpeaches.github.io/Apktool/)
2. `apksigner` and `zipalign` from android build-tools

# supported platforms?
Not Windows!

# why did I create this?
I don't know.
