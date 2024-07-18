<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Hyprhook/Hyprhook">
    <img src="https://repository-images.githubusercontent.com/812448348/684c24bc-4669-431d-b7bf-2d2e266d4db8" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Hyprhook</h3>

  <p align="center">
    A plugin for Hyprland that can call a script when an event occurs
    <br />
    <a href="https://github.com/Hyprhook/Hyprhook/blob/master/README.md"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Hyprhook/Hyprhook">View Demo</a>
    ·
    <a href="https://github.com/Hyprhook/Hyprhook/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/Hyprhook/Hyprhook/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

## Installation

### Manual

To build, have hyprland headers installed and under the repo directory do:

```
make all
```

Then use `hyprctl plugin load` followed by the absolute path to the `.so` file to load, you could add this to your `exec-once` to load the plugin on startup

### Hyprpm

```
hyprpm add https://github.com/Yusuf-Duran/Hyprhook
hyprpm enable Hyprhook
```

### Nix

Refer to the [Hyprland wiki](https://wiki.hyprland.org/Nix/Hyprland-on-Home-Manager/#plugins) on plugins, but your flake might look like this:

<!-- MARKDOWN LINKS & IMAGES -->

[contributors-shield]: https://img.shields.io/github/contributors/Hyprhook/Hyprhook.svg?style=for-the-badge
[contributors-url]: https://github.com/Hyprhook/Hyprhook/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Hyprhook/Hyprhook.svg?style=for-the-badge
[forks-url]: https://github.com/Hyprhook/Hyprhook/network/members
[stars-shield]: https://img.shields.io/github/stars/Hyprhook/Hyprhook.svg?style=for-the-badge
[stars-url]: https://github.com/Hyprhook/Hyprhook/stargazers
[issues-shield]: https://img.shields.io/github/issues/Hyprhook/Hyprhook.svg?style=for-the-badge
[issues-url]: https://github.com/Hyprhook/Hyprhook/issues
[license-shield]: https://img.shields.io/github/license/Hyprhook/Hyprhook.svg?style=for-the-badge
[license-url]: https://github.com/Hyprhook/Hyprhook/blob/master/LICENSE.txt
