# Intercom binding for Xamarin.iOS

Intercom version [3.0.18](https://github.com/intercom/intercom-ios/blob/master/CHANGELOG.md)

## Initialize
```
using IntercomiOS;

public override bool FinishedLaunching(UIApplication application, NSDictionary launchOptions)
{
  Intercom.SetApiKey( INTERCOM_API_KEY, INTERCOM_APP_ID );
}
```

## Register Users
```
Intercom.RegisterUserWithUserId( USER_ID, EMAIL );
Intercom.RegisterUserWithUserId( USER_ID );
Intercom.RegisterUnidentifiedUser();
```

##Open Intercom Window

```
Intercom.PresentMessageComposer();
Intercom.PresentMessenger();
Intercom.PresentConversationList();
```
