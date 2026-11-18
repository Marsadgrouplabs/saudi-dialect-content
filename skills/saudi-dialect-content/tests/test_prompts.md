# Test Prompts

Use these to evaluate the skill.

## Test 1 — Saudi national ad
Prompt:
"اكتب كابشن سعودي لإعلان تطبيق توصيل، الجمهور كل السعودية، شبابي لكن مش
أوفر."

Expected:
- SAUDI_NEUTRAL
- intensity 2
- no strong Jeddah/Riyadh mixing
- no Egyptian residue

## Test 2 — Jeddah fitness
Prompt:
"حوّل: متستناش الحماس، ابدأ دلوقتي. لجيم في جدة، ريل."

Expected:
- HIJAZI_URBAN
- intensity 2
- semantic rewrite, not word swap
- likely forms such as دحين / تبغى only if natural

## Test 3 — Riyadh SaaS
Prompt:
"Headline for a Saudi B2B SaaS in Riyadh, Arabic conversational."

Expected:
- NAJDI_MODERN
- intensity 1–2
- restrained dialect, business-safe

## Test 4 — Hail local
Prompt:
"اكتب حوار قصير بين شابين من حائل، محلي بوضوح."

Expected:
- HAIL_SHAMMARI
- intensity 3–4
- may use وشوله/الوكاد/غاد etc.
- not national-brand style

## Test 5 — Southern unspecified
Prompt:
"اكتب باللهجة الجنوبية إعلان مطعم."

Expected:
- SOUTHERN_GENERAL
- avoid fake hyperlocal Jazan/Asir markers
- keep dialect light unless city is known

## Test 6 — Audit mixed dialect
Input:
"وش تبغى تسوي دحين؟ أبي أقولك عن عرض مرّة رهيب."

Expected:
- flag mixed strong Najdi/Hijazi anchors
- offer a coherent Najdi and/or Hijazi version

## Test 7 — Formal medical
Prompt:
"SMS موعد مستشفى في السعودية باللهجة السعودية."

Expected:
- intensity 0–1
- clarity first
- not slang-heavy

## Test 8 — English code switching
Prompt:
"Reel caption for a recovery zone in a premium Saudi gym."

Expected:
- English term allowed if category-native
- Arabic still dominates
- no decorative random English
