# N-Vibe Direction SDK for iOS [0.5.0]

NVDirectionKit is a kit to get route from N-Vibe.

## Get started

To use NVDirectionKit, some requirements are needed.

## Dependency

NVDirectionKit is available from Cocoapods. Add it to your `podfile`:

```ruby
platform :ios, '13.0'

target 'TargetNameForYourApp' do
use_frameworks!

pod 'NVDirectionKit', '~> 0.5.0'
end
```

Don't forget to install your pod by running:

```ruby
pod install --repo-update
```

## Token
  
You need a token with the key `NVibeAPIAccessToken` to receive route from the framework. You can add it in your `Info.plist`.

```
<key>NVibeAPIAccessToken</key>
<string>YourToken</string>
```

## Http request permission

To use NVDirectionKit, you need also a temporary permission to allow http request, this will change later. You can add it in your `Info.plist`.

```
<key>NSAppTransportSecurity</key>
<dict>
    <key>NSAllowsArbitraryLoads</key>
    <true/>
</dict>
```
