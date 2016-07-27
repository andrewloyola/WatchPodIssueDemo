source 'https://github.com/CocoaPods/Specs.git'

use_frameworks!

def shared_pods_watch
    pod 'Alamofire', :git => 'https://github.com/Alamofire/Alamofire.git', :branch => 'swift2.3'
    pod 'SwiftDate'
    pod 'SwiftyJSON'
end

def shared_pods
    
    #Logging
    pod 'CocoaLumberjack/Swift'
end


target 'watchapp Extension' do
    platform :watchos, '2.0'
    shared_pods_watch
    shared_pods
end

target 'WatchPodIssue' do
    platform :ios, '9.0'
    
    shared_pods
end
