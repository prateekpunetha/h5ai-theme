# h5ai-theme

![Screenshot](./screenshots/screenshot.png)

### Requirements

- Latest version of [h5ai](https://larsjung.de/h5ai/)

### Installation

- clone this repo and cd into it `git clone https://github.com/prateekpunetha/h5ai-theme h5ai-theme && cd $_`
- copy style sheet `cp css/styles.css /var/www/dl/_h5ai/public/css/`
- copy icons `cp -r icons/material-ocean /var/www/dl/_h5ai/public/images/themes/`
- copy config for icons `cp conf/types.json /var/www/dl/_h5ai/private/conf/`
- set `theme` to `material-ocean` in your `_h5ai/private/conf/options.json` OR `sed -i 's/comity/material-ocean/' /var/www/dl/_h5ai/private/conf/options.json`
