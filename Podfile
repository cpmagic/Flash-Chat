# Uncomment the next line to define a global platform for your project
platform :ios, '9.0'

target 'Flash Chat' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Flash Chat
pod 'Firebase'
pod 'Firebase/Auth'
pod 'Firebase/Database'
pod 'SVProgressHUD'
pod 'ChameleonFramework'
# Pods for PodTest
pod 'Fabric', '~> 1.8.2'
pod 'Crashlytics', '~> 3.11.1'
end
post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['CLANG_WARN_DOCUMENTATION_COMMENTS'] = 'NO'
        end
    end
end


