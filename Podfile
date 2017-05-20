# Uncomment this line to define a global platform for your project
platform :ios, '9.0'

target 'MyDiary' do
  # Uncomment this line if you're using Swift
  use_frameworks!

  pod 'DynamicColor', '~> 3.0'
  pod 'SnapKit', '~> 3.0'
  pod 'ObjectMapper', '~> 2.0'
  pod 'RealmSwift'

  # Beta dependencies for Swift 3.0
  pod 'Moya-ObjectMapper/RxSwift', '~> 2.3'
  pod 'Moya',       '~> 8.0'
  pod 'RxSwift',    '~> 3.4'
  pod 'RxCocoa',    '~> 3.0'
  # pod 'Moya/RxSwift'

  def testing_pods
    pod 'Quick'
    pod 'Nimble'
  end

  target 'MyDiaryTests' do
    inherit! :search_paths
    testing_pods
  end

  target 'MyDiaryUITests' do
    inherit! :search_paths
    testing_pods
  end
end
