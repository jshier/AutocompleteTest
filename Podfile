platform :ios, '12.0'

project 'AutocompleteTest', 'Testing' => :debug

pod 'SwiftLint'

target 'AutocompleteTest' do
  use_frameworks!
  pod 'Alamofire', '~> 5.0.0-beta.5'

  target 'AutocompleteTestTests' do
    inherit! :search_paths

    pod 'OHHTTPStubs/Swift'
  end

end
