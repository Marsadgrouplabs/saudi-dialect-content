---
name: saudi-dialect-content
description: >
  Write, rewrite, localize, audit, and adapt Arabic content for Saudi audiences
  using either a supra-local Saudi "white" dialect or a region-specific Saudi
  variety (Najdi/Central, Hijazi/Western, Eastern, Northern, Southern). Use for
  social media, ads, scripts, captions, customer service, landing pages, SMS,
  push notifications, influencer/UGC copy, and conversational brand writing.
argument-hint: "<content or brief> [region] [platform] [dialect-intensity 0-4]"
---

# Saudi Dialect Content Skill

Version: 1.0  
Research freeze: 2026-09-26

## Core principle

There is no single homogeneous "Saudi dialect". Saudi Arabic is a cluster of
regional varieties. For content work, choose the narrowest dialect that the
brief actually supports, and default to a modern supra-local Saudi register
("Saudi white" / koine-like) when the target is national or unspecified.

Never create "Saudi" by mechanically replacing Egyptian or MSA words with
random Gulf words. Rewrite the message as a Saudi speaker would naturally say
it in the requested register.

## 1) Resolve these variables before writing

Infer them from the user's request and conversation context. Ask only if a
missing variable would materially change the result.

- `REGION`
  - `SAUDI_NEUTRAL` — default for national Saudi audiences or unspecified city.
  - `NAJDI_MODERN` — Riyadh / central urban Saudi.
  - `QASSIMI_LOCAL` — Qassim-specific; use only when explicitly requested.
  - `HIJAZI_URBAN` — Jeddah, Makkah, Madinah; modern urban Hijazi.
  - `EASTERN_GENERAL` — Dammam/Khobar and broad Eastern audience.
  - `AHSA_LOCAL` — Al-Ahsa; use only when requested.
  - `QATIF_LOCAL` — Qatif/Siḥat/Tarout; use only when requested.
  - `NORTHERN_GENERAL` — northern Saudi, with conservative use of local markers.
  - `HAIL_SHAMMARI` — Hail/Shammar-specific; use only when requested.
  - `SOUTHERN_GENERAL` — broad south; keep regional markers light.
  - `ASIRI_LOCAL` — Asir; local-heavy only when requested.
  - `JAZANI_LOCAL` — Jazan; local-heavy only when requested.
  - `NAJRANI_LOCAL` — Najran; local-heavy only when requested.
  - `BAHA_LOCAL` — Al-Baha; local-heavy only when requested.

- `REGISTER`
  - corporate
  - premium/luxury
  - mainstream brand
  - youth/social
  - influencer/UGC
  - customer service
  - dialogue/character voice
  - formal public information

- `INTENSITY` (0–4)
  - `0`: MSA / formal Arabic, no deliberate dialect markers.
  - `1`: light Saudi flavor; mostly simple Arabic with Saudi rhythm.
  - `2`: natural conversational Saudi; best default for social/ads.
  - `3`: clearly regional Saudi; several region-specific markers.
  - `4`: hyperlocal/traditional; use only when the user asks for authentic
    local speech, dialogue, comedy, oral-history style, or a specific community.

- `PLATFORM`
  Social caption, X post, TikTok/Reel script, ad, landing page, WhatsApp/SMS,
  customer service, email, OOH, push notification, long-form, etc.

## 2) Default routing rules

1. If user says only "باللهجة السعودية" → `SAUDI_NEUTRAL`, intensity 2.
2. Saudi-wide campaign → `SAUDI_NEUTRAL`, intensity 1–2.
3. Riyadh → `NAJDI_MODERN`, intensity 2 unless the brand is very formal.
4. Jeddah/Makkah/Madinah → `HIJAZI_URBAN`, intensity 2.
5. Eastern Province without a city → `EASTERN_GENERAL`, intensity 1–2.
6. North/South without a specific city/tribal variety → use regional-general,
   not a hyperlocal imitation.
7. Government, legal, medical instructions, policies, safety, or formal public
   information → intensity 0–1 by default.
8. Influencer/UGC/dialogue may go to 3. Intensity 4 requires an explicit local
   target or source material from the user.

## 3) The five major Saudi dialect families

Academic and corpus work commonly identifies five broad regional families:
Central/Najdi, Western/Hijazi, Eastern, Northern, and Southern. Each contains
multiple local varieties. A 2026 nationwide Saudi speech-corpus project covers
more than 55 local varieties, so "one exact Saudi vocabulary" does not exist.

### A. Saudi Neutral / White / Supra-local

Purpose: national brands, multi-city campaigns, default Saudi localization.

Use:
- clear colloquial syntax
- common Saudi/Gulf-Arabian vocabulary only when broadly understandable
- short natural clauses
- mild markers such as: مو, الحين, ترى, مرّة, طيب, خلاص, عادي, تقدر, خلّك
  when they fit the brand
- neutral question structures that do not force a region when possible

Avoid:
- stacking strong regional markers in one sentence
- phonetic spellings that identify a very local variety
- old/heritage vocabulary unless context requires it
- random "Khaleeji" items merely to sound Saudi

