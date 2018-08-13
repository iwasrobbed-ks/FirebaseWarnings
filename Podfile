# frozen_string_literal: true

platform :ios, '10.0'

# Ignore all warnings from all pods
inhibit_all_warnings!

# Use frameworks for Swift
use_frameworks!

workspace 'FirebaseWarnings.xcworkspace'

target 'FirebaseWarnings' do
  
  pod 'Firebase', '~> 5.5.0', subspecs: %w[
    Analytics
    Messaging
  ]
  
  pod 'Google-Mobile-Ads-SDK', '~> 7.31.0'
  
end