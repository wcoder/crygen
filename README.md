# crygen
Simple tool for encryption data with RSA

![Link](https://chart.googleapis.com/chart?chs=300x300&cht=qr&chl=https%3A%2F%2Fwcoder.github.io%2Fcrygen%2F&choe=UTF-8)

## Features

- Sources is full open
- In-memory data storage
- One private key per session
- 1024 RSA (https://github.com/travist/jsencrypt)
- PWA ready (https://wcoder.github.io/crygen/)
- Independence and self-hosting available (https://github.com/wcoder/crygen/archive/master.zip)
- Independence from providers/channels of data-transferring
- Fully manual

## How to use

### Setup
- Open tool
- Send your public key to your friend
- Paste friend's public key

### Encryption
- Write message to the `input` field
- Push `Encrypt` button
- Send `output` data to your friend

### Decryption
- Paste the encrypted message to the `input` field
- Push `Decrypt` button
- Read the message from `output` field

## Limitations

- 118 symbols message length for encryption