A Saudi advertising study found evidence of an emerging supra-local koine with
Najdi and Hijazi influence, and local marked features were avoided in the
advertisements sampled. Treat that as a useful copywriting principle, not as a
claim that Saudi dialects have merged into one.

### B. Najdi / Central

Modern Riyadh anchors:
- وش = what
- أبي / تبي / نبي = want
- الحين = now
- مو / موب = not (distribution depends on structure and speaker)
- وين = where
- ليش = why
- ودي = I would like / I feel like
- ترى = note that / you know / actually
- صدق = really / truly
- طيب, خلاص, عاد, والله, مرّة as discourse/intensity resources

Grammar/pragmatics:
- verbal negation commonly uses ما.
- non-verbal negation can use مو/موب; local Najdi/Qassimi forms vary.
- do not force old/local affricated spellings into normal brand copy.
- Riyadh speech is not identical to Qassimi, Hail, Dawasir, or every Najdi
  community.

Qassimi/Hail-specific words belong in local mode, not default Riyadh copy.

### C. Hijazi / Western Urban

Modern urban anchors:
- إيش = what
- أبغى / تبغى / نبغى = want
- فين = where
- دحين = now
- ليش = why
- مو = not
- مرّة = very
- سيب / سيبه = leave it/him (more colloquial)
- أهرج / هرجة = talk / story-conversation (regionally marked)
- قوام = quickly (stronger/older local marker)

Grammar/pragmatics:
- urban Hijazi has a long descriptive tradition and is strongly associated with
  Jeddah/Makkah/Madinah.
- the future particle حـ is a documented Hijazi feature, but do not overuse
  phonetic forms in brand copy.
- use modern forms first; reserve older neighborhood vocabulary for dialogue,
  heritage, or explicitly local storytelling.

### D. Eastern

The Eastern region is internally diverse. Dammam/Khobar urban speech, Al-Ahsa,
and Qatif are not one interchangeable dialect.

For broad Eastern copy:
- keep it close to Saudi-neutral
- allow light Gulf/Eastern rhythm only if the brief supports it
- do not default to Qatifi or Hassawi markers for all Eastern audiences

Qatif-local examples include forms such as ويش / حق ويش and local vocabulary
documented in Qatif sources. Hassawi negation shows its own variation. These
belong in local mode.

### E. Northern

Northern Saudi includes several varieties; Hail/Shammari speech shares many
features with Najdi while retaining salient local vocabulary.

Hail/Shammari local examples:
- وشوله = why
- وشبلاك / وشنوحك = what is wrong with you
- وغدان = children
- الوكاد = the important thing / certainly
- مامن = there is none
- غاد = there
- دوك = take / here you go
- هقوتي = I think / I expect
- مشوين = a little while ago
- باتسر = tomorrow (strong local marker)
- حلولات = if only / I wish

Use these only when local northern/Hail voice is wanted. Do not sprinkle them
into national Saudi ads.

### F. Southern

"Southern" is the most dangerous family to fake because Asir, Jazan, Al-Baha,
Najran, Tihama, mountain and tribal varieties can differ strongly.

Rules:
- for `SOUTHERN_GENERAL`, stay near Saudi-neutral and use only light regional
  flavor.
- for local speech, require a specific subregion when possible.
- the `am-` definite article (replacing al-) is documented in some Tihami/Asiri
  and Jazan varieties; it is NOT a universal southern feature.
- Jazan contains multiple local dialects and distinctive local words/forms.
- never write exaggerated pseudo-southern speech merely for comic effect.

## 4) Saudi-neutral lexical anchors

Use naturally, never all at once.

- أبشر / أبشري — sure, consider it done, gladly
- حياك الله — welcome
- الله يحييك — response to welcome
- يعطيك العافية — thanks / appreciation / well done
- الله يعافيك — response
- ما قصرت — much appreciated / you did enough
- طيب — okay / well
- خلاص — done / enough / alright
- عادي — no problem / normal
- أكيد — of course
- تقدر — you can
- خلّك — stay/be
- لا يفوتك — don't miss it
- ترى — you know / note / actually (casual)
- مرّة — very (common in urban Saudi, but register-sensitive)
- صدق — really / truly (casual)
- والله — really / I swear / emphasis; use sparingly in brand copy
- بعدين — then / later
- الحين — now (leans Najdi but broadly understood)
- وين — where
- ليش — why
- مو — not

## 5) Register policy

### Formal / regulated
Prefer MSA or very light Saudi-neutral. Dialect can appear in headline/CTA but
not at the expense of precision.

### Mainstream brand
Intensity 1–2. Natural syntax > regional performance.

### Youth / social
Intensity 2–3. Short clauses, conversational questions, mild discourse markers,
and platform-native rhythm are appropriate.

### Influencer / UGC
Intensity 3 can be natural. Use fillers/discourse markers only when they help
voice. Do not turn every sentence into slang.

### Hyperlocal dialogue
Intensity 4. Use only the requested local profile. If authenticity matters and
the term is not in the references, verify it from a reliable Saudi source when
web access is available.

## 6) Orthography rules for written dialect

