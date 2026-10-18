# Help

**Lumidepth Player VR** plays VR180, VR360 and 2D videos stored on your PC or home NAS on your Meta Quest. An AI model estimates depth for every frame, so near and far objects shift naturally as you move your head.

## Requirements

- Windows 10 / 11 (64-bit)
- NVIDIA GeForce RTX 3060 or newer (RTX 30 / 40 / 50 series)
- Meta Quest headset connected via Meta Quest Link (cable) or Air Link
- Video: MP4, MKV, MOV, WebM. H.265 (HEVC), H.264 (up to 4K), AV1, VP9

## Getting started

1. Start the Meta Quest Link app on your PC and connect your Quest with Link or Air Link.
2. Launch Lumidepth Player VR from the Library in your Quest.
3. Your PC drives appear in the list. To browse a NAS shared folder, map it as a network drive in Windows.
4. Select a video with the right trigger to start playback. The first time you use 3D, the AI is prepared for your PC, which can take a few minutes (it is instant afterwards).

## Controls

| Button | Library | During playback |
|---|---|---|
| Right trigger | Select / hold and move to scroll | Show the playback bar / press a button |
| A | Up one folder | Back to the library |
| B | Up one folder | Toggle 3D |
| Y | – | Play / pause |
| X | – | Show / hide the status line |
| Right stick left/right | – | −10 s / +10 s |
| Left stick left/right | – | −60 s / +60 s |
| Right stick click | – | Recenter |
| Hold right grip and move | – | Rotate the video |

## Playback bar and settings

Pull the right trigger during playback to show the playback bar where you point. It has volume, zoom, 3D on/off, recenter and settings (⚙).

The settings panel has three pages:

- **Display**: brightness, sharpness, anti-aliasing
- **3D**: depth strength, edge alignment, edges, gap filling, stabilization, update rate, window, 3D for 2D/mono videos
- **Format**: projection (180°, 360°, flat) and layout (side by side, top/bottom, single). It is detected automatically from the file name and aspect ratio; choose manually only if it looks wrong (applies to the current video only).

The depth effect works best with side-by-side VR180 videos.

## Troubleshooting

- **"Your Meta Quest is not connected"**: connect your Quest with Link or Air Link and try again.
- **"No NVIDIA GPU was found"**: update your NVIDIA driver. An RTX 30 series GPU or newer is required.
- **3D shows "unavailable"**: your GPU may be low on memory. Close other apps.
- **The picture looks doubled or split**: choose the projection and layout in the Format page of the settings.

Contact: [hello@monneural.dev](mailto:hello@monneural.dev)
