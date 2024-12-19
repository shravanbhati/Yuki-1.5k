# Yuki 1.5k

Welcome to the public repository for **Yuki 1.5k**, the modernized and enhanced version of the Kaishi 1.5k Anki deck. Designed for beginners, **Yuki 1.5k** introduces foundational Japanese vocabulary in a modular format with numerous improvements for a smoother learning experience. This page explains the deck’s features and customization options to help you tailor it to your preferences.

Here is what the front of the deck looks like:

<img src="https://github.com/shravanbhati/Yuki-1.5k/blob/main/image/front.png" alt="Front of a Card in Yuki 1.5k" style="width: 100%; height: auto">

The deck presents the word and highlights it within the sentence, allowing you to focus on key information. The word comes first for quicker review once it’s familiar. Here’s the backside of the default deck:

<img src="https://github.com/shravanbhati/Yuki-1.5k/blob/main/image/back.png" alt="Back of a Card in Yuki 1.5k" style="width: 100%; height: auto">

Furigana provides the reading, followed by the word’s meaning. Both word and sentence audio are available, with additional options like pitch accent and notes for deeper understanding. 

### Table of Contents

- [Where Do I Get the Deck?](#where-do-i-get-the-deck)
- [What’s New in Yuki 1.5k?](#whats-new-in-yuki-15k)
- [Other Related Decks](#other-related-decks)
- [Customizing the Deck](#customizing-the-deck)
  - [Minor Customizations](#minor-customizations)
- [How to Import Yuki on Top of Another Deck](#how-to-import-yuki-on-top-of-another-deck)
- [The Genesis of the Deck](#the-genesis-of-the-deck)
- [Credits](#credits)

## Where Do I Get the Deck?

You can download Yuki 1.5k from the [releases](https://github.com/YukiNihongo/Yuki1.5k/releases/) page on GitHub or [AnkiWeb](https://ankiweb.net/shared/info/1234567890) if it is available for public use. **Note:** The deck is supported on Anki 2.1.50+.

## What’s New in Yuki 1.5k?

Yuki 1.5k builds upon Kaishi 1.5k with several updates:

- **Improved Sentence Quality**: Enhanced example sentences for clarity and accuracy.
- **Optimized Audio**: Refined audio normalization for consistent quality.
- **Expanded Notes**: Additional insights and usage notes for words.
- **Enhanced CSS Styling**: A more modern look with better readability and dark mode support.
- **Pitch Accent Integration**: Streamlined options for pitch accent learners.

## Other Related Decks

We recommend combining Yuki 1.5k with the **Radicals Deck by ねむい**, which links kanji radicals in Yuki with their corresponding vocabulary. This deck introduces radicals as you progress, simplifying kanji learning. [Download it here](https://ankiweb.net/shared/info/1722008986).

## Customizing the Deck

Yuki 1.5k provides multiple customization options. To modify the deck, go to `Browse`, select a card, and click `Cards...` in the top right.

### Minor Customizations

#### Furigana
Remove furigana by deleting `furigana:` in the `Back Template`.

#### Changing Card Type
Modify the `Front Template` to adjust card type. Example:

- For word cards:
  ```HTML
  {{Word}}
  ```

- For sentence cards:
  ```HTML
  {{Sentence}}
  ```

#### Adjusting Styling
Edit the `Styling` section to modify fonts, colors, and layout. Example:

```CSS
.card {
  font-family: "Noto Sans JP", sans-serif;
  font-size: 44px;
  text-align: center;
}

b { color: #5586cd; }
```

## How to Import Yuki on Top of Another Deck

Follow these steps to merge Yuki 1.5k with an existing deck:

1. Import Yuki 1.5k using the `.apkg` file.
2. Export Yuki 1.5k as `Notes in Plain Text (.txt)`.
3. Delete the Yuki 1.5k deck.
4. Change the note type of the target deck to `Yuki 1.5k`.
5. Import the `.txt` file, ensuring correct field alignment.
6. Add tags for easier card management.
7. Delete cards not included in Yuki 1.5k, if desired.

## The Genesis of the Deck

Yuki 1.5k originated from feedback on Kaishi 1.5k. The community highlighted areas for improvement, prompting us to:

- Refine word selection using updated frequency dictionaries.
- Enhance sentence quality and translations.
- Normalize audio and ensure pitch accent accuracy.

“Yuki” (雪) means snow, symbolizing a fresh start and clarity. This deck aims to provide learners with a clean, intuitive foundation in Japanese.

## Credits

- Kaishi Deck - Foundational material and inspiration

Enjoy your journey with Yuki 1.5k!
