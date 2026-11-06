# kelGPS — other stores listing kit (v1.9)

Prepared 6 Nov 2026. Samsung is blocked on the business + D-U-N-S
requirement, and a mock-location app may be refused there on policy
grounds anyway; these three stores do NOT need a registered business.
What they all still need is Kel's own account — the sign-up and identity
verification cannot be done for him.

## App facts (same for all three stores)

- App title: kelGPS
- Package: com.kelick.fakegps
- Version: 1.9 (versionCode 12), target SDK 34, min SDK 26
- APK: kelGPS-v1.9.apk (5,975,617 bytes)
  SHA-256: 1f4038dca51642c6c307ee88c746147e174a3ffcbf6f0eb6c8843c226fb8d342
  Signing cert SHA-256: 94ea6f5bea796131add8cf7de3bdbb4644aa60826c2da41659961fc189347758
- Icon: store-listing/icon-512.png (512x512, 24,341 bytes) — drawn from
  the app's own green pin drawable (#4CAF50) on a dark rounded square.
- Support email: 01kelick@gmail.com
- Website: https://kelickhub.com.ng
- Privacy policy: https://kelickhub.com.ng/privacy
- Price: Free, no in-app purchases

## Short description (all stores)

Fake GPS + VPN, for your own phone.

## Full description (all stores)

kelGPS lets you set the location your phone reports, for testing and
for privacy. Pick a place on the map or search for it, and your phone
reports that location to other apps. Walk around with the on-screen
joystick, simulate a route, and save your favorite places.

It also has a VPN section: import your own WireGuard config for a live
tunnel, or switch on the local DNS filter that blocks ads and trackers.

Setup: after installing, choose Kelick Fake GPS in Settings →
Developer options → Select mock location app. OpenStreetMap built in,
no API key needed. No account, no ads.

## Screenshots — STILL NEEDED (all three stores)

No v1.9 screenshots exist yet. Take 4–8 on the phone from the installed
v1.9 app: 1. map screen with the gloomy background, 2. search /
teleport, 3. joystick in use, 4. VPN screen, 5. ☰ menu open.

## Permissions / data safety (all stores)

- INTERNET + ACCESS_NETWORK_STATE — map tiles and VPN.
- ACCESS_FINE_LOCATION / ACCESS_COARSE_LOCATION — reading and
  reporting location.
- ACCESS_MOCK_LOCATION — the whole point of the app: it registers as a
  mock location provider. The user must select it in Developer options;
  the app cannot enable itself.
- FOREGROUND_SERVICE — keeping the mock location running.
- BIND_VPN_SERVICE — the VPN section only.
- No account, no analytics, no ads. Favorites, history and VPN settings
  stay only on the device. Map tiles come from OpenStreetMap's servers.
  The DNS filter blocks listed ad/tracker domains on the device; it does
  not send browsing data anywhere.

## Policy risk — read before submitting anywhere

A mock-location ("fake GPS") app can be refused by a store: it changes
the location other apps see, which can be used to deceive
location-based services. Uptodown and APKPure are more lenient than
Huawei about this kind of app, but none of the three is a promise.
GitHub (live now) and the site's own download page are the reliable
channels for kelGPS.

---

## 1. Huawei AppGallery

- Console: AppGallery Connect (developer.huawei.com) — needs a HUAWEI ID.
- Individuals CAN publish; registration is free; identity verification
  takes 1–2 working days (bank document with full name in English +
  ID/passport/driver's licence). No D-U-N-S needed for an individual.
  An individual account can never become an enterprise account later,
  and the country picked during verification cannot be changed.
- At app creation enter the SHA-256 certificate fingerprint:
  94ea6f5bea796131add8cf7de3bdbb4644aa60826c2da41659961fc189347758
- Upload the APK. Category: Tools. App review usually 1–3 working days.
- Compatibility: kelGPS uses OpenStreetMap, not Google Play services,
  so it should run on Huawei phones without Google services.

## 2. Uptodown

- Console: https://en.uptodown.com/developers-console — free. Sign up
  with a Google account or the form (organisation name, email,
  password). Identity verification before the first submission goes live.
- Submit: Apps → Add new app → upload the signed APK → icon (square
  PNG, minimum 256x256), name, website, short + full description →
  Submit for review. Every file is scanned across 70+ VirusTotal
  engines. A 1024x500 featured banner is recommended but not mandatory.
- Category: Tools (confirm against Uptodown's own list in the console).

## 3. APKPure

- Console: APKPure Developer Console (apkpure.com/developer.html) —
  free. Submit the APK; review, and if not approved within 3 business
  days, check their guidelines. Developer contact:
  developer@apkpure.com.
- Icon: 512x512, 32-bit PNG with alpha, max 1,024 KB (ours is 24,341
  bytes — fine). Screenshots: JPEG or 24-bit PNG, 320–3,840 px.
  Feature graphic 1024x500.
- Category: Tools.
