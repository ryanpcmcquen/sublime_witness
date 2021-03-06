## Witness color scheme for Sublime Text
Jon Blow's Emacs color scheme for Sublime Text.

There is also an [Emacs version](https://github.com/ryanpcmcquen/emacs_witness) (of course).

Here they are side by side:
![Side by side comparison](https://user-images.githubusercontent.com/772937/60928361-ef30f000-a261-11e9-92a5-215dece0a345.png)

For the best experience, be sure to set:

```json
    "block_caret": true,
```

In your `Preferences.sublime-settings`.

### Installation:

#### Package Control:

https://packagecontrol.io/packages/Witness%20color%20scheme

#### Manual install:

Linux:

    wget -N https://raw.githubusercontent.com/ryanpcmcquen/sublime_witness/master/Witness.sublime-color-scheme -P ~/.config/sublime-text-3/Packages/User

Mac OS:

    wget -N https://raw.githubusercontent.com/ryanpcmcquen/sublime_witness/master/Witness.sublime-color-scheme -P ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/

Windows:

    curl https://raw.githubusercontent.com/ryanpcmcquen/sublime_witness/master/Witness.sublime-color-scheme -o "%AppData%\Sublime Text 3\Packages\User\Witness.sublime-color-scheme"

### Twitch clips:
https://www.twitch.tv/naysayer88/clip/SpoopyEphemeralClipzTriHard

#### Known issues:

You may notice a few discrepancies between the [Emacs version](https://github.com/ryanpcmcquen/emacs_witness) and the Sublime version. Sublime doesn't categorize the same scopes that Emacs does, which makes certain syntax structures difficult to reproduce. If you have ideas on how to make it more closely match the original, please send in a PR!
