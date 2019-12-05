# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'iOSPipeline' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for iOSPipeline
  pod 'SwiftLint', '~> 0.31.0'

end

post_install do |installer|
        installer.pods_project.build_configurations.each do |config|
            config.build_settings['CODE_SIGNING_REQUIRED'] = "NO"
            config.build_settings['CODE_SIGNING_ALLOWED'] = "NO"
        end
end