1. Use Arabic script by default.
2. Prefer readable conventional Arabic spelling for brand content.
3. Represent dialect mainly through vocabulary, syntax, and rhythm—not through
   excessive phonetic spelling.
4. Do not use Arabizi unless the user asks.
5. Do not add full diacritics unless needed to disambiguate a local term.
6. Avoid stretched spellings (مررررة, يلااا) unless the platform/tone asks for
   expressive social writing.
7. For local Eastern forms using چ/گ or highly local southern/northern
   pronunciations, write them phonetically only in local/dialogue mode.
8. Keep brand/product names exactly as the user provides them.

## 7) Arabic-English code-switching

Saudi social advertising is predominantly Arabic, with English switches used
selectively. Use English when:
- the audience genuinely uses the English category term (fitness, tech, beauty,
  product/UI terminology)
- it is a brand/product term
- translating it would sound less natural

Do not add English just to look trendy.

Good:
- جرّب الـ Recovery Zone بعد التمرين.
- حدّث الـ app وخلك جاهز.

Bad:
- خلّ تجربتك More Powerful عشان تحقق Better Results.

## 8) Localization from Egyptian Arabic, MSA, or English

Do semantic rewriting, not word replacement.

Bad process:
Egyptian sentence → replace "عايز" with "أبغى" → replace "دلوقتي" with "الحين".

Correct process:
1. identify the intended meaning and persuasion job
2. choose Saudi region/register/intensity
3. rewrite sentence structure naturally
4. apply only the markers needed
5. audit for dialect mixing and foreign residue

Egyptian residues to audit for national Saudi copy include:
- عايز
- أوي
- إزاي
- دلوقتي
- مش
- لسه (unless Hijazi use is intentional)
- بص / بصّ
- خالص as Egyptian intensifier
- بتاع

Some spellings/words may overlap with specific Saudi varieties, so do not apply
a blind banned-word list; check the selected region.

## 9) Dialect-mixing guardrail

Strong regional anchors must agree with the selected profile.

Examples:
- Najdi cluster: وش + أبي/تبي + الحين
- Hijazi cluster: إيش + أبغى/تبغى + دحين/فين

Do not casually stack:
- وش + تبغى + دحين
- إيش + أبي + باتسر
- Qatifi phonology + Riyadh vocabulary + Jazan local grammar

Mixed forms can occur naturally in real Saudi speech because of mobility and
koineization, but content localization should mix only when the brief calls for
a pan-Saudi voice or a real character whose speech is mixed.

## 10) Content-generation workflow

For every request:

### Step 1 — classify
Determine REGION, REGISTER, INTENSITY, PLATFORM, audience age, and brand tone.

### Step 2 — choose anchors
Select 2–5 lexical/syntactic anchors appropriate to the length. A one-line ad
often needs only one or two.

### Step 3 — draft from meaning
Write from the intended idea, not as a literal translation.

### Step 4 — dialect audit
Check:
- no Egyptian residue unless intended
- no non-Saudi Gulf marker unless region-appropriate
- no conflicting strong regional markers
- no heritage term in modern brand copy without reason
- natural gender/number agreement
- CTA sounds like real Saudi copy
- English terms are functional, not decorative
- readability is more important than "proving" the dialect

### Step 5 — output
Unless the user asks for analysis, return the requested copy directly.
If useful, give 2–3 variants with a short label such as:
- سعودي أبيض
- نجدي خفيف
- حجازي خفيف

Do not provide a linguistic lecture unless requested.

## 11) Audit mode

If the user gives existing Saudi copy and asks whether it sounds natural:

Return:
1. `Verdict`: natural / mostly natural / mixed / non-Saudi residue
2. `Detected profile`
3. `Problematic phrases`
4. `Suggested rewrite`
5. `Why` — concise, phrase-level explanation

Never claim a city-level origin from one weak marker alone.

## 12) Confidence policy

- HIGH: core grammar/terms supported by academic descriptions or repeated Saudi
  sources.
- MEDIUM: widely attested colloquial usage but region boundaries are fluid.
- LOCAL: use only when specific subregion is selected.
- UNCERTAIN: do not invent; verify or choose a safer neutral phrase.

If a user asks for a hyperlocal variety that the references do not cover well,
prefer saying "خلّيني أخليها جنوبية/شرقاوية خفيفة" rather than fabricating
hyperlocal slang.

## 13) Research-backed constraints

The skill is intentionally conservative because:
- Saudi dialect research consistently identifies five major regional groups.
- current nationwide corpus work covers 55+ local varieties.
- social and geographic mobility creates leveling and mixed supra-local forms.
- a Saudi advertising study found local marked variants were avoided in its ad
  sample and a Najdi/Hijazi-influenced koine was emerging.
- formal Saudi institutional Twitter data is still overwhelmingly MSA, so
  "Saudi audience" does not automatically mean heavy colloquial Arabic.
- Saudi Snapchat advertising data shows Arabic dominates and English
  code-switching is selective rather than constant.

See `references/source_notes.md` for the research basis and
`references/lexicon_core.csv` for the curated working lexicon.
