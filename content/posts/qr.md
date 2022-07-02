---
title: "The QR Code Scam"
date: 2022-07-01
draft: false
aliases:
    - /qr
---

**TL;DR: DO NOT JOIN RANDOM SERVERS FROM DMs AND DO NOT SCAN UNKNOWN QR CODES**

Recently, there has been a scam going around Discord where scammers trick users into scanning a Discord mobile login QR code.

## How it Works

The scam usually starts out like this: You get a dm from an account giving you some sort of reason to join a random server. These reasons can vary, but are usually urgent in tone and give you a reason to join right away and see what is going on.  Here is an example of one such message below:
![Screenshot of a message used by scammers](/images/qr-scam-invite.png)


After joining the server, you are greeted by a message saying something along the lines of "Verification Required to access this server" - this works because it is blocking you from accessing whatever content you were promised in the DM. The accounts that sent these messages are usually unverified bots with names like "Wick" or "Captcha.bot", impersonating real verification bots. The message might look something like this: ![Screenshot of fake verification message](/images/qr-scam-verification.png)

If you end up clicking the "Verify" button (which you shouldn't), the bot will send a new message asking for you to scan a QR code with your mobile device (which you shouldn't). It will look something like this:
![Screenshot of fake QR verification message](/images/qr-scam-qr-small.png)

The QR leads to a Discord Mobile login link, [normally used for quickly logging into Discord from your phone](https://support.discord.com/hc/en-us/articles/360039213771). If you scan the QR (don't), and proceed, the scammer will login to your account and use it to spam the same invite link, causing more accounts to be stolen.

## What to do if you get compromised

If you fall for this scam and get your account stolen, *don't worry*, changing your password will reset your token and kick the scammers out of your account. You can do this by going to the "Password and Authentication" section of your account settings, clicking "Change Password", and filling out the details in the form, as detailed below:
|                                                         |                                                                  |
|---------------------------------------------------------|------------------------------------------------------------------|
|![Account Settings](/images/password-reset-1-small.png)     |![Password Reset Form](/images/password-reset-2-small.png)     |