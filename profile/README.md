# ComOffice

**Word, Excel and PowerPoint files in your own apps and systems.** Powered by KDAN.

ComOffice is the document engine behind [LynxOffice](https://lynxoffice.com), packaged as an SDK: read, edit, save and render `.docx`, `.xlsx` and `.pptx` files, and convert them to PDF, in your process, with no Microsoft Office, no LibreOffice and no network calls.

- **Convert in bulk:** a whole folder to PDF at once, on a server in worker processes, or in a Windows or Linux container.
- **Safe with files you did not write:** macros are kept but never run, a file that would unpack far past its size is refused, and on a server a document that crashes takes down only its own worker.

| Repository | For | Ships as |
|---|---|---|
| [ComOfficeKit-Apple](https://github.com/ComOfficeKit/ComOfficeKit-Apple) | iOS, iPadOS and macOS apps, in Swift | Two binary frameworks, with samples |
| [ComOfficeKit-Windows](https://github.com/ComOfficeKit/ComOfficeKit-Windows) | Windows apps, and services on Windows Server or x64 Linux, in .NET 8 or later | One NuGet package with the Windows and Linux engines inside, with samples |

Each repository's README covers the API, the requirements, the free trial and licensing.

### Open source, on the .NET SDK

Two companions you can copy into your own product, under the MIT licence. The SDK they call is not open source: it needs a licence key, and the evaluation key in the ComOfficeKit-Windows README works.

| Repository | What it is |
|---|---|
| [ComOfficeKit-WebViewer](https://github.com/ComOfficeKit/ComOfficeKit-WebViewer) | A view-only web component for Word, Excel and PowerPoint documents: your server draws the pages with the SDK, the browser shows them. With HTML, React and Vue starters |
| [ComOfficeKit-MCP](https://github.com/ComOfficeKit/ComOfficeKit-MCP) | A Model Context Protocol server and command line that let AI agents open, read, edit, render and compare Word, Excel and PowerPoint files |

[Website](https://comofficekit.com) · Contact: [support@comofficekit.com](mailto:support@comofficekit.com)

---

ComOffice by KDAN. © 2009–2026 Kdan Mobile Software Ltd. All Rights Reserved.
