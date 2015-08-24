# Podfile for GH issue https://github.com/bitstadium/HockeySDK-iOS/issues/190
# Uncomment this line to define a global platform for your project
platform :ios, '7.0'

# If HockeySDK is applied in this main part it also flows down to the test target, causing
# the project to fail to link. HockeySDK and OHHTTPStubs don't seem to get along...
pod 'HockeySDK', '3.7.2'

target 'HelloWorld' do
    # Moving the definition of the pod to here made everything happy (note you'll need to
    # update the project config to remove the custom configuration set to make pod install
    # work properly)
    #pod 'HockeySDK', '3.7.2'
end

target 'HelloWorldTests' do
    pod 'OHHTTPStubs', '~> 4.1.0'
end

