source 'https://github.com/CocoaPods/Specs.git'

xcodeproj 'WordPress/WordPress.xcodeproj'

inhibit_all_warnings!

platform :ios, '7.0'
pod 'AFNetworking',	'~> 2.3.1'
pod 'Reachability',	'3.1.1'
pod 'NSURL+IDN', '0.3'
pod 'DTCoreText',   '1.6.13'
pod 'UIDeviceIdentifier', '~> 0.1'
pod 'SVProgressHUD', '~> 1.0'
pod 'wpxmlrpc', '~> 0.5'
pod 'WordPressApi', :git => 'https://github.com/wordpress-mobile/WordPressApi.git', :tag => '0.2.0'
pod 'NSObject-SafeExpectations', '0.0.2'
pod 'Mixpanel', '2.5.4'
pod 'CocoaLumberjack', '~>1.8.1'
pod 'NSLogger-CocoaLumberjack-connector', '~>1.3'
pod 'google-plus-ios-sdk', '~>1.5'
pod 'MGImageUtilities', :git => 'git://github.com/wordpress-mobile/MGImageUtilities.git', :branch => 'gifsupport'
pod 'EmailChecker', :podspec => 'https://raw.github.com/wordpress-mobile/EmailChecker/master/ios/EmailChecker.podspec'
pod 'CrashlyticsLumberjack', '~>1.0.0'
pod 'HockeySDK', '~>3.5.0'
pod 'Helpshift', '~>4.8.0'
pod 'CTAssetsPickerController', '~> 2.7.0'
pod 'WordPress-iOS-Shared', '0.1.3'
pod 'WordPress-iOS-Editor', :git => 'git://github.com/wordpress-mobile/WordPress-iOS-Editor', :commit => '39a0ddb1e0b2913d3002398f203fe0285e6c0d45'
pod 'WordPressCom-Stats-iOS', '0.1.4'
pod 'WordPressCom-Analytics-iOS', '0.0.12'
pod 'NSObject-SafeExpectations', '0.0.2'
pod 'SocketRocket', :git => 'https://github.com/jleandroperez/SocketRocket.git', :branch => 'master'
pod 'Simperium', '0.7.2'
pod 'Lookback', '0.6.5', :configurations => ['Release-Internal']
pod "AppbotX", :git => "https://github.com/wordpress-mobile/appbotx.git", :commit => "2a81f52278a549b5b7baa7d2ae66f12feecd7243"

target 'WordPressTodayWidget', :exclusive => true do
    pod 'WordPressCom-Stats-iOS', '0.1.4'
end

target :WordPressTest, :exclusive => true do
  pod 'OHHTTPStubs', '1.1.1'
  pod 'OCMock'
end

target 'UITests', :exclusive => true do
    pod 'KIF', :git => 'https://github.com/SergioEstevao/KIF.git', :branch => 'issue/470-AccessibilityIdentifier'
end
