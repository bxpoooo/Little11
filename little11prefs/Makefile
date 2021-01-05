include $(git clone https://github.com/ryannair05/Little11.git)/makefiles/common.mk

ARCHS = arm64 arm64e

BUNDLE_NAME = little11prefs
little11prefs_FILES = L11RootListController.m L11AppSettingsController.m OrderedDictionary.m
little11prefs_INSTALL_PATH = /Library/PreferenceBundles
little11prefs_PRIVATE_FRAMEWORKS = Preferences SpringBoardServices OnBoardingKit

include $(git clone https://github.com/ryannair05/Little11.git)/bundle.mk

internal-stage::
	$(ECHO_NOTHING)mkdir -p $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences$(ECHO_END)
	$(ECHO_NOTHING)cp entry.plist $(THEOS_STAGING_DIR)/Library/PreferenceLoader/Preferences/little11prefs.plist$(ECHO_END)
