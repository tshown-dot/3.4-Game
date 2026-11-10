# Galactic Translator 👽

An alien-translation game for **enVision 2.0 · Grade 6 · Topic 3 · Lesson 3-4: Write Algebraic Expressions** (including the parts of an expression).

Aliens send messages in words. Students translate them into algebra by tapping tiles (or typing), then press TRANSLATE. If a translation is wrong, the ship runs a **Test Beam**: it plugs a number into both expressions so students can see that the meaning changed (for example, "6 less than x" with x = 10 is 4, but 6 − x is −4).

## Sectors (19 transmissions, about 10 minutes)

1. **Keyword Station:** one-operation phrases (sum, more than, product, quotient, twice, half of…)
2. **Backwards Belt:** phrases that flip the order ("6 less than x", "subtracted from", "the quotient of 8 and n")
3. **Double Signal:** two-step phrases, with and without parentheses ("3 more than 2 times n" vs. "2 times the sum of n and 3")
4. **Parts Lab:** terms, coefficients, constants, and variables. Students tap the part of the expression the alien asks for.
5. **Trading Post:** real-world situations ("$20 to join plus $12 per month for m months")
6. **Reverse Transmission:** given an expression, choose the phrase that means exactly the same thing

## Feedback that teaches

- Hints for specific mistakes: reversed subtraction/division, wrong operation, missing parentheses, mixing up which number multiplies the variable, and vocabulary mix-ups (coefficient vs. constant).
- Color-matched underlines show which words became which symbols.
- Any equivalent expression is accepted (`n + 5` or `5 + n`).
- Two misses bring up the correct translation and a backup message of the same type.
- The **Mission Report** at the end shows points, accuracy, sector stars, time, and "skills to sharpen."

Problems are randomly generated on every play. No student names or identifiers are collected; only a best score and the sound setting are saved on the device. It's a single `index.html` with no external libraries or fonts.

## Deploy on Render

1. In Render, choose **New → Static Site** and connect this repo.
2. Leave the **Build command** blank and set the **Publish directory** to `.`
3. Click **Create Static Site**.

Every push to `main` redeploys automatically.
