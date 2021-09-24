---
type: posts
title: "(Updated) ~Moving back to Keychain~"
date: 2021-08-22
description: moving off 1Pass
tags:
  - tech
---

_I’m back on 1Password because the Safari extension is excellent. My only remaining frustration is that the cmd \ keyboard shortcut is intermittently failing._

With the announcement of [1Password 8](https://blog.1password.com/1password-8-for-mac-is-now-in-early-access/) and its move to Electron, along with iOS 15 bringing a Safari password service capable of creating two-factor passwords, it seems like the perfect time to try moving back to the keychain.

Until I worked at [Turbine Labs](https://www.turbinelabs.io), I'd never used a standalone password manager. In 2015, the sheer number of logins I managed were comparatively small, and the options for two-factor limited. I probably used insecure passwords a fair bit too. 1Password had shared vaults for the team though, and with our company buying a subscription it seemed like an easy choice to switch my personal data over as well. 

Seven years later, and a number of funding rounds for 1Password means they're catering to enterprise users more explicitly, which isn't much solace as an individual user. I don't doubt 1Password will continue to be an excellent app for some time to come, but I wanted to see if I could keep it exclusively for work.

iOS 15 has a further preview improvement hinting at [a future without passwords](https://www.theverge.com/2021/6/11/22529266/passkeys-icloud-keychain-ios-15-passwordless-future-security-login). At this point I already remember almost no passwords at all, so it stands to reason the complexity will become less visible to end-users and we'll be able to use biometrics or a single passphrase and second-factor to handle all auth.

Granted, moving to Apple's Keychain means I can't authenticate as easily to other browsers, but I only use Safari these days save for work, so that shouldn't be a big problem. Worst case I can always copy passwords out of the Keychain.

## How I moved

Safari's Keychain can't import CSV or text password exports directly, which means the import is a slow process that meant switching the default password service to Safari and saving any password I need to pull from 1Password. Since there's no real deadline or forcing function, it seems easiest to just move steadily. That way I'm also not destroying any passwords of preventing a return to 1Password in the future if it turns out to be the right thing to stay with.

## Keeping my data

This whole thing might be a silly experiment, but I worry generally about the portability of data and files, which means this feels like a valuable test regardless. I might be a bit silly, but when it comes to my [writing](https://www.brookshelley.com/posts/2019-05-02-on-notes-and-todos/) and my photos, I prefer portability to most anything else.