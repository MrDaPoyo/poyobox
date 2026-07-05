<h1 align="center" id="title">PoyoBox</h1>

<p id="description">PoyoBox is a free open-source DrawBox service built for those who want to have a different kind of guestbook!</p>

<p align="center"><img src="https://img.shields.io/github/languages/code-size/mrdapoyo/poyobox" alt="shields"></p>

<h2>Features</h2>

PoyoBox gives users the ability to:
*   Create a DrawBox
*   Attach their own domain.
*   Modify their page's CSS.

<h2>Setup</h2>
Your `.env` should look like:

```env
HOST=localhost:3000
CLEAN_HOST=localhost
PORT=3000

AUTH_SECRET=your_secret_key_here

CONFIG_MAX_USERS=1000
CONFIG_MAX_MESSAGE_SIZE=2000

USER_MAX_MESSAGES=1000

MAILER_ADDRESS=censored@censored.com
MAILER_ALIAS=mailer@poyobox.net
MAILER_PASSWORD=xxxx xxxx xxxx xxxx
```

Note: Make sure to replace `your_secret_key_here` with a secure random string.

NOTE: This project is very old, and likely insecure. Please write something similar yourself instead of using my code.
