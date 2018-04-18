# Sorry. I'm editing this repository.



# Shop View
 [![API](https://img.shields.io/badge/API-16%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=16) [![Hex.pm](https://img.shields.io/hexpm/l/plug.svg?maxAge=2592000)](http://www.apache.org/licenses/LICENSE-2.0)

Shop View android guide app with Kotlin and Firebase


[FULL VIDEO]

## Features used in app

#### [Back-end]

* Get current location fast once(GPS[lat, lng]) - LocationListener(requestSingleUpdate)

[GIF SNAP VIDEO]

* Address Translation - Geocoder API
* Modify current location - Google Map API
* Mark in shop location and current location - Google Map API
* [Firebase Realtime Database](https://firebase.google.com/docs/database/) - write/read data to database
* Calculation to distance - distanceTo()
* Sort by distance from current location - sortWith()
* In-app purchase - [Google Play In-app Billing API v3 Library](https://github.com/anjlab/android-inapp-billing-v3)
* (Firebase AdMob)
* (Firebase Auth)
* (Firebase Analytics)

<h4>[UI]</h4>

* ViewPager
* [Firebase UI - FirebaseRecyclerView](https://github.com/firebase/FirebaseUI-Android/blob/master/database/README.md)
* Button click animation - scale
* Activity transition animation - slide
* CardView - product list
* [Anko Commons - Custom Dialog](https://github.com/Kotlin/anko/wiki/Anko-Commons-%E2%80%93-Dialogs)
* Android Extension - inflate
* Custom Number Picker
* [Picasso - Image Library](https://github.com/square/picasso)



<h4>Code Index</h4> 

|Feature|Code Location|
|---|---|
| Get current location fast once(GPS)      | ui/NearMeActivity.kt: 130-140 |
| Address Translation     | String |
| Modify current location      | String |
| Sort list by distance      | String |
| Fingerprint      | String |
| Hardware      | String |
| Radio Version     | String |
| Device      | String |
| Board      | String |

## Download
[URL]

## Contribution
I love contribution. I don't think this app and code are perfect. I need your help.
```html
1. add issue tracker or send marcokoo19@gmail.com
2. clone
3. commit
```
