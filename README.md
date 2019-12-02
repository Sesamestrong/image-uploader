# image-uploader

An automatic image taker and uploader that uploads to Google Drive via Google Apps Script.

## Use

This project specifically is configured with an education-specific account and cannot be used elsewhere.
However, if one deploys the Google Apps Script backend to a public (@gmail.com) account,
one can copy-paste the ```/exec``` link to the running web app backend into the ```<meta>``` tag at the top of [index.html](index.html).

## Options

There are two modes of operation of this program:

1. Uploading as Google Drive images
  - Affected by Google Drive capacity quotas
  - Easily accessible once uploaded
2. Uploading as rows in a Google Sheet
  - Unlimited storage due to Google Drive policy
  - A bit more difficult to see
  - Good for large-scale computation and analysis

Both can be used  at the choice of the user by toggling a button in the webpage.
