# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'FindDust' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!
  pod 'SwiftLint', '~> 0.27'
  pod 'Then', '~> 2.4.0'
  pod 'SwiftGen'
  # Pods for FindDust

  def testing_pods
    pod 'Quick', '~> 1.3'
    pod 'Nimble', '~> 7.3'
  end
  target 'FindDustTests' do
    inherit! :search_paths
    testing_pods
    # Pods for testing
  end

  target 'FindDustUITests' do
    inherit! :search_paths
    # Pods for testing
  end

end
