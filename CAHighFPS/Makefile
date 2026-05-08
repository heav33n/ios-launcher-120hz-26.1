$THEOS/toolchain/linux/iphone/bin/clang \
    -target arm64-apple-ios15.0 \
    -isysroot $THEOS/sdks/iPhoneOS16.5.sdk \
    -shared \
    -fmodules \
    -fobjc-arc \
    -framework Foundation \
    -framework QuartzCore \
    -o CAHighFPS.dylib \
    Tweak.m

ldid -S CAHighFPS.dylib
