# Visual Studio Code AppImage

Unofficial community build of the stable Visual Studio Code Linux release as an AppImage.

## Download

Download the latest AppImage from [Releases](https://github.com/sevinsaygi3080-tech/VSCode-AppImage/releases/latest).

Make it executable and run it:

```bash
chmod +x VSCode-*.AppImage
./VSCode-*.AppImage
```

## Automated builds and releases

GitHub Actions checks for the latest stable Visual Studio Code release every Monday at 09:00 UTC and publishes the AppImage to GitHub Releases. You can also start a build manually from **Actions → Build VSCode AppImage → Run workflow**.

The workflow uses [valicm/appimage-bash](https://github.com/valicm/appimage-bash) to package the official stable Linux x64 archive. GitHub Actions must have **read and write permissions** for repository contents so the workflow can publish releases. Configure this under **Settings → Actions → General → Workflow permissions** if publishing fails.

## Source

Visual Studio Code is developed by [Microsoft](https://github.com/microsoft/vscode). This is an unofficial community packaging project and is not affiliated with Microsoft.
