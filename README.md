> This package was developed to work with data stored in Blackbaud SIS/LMS/SWS instances. We are no longer Blackbaud users, and therefore no longer actively maintaining this package. If you would like to discuss this tool, or the approaches it took to accessing otherwise inaccessible data in Blackbaud, please reach out directly to [Seth Battis](mailto:seth@battis.net?subject=Blackbaud%20Athletics%20RSS)

# Blackbaud Athletics RSS

Generate RSS feeds for Blackbaud athetics team schedules

## Install

Prerequisites:

- [Node](https://nodejs.org) (and, optionally, [pnpm](https://pnpm.io/))
- [Composer](https://getcomposer.org)
- [gcloud CLI](https://cloud.google.com/sdk/docs/install)
- [Google Cloud](https://console.cloud.google.com/) account with [billing](https://console.cloud.google.com/billing) configured

Clone repo and install dependencies:

```sh
git clone git@github.com:groton-school/blackbaud-athletics-rss.git path/to/project
cd path/to/project
composer install
npm install
```

Deploy to Google Cloud with interactive wizard:

```sh
npm run deploy
```

## Usage

Visit the app URL, once deployed, to configure a rendering of the athletic schedule as either WebCal, RSS, or HTML feeds. The RSS feed (technically Atom) plays well with Carousel's feed reader bulletin.
