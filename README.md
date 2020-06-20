# Site from Google Sheet

Auto-generate a full, deployable, static website based on data from a Google Sheet.

## Table of Contents

* [Install](#install)
* [Usage](#usage)
* [License](#license)

## Install

```
$ git clone https://github.com/sebastienvercammen/node-site-from-google-sheet.git
$ cd node-site-from-google-sheet
$ npm install
```

## Usage

1. Copy [`.env.example`](.env.example) to `.env`
2. Edit `.env` for configuration
    1. Authentication
        * Full access via private key (`GOOGLE_SERVICE_ACCOUNT_EMAIL` and `GOOGLE_PRIVATE_KEY`)
        * Read-only access via API key (`GOOGLE_API_KEY`)
    2. Data source: Set `GOOGLE_SPREADSHEET_ID` to the spreadsheet ID in its URL
3. `npm start`

## License

Licensed under [AGPLv3](LICENSE).
