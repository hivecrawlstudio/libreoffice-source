# LibreOffice source for PDF Reader's Exact view

PDF Reader (`com.hivecrawlstudio.pdfreader`) by HiveCrawl Studio offers an optional download, Exact view, that runs LibreOffice to lay out Office files. This repository keeps the complete corresponding source of that LibreOffice build available, as its licences (Mozilla Public License 2.0 and the third-party licences it includes) require.

Each release holds the source archive for one build (one per phone CPU type), mirrored unchanged:

| Release | Build | Source |
|---|---|---|
| [libreoffice-viewer-131](https://github.com/hivecrawlstudio/libreoffice-source/releases/tag/libreoffice-viewer-131) | F-Droid LibreOffice Viewer 131, arm64-v8a (LibreOffice 26.2.6.3) | `org.documentfoundation.libreoffice_131_src.tar.gz`, SHA-256 `0e102144a7cce24e7291e744bef87a573dfb629d595e6a40f0d9fc8a4accb82b` |
| [libreoffice-viewer-130](https://github.com/hivecrawlstudio/libreoffice-source/releases/tag/libreoffice-viewer-130) | F-Droid LibreOffice Viewer 130, armeabi-v7a (LibreOffice 26.2.6.3) | `org.documentfoundation.libreoffice_130_src.tar.gz`, SHA-256 `ab37fe28f735e5b710d0de2e14e2c4302ca422e72754afe3cbaaf40a0c6e19a9` |
| [libreoffice-viewer-129](https://github.com/hivecrawlstudio/libreoffice-source/releases/tag/libreoffice-viewer-129) | F-Droid LibreOffice Viewer 129, x86_64 (LibreOffice 26.2.6.3) | `org.documentfoundation.libreoffice_129_src.tar.gz`, SHA-256 `1d4264ae8b7f68c55124c3f68d38caa3dda31781fcf6f88c7b0a08e091963f1f` |

PDF Reader uses these builds unchanged except for `LibreOfficeKit.java`, whose full changed source ships inside the app under Settings › Open-source licences.

LibreOffice is a registered trademark of The Document Foundation. This project is not affiliated with or endorsed by The Document Foundation.
