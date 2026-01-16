# openpgpkey-juanchb
openpgpkey-juanchb
# WKD for jchb@juanchb.com

This repository hosts the **Web Key Directory (WKD)** for my PGP key used with the email `jchb@juanchb.com`.

## Structure

- `.well-known/openpgpkey/hu/aroptu6sq9atiskj9h5y3w185r1qg87x`  
  Contains the public PGP key in WKD format.

## Purpose

WKD allows email clients that support the Web Key Directory protocol (like Thunderbird or Apple Mail with GPG) to automatically fetch my **trusted public key** for secure email communication.

## How to use

- Email clients configured with WKD will automatically locate and verify my public key via:
https://openpgpkey.juanchb.com/.well-known/openpgpkey/hu/aroptu6sq9atiskj9h5y3w185r1qg87x
- No additional configuration is required on the client side.

## Notes

- HTTPS may take a few minutes to become valid after adding the custom domain (`openpgpkey.juanchb.com`) to GitHub Pages.
- This repository is **read-only** for security purposes.
