# Uncomment the next line to define a global platform for your project
platform :ios, '11.0'



target 'Platform' do
  use_frameworks!

  pod 'Alamofire', '~> 5'
  pod 'AlamofireImage', '~> 4.1'

  pod 'AnyFormatKit', '~> 2.5.1'
  pod 'CocoaLumberjack/Swift', '~> 3.7.4'
  pod 'DatePickerDialog', '4.0'
  pod 'Firebase/AnalyticsWithoutAdIdSupport'
  pod 'Firebase/Messaging'
  pod 'Firebase/Crashlytics'
  pod 'FloatRatingView', '2.0'
  pod 'FSCalendar', '~> 2.7.9'
  pod 'GoogleMaps'
  pod 'GooglePlaces'
  pod 'IBLocalizable', '1.3.0'
  pod 'ObjectMapper', '3.3.0'
  pod 'paper-onboarding', '6.1.3'
  pod 'R.swift', '6.1.0'
  pod 'RxAlamofire', '6.1.1'
  pod 'RxKeyboard', '~> 2.0.0'
  pod 'RxSwift', '~> 6.5.0'

  pod 'SegueKit', :git => 'https://github.com/langyanduan/SegueKit'
  pod 'Socket.IO-Client-Swift', '~> 13.1.3'
  pod 'Swinject', '~> 2.4.0'
  pod 'SwiftLocation', '~> 3.2.3'
  pod 'XLPagerTabStrip', '~> 9.0.0'
  pod 'MaterialComponents/ActivityIndicator', '124.2.0'

  target 'ClientApp' do
    use_frameworks!

    pod 'Alamofire', '~> 5'
    pod 'AlamofireImage', '~> 4.1'

    pod 'AnyFormatKit', '~> 2.5.1'
    pod 'CocoaLumberjack/Swift', '~> 3.7.4'
    pod 'DatePickerDialog', '4.0'
    pod 'Firebase/AnalyticsWithoutAdIdSupport'
    pod 'Firebase/Messaging'
    pod 'Firebase/Crashlytics'
    pod 'FloatRatingView', '2.0'
    pod 'FSCalendar', '~> 2.7.9'
    pod 'GoogleMaps'
    pod 'GooglePlaces'
    pod 'IBLocalizable', '1.3.0'
    pod 'ObjectMapper', '3.3.0'
    pod 'paper-onboarding', '6.1.3'
    pod 'R.swift', '6.1.0'
    pod 'RxAlamofire', '6.1.1'
    pod 'RxKeyboard', '~> 2.0.0'
    pod 'RxSwift', '~> 6.5.0'

    pod 'SegueKit', :git => 'https://github.com/langyanduan/SegueKit'
    pod 'Socket.IO-Client-Swift', '~> 13.1.3'
    pod 'Swinject', '~> 2.4.0'
    pod 'SwiftLocation', '~> 3.2.3'
    pod 'XLPagerTabStrip', '~> 9.0.0'
    pod 'SnapKit', '~> 5.0.0'
    
    pod 'TinkoffASDKCore', '~> 2.4.3'
    pod 'TinkoffASDKUI', '~> 2.4.3'
    pod 'SimpleCheckbox'
    pod 'MaterialComponents/ActivityIndicator', '124.2.0'
  end

  target 'EmployerApp' do
    use_frameworks!

    pod 'Alamofire', '~> 5'
    pod 'AlamofireImage', '~> 4.1'

    pod 'AnyFormatKit', '2.5.1'
    pod 'CocoaLumberjack/Swift', '~> 3.7.4'
    pod 'DatePickerDialog', '4.0'
    pod 'Firebase/AnalyticsWithoutAdIdSupport'
    pod 'Firebase/Messaging'
    pod 'Firebase/Crashlytics'
    pod 'FloatRatingView', '2.0'
    pod 'FSCalendar', '~> 2.7.9'
    pod 'GoogleMaps'
    pod 'GooglePlaces'
    pod 'IBLocalizable', '1.3.0'
    pod 'ObjectMapper', '3.3.0'
    pod 'paper-onboarding', '6.1.3'
    pod 'R.swift', '6.1.0'
    pod 'RxAlamofire', '6.1.1'
    pod 'RxKeyboard', '~> 2.0.0'
    pod 'RxSwift', '~> 6.5.0'
    pod 'SegueKit', :git => 'https://github.com/langyanduan/SegueKit'
    pod 'Socket.IO-Client-Swift', '~> 13.1.3'
    pod 'Swinject', '~> 2.4.0'
    pod 'SwiftLocation', '~> 3.2.3'
    pod 'XLPagerTabStrip', '~> 9.0.0'
    pod 'SnapKit', '~> 5.0.0'
    pod 'MaterialComponents/ActivityIndicator', '124.2.0'


  end
  
  post_install do |installer|
      installer.pods_project.targets.each do |target|
          target.build_configurations.each do |config|
              if ['paper-onboarding'].include?(target.name)
                  config.build_settings['SWIFT_VERSION'] = '4.2'
              end
          end

          if ['FloatRatingView'].include? target.name
            target.build_configurations.each do |config|
              config.build_settings['SWIFT_VERSION'] = '4.0'
            end
          end
      end
  end


end
