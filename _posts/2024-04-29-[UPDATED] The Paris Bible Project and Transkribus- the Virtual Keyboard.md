---
layout: post
title: "[UPDATED] The Paris Bible Project and Transkribus: the Virtual Keyboard"
subtitle: Each post also has a subtitle
gh-repo: daattali/beautiful-jekyll
tags: [PBP , software, Trasnkribus]
comments: false
---

# **[UPDATED] The Paris Bible Project and Transkribus: the Virtual Keyboard** 

Since [the original blog post](https://parisbible.github.io/2021-07-14-TheParisBibleProjectandTranskribusVirtualKeyboard/) on the virtual keyboard feature in Transkribus was published in 2021, a few things have changed, and it was time for an updated manual on how to use it. In the context of the Paris Bible Project, we find ourselves using two main categories of special characters: **diacritics** and **superscript letters.** Those were used by medieval scribes to denote an abbreviation within the text (see image below). 

<br>

<img src="/assets/Macron_example.png">

**The virtual keyboard is absolutely indispensable when working with old manuscripts, but also with newer ones.** Think, for example, of handwritten authorial notes, or shorthand, where abbreviations and idiosyncratic features are often used and may need to be transcribed as such, depending on what kind of research is being carried out. 

The virtual keyboard uses [**unicode blocks**](https://www.compart.com/fr/unicode/block) to code those special characters. Unicode blocks are made up of unicode characters, each with its own specific code; usually, something along the lines of: U+0… or U+A… and so on. In the case of the Paris Bible Project, we use eight main unicode blocks, since the special characters we need are spread out within several blocks, and not gathered into one:

- Combining Diacritical Marks (U+0300–U+036F)
- Letterlike Symbols (U+2100–U+214F)
- Latin Extended-A (U+0100–U+017F)
- Latin Extended-D (U+A720–U+A7FF)
- Latin-1 Supplement (U+0080–U+00FF)
- Unified Canadian Aboriginal Syllabics (U+1400–U+167F)
- General Punctuation (U+2000–U+206F)
- Supplemental Punctuation (U+2E00–U+2E7F)

<br>

### But how do we add only the characters we want from a specific unicode block?

In the Transkribus browser client (Transkribus Lite), to open up the virtual keyboard, you first need to open the document you wish to transcribe. Then, **in the bottom right-hand corner, click on the settings tab** (see image below).

<br>

<img src="/assets/VK_IMG1.png">

<br>

Once there, **click on “Virtual Keyboard” and type in the “Search unicode ranges” whichever unicode *blocks* you need (not characters; *blocks*).** For example: “Combining diacritical marks”. 

<br>

<img src="/assets/VK_IMG2.png">

<br>

This is where things are going to get a little trickier, since, as you can see on the image above, some characters do not show up in the “Add characters” tab. **Each blank button denotes one unicode character.** In the images above, the virtual keyboard has already been configured, but when you first enter a unicode block, you’ll get many, many more such blank buttons.

***Note:*** Not all unicode blocks show up as blank buttons, but some will. 

In order to clean up which characters you’ll need in your own virtual keyboard, and which ones you can discard, since you can’t see what they look like right off the bat, **you need to hover your mouse cursor over each blank button for a few seconds, until you see a miniature of the special character show up** (see image below). 

<br>

<img src="/assets/VK_IMG3.png">

#### This is an example showing the macro special character, a long line very often used by medieval scribes above letters to signify an abbreviation within a word. It’s a symbol absolutely essential in the context of the Paris Bible Project; not transcribing it is not an option.

Picking and choosing your own set of unicode characters is going to take some time, especially if you need a lot of those that, for some reason, do not appear in the “Virtual keyboard” interface on the transcription page. **Go slowly! If you mess it up and accidentally delete a character you needed, you’ll have to delete the entire block and start again from scratch!** 

Don’t forget to save!

***Note:*** Don’t worry! Once you start transcribing, all unicode characters will actually show up, making your life so much easier during the transcription process. You won’t need to guess.

<br>

## **Suggested citation:** 

Fournier, Alice. (29 April 2024).[UPDATED] The Paris Bible Project and Transkribus: the Virtual Keyboard. *Paris Bible Project*. https://doi.org/10.5281/zenodo.8040632. 

This post is published with a CC BY-SA-NC 4.0 International license.
