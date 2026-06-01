# Chat Overlay

A local first chat overlay using TMI.js and EmoteTTV to present chat in a clean and readable manner. Customization is easy with CSS and can be shared by just pasting over the style.css file with a new one!

## Features

- **Local First:** Runs natively as a local file within OBS.
- **Real-Time Updates:** Uses TMI.js to connect with Twitch's IRC implementation. Emotes are parsed locally using EmoteTTV and cached to reduce server calls.
- **Easily Customazible:** Fully customizable with easy to read CSS!
- **Automated fade out:** Chats can optionally be set to fade out over a configurable amount of time.

## Prerequisites

- OBS Studio
- A Twitch channel to connect to

## Setup Instructions

### 1. Download and configure

1. Download the most recent version from releases
2. Open index.html with your preferred text editor
3. In the `USER SETTINGS` block change `TWITCH_CHANNEL = 'your_username_here'` to the desired channel.
4. Configure `MAX_MESSAGES` and fade out as desired.
5. Add index.html as a Browser source in OBS, adjusting width and height to your preference.

Styles can be customized in style.css according to your preference! Messages by default are in a pillbox format to improve readability.

## Credits

https://github.com/tmijs/chat - TMI.js

https://github.com/doceazedo/emotettv - EmoteTTV
