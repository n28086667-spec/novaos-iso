NOVAOS ISO BUILD PROJECT
=======================
This is a build project, NOT the finished ISO.

BUILD FROM WINDOWS
1. Create/sign in to GitHub: https://github.com/
2. Create a new empty repository named novaos-iso.
3. Extract this ZIP on Windows.
4. Upload the files and folders from this folder to the repository.
   Keep the hidden .github folder.
5. Open the repository's Actions tab.
6. Choose "Build novaOS ISO" and click "Run workflow".
7. If the workflow succeeds, open the completed run and download the
   artifact named "novaos-iso". The ISO is inside that download.

IMPORTANT
- Targets x86-64 Intel/AMD PCs.
- Experimental Debian-based live desktop using XFCE.
- This workflow has not been run or tested here; a successful build is not guaranteed.
- Calamares is included, but a Windows-preserving "install alongside Windows"
  partitioning flow has NOT been configured or verified.
- Test booting in a virtual machine first. Do not install on your real PC until
  the installer and partitioning behaviour have been reviewed and tested.
- Back up important files before any real dual-boot installation.
