# Cobrowse.io - MacOS SDK

Cobrowse.io is 100% free and easy to try out in your own apps. Please see full documentation at [https://docs.cobrowse.io](https://docs.cobrowse.io).

Try our **online demo** at the bottom of our homepage at <https://cobrowse.io/#tryit>.

## Installation

We recommend installing the Cobrowse.io MacOS SDK using Cocoapods. Add this to your Podfile:

```ruby
pod 'CobrowseIO', '~>2'
```

*Don't forget to run `pod repo update` then `pod install` after you've edited your Podfile.*

#### Swift
```swift
import CobrowseIO

func applicationDidFinishLaunching(_ aNotification: Notification)
{
    CobrowseIO.instance().license = "<your license key here>"
    CobrowseIO.instance().start()
}
```

#### Objective C
```objective-c
@import CobrowseIO;

- (void)applicationDidFinishLaunching:(NSNotification *)notification
{
    CobrowseIO.instance.license = @"<your license key here>";
    [CobrowseIO.instance start];
}
```

### Add your License Key

Please register an account and generate your free License Key at <https://cobrowse.io/dashboard/settings>.

This will associate sessions from your mobile app with your Cobrowse account.

## Try it out

Once you have your app running, navigate to https://cobrowse.io/dashboard to see your device listed. You can click the "Connect" button to initiate a Cobrowse session!

## Optional features

[Identify your devices](https://docs.cobrowse.io/sdk-features/identify-your-devices)

[Use 6-digit codes](https://docs.cobrowse.io/sdk-features/6-digit-codes)

[Redact sensitive data](https://docs.cobrowse.io/sdk-features/redact-sensitive-data)

[Customize the interface](https://docs.cobrowse.io/sdk-features/customize-the-interface)

[Initiate sessions with push](https://docs.cobrowse.io/sdk-features/initiate-sessions-with-push)

[Full device capabilities](https://docs.cobrowse.io/sdk-features/full-device-capabilities)

[Advanced features](https://docs.cobrowse.io/sdk-features/advanced-features)

## Questions?
Any questions at all? Please email us directly at [hello@cobrowse.io](mailto:hello@cobrowse.io).

## Requirements

* MacOS 10.10 or later
