# Timer for Websites That Steal Your Time

This project helps to control time was spent on sites. It requires special extension for Chrome browser.

# Installing

Install extension for Chrome browser [Custom JavaScript for websites](https://chrome.google.com/webstore/detail/custom-javascript-for-web/poakhlngfciodnhlhhgnaaelnpjljija).

Open configuration of [cjs](https://chrome.google.com/webstore/detail/custom-javascript-for-web/poakhlngfciodnhlhhgnaaelnpjljija) browser extension on the site you want to controll. Click on the link "your own external scripts", add path https://cdn.rawgit.com/enibeni/34_timemachine/b3be2878e4bfcaf7ae0072919c9dd4400ecc41c4/index.js. Don`t forget to press "enable cjs for this host" to enable custom JS.

After that you'll see the timer in the top-left corner of web page. The timer preset is 3 minutes after which the motivation message will be shown. Next messages will be shown every 30 seconds.

For faster development you can use JS code hosted on localhost. Simple web server can be used for that, run:

```bash
python3 -m http.server
```

Add path `http://localhost:8000/index.js` to [cjs](https://chrome.google.com/webstore/detail/custom-javascript-for-web/poakhlngfciodnhlhhgnaaelnpjljija) browser extension. Done.


# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
