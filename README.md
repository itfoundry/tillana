# Tillana

Tillana is a refreshingly informal family of typefaces for Devanagari and Latin. The fonts were first published by the Indian Type Foundry as an open source project in 2014. Coming in at 1021 glyphs per weight, Tillana has all of the characters necessary to set a variety of European languages, as well as Indian languages like Hindi, Marathi, Nepali, and more. The Tillana family includes five styles, which range in weight from Regular through Extra Bold. Tillana’s Latin do not connect; this part of the family is a non-joining script type. The Devanagari part is one of the few “true cursive” designs currently available for the script.

Characters from both writing systems appear as if they were fluidly handwritten, particularly the Devanagari. Tillana’s letterforms are slanted at a 10 degree angle. The strokes are show visible contrast, and the dynamic counter forms are one of the design’s most prominent features. The forms involve many loops and hooks and most of the knots are loops rather than closed, black forms. All vertical strokes in both scripts have swelling at their tops and bottoms, and the Devanagari characters’ central vertical strokes almost always break through the headline. Handwriting artefacts are present in the Latin letters, too, such as hook on the descender of the lowercase q.

Tillana’s Devanagari base character height falls vertically between the Latin upper and lowercase letter heights. The Latin characters have a small x-height and long ascenders and descenders. Lipi Raval designed the Devanagari components of Tillana, and worked together with Jonny Pinhorn on the Latin.

## Code base

This working directory is forked from the common code base, [ITF Base Devanagari (for Google Fonts)](https://github.com/itfoundry/base-devanagari-gf).

## Dependencies

- [Adobe Font Development Kit for OpenType](http://www.adobe.com/devnet/opentype/afdko.html) (AFDKO), version 2.5 build 63209 (Sep 18 2014) or newer.
- A script [`UFOInstanceGenerator.py`](https://github.com/adobe-type-tools/python-scripts/blob/master/FDK%20Extras/UFOInstanceGenerator.py) (to be placed in AFDKO’s directory `FDK/Tools/osx`) and two [modules](https://github.com/adobe-type-tools/python-modules) (to be placed in Python’s `site-packages` directory) from Adobe.
