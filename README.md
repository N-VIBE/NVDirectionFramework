# N-Vibe Direction SDK for iOS [0.2.3]

NVDirectionKit is a kit to get route from N-Vibe.

## Get started

To use NVDirectionKit, some requirements are needed.

   - ## Installation

     - ## Dependency

       NVDirectionKit is only available via Cocoapods for now.

       ```ruby
       platform :ios, '13.0'

       target 'TargetNameForYourApp' do
         use_frameworks!
         
         pod 'NVDirectionKit', '~> 0.2.3'
       end
       ```
     - ## Token
       
       You need one token with the key NVibeAPIAccessToken to get the route from the N-Vibe calculator.

       ```
       <key>NVibeAPIAccessToken</key>
       <string>YourToken</string>
       ```

     - ## Http request permission
    
       To use NVDirectionKit, you need also a temporary permission to allow http request, this will change later.

       To add this permission, you need to add this key in your Info.plist.

       ```
       <key>NSAppTransportSecurity</key>
       <dict>
         <key>NSAllowsArbitraryLoads</key>
         <true/>
       </dict>
       ```
