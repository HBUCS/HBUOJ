# HBU Online Judge

![Python Version](https://img.shields.io/badge/python-3.6%20%7C%203.7-blue.svg)
![Django Version](https://img.shields.io/badge/django%20versions-2.1-blue.svg?style=popout-square)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/b881b108692a4e268c597ebf45edc3cf)](https://www.codacy.com/app/xingji2163/HBUOJ?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=HBUCS/HBUOJ&amp;utm_campaign=Badge_Grade)

⚠️ This project is an old version of Hebei University Online Judge, which was based on the [DMOJ](https://github.com/DMOJ) open source project for secondary development. I would like to thank all members of the project team. We no longer maintain this project and re-develop a new [Programming Teaching Plaform](https://github.com/HBUCS/ProgramingTeachingPlatform) for Hebei University. (2019.2.20 - Boyce Li)

![Home](https://raw.githubusercontent.com/HBUCS/HBUOJ/dev/docs/screenshots/home.png)

## Features

* Friendly and highly featured user interface.
* Strive for complete functionality, out of the box.
* Extensible programming language support.
* Use Markdown and MathJax.
* Live submission status.

......

## Getting Start

### develop

* Installing dependencies (for macOS):

  ```bash
  brew cask install docker
  brew install docker-compose python3 nodejs npm
  npm install -g sass pleeease-cli
  pip3 install -r requirements.txt
  pip3 install flake8
  ```

* Runing script:

  ```bash
  ./tools/init.sh
  ```

* Enjoy Coding!

### deploy

```bash
./tools/build.sh
```
