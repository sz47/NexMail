<p align="center">
  <img src="https://github.com/sz47/NexMail/blob/main/images/onemore.png" align="center" alt="NexMail screencap"> 
</p>

# NexMail

A QT based email client that encrypts the mail before sending. So even if mail providers like gmail or outlook wanted to read your mail, they can't :)

One caveat though, you'll need this client to decrypt the mail and the associated key (good news, this application will be cross platform).

## Features

```
[x] Login
  - [x] Online
  - [ ] Local login

[o] Read Mail from Inbox
  - [o] Categories in mail
  - [o] Add pages in inbox

[o] Tab Layout for multitasking

[o] Send Mail
  - [ ] With encryption

[ ] Local mail storage
  - [ ] Encrypted storage

[ ] Mail search

[ ] Vim keybindings (ofc)

[o] Dark Mode for reading mails

x = done
o = in progress
```

## Dependencies

+ [PySide6](https://pypi.org/project/PySide6/)

## Run

``` console
py main.py
```

## Thanks

+ Icons taken from [Material Design Icons](https://materialdesignicons.com/)
+ QSS stylesheet source [GTRONICK/QSS](https://github.com/GTRONICK/QSS)
+ Dark Theme for WebEngine Nikita Vasilyev
