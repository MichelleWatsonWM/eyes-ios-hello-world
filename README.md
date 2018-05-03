# eyes-ios-hello-world
Installation with CocoaPods
CocoaPods is a dependency manager for Objective-C, which automates and simplifies the process of using 3rd-party libraries like AFNetworking in your projects. See the "Getting Started" guide for more information. You can install it with the following command:

$ gem install cocoapods
CocoaPods 0.39.0+ is required to build AFNetworking 3.0.0+.

Podfile
To integrate AFNetworking into your Xcode project using CocoaPods, specify it in your Podfile:

source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'

target 'TargetName' do
pod 'AFNetworking', '~> 3.0'
end
Then, run the following command:

$ pod install
