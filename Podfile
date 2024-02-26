# Uncomment the next line to define a global platform for your project
source 'https://github.com/CocoaPods/Specs.git'
$iOSVersion = '14.0'
platform :ios, $iOSVersion
# ignore all warnings from all pods
inhibit_all_warnings!
# def shared_pods_with_extensions
#     pod 'Alamofire', '~> 4.7'
#     pod 'CryptoSwift', '~> 0.7.2'
#     pod 'KeychainAccess'
#     pod 'Moya', '~> 13.0.0'
#     pod 'TrustKit'
# end
# def aion_SDK_pods
  
#   pod 'DaonFrameworks', :git => 'https://aiondevsupport:380bcc8ca003215391bc6f8c997250909709697a@github.com/aiondigital/daon-framework', :tag => '1.7.1'
# #pod 'DaonFrameworks', :git => "https://aiondevsupport:380bcc8ca003215391bc6f8c997250909709697a@github.com/aiondigital/daon-framework"
#   pod 'AFNetworking', '~> 4.0'
#   pod 'MBProgressHUD', '~> 1.2.0'
#   pod 'JWT', '~> 2.2.0'
#   pod 'FirebaseDatabase'
#   pod 'FirebaseAppCheck'
# end
 
target 'testingPods' do
    # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
    use_frameworks!
    # shared_pods_with_extensions
    # aion_SDK_pods
    # pod 'AlamofireImage', '~> 3.5'
    # pod 'SwiftMessages', :git => 'https://github.com/SwiftKickMobile/SwiftMessages.git'
    # pod 'SwiftLint'
    # pod 'RxSwift', '6.0.0-rc.1'
    # pod 'RxCocoa', '6.0.0-rc.1'
    # pod 'Reusable'
    # pod 'IQKeyboardManagerSwift'
    # pod 'FAPanels'
    # pod 'XLPagerTabStrip', :git => 'https://github.com/falsharabati/XLPagerTabStrip.git'
    # pod 'SkeletonView', '~> 1.7.0'
    # pod 'Swinject', '~> 2.7.1'
    # pod 'SwinjectStoryboard', :git => 'https://github.com/Swinject/SwinjectStoryboard.git', :commit => '0ca45c83a8aa398c153d8a036c95abb4343cfa0c'
    # pod 'FSPagerView'
    # pod 'ARNTransitionAnimator'
    # pod 'SQLite.swift', '~> 0.12.0'
    pod 'FirebaseMessaging'
    pod 'Firebase/Analytics'
    pod 'Firebase/Crashlytics'
    pod 'FirebaseFirestore'
    pod 'GoogleMLKit/Translate'
    # pod 'AMPopTip'
    # pod 'Toucan'
    # pod 'SnapKit'
    # pod 'STULabelSwift', '~> 0.8.11'
    # pod 'Wormholy', :configurations => ['Debug', 'ISD']
    # # For security
    # pod 'IOSSecuritySuite'
 
    # #For Msa3ed
    # pod 'URLEmbeddedView'
    # pod 'lottie-ios' , '2.1.5'
    # pod "YoutubePlayer-in-WKWebView", "~> 0.3.0"
    pod 'GoogleMaps'
    # pod 'Charts'
 
    # target 'BoubyanTests' do
    #     inherit! :search_paths
    #     #for unit test
    #     pod 'SwiftyMocky'
    # end
end
 
 
# target 'watch Extension' do
#     use_frameworks!
#     platform :watchos, '3.2'
#     shared_pods_with_extensions
# end
 
# target 'BoubyanWidgetExtension' do
#     use_frameworks!
#     shared_pods_with_extensions
#     pod 'SQLite.swift', '~> 0.12.0'
# end
 
# target 'BoubyanWidgetIntentHandler' do
#     use_frameworks!
#     shared_pods_with_extensions
# end

# # Workaround for Cocoapods issue #7606 - XLPagerTabStrip with IBDesignable
# post_install do |installer|
#     installer.pods_project.build_configurations.each do |config|
#         config.build_settings.delete('CODE_SIGNING_ALLOWED')
#         config.build_settings.delete('CODE_SIGNING_REQUIRED')
#         config.build_settings['GCC_WARN_INHIBIT_ALL_WARNINGS'] = "YES"
#         config.build_settings['CODE_SIGNING_ALLOWED'] = 'NO'
#     end
    
#     # Xcode 13 minimum IPHONEOS_DEPLOYMENT_TARGET is 13.0
#     installer.pods_project.targets.each do |t|
#       t.build_configurations.each do |bc|
#           bc.build_settings['ONLY_ACTIVE_ARCH'] = 'NO'
#           bc.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = $iOSVersion
#       end
#     end
#     installer.pods_project.targets.each do |target|
#       target.build_configurations.each do |config|
#         xcconfig_path = config.base_configuration_reference.real_path
#         xcconfig = File.read(xcconfig_path)
#         xcconfig_mod = xcconfig.gsub(/DT_TOOLCHAIN_DIR/, "TOOLCHAIN_DIR")
#         File.open(xcconfig_path, "w") { |file| file << xcconfig_mod }
#       end 
#   end