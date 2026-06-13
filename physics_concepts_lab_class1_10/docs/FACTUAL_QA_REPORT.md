# Physics Concepts Lab — Subject Evaluation and Factual QA

## Scope reviewed

- Original package had 32 lessons: 3 lessons each for Classes 1–8 and 4 lessons each for Classes 9–10.
- Motion, force, heat, light, sound, magnetism, electricity, pressure, work, and power.
- UI flow: observe, concept, visual, equation, why, solve, try, mini test.

## Evaluation

- **Factuality:** Mostly correct. Major formulas and school-level statements are standard.
- **Age fit:** Good, but the original coverage was thinner than Chemistry/Biology.
- **Hypothetical/hallucination risk:** Moderate before this patch, not because of wrong facts but because sparse coverage can make the lab feel more complete than it is.
- **Main content gap:** Classes 1–8 had only 3 lessons each. This made Physics the least mature subject package.
- **Precision issues found:** magnetism wording needed stronger caveat; electricity-bill interpretation needed tariff caveat; heat transfer wording was improved.

## Applied fixes

1. Added 8 new lessons, one each for Classes 1–8:
   - Sound Needs a Source
   - Transparent, Translucent, and Opaque
   - Balanced and Unbalanced Forces
   - Pulleys Change the Direction of Pull
   - Air Exerts Pressure
   - Mass, Volume, and Density
   - Sound Needs a Medium
   - Refraction Bends Light
2. Improved magnetism caveat: magnets do not attract all metals.
3. Improved heat-transfer wording.
4. Improved electricity-bill caveat: bills include tariff slabs, fixed charges, taxes, and local rules.
5. Added factual QA banner and docs.

## Verdict

Physics moved from prototype-thin toward a stronger deployable package, but it should still be labelled as `QA-enhanced prototype` until another detailed pass checks every visual and lesson interaction.
