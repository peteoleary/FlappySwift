# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'FlappyBird' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  # use_frameworks!

  # Pods for FlappyBird
  pod 'KISSmetrics-iOS-SDK', :git => 'https://github.com/peteoleary/KISSmetrics-iOS-SDK.git'

  target 'FlappyBirdTests' do
    inherit! :search_paths
    # Pods for testing
  end

end

plugin 'cocoapods-keys', {
    :project => "FlappyBird",
    :keys => [
    "KMTrackingAPIKey"
    ]}
