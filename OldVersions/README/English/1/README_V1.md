
***

# AI2001 API

`🧠️🖥️2️⃣️0️⃣️0️⃣️1️⃣️🔵️🟤️ The API for the AI2001 Artificial Intelligence software suite.`

## Status

The AI2001 API is far from ready, and is still in the early draft phase. I worked on it on and off for about a month, but never got the needed spark to get it where I wanted the idea to be. I will not rush such an important feature, so suggestions and improvements are welcome, and it won't go into the rough draft phase until absolutely ready. I gave myself the deadline of 2023 August 19th, but couldn't get it to the rough draft phase by then, so it was published in full in its alpha phase.

## Languages

The API will have multiple implementation languages, the current focus is to implement the API in Python. Other language goals include:

- C
- Julia
- Rust

***

## Early drafts (before 2023 August 19th)

Here are the early drafts of the API in full (note that there was an error in importing, the files were not properly saved, and there was a duplicate where V2 should be, and one file was not included in its own file (V1) so its sole appearance is in this file. All files are referenced by the wrong names, but all of the data is there.)

### Draft 1 ([2023, ?th](/API/Early-Drafts/AI2001_API_2023.08.07_V1.txt))

<details><summary><p><b>Click/tap here to show/hide draft 1</b></p></summary>

```plain-text
New AI2001 API under development
Future plans for 3rd party GPT-2 and GPT-3 support (although a bit outdated, they can still be useful for historical purposes) GPT-4 cannot be included, as it is proprietary software

AI2001

Dataset handling modes

3PARTY.GPT2
3PARTY.GPT3

Modes (actions)

🎞️ - Indicates this works in video mode
🖼️ - Indicates this works in image mode
🎵️ - Indicates this works in audio mode
📃️ - Indicates this works in text mode

Classification 🎞️🖼️🎵️📃️
Detection 🎞️🖼️🎵️📃️
Optimization 🎞️🖼️🎵️📃️
Upscaling 🎞️🖼️🎵️
Downscaling 🎞️🖼️🎵️
Filtering 🎞️🖼️🎵️📃️
Splitting 🎞️🖼️🎵️📃️
Cropping 🎞️🖼️🎵️
Realism 🎞️🖼️🎵️
Programming 🎞️🖼️📃️
Translating 🎞️🖼️🎵️📃️
Text entry 🎵️📃️
Converting 🎞️🖼️🎵️📃️
Noise reduction 🎵️

Modes (category)

Video mode 🎞️
Image mode 🖼️
Audio mode 🎵️
Text mode 📃️
```

</details>

---

### Draft 2 ([2023, August 7th](/API/Early-Drafts/NEWAPI_2023.08.12_AI2001_WORKWITHME.ai))

<details><summary><p><b>Click/tap here to show/hide draft 2</b></p></summary>

```plain-text
New AI2001 API under development
Future plans for 3rd party GPT-2 and GPT-3 support (although a bit outdated, they can still be useful for historical purposes) GPT-4 cannot be included, as it is proprietary software

AI2001

Dataset handling modes

3PARTY.GPT2
3PARTY.GPT3

Modes (actions)

🎞️ - Indicates this works in video mode
🖼️ - Indicates this works in image mode
🎵️ - Indicates this works in audio mode
📃️ - Indicates this works in text mode

Classification 🎞️🖼️🎵️📃️
Detection 🎞️🖼️🎵️📃️
Optimization 🎞️🖼️🎵️📃️
Upscaling 🎞️🖼️🎵️
Downscaling 🎞️🖼️🎵️
Filtering 🎞️🖼️🎵️📃️
Splitting 🎞️🖼️🎵️📃️
Cropping 🎞️🖼️🎵️
Realism 🎞️🖼️🎵️
Programming 🎞️🖼️📃️
Translating 🎞️🖼️🎵️📃️
Text entry 🎵️📃️
Converting 🎞️🖼️🎵️📃️
Noise reduction 🎵️

Modes (category)

Video mode 🎞️
Image mode 🖼️
Audio mode 🎵️
Text mode 📃️

Commands

Dataset integration
```

</details>

---

### Draft 3 ([2023, August 12th](/API/Early-Drafts/AI2001_API_V3_2023.08.12.ai))

<details><summary><p><b>Click/tap here to show/hide draft 3</b></p></summary>

