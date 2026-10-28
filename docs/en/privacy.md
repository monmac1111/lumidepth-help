# Privacy Policy

**Lumidepth Player VR**

- Effective date: October 19, 2026
- Last updated: October 28, 2026 (added home network servers)
- Provider: mon neural
- Contact: [hello@monneural.dev](mailto:hello@monneural.dev)

## 1. Information we collect

We do not collect any personal information, usage data, or video content. The app does not communicate with our servers and contains no advertising or analytics.

## 2. Data stored on your PC

The following data is stored only on your PC and is never sent anywhere:

- Settings (display and 3D options, and the addresses of shared folders and servers you register)
- Diagnostic logs (these do not contain video file names or locations)
- AI depth model data optimized for your GPU
- Thumbnail images shown in the video library

Uninstalling the app and deleting the folder `%LOCALAPPDATA%\LumidepthPlayerVR` removes all of it.

## 3. Meta platform

The app is distributed through the Meta store and uses the Meta platform to verify your purchase. Any information involved is handled by Meta under the [Meta Privacy Policy](https://www.meta.com/legal/privacy-policy/). We do not receive it.

## 4. Network

Apart from the purchase check, the app only connects to:

- Drives and shared folders that you open yourself (for example a NAS on your home network)
- Servers that you register yourself (WebDAV, Jellyfin)
- Media servers (DLNA) found on your home network. To find them, the app sends a discovery request (SSDP) on your home network.

Server user names and passwords are read from what you saved in Windows Credential Manager. The app does not store them and never writes them to logs.

The app identifies this PC to Jellyfin servers with an ID, so the server does not list a new device each time. The ID is a hash derived from the Windows machine ID; the machine ID itself is not sent.

## 5. Children

The app does not collect information from children.

## 6. Changes

We will post any changes to this policy on this page.
