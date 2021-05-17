# axis-live
![Axis Linux](https://user-images.githubusercontent.com/61242573/118399404-43c30480-b65d-11eb-9c81-82fccb9cf14e.png)

<h3 align="center">Build files for Axis Linux</h3>

<h4 align="center">This is where you can find <a href="https://github.com/axislinux/axis-live/releases">releases</a> of Axis Linux</h4>

<p align="center"><img alt="powered-by-electricity" src="https://forthebadge.com/images/badges/powered-by-electricity.svg"/></p>

<p align="center">
  <img alt="license" src="https://img.shields.io/github/license/axislinux/axis-live?style=for-the-badge"/>
  <img alt="issues" src="https://img.shields.io/github/issues/axislinux/axis-live?style=for-the-badge"/>
</p>

---

## About

Creator: [XXCoreRangerX](https://github.com/XXCoreRangerX) (mail@xxcore.pl)

## How to build the iso

### Requirements:
- an Arch-based distribution installed
- a PC <sub><sup>(unless some madlad wants to compile on a phone)</sub></sup>
- `archiso` installed

### Building

1. Clone the repo.
```console
git clone https://github.com/axislinux/axis-live.git
```
2. CD to the repo.
```console
cd axis-live
```
3. Use `mkarchiso` to build the ISO file.
```console
sudo mkarchiso -v axislive
```

## License
This project is licensed under the [MIT license](https://github.com/axislinux/axis-live/blob/master/LICENSE).
