<p align="center">
  <img src="https://mirrors.creativecommons.org/presskit/icons/cc.xlarge.png" height="150">
  <h2 align="center">CC Search Browser Extension</h2>
    <h4 align="center">
    <a href="https://addons.mozilla.org/en-US/firefox/addon/cc-search-extension/">
      Firefox
    </a>
    <span> | </span>
    <a href="https://chrome.google.com/webstore/detail/cc-search/agohkbfananbebiaphblgcfhcclklfnh">
      Chrome
    </a>
    <span> | </span>
    <a href="https://addons.opera.com/en/extensions/details/cc-search/">
      Opera
    </a>
  </h4>
  <p align="center">A Cross-Browser Extension which lets you search and filter content in the public domain and under Creative Commons licenses.<p>
  <p align="center">
    <a href="https://github.com/creativecommons/ccsearch-browser-extension/blob/master/LICENSE">
      <img alt="MIT License" src="https://img.shields.io/github/license/creativecommons/ccsearch-browser-extension.svg?color=brightgreen" />
    </a>
    <a href="https://circleci.com/gh/creativecommons/ccsearch-browser-extension/tree/master">
    	<img src="https://circleci.com/gh/creativecommons/ccsearch-browser-extension/tree/master.svg?style=shield" alt="platforms" />
    </a>
    <a href="https://github.com/creativecommons/ccsearch-browser-extension/blob/master/CONTRIBUTING.md">
	    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="prs welcome">
    </a>
  </p>
</p>

<p align="center">
  <img src="https://i.imgur.com/KOgFgWU.png" width="900px">
</p>

## Install

| [Firefox addon store](https://addons.mozilla.org/en-US/firefox/addon/cc-search-extension/) | [Chrome web store](https://chrome.google.com/webstore/detail/cc-search/agohkbfananbebiaphblgcfhcclklfnh) | [Opera addon store](https://addons.opera.com/en/extensions/details/cc-search/) |
|---------|--------|-------|

## Features

| Feature | <img src="https://i.imgur.com/tVOpDmP.png" width="16" height="16"> Firefox | <img src="https://i.imgur.com/r33ZXs4.png" height="16" width="16"> Chrome | <img src="https://i.imgur.com/CBgAqSl.png" heigth="16" width="16"> Opera |
|--------------------------------------------------------|---------|--------|-------|
| Search and filter CC Licensed content.                 |  Yes    | Yes    | Yes   |
| One click attribution.                                 | Yes     | Yes    | Yes   |
| Download images (and attribution).                     | Yes     | Yes    | Yes   |
| Bookmark images.                                       | Yes     | Yes    | Yes   |
| Export and import bookmarks.                           | Yes     | Yes    | Yes   |
| Sync your custom setting and bookmarks across devices. | Yes     | Yes    | No    |
| Options-UI for custom settings.                        | Yes     | Yes    | Yes   |
| Dark Mode.                                             | Yes     | Yes    | Yes   |

<p align="center">
  <img src="https://i.imgur.com/Dh7wczv.png">
</p>

## Installation from source
You can install the extension directly from the source. Follow the following steps:

1. Clone the repo: `git clone https://github.com/creativecommons/ccsearch-browser-extension.git`.

2. Run: `npm install`.

3. Run: `npm run dev`. This would compile SASS to CSS and bundle JS. The compiled version will be in dist folder.

4. Load the extension to the browser:
    - **Mozilla Firefox**
      - Navigate to _about:debugging_.
      - Click on "Load Temporary Add-on" button.
      - From the file explorer, choose `ccsearch-browser-extension/dist/firefox/manifest.json`.
    - **Google Chrome**
      - Navigate to _chrome://extensions_.
      - Click on "Load Unpacked" button (make sure you have enabled the _Developer mode_).
      - From the file explorer, choose `ccsearch-browser-extension/dist/chrome`.
    - **Opera**
      - Navigate to _about://extensions_.
      - Click on "Load Unpacked" button (make sure you have enabled the _Developer mode_).
      - From the file explorer, choose `ccsearch-browser-extension/dist/opera`.

## Contribution
Checkout [CONTRIBUTING.md](https://github.com/creativecommons/ccsearch-browser-extension/blob/master/CONTRIBUTING.md) for general guidelines for contributing code to CC Open Source.

For contribution guidelines and development instructions specific to this particular project, please checkout [INSTRUCTIONS.md](https://github.com/creativecommons/ccsearch-browser-extension/blob/master/INSTRUCTIONS.md).

## License
See [LICENSE](https://github.com/creativecommons/ccsearch-browser-extension/blob/master/LICENSE).

