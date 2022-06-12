# My Portfolio Website

This is my first try of a portfolio website. It is the first html and css project that I have ever done and is based on the knowlage of the coursera course "HTML, CSS and Javascript for web developers" which I did in 2022.

## Requirements

- node v16.15.1 (a lower version should be OK as well)
- npm 8.11.0
- browser-sync 2.27.7
- I used Bootstrap v5.1.3. You can download it [here](https://getbootstrap.com/).

## How to work on it

- Install Browsersync via npm, see [this](https://browsersync.io/) link for details
- Go to one folder over the root of this repository to start browser-sync
  - `$ cd ..`
  - `browser-sync start --server --directory --files "**/*"`
- The browser will open it up and you can go to `my_website/home/index.html` to see the start page of my website in the debug configuration
- In order to debug the code, I used the chrome developertools
  - The optimize for the mobile view, I used the _Samsung Galaxy S8+_ setting, since it has the smallest width of all devices within the chrome developer tools
