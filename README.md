# alif-toolkit

[![Greenkeeper badge](https://badges.greenkeeper.io/Georeactor/alif-toolkit.svg)](https://greenkeeper.io/)

## Origin

When I made <a href="https://github.com/mapmeld/crossword-unicode">crossword-unicode</a>
 and <a href="https://github.com/mapmeld/wiki-crossword">wiki-crossword</a>
(which generates crossword puzzles from scraping random Wikipedia articles),
Arabic script posed some interesting challenges. I open sourced my work, but
it started me thinking about more general data and tools to make it easier to
build language games for Arabic-script languages.

Consider these game ideas:

- Crossword puzzles for younger students with names of animals
- Fill-in-the-blank where the neighboring letters should show connecting forms (for example "العَرَبِ_ة‎" vs "العَرَ بـ_ـة‎")
- A game where you add long vowels or tashkeel marks
- Games which show and hide tashkeel based on skill level
- Games which should support Arabic, Farsi, Urdu, and Pashto words

## Goals

- Open queryable word bank, based on Wikipedia and Wiktionary
- Multiple categories on words (animals / cities / countries)
- Shared word banks (visible to check for inappropriate words)
- Breakdowns of words into individual letters, glyphs (such as LA), text-shaped letters
- Tashkeel options
- English and Chinese translations

## Setup

- Download a Wikipedia no-pictures dataset from Kiwix
- npm install
- npm run import-words
- generate records into MongoDB

## Usage

TODO

- Fill-in-the-blanks example
- Animals crossword example

## Technology

MongoDB

## License

Content / data largely CC-BY-SA Wikipedia, Wiktionary, and Kiwix

Code open sourced under an MIT license
