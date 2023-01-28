# Microtool, Inc. Website

Hugo-based website for Microtool, Inc.

## Components

- [Hugo](https://gohugo.io) v0.109.0
- [Hugo Fresh theme](https://github.com/StefMa/hugo-fresh) as submodule

## Dependencies

- [Bootstrap Min CSS/JS](https://getbootstrap.com/docs/4.3/getting-started/download/) v4.3
- [Lightbox2](https://lokeshdhakar.com/projects/lightbox2/) v2.11.3
- [Magnific Popup](https://dimsemenov.com/plugins/magnific-popup/) v1.1.0
- [Themify Icons](https://themify.me/themify-icons)

## Local testing

1. Install [Hugo](https://gohugo.io)
2. Clone repo

```bash
git clone https://github.com/microtoolinc/microtool.git
cd microtool
```

3. Setup submodule locally

```bash
git submodule init
git submodule update --recursive
```

4. Run local dev environment

```bash
hugo serve
```