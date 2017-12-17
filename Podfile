platform :ios, '11.0'

target 'CoinX' do
  use_frameworks!
  pod 'RxSwift',    '~> 4.0'
  pod 'RxCocoa',    '~> 4.0'
  pod 'RxAlamofire'
  pod 'RxRealm'
  pod 'RxSwiftExt'
  pod 'RxDataSources'

  target 'CoinXTests' do
    inherit! :search_paths
    pod 'RxBlocking', '~> 4.0'
    pod 'RxTest',     '~> 4.0'
  end

  target 'CoinXUITests' do
    inherit! :search_paths
  end

end
