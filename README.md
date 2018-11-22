# Media Keys for the masses
This project aims to give you global media keys (play, pause, next, previous, volume up/down, mute) if your keyboard doesn't support it.

The motivation of this very small repository is to give a way of providing global media keys shortcuts to be used by Spotify or any other players, when your keyboard doesn't have media keys by default (quite common in corporate environments (e.g. in the company that I'm currently working, they provided a smart-card bundled Fujitsu keyboard which doesn't offer the standard media keys)).

Also, I did this because I saw lots of over-complicated AutoHotKey scripts over the web for Spotify, trying to provide global shortcuts for it. As a long-term Winamp user (which contained an awesome built-in global hotkeys plugin - yes, I'm "old-school" haha), I missed the essential functionality of play, pause, next/prev track global hotkeys while using keyboards which don't provide these keys.

This is a no-frills, uncompromised, tiny AutoHotkey script, which provides mappings to common media keys, so, there's no need to provide over-complicated mappings depending on which player you rely on.

## Remarks
- By now, this is a Windows-only thing, to be used with AutoHotKey (https://www.autohotkey.com/)
- I'm a "right-handed" and prefer to use media keys with my right hand. The current script aims to use Alt-Gr + Function keys (F9~F12), but I'm open for suggestions through "GitHub Issues".
- If you want to customise it, feel free to download the script and adapt it to your needs.

## How to use it?
- First, install AutoHotKey in your pc (https://www.autohotkey.com/download/)
- Download/copy the "media-keys-for-the-masses.ahk" script and place it in an easy-reachable location in your pc (usually I put it at "C:\Users\Default" folder).
- Create a shortcut to the script in the following location to provide this awesomeness for all users: "C:\ProgramData\Microsoft\Windows\Start Menu\Programs\Startup"
- Restart your PC
- Profit!
