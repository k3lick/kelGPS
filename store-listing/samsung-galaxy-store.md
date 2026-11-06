# Samsung Galaxy Store — kelGPS listing kit (v1.9)

Prepared 6 Nov 2026. Copy each field into Seller Portal (seller.samsungapps.com).

## App information

- App title: kelGPS
- Package: com.kelick.fakegps
- Version: 1.9 (versionCode 12)
- Category: Tools
- Price: Free, no in-app purchases
- Content rating: Everyone
- Support email: 01kelick@gmail.com
- Support / website URL: https://kelickhub.com.ng
- Privacy policy URL: https://kelickhub.com.ng/privacy
- Binary: kelGPS-v1.9.apk (5,975,617 bytes)
  SHA-256: 1f4038dca51642c6c307ee88c746147e174a3ffcbf6f0eb6c8843c226fb8d342
  Signing cert SHA-256: 94ea6f5bea796131add8cf7de3bdbb4644aa60826c2da41659961fc189347758
- Target SDK: 34 (Galaxy Store needs 33 or higher — met)
- Min SDK: 26 (Android 8.0+)
- Icon: STILL NEEDED — 512x512 PNG, under 1,024 KB. The app has no
  raster launcher icon (it uses a vector pin drawable), so one must be
  made from the pin artwork before submitting.

## Short description (keep under 40 characters for Galaxy Store)

Fake GPS + VPN, for your own phone.

## Full description (paste as the app description)

kelGPS lets you set the location your phone reports, for testing and
for privacy. Pick a place on the map or search for it, and your phone
reports that location to other apps. Walk around with the on-screen
joystick, simulate a route, and save your favorite places.

It also has a VPN section: import your own WireGuard config for a live
tunnel, or switch on the local DNS filter that blocks ads and trackers.

Setup: after installing, choose Kelick Fake GPS in Settings →
Developer options → Select mock location app. OpenStreetMap built in,
no API key needed. No account, no ads.

## Keywords / tags

fake GPS, mock location, GPS changer, joystick, VPN, WireGuard,
teleport, route simulation

## Screenshots — STILL NEEDED (4 minimum, 8 maximum)

Galaxy Store wants 4–8 screenshots, PNG or JPG, 320–3840 px on a side,
aspect ratio no wider than 2.3:1. Take them on the phone from the
installed kelGPS v1.9 app:

1. Map screen with the gloomy background
2. Search / teleport
3. Joystick in use
4. VPN screen (WireGuard import / DNS filter)
5. ☰ menu open

No v1.9 screenshots have been sent yet.

## Permissions to declare in review notes

- INTERNET + ACCESS_NETWORK_STATE — map tiles and VPN.
- ACCESS_FINE_LOCATION / ACCESS_COARSE_LOCATION — reading and
  reporting location.
- ACCESS_MOCK_LOCATION — the whole point of the app: it registers as
  a mock location provider. The user must select it in Developer
  options; the app cannot enable itself.
- FOREGROUND_SERVICE — keeping the mock location running.
- BIND_VPN_SERVICE — the VPN section only.

## Data safety (what the app does with user data)

- No account, no analytics, no ads.
- Favorites, history and VPN settings stay only on the device.
- Map tiles come from OpenStreetMap's servers when the map loads.
- The DNS filter blocks listed ad/tracker domains on the device; it
  does not send browsing data anywhere.
- No data is collected by Kelick.

## Seller account — BLOCKER, same as Kelingua

Samsung does not let an individual publish with just a Samsung account.
To distribute free or paid apps you need Commercial Seller status, and
outside mainland China that means a Corporate Commercial Seller request
with D-U-N-S certification — D-U-N-S verification alone can take up to
10 business days. There is no sign-up or annual fee, but you need a
registered business with a D-U-N-S Number plus a bank account or
PayPal. Kel has no registered business on record, so this step cannot
be completed as-is. Do not start the submission until the seller status
is approved.

## Policy risk — read before submitting

A mock-location ("fake GPS") app can be refused by a store: it changes
the location other apps see, which can be used to deceive
location-based services. Samsung may reject it even with an honest
description, and the review may ask for a justification. GitHub (live
now) and the site's own download page are the reliable channels for
this app; the Galaxy Store is a try, not a promise. Also note: since
2 September 2026 Samsung blocks Seller Portal submissions whose binary
is not Android-developer-verified (ADV), so the signing certificate
may first need registering in Play Console under Android developer
verification for this package name.
