ARCHS := arm64
TARGET := iphone:clang:latest:15.0

include $(THEOS)/makefiles/common.mk

LIBRARY_NAME = CAHighFPS
CAHighFPS_FILES = Tweak.m
CAHighFPS_CFLAGS = -fobjc-arc -fmodules
CAHighFPS_FRAMEWORKS = Foundation QuartzCore
CAHighFPS_INSTALL_PATH = /Applications/Geode.app/Frameworks

include $(THEOS_MAKE_PATH)/library.mk