```plakin-text
New AI2001 API under development
Future plans for 3rd party GPT-2 and GPT-3 support (although a bit outdated, they can still be useful for historical purposes) GPT-4 cannot be included, as it is proprietary software

AI2001 API

Implementation language: Python
Secondary languages: R, Julia, Rust, Cython

Dataset handling modes

3PARTY.GPT2
3PARTY.GPT3

Modes (actions)

🎞️ - Indicates this works in video mode
🖼️ - Indicates this works in image mode
🎵️ - Indicates this works in audio mode
📃️ - Indicates this works in text mode

Classification 🎞️🖼️🎵️📃️
Detection 🎞️🖼️🎵️📃️
Optimization 🎞️🖼️🎵️📃️
Upscaling 🎞️🖼️🎵️
Downscaling 🎞️🖼️🎵️
Filtering 🎞️🖼️🎵️📃️
Splitting 🎞️🖼️🎵️📃️
Cropping 🎞️🖼️🎵️
Realism 🎞️🖼️🎵️
Programming 🎞️🖼️📃️
Translating 🎞️🖼️🎵️📃️
Text entry 🎵️📃️
Converting 🎞️🖼️🎵️📃️
Noise reduction 🎵️

Modes (category)

Video mode 🎞️
Image mode 🖼️
Audio mode 🎵️
Text mode 📃️

Commands


Dataset integration

Flags

--classification | --videos
--classification | --images
--classification | --audio
--classification | --documents

--detection | --videos
--detection | --images
--detection | --audio
--detection | --documents

--optimization | --videos
--optimization | --images
--optimization | --audio
--optimization | --documents


--upscale | --videos
--upscale | --images
--upscale | --audio
--upscale | --documents # return: invalid

Additional options

# Videos
Define new resolution (X):
Define new resolution (Y):
Define new framerate:
# If any fields are left empty, it will keep it the same as the original

# For 3D videos (proposal only for now)

Define new resolution (X):
Define new resolution (Y):
Define new resolution (Z):
Define new framerate:

# If any fields are left empty, it will keep it the same as the original

# A lot of options missing, as I don't know how to enhance 3D videos yet.

# Images
Define new resolution:
Define new framerate:
# If either are left empty, it will keep it the same as the original

# Audio
Define new bitrate:
Define action: # Valid actions: Filtering, Realism, Noise reduction

# Documents
Documents cannot be upscaled. Only videos, images, and audio can be upscaled.

--downscale | --videos
--downscale | --images
--downscale | --audio
--downscale | --documents # return: invalid

Additional options

# Videos
Define new resolution (X):
Define new resolution (Y):
Define new framerate:
# If any fields are left empty, it will keep it the same as the original

# For 3D videos (proposal only for now)

Define new resolution (X):
Define new resolution (Y):
Define new resolution (Z):
Define new framerate:

# If any fields are left empty, it will keep it the same as the original

# A lot of options missing, as I don't know how to enhance 3D videos yet.

# Images
Define new resolution:
Define new framerate:
# If either are left empty, it will keep it the same as the original

# Audio
Define new bitrate:
Define action: # Valid actions: Filtering, Realism, Noise reduction

# Documents
Documents cannot be upscaled. Only videos, images, and audio can be upscaled.

--prompts | --programming

--Detection 🎞️🖼️🎵️📃️
Optimization 🎞️🖼️🎵️📃️
Upscaling 🎞️🖼️🎵️
Downscaling 🎞️🖼️🎵️
Filtering 🎞️🖼️🎵️📃️
Splitting 🎞️🖼️🎵️📃️
Cropping 🎞️🖼️🎵️
Realism 🎞️🖼️🎵️
Programming 🎞️🖼️📃️
Translating 🎞️🖼️🎵️📃️
Text entry 🎵️📃️
Converting 🎞️🖼️🎵️📃️
Noise reduction 🎵️

SCRAP THIS:

$ ai2001()
> # AI2001 session started
mode = linguistics
> > # Mode set to Linguistics
help()
> > return help()
classification /AI2001/?type=dir # Starts classifying a set of images in a folder/directory



Prompts

$ ai2001()
mode = chatbot()
# This will open a chatbot session



help()
# Work in progress

```

</details>

***

# File info

**File version:** `1 (2023, Saturday, August 19th at 5:31 pm PST)`

***

# File history

<details><summary><p><b>Click/tap here to expand/collapse the file history section</b></p></summary>

## Version 1 (2023, Saturday, August 19th at 5:31 pm PST)

<details><summary><p><b>Click/tap here to expand/collapse the file history section entry for version 1</b></p></summary>

- This release was created by [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> **Note** _The first version of this file._

> Changes:

- [x] Started the file
- [x] Added the title section
- [x] Added the `Status` section
- [x] Added the `Languages` section
- [x] Added the `Early drafts (before 2023 August 19th)` section
- - [x] Added the draft 1 section
- - [x] Added the draft 2 section
- - [x] Added the draft 3 section
- [x] Added the `File info` section
- [x] Added the `File history` section
- - [x] Added an entry for version 1
- [ ] No other changes in version 1

</details>

</details>

***
