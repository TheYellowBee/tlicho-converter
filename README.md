# Tłı̨chǫ Yatı Converter

A simple, single-page web tool for converting Tłı̨chǫ Roman orthography into **Practical Syllabics** and **IPA** pronunciation.

🔗 **[Open the converter](https://theyellowbee.github.io/tlicho-converter)**

---

## What it does

- Type any Tłı̨chǫ word or phrase in Roman orthography
- Instantly see the **Practical Syllabics** equivalent
- Also shows the **IPA** (International Phonetic Alphabet) pronunciation
- **Hover any output symbol** to highlight the Roman letters it comes from
- Built-in special character panel — no Tłı̨chǫ keyboard needed
- **Dark mode** — follows your device's light/dark setting automatically
- Side-by-side layout on desktop, stacked on phone; fully offline after first load

## How to use

1. Open the link above in any browser
2. Type Tłı̨chǫ Roman text in the input box
3. Use the character buttons to add diacritics (ı̨, ǫ, ł, ɂ, etc.)
4. Copy the syllabics or IPA output with the Copy button

**Tip:** Nasal vowels (ǫ, ı̨) affect the syllabics output, and tone marks (à, ǫ̀) show up in the IPA — the more accurate your Roman input, the more accurate the output.

## Examples

| Roman | Syllabics | IPA |
|-------|-----------|-----|
| tłı̨chǫ | ᖇᐠᗱᐠ | /tɬʰ ĩ tʃʰ õ/ |
| whaèhdǫǫ̀ | ᒐᐁᐧᑐ̇ᐠ | /ʍ a ɛ̀ h t õ̀ː/ |
| sı̨ godı | ᓯᐠ ᗂᑎ | /s ĩ k o t i/ |

## About the Syllabics

Tłı̨chǫ is written today primarily in Roman orthography. A traditional syllabics system exists, based on the French/Catholic missionary tradition, but it doesn't distinguish all sounds of the language — for example, /j/ and /ch'/ share the same symbol, and fluent speakers infer the correct one from context.

The **Practical Syllabics** used in this converter is a proposed system developed by [languagegeek.com](https://www.languagegeek.com/dene/transdene/trans_dene_syllabarium.html) to more accurately represent Tłı̨chǫ sounds within the Unified Canadian Aboriginal Syllabics (UCAS) Unicode standard. It has not been officially adopted by the community — think of it as a demonstration of what syllabics *could* look like for Tłı̨chǫ.

## Technical notes

- Pure HTML + JavaScript, no frameworks, no server
- All syllabics data is embedded — works offline
- Based on the proposed **Tłı̨chǫ Practical Syllabics** system by languagegeek.com
- Handles all 41 letters of the Tłı̨chǫ alphabet including digraphs (ch, tł, kw', etc.)
- Long vowels, nasal vowels, low tone, and prenasalised stops (nd, mb) all supported

## About Tłı̨chǫ

Tłı̨chǫ (also known as Dogrib) is a Dene language spoken in the Northwest Territories of Canada by the Tłı̨chǫ people. It uses both a Roman orthography and a Practical Syllabics writing system.

---

*Built with care for the Tłı̨chǫ community · Made with [Claude](https://claude.ai) (Anthropic)*
