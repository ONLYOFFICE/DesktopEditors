[![License](https://img.shields.io/badge/License-GNU%20AGPL%20V3-green.svg?style=flat)](https://www.gnu.org/licenses/agpl-3.0.en.html)
![Platforms Windows | macOS | Linux](https://img.shields.io/badge/Platforms-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg?style=flat) ![Release](https://img.shields.io/badge/Release-v8.0.1-blue.svg?style=flat)

## Overview

[ONLYOFFICE Desktop Editors][4] is a free office suite that combines text, spreadsheet and presentation editors allowing to create, view and edit documents stored on your Windows/Linux PC or Mac without an Internet connection. It is fully compatible with Office Open XML formats: .docx, .xlsx, .pptx.

## Components

ONLYOFFICE Desktop Editors contain the following components:

* [desktop-apps](https://github.com/ONLYOFFICE/desktop-apps) - the frontend for ONLYOFFICE Desktop Editors which is used to build the program interface for the operating system selected.
* [desktop-sdk](https://github.com/ONLYOFFICE/desktop-sdk) - SDK which is a core part of ONLYOFFICE Desktop Editors.
* [core](https://github.com/ONLYOFFICE/core) - server core components for [ONLYOFFICE Document Server][2] which is a part of ONLYOFFICE Desktop Editors and is used to enable the conversion between the most popular office document formats (DOC, DOCX, ODT, RTF, TXT, PDF, HTML, EPUB, XPS, DjVu, XLS, XLSX, ODS, CSV, PPT, PPTX, ODP).
* [sdkjs](https://github.com/ONLYOFFICE/sdkjs) - JavaScript SDK for the [ONLYOFFICE Document Server][2] which is a part of ONLYOFFICE Desktop Editors and contains API for all the included components client-side interaction.
* [web-apps](https://github.com/ONLYOFFICE/web-apps) - the frontend for [ONLYOFFICE Document Server][2] which is a part of ONLYOFFICE Desktop Editors that allows the user to create, edit, save and export text, spreadsheet and presentation documents using the common interface of a document editor.
* [dictionaries](https://github.com/ONLYOFFICE/dictionaries) - the dictionaries of various languages used for spellchecking in ONLYOFFICE Desktop Editors.

## Plugins

ONLYOFFICE Desktop Editors offer support for plugins allowing developers to add specific features to the editors that are not directly related to the OOXML format. For more information see [our API](https://api.onlyoffice.com/plugin/basic) or visit github [plugins repo](https://github.com/ONLYOFFICE/onlyoffice.github.io).

## Functionality

ONLYOFFICE Desktop Editors include the following editors:

* [ONLYOFFICE Document Editor](https://www.onlyoffice.com/document-editor.aspx?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDesktop)
* [ONLYOFFICE Spreadsheet Editor](https://www.onlyoffice.com/spreadsheet-editor.aspx?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDesktop)
* [ONLYOFFICE Presentation Editor](https://www.onlyoffice.com/presentation-editor.aspx?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDesktop)
* [ONLYOFFICE Form Creator](https://www.onlyoffice.com/form-creator.aspx?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDesktop)
* [ONLYOFFICE PDF editor, reader & converter](https://www.onlyoffice.com/pdf-reader.aspx?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDesktop)

The editors allow you to create, edit, save and export text, spreadsheet and presentation documents.

## Installation methods

* Deb, rpm, exe, dmg on the [official website](https://www.onlyoffice.com/download-desktop.aspx?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDesktop)
* Snap package. Get on [snapcraft.io](https://snapcraft.io/onlyoffice-desktopeditors). The official [source code](https://github.com/ONLYOFFICE/snap-desktopeditors) for ONLYOFFICE Desktop Editors Snap package
* Flatpak. Get on [flathub.org](https://flathub.org/apps/details/org.onlyoffice.desktopeditors). The official [source code](https://github.com/flathub/org.onlyoffice.desktopeditors) for ONLYOFFICE Desktop Editors Flatpak
* AppImage.  Get on [AppImageHub](https://appimage.github.io/ONLYOFFICE/). The official [source code](https://github.com/ONLYOFFICE/appimage-desktopeditors) for ONLYOFFICE Desktop Editors AppImage

## License

ONLYOFFICE Desktop Editors is licensed under the GNU Affero Public License, version 3.0. See [LICENSE](https://onlyo.co/38YZGJh) for more information.

## How to Build

Instructions for building ONLYOFFICE Desktop Editors are in [build_tools](https://github.com/ONLYOFFICE/build_tools#desktop-editors).

## User Feedback and Support

If you have any problems with or questions about ONLYOFFICE Desktop Editors, please visit our official forum to find answers to your questions: [forum.onlyoffice.com][1] or you can ask and answer ONLYOFFICE development questions on [Stack Overflow][3].

  [1]: https://forum.onlyoffice.com
  [2]: https://github.com/ONLYOFFICE/DocumentServer
  [3]: https://stackoverflow.com/questions/tagged/onlyoffice
  [4]: https://www.onlyoffice.com/desktop.aspx?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDesktop
