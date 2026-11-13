[![License](https://img.shields.io/badge/License-GNU%20AGPL%20V3-green.svg?style=flat)](https://docspace.onlyoffice.com/s/gnC2xcxWjHhHmsM)
[![Platforms Windows | macOS | Linux](https://img.shields.io/badge/Platforms-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg?style=flat)](https://www.onlyoffice.com/download-desktop) [![Release](https://img.shields.io/github/v/tag/ONLYOFFICE/DesktopEditors?sort=semver&style=flat&label=Release&color=blue)](https://github.com/ONLYOFFICE/DesktopEditors/tags)

## Welcome to the ONLYOFFICE Desktop Editors repo!

[ONLYOFFICE Desktop Editors](https://www.onlyoffice.com/desktop?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDesktop) is a free office suite that combines text, spreadsheet, presentation, and PDF editors & Diagram Viewer. The application allows creating, viewing and editing documents stored on your Windows/Linux PC or Mac without an Internet connection. It is fully compatible with Office Open XML formats: .docx, .xlsx, .pptx.

![ONLYOFFICE Desktop Editors](./screenshots/ONLYOFFICE%20Desktop%20Editors.png)

## What's new in version 10.0 🚀

[ONLYOFFICE Desktop Editors 10.0](https://www.onlyoffice.com/blog/2026/10/onlyoffice-desktop-editors-10?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDesktop) brings a new approach to AI, a redesigned start window, a new cloud provider, and more:

* **AI Chat** – talk to the AI assistant of your choice (ChatGPT, Claude, Mistral, Google Gemini, Groq, xAI, DeepSeek, or local LLMs via Ollama, LM Studio, or GPT4All) right from the start window. Attach documents, spreadsheets, presentations, forms, or PDFs and work with them without opening the editors.
* **AI Tools** – ready-made presets for common tasks: review, compare, translate, and summarize documents; clean data, spot formula errors, and build pivot tables and charts in spreadsheets; generate slides or turn documents into presentations; merge, split, and redact PDFs.
* **AI in every editor**, including the PDF Editor, plus custom quick actions, AI assistants that respond to your edits, and saved prompts.
* **Optional AI module (beta)** – AI is no longer pre-installed, so you get an AI-free editing experience by default. Install the module in one click from the start window when you need it, and uninstall it anytime in Settings.
* **Redesigned start window** with a cleaner sidebar and refreshed Templates and Cloud sections.
* **Odoo** as a new cloud provider.
* **Linux and macOS improvements**: thinner window frames and window shadows on Linux, context menus for file tabs on macOS.
* **Editor updates**: metadata removal with the Redact tool, reusable signatures in forms, sheet backgrounds and an AutoComplete toggle in spreadsheets, new display modes and extended print settings in presentations, exporting slides as GIF or video, and more.

<p align="center">
  <a href="https://www.onlyoffice.com/blog/2026/10/onlyoffice-desktop-editors-10">
    <img width="840" src="https://static-blog.onlyoffice.com/wp-content/uploads/2026/10/12174610/AI-Tools-1.png" alt="ONLYOFFICE Apps">
  </a>
</p>

See the [full changelog](https://github.com/ONLYOFFICE/DesktopEditors/blob/master/CHANGELOG.md#1000) for details.

## Features you'll love ✨

Take advantage of the powerful editors included in ONLYOFFICE Desktop Editors:

* [ONLYOFFICE Document Editor](https://www.onlyoffice.com/word-processor?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDesktop)
* [ONLYOFFICE Spreadsheet Editor](https://www.onlyoffice.com/sheets?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDesktop)
* [ONLYOFFICE Presentation Editor](https://www.onlyoffice.com/slides?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDesktop)
* [ONLYOFFICE Form Creator](https://www.onlyoffice.com/form-creator?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDesktop)
* [ONLYOFFICE PDF Editor](https://www.onlyoffice.com/pdf-editor?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDesktop)
* [ONLYOFFICE Diagram Viewer](https://www.onlyoffice.com/diagram-viewer?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDesktop)

The suite empowers you to create, edit, save, and export text documents, spreadsheets, presentations, PDFs, fill out PDF forms, open diagrams, all while offering additional advanced features such as:

* Connection to the cloud (ONLYOFFICE, Moodle, Box, Dropbox, ownCloud, Nextcloud, Seafile, Liferay, kDrive, Odoo) for [real-time collaboration](https://www.onlyoffice.com/seamless-collaboration?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDesktop) ☁️
* [AI Chat and AI Tools](https://www.onlyoffice.com/ai-assistants?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDesktop) working with the AI provider of your choice, including local models, available as an optional module 🤖
* Ready-to-use templates for documents, spreadsheets, presentations, and forms 📋
* Digital signatures ✍️🔏
* Password protection 🔒🔑
* Scalable UI options (including dark mode 🌓)

## Localization 🌐

ONLYOFFICE is constantly improving localization of the editors to make the suite accessible to all users, all over the world.

* Interface available in 46 languages
* RTL support
* Hieroglyph support 🈴

## Plugins 🧩

ONLYOFFICE Desktop Editors offer support for plugins allowing developers to add specific features to the editors that are not directly related to the OOXML format. For more information, see [our API](https://api.onlyoffice.com/docs/plugins/get-started/overview) or visit the [GitHub plugins repo](https://github.com/ONLYOFFICE/onlyoffice.github.io).

Would like to explore the existing plugins in details? You are welcome to visit our [Marketplace](https://www.onlyoffice.com/app-directory?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDesktop).

## Components 📦

ONLYOFFICE Desktop Editors contain the following components:

* [desktop-apps](https://github.com/ONLYOFFICE/desktop-apps) - the frontend for ONLYOFFICE Desktop Editors which is used to build the program interface for the operating system selected.
* [desktop-sdk](https://github.com/ONLYOFFICE/desktop-sdk) - SDK which is a core part of ONLYOFFICE Desktop Editors.
* [core](https://github.com/ONLYOFFICE/core) - server core components for [ONLYOFFICE Document Server][2] which is a part of ONLYOFFICE Desktop Editors and is used to enable the conversion between the most popular office document formats (DOC, DOCX, ODT, RTF, TXT, PDF, HTML, EPUB, XPS, DjVu, XLS, XLSX, ODS, CSV, PPT, PPTX, ODP).
* [sdkjs](https://github.com/ONLYOFFICE/sdkjs) - JavaScript SDK for the [ONLYOFFICE Document Server][2] which is a part of ONLYOFFICE Desktop Editors and contains API for all the included components client-side interaction.
* [web-apps](https://github.com/ONLYOFFICE/web-apps) - the frontend for [ONLYOFFICE Document Server][2] which is a part of ONLYOFFICE Desktop Editors that allows the user to create, edit, save and export text, spreadsheet and presentation documents using the common interface of a document editor.
* [dictionaries](https://github.com/ONLYOFFICE/dictionaries) - the dictionaries of various languages used for spellchecking in ONLYOFFICE Desktop Editors.

## Easy installation options

Get set up quickly with **deb**, **rpm**, **exe**, or **dmg** packages from our [official website️](https://www.onlyoffice.com/download-desktop?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDesktop).

Prefer other methods? 

* **Snap package**. Get on [snapcraft.io](https://snapcraft.io/onlyoffice-desktopeditors). The official [source code](https://github.com/ONLYOFFICE/snap-desktopeditors) for ONLYOFFICE Desktop Editors Snap package.
* **Flatpak**. Get on [flathub.org](https://flathub.org/en/apps/org.onlyoffice.desktopeditors). The official [source code](https://github.com/flathub/org.onlyoffice.desktopeditors) for ONLYOFFICE Desktop Editors Flatpak.
* **AppImage**.  Get on [AppImageHub](https://appimage.github.io/ONLYOFFICE/). The official [source code](https://github.com/ONLYOFFICE/appimage-desktopeditors) for ONLYOFFICE Desktop Editors AppImage.
* **Microsoft Store**. [Download](https://apps.microsoft.com/detail/xpdlh3xbzxqv23?cid=PCCongratsBnr)

## License 📄

ONLYOFFICE Desktop Editors is licensed under the GNU Affero Public License, version 3.0, ensuring its transparency and commitment to the open-source community.

See [LICENSE](https://docspace.onlyoffice.com/s/gnC2xcxWjHhHmsM) for more information.

## How to build 🛠

You can find the detailed instructions for building ONLYOFFICE Desktop Editors in [build_tools](https://github.com/ONLYOFFICE/build_tools#desktop-editors).

## 💡 Need help or have an idea?

We ❤️ community contributions!

* **🐞 Found a bug?** Please report it by creating an [issue](https://github.com/ONLYOFFICE/DesktopEditors/issues).
* **❓ Have a question?** Ask other users and our developers in the [ONLYOFFICE Community][1].
* **🥷 Want to be a power user?** Visit our [YouTube channel](https://www.youtube.com/onlyofficeTV) and [Help Center](https://helpcenter.onlyoffice.com/desktop/getting-started?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDesktop).
* **👨‍💻 Need help for developers?** Check our [API documentation](https://api.onlyoffice.com/?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDesktop).
* **💡 Want to suggest a feature?** Share your ideas [here](https://community.onlyoffice.com/c/suggestions/40).

**Ready to try ONLYOFFICE Desktop Editors?** 👉 [Download](https://www.onlyoffice.com/download-desktop?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDesktop) ✨

---
<p align="center"> Made with ❤️ by the ONLYOFFICE Team </p>

  [1]: https://community.onlyoffice.com/
  [2]: https://github.com/ONLYOFFICE/DocumentServer