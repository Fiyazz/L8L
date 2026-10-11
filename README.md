# L8L

The website for L8L (Little Africa), a learning app for young people aged 11 to 19. Made by Lustr8lab in Lagos, Nigeria.

Live at https://fiyazz.github.io/L8L/

## What is in here

- `index.html` is the whole site: the page, its styles and its script in one file.
- `send/index.html` is a small page that opens a visitor's email app with their waitlist message filled in.
- `404.html` is shown when someone follows a link that does not exist.
- `og.png` is the picture people see when the link is shared. `icon.svg`, `icon-192.png` and `apple-touch-icon.png` are the site icons.

## Changing things

- Contact details are at the top of the script in `index.html`, under "settings you may want to change".
- Colours are at the top of the styles in `index.html`, in the `:root` block.

## The waitlist

The form does not store anything. It writes one message from the answers, then opens WhatsApp or the visitor's email app with that message ready. The visitor presses send.
