
<!-- Test: `readme-icon` expects exactly this line -->

<img src="app-icon.png" align="right" width="200px">' or '<image src="app-icon.png" align="right" width="200px">

<!-- Test: `readme-title-net` requires the for-.net-.CMSs suffix (don't write it here, otherwise this would match) -->

# App to test the quality check verification for .net CMSs

> Special Note about the readme.md
>
> The readme.md is also tested by the quality checks,
> so we can't use it for docs the way we usually would,
> since it's part of the testing.
>
> This is why most of the docs are currently in the Home.cshtml file, which is not tested by the quality checks.

<!-- Test: `readme-platform-info` looks for exactly this intro line below -->

> This is a [2sxc](https://2sxc.org) App for [DNN ☢️](https://www.dnnsoftware.com/) and [Oqtane 💧](https://www.oqtane.org/)

<!-- Test: `readme-aspect-table` looks for the beginning of this table -->

| Aspect              | Status | Comments or Version
| ------------------- | :----: | -------------------
| 2sxc                | ✅     | requires 2sxc v22.00.00

<!-- Test: `readme-history-section` needs this exact title -->

## History

### First version 2026-08

1. @2dm: created the app 2026-08-12
1. @2dm: added SCSS and some Razor 2026-08-13
1. @2dm: added the readme.md 2026-08-14

<!--
  Various additional Tests below
-->

<!-- Test: `readme-customize-section` looks for this exact title -->

## Customize the App
