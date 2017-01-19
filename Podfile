platform :ios, '7.0'

# Import CocoaPods sources
source 'https://github.com/CocoaPods/Specs.git'

#target 'ChatDemo-UI3.0' do

#link_with 'ChatDemo-UI3.0' 'YouliaoYouliao'

#pod 'HyphenateFullSDK'

#pod 'EaseUI', :git => 'https://github.com/easemob/easeui-ios-hyphenate-cocoapods.git'


def shared_pods
    pod 'HyphenateFullSDK'
end

def memory_pods
    pod 'PLeakSniffer'
    pod 'MLeaksFinder'
end

target 'ChatDemo-UI3.0' do
    shared_pods
    memory_pods
end

target 'YouliaoYouliao' do
    shared_pods
end
