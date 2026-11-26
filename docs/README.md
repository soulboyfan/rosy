# Rosy - Browse, Watch, and Chat Together

<p align="center">
  <img src="assets/icon.png" width="88" alt="Rosy icon">
</p>

[中文](README_ZH.md) | **English**

Rosy is a browser extension: open a room, share the room code with friends, and everyone can browse the same pages, watch videos in sync, and chat in real time. No account needed — just install and you can use it.

## Features

### Watch videos together

When the host plays, pauses, seeks, or changes playback speed, everyone's video follows instantly. Works with major video sites, and we've done our best to support tricky cases like pre-roll ads, video preloading, and iframe-based players.

### Browse together

When the host switches to a new page, everyone's tab follows automatically, with video playback position restored. If a member navigates away from the host's page, they are pulled back forcefully.

### Real-time chat

A chat bubble on the right opens with one click, or press `/` to summon it. Messages fade away after about a minute, leaving no trace. In rooms with more than two people, nicknames are shown.

### Room management

Create or join a room in one click, with live status showing your role and how many people are online. Host can transfer their role to anyone; when the host leaves, the room closes automatically. Multiple tabs can join different rooms without interfering with each other.

### Reliable connection

Automatic reconnection on network drops — page position and video playback resume on their own, no need to rejoin. Members going offline and coming back are announced, without any manual handling.

## FAQ

<details>
<summary><b>Which browsers are supported?</b></summary>
Desktop Chrome and Edge for now. Other browsers are untested and unsupported.
</details>

<details>
<summary><b>How do I install it manually?</b></summary>
Enable Developer Mode in your browser's extension management page, then drag the downloaded zip file into the browser window.
</details>

<details>
<summary><b>Is there a room size limit?</b></summary>
No practical limit.
</details>

<details>
<summary><b>The default server is unreachable?</b></summary>
Switch to another node in "Settings → Custom Server". Everyone in the room must use the same server.
</details>

<details>
<summary><b>Which video sites are supported?</b></summary>
Online video sites should all work. If you run into problems, please report them.
</details>

<details>
<summary><b>How is this different from remote control?</b></summary>
Rosy works at the level of the browser's current tab and only transmits the necessary commands, using minimal bandwidth. Please close your room when you're done to save server resources.
</details>

<details>
<summary><b>Is it free?</b></summary>
Yes, made for love.
</details>
