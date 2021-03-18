<h1 align="center">Jellyfin Missing Episode Provider Plugin</h1>
<h3 align="center">Part of the <a href="https://jellyfin.media">Jellyfin Project</a></h3>

<p align="center">
<img alt="Plugin Banner" src="https://raw.githubusercontent.com/jellyfin/jellyfin-ux/master/plugins/SVG/jellyfin-plugin-missingepisodeprovider.svg?sanitize=true"/>
<br/>
<br/>
<a href="https://github.com/jellyfin/jellyfin-plugin-missingepisodeprovider/actions?query=workflow%3A%22Test+Build+Plugin%22">
<img alt="GitHub Workflow Status" src="https://img.shields.io/github/workflow/status/jellyfin/jellyfin-plugin-missingepisodeprovider/Test%20Build%20Plugin.svg">
</a>
<a href="https://github.com/jellyfin/jellyfin-plugin-missingepisodeprovider">
<img alt="GPLv3 License" src="https://img.shields.io/github/license/jellyfin/jellyfin-plugin-missingepisodeprovider.svg"/>
</a>
<a href="https://github.com/jellyfin/jellyfin-plugin-missingepisodeprovider/releases">
<img alt="Current Release" src="https://img.shields.io/github/release/jellyfin/jellyfin-plugin-missingepisodeprovider.svg"/>
</a>
</p>

## About
This plugin automatically populates your series with missing episode data based on [TheTVDB's](https://www.thetvdb.com/) series data.

## Build Process

1. To build and run this plugin you will need [jprm](https://github.com/oddstr13/jellyfin-plugin-repository-manager) as well as [.Net Core 5.x](https://dotnet.microsoft.com/download/dotnet/5.0).

2. Run the build via `jprm`
  ```
  jprm plugin build --output=../artifacts
  ```

3. Place the resulting file in the `plugins` folder of your JF install
