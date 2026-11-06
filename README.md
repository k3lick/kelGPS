# kelGPS

A fake GPS (mock location) app for Android, with a VPN section.

Built for the owner's own phone: pick a place on the map — or search for
it — and the phone reports that location to other apps, for testing and
for privacy. It uses Android's mock location provider, so it must be
chosen in **Settings → Developer options → Select mock location app**
after installing.

- **GPS changer:** OpenStreetMap (no API key needed), tap or search to
  teleport, joystick to walk around, route simulation, favorites and
  history.
- **VPN:** import a real WireGuard config to run a live tunnel, plus a
  local VPN that filters ads and trackers by DNS (31 built-in domains
  plus your own list). The DNS filter alone does **not** change your IP
  address — it only blocks those domains. A live tunnel needs your own
  server config; none is built in.
- **Look (v1.9):** live gloomy animated background — dark storm sky with
  slow fog and falling rain — restyled text, and a ☰ menu button to
  switch between the GPS changer and the VPN from either screen.

## Install

Download **kelGPS-v1.9.apk** from the
[latest release](https://github.com/malwar77/kelGPS/releases/latest)
and install it on your Android phone (Android 8.0+). It installs over
earlier kelGPS versions without uninstalling, and your favorites and
history are kept.

- Package: `com.kelick.fakegps`
- Version: 1.9 (versionCode 12), target SDK 34
- SHA-256: `1f4038dca51642c6c307ee88c746147e174a3ffcbf6f0eb6c8843c226fb8d342`
- Signing certificate SHA-256:
  `94ea6f5bea796131add8cf7de3bdbb4644aa60826c2da41659961fc189347758`
- Permissions: Internet, network state, location, mock location,
  foreground service, VPN (for the VPN section)

Also available from the download page at https://kelickhub.com.ng/gps-download

## Setup

1. Install the APK.
2. Settings → Developer options → **Select mock location app** →
   **Kelick Fake GPS**. (If Developer options is hidden, tap Build
   number 7 times in Settings → About phone first.)
3. Open kelGPS, pick a place, tap Start. Tap Stop to return to your
   real location.

## Honest limits

- This app changes the location your phone *reports*. It does not
  change your real position, and apps that check for mock locations
  can detect it.
- The built-in VPN filter is DNS-only and does not hide your IP. A
  real tunnel needs a WireGuard config from your own VPN server.
- No account, no ads, no data sent to Kelick servers.

## Support

Email: 01kelick@gmail.com
Website: https://kelickhub.com.ng
