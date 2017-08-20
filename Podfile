# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'


def rx_swift
    pod 'RxSwift', '~> 3.0'
end

def firebase
    pod 'Firebase/Core'
    pod 'Firebase'
    pod 'Firebase/Auth'
    pod 'Firebase/Database'
    pod 'Firebase/Storage'
end


target 'RxFirebase' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!
  rx_swift
  firebase
  # Pods for RxFirebase

  target 'RxFirebaseTests' do
    inherit! :search_paths
    # Pods for testing
  end
  
  

end

