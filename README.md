# Second Brain Convert

**Drag files onto a format and they're converted, on your own computer.**
Part of the Second Brain family, alongside the [Second Brain phone app](https://github.com/khalil203/second-brain).

Hold <kbd>Ctrl</kbd> (<kbd>Option</kbd> on macOS), drag files, and drop them on a format in the donut that opens at your cursor. Only formats that fit your files appear.

## What it does

- **200+ formats:** images, PDF, Word, Excel, PowerPoint, HWP/HWPX, video, audio, e-books, archives, fonts, CAD and 3D models
- **No Office needed** for most conversions; large engines (FFmpeg, LibreOffice, Pandoc, calibre, Ghostscript) download only when a conversion needs them
- **Private:** files never leave your computer, no tracking
- **Batch and multi-step** conversions, **watch folders**, and a command line
- Light and dark themes, many languages

## Install (Windows 10/11)

Download the latest `SecondBrainConvert-win-x64.zip` from [Releases](https://github.com/khalil203/second-brain-convert/releases), unzip it anywhere and run **SecondBrainConvert.exe**.

## Build

Requires the .NET 10 SDK.

```
dotnet run --project src/Filee.App
dotnet publish src/Filee.App -c Release -r win-x64 --self-contained -o publish/win-x64
```

## Credits and license

Second Brain Convert is based on **[Filee](https://github.com/KnifeLemon/Filee)** by Myeonggu Kim (KnifeLemon) and the Filee contributors, used under the MIT license. Changes in this version: name, logo, colors, update channel, data folders and support links.

MIT license — see [LICENSE](LICENSE). Third-party engines keep their own licenses, listed in [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).
