# rime-sasanka

<head>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif+Bengali:wght@100..900&display=swap" rel="stylesheet">
</head>

[![Static Badge](https://img.shields.io/badge/%E3%9E%A2%E0%A6%B6-blue?style=for-the-badge&link=https%3A%2F%2Fanamitro.github.io%2Frime-sasanka)](https://anamitro.github.io/rime-sasanka)
<img src="cat.png" alt="drawing" width="300"/><img src="er.png" alt="drawing" width="200"/><img src="sasanka_blue.svg" alt="drawing" width="300"/>

- **Custom Phonetic Engine** It is a specialized Unicode Bengali input engine designed for the rime framework, focusing on a custom phonetic layout that prioritizes ease of typing.
- **Unique Transcription Rules** The engine uses a unique set of transcription rules specifically tuned for the Bengali language, aiming to provide a more intuitive experience than standard layouts.
- **Fixed layout** so that the user can type practically without looking at the screen if he chooses to.
- **Minor conjunct-related grammatical corrections** inbuilt.
- **Minimized input key strings** for faster typing.
- **Open Source Accessibility** Developed by Anamitro Biswas, the project is hosted on GitHub to allow for community contributions and transparent development of Bengali digital tools.  
- **Platform Support** As an ibus based tool, it is primarily designed for Linux environments, enabling seamless Bengali input across various applications and terminal emulators.
- **Works with wired/bluetooth remote keyboard, as well as UI.**


## Installation
Install [RIME](https://rime.im/download/) for your OS. Weasel for Windows etc. I do not recommend any. You'll find good options in the internet.

### TRIME, for Android
Install [TRIME](https://github.com/osfans/trime). Save the .yaml files to `/storage/emulated/0/rime`. Deploy.

### Windows
Save the .yaml files to C:\Users\Your_Username\AppData\Roaming\Rime

### MacOS
Save .yaml files in ~/Library/Rime/ directory on your Mac. Click "Deploy" in the Squirrel Rime menu bar icon.

### iOS
See [this page](https://blog.fernvenue.com/archives/configure-hamster-and-rime-on-ios/).

### Linux
#### For IBus:
Create a custom yaml file using terminal commands like mkdir -p ~/.config/ibus/rime && nano ~/.config/ibus/rime/default.custom.yaml

A better similar option might be my [ibus-table-sasanka](https://anamitro.github.io/ibus-table-sasankadeva).
#### For Fcitx5:
Place your custom configuration files in ~/.local/share/fcitx5/rime/

## Typing Manual

### Vowels

|  |  |  |  |
| --- | --- | --- | --- |
| <span style="font-family: 'Noto Serif Bengali', serif;">অ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">আ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ই</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ঈ</span> |
| <span style="font-family: 'Noto Serif Bengali', serif;">উ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ঊ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ঋ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ৠ</span> |
| <span style="font-family: 'Noto Serif Bengali', serif;">ঌ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ৡ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">এ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ঐ</span> |
| <span style="font-family: 'Noto Serif Bengali', serif;">ও</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ঔ</span> |  |  |

| একক | স্বরবর্ণ |  |  |
| --- | --- | --- | --- |
| A | AA/aa | I | II |
| U | UU | R | R< |
| LLi | LLi} | E | AI |
| O | AU |  |  |

| স্বরবর্ণ | -কার |  |  |
| --- | --- | --- | --- |
|  | a | i | ii |
| u | uu | < | << |
| } | }} | e | ai |
| o | au |  |  |

### Consonants

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| <span style="font-family: 'Noto Serif Bengali', serif;">ক</span> | <span style="font-family: 'Noto Serif Bengali', serif;">খ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">গ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ঘ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ঙ</span> |
| <span style="font-family: 'Noto Serif Bengali', serif;">চ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ছ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">জ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ঝ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ঞ</span> |
| <span style="font-family: 'Noto Serif Bengali', serif;">ট</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ঠ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ড</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ঢ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ণ</span> |
| <span style="font-family: 'Noto Serif Bengali', serif;">ত</span> | <span style="font-family: 'Noto Serif Bengali', serif;">থ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">দ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ধ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ন</span> |
| <span style="font-family: 'Noto Serif Bengali', serif;">প</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ফ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ব</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ভ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ম</span> |
| <span style="font-family: 'Noto Serif Bengali', serif;">য</span> | <span style="font-family: 'Noto Serif Bengali', serif;">র</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ল</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ব</span> | <span style="font-family: 'Noto Serif Bengali', serif;">শ</span> |
| <span style="font-family: 'Noto Serif Bengali', serif;">ষ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">স</span> | <span style="font-family: 'Noto Serif Bengali', serif;">হ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ড়</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ঢ়</span> |
| <span style="font-family: 'Noto Serif Bengali', serif;">য়</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ৎ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ং</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ঃ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ঁ</span> |

#### সাধারণ ব্যঞ্জনবর্ণ অ-কারান্ত রূপ ও যুক্তাক্ষরের প্রথম বর্ণ

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| k | kh | g | gh | Ng |
| c | ch | j | jh | & |
| T | Th | D | Dh | N |
| t | th | d | dh | n |
| p | f | b | v/bh | m |
| z | r | l | b | S |
| Sh | s | h | q | Q |
| y | { | ` | H | ~ |

#### যুক্তাক্ষরের পরবর্তী বর্ণ

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| K | Kh | G | Gh |  |
| C | Ch | J | Jh |  |
| Z | Zh | X | Xh | [ |
| V | Vh | W | Wh | > |
| P | F | w | Bh | M |
| ] | / | L | w |  |
|  | \s |  |  |  |
|  |  |  |  |  |

All conjunct second components can also be typed as
> \ (consonant as first component)

#### যুক্তাক্ষরের প্রথম বর্ণ

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
|  |  |  |  | n |
|  |  |  |  | n |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  | । |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |

### Assamese

| <span style="font-family: 'Noto Serif Bengali', serif;">ৰ</span> | <span style="font-family: 'Noto Serif Bengali', serif;">ৱ</span> |
| --- | --- |
| = | B |

### Sanskrit

| 𑁍 | ঽ | ৺ | ্ |
| --- | --- | --- | --- |
| # | hh | ^ | \ |

### Symbols

| ☸ | ₹ | $ | 🇮🇳 |
| --- | --- | --- | --- |
| @ | $ | $$ | ## |

### Zero Width Non Joiner
 _ (underscore)
 
 **Use:**
 
 | r\z | r_\z |
 | --- | --- |
 | <span style="font-family: 'Noto Serif Bengali', serif;">র্য</span> | <span style="font-family: 'Noto Serif Bengali', serif;">‍র‍্য</span> |
 | । z | r] |
 

Named after King Sasankadeva of Gauda (Bengal) of the 7th century. The logo is a Bengali "Śa", in bold Tiro Bangla font, like the designs of popular ibus-tables, colored as Bharata Mata's attire in Abanindranath Tagore's painting.

## Author
[Anamitro Biswas](https://anamitro.github.io)

**Email:** anamitroappu@gmail.com (feel free to get in touch if needed)

🇮🇳 Made in India

Copyright (C) 2021-2026 Anamitro Biswas. Licensed under LGPL 2.1.
