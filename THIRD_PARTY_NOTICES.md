# Third-party notices

Zynko includes or uses the components and services below. Each is distributed under its own license. This list will be completed with exact versions and full license texts (in a `licenses/` folder inside the installer) with the first release.

## Components shipped with Zynko

| Component | Use | License |
|---|---|---|
| [mpv / libmpv](https://mpv.io) | Video playback engine | GNU LGPL 2.1 or later (built without GPL-only parts) |
| [FFmpeg](https://ffmpeg.org) | Audio and video decoding | GNU LGPL 2.1 or later (built without GPL-only parts) |
| [libplacebo](https://code.videolan.org/videolan/libplacebo) | Rendering, HDR tone mapping | GNU LGPL 2.1 or later |
| [.NET](https://dotnet.microsoft.com) | Runtime | MIT |
| [Avalonia](https://avaloniaui.net) | User interface | MIT |
| [Quicksand](https://fonts.google.com/specimen/Quicksand), [Manrope](https://fonts.google.com/specimen/Manrope) | Fonts | SIL Open Font License 1.1 |
| [SQLite](https://sqlite.org) | Local database | Public domain |
| [HueApi](https://github.com/michielpost/Q42.HueApi) | Philips Hue connection and Entertainment streaming | MIT |
| [Bouncy Castle for .NET](https://www.bouncycastle.org/csharp/) | DTLS for Hue Entertainment streaming | MIT |
| [Velopack](https://velopack.io) (planned) | Installer and updates | MIT |
| [VS Chamber Orchestra: Community Edition](https://github.com/sgossner/VSCO-2-CE) | Orchestral recordings used in the intro music and interface sounds | CC0 1.0 (public domain dedication) |

### Orchestral recordings

The intro music, the setup music and the interface sounds are built from recordings in **VS Chamber Orchestra: Community Edition** by Versilian Studios, recorded by Sam Gossner and Simon Dalzell, with sample cutting by Elan Hickler (Soundemote). The library is released under CC0 1.0, so no attribution is required; we credit it with thanks.

### LGPL components

libmpv, FFmpeg and libplacebo are dynamically linked and can be replaced by the user with compatible builds. Their source code, and the exact build configuration used by Zynko, will be available at the location given in each release notes. The LGPL rights apply to those components only.

## Services

- **TMDB:** titles, images, cast and availability. *This product uses the TMDB API but is not endorsed or certified by TMDB.*
- **JustWatch:** "Available in" data is provided by JustWatch through TMDB. Zynko does not connect to JustWatch directly.
- **Plex:** Plex is a trademark of Plex, Inc. Zynko is not affiliated with, endorsed or sponsored by Plex, Inc.
- **Philips Hue:** Philips and Hue are trademarks of Koninklijke Philips N.V. / Signify. Zynko is not affiliated with them.
- **Netflix, Prime Video, Disney+, HBO Max, Apple TV** and other platform names and logos are trademarks of their owners and are shown for information only.
