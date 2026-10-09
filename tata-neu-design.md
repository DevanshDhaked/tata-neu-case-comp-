# Tata Neu — Design Guide for the Neu Nights Deck

*Compiled 9 Oct 2026 for the CaseCom (IIM Raipur) Tata Neu case · Companion to `neu-nights.md` and `neu-nights-marketing.md`*

> **How these values were gathered.** Fonts, UI colours, corner radii, shadows and type sizes were read from the **live computed CSS of tataneu.com** (9 Oct 2026), so they are exact. The logo gradient, the pastel backgrounds and the deep purples were **sampled pixel by pixel** from Tata Neu's official logo file and its Google Play screenshots, so treat those as close approximations. Anything marked **(proposal)** is my suggestion for the deck, not something Tata uses. Tata Neu has no public brand book.

---

## 0. Quick start — 8 rules that get you 80% of the way

1. **One font: Figtree.** Bold for titles, SemiBold for labels and buttons, Regular for body.
2. **One action colour: Tata Neu purple `#8800EC`.** Use it for the thing you want the judge to notice: the key number, the CTA, the active step. Nothing else on the slide should be that colour.
3. **Quiet canvas.** Off-white `#FDFDFD` or white, headings `#1A1A1A`, body `#4D4D4D`, hairlines `#EAEAEA`.
4. **Rounded white cards.** 16 px radius, hairline border or a very soft shadow.
5. **The rainbow gradient is a garnish, not a background.** It belongs to the logo "N", the NeuCoin and thin accent bars only.
6. **Pastel "sky" backgrounds for big moments.** Tata's ads fade lavender, sky blue, apricot or orchid into white, top to bottom.
7. **One idea per slide.** A 1–2 line headline with the key number highlighted, then one visual.
8. **(proposal) Day vs night.** Slides about Tata Neu *today* use the light Tata Neu look. Slides about *Neu Nights* switch to a deep-indigo night palette built from Tata's own darkest tones. The colour change itself tells the story.

---

## 1. What Tata Neu looks like today

Tata Neu speaks in **two visual registers**, and the deck can borrow both.

| Register | Where you see it | Feel |
|---|---|---|
| **Product UI** | tataneu.com, the app's screens | Quiet, airy, utilitarian. White and off-white surfaces, grey text, rounded cards, one purple CTA. Colour comes from photos and product images, not from the interface. |
| **Marketing** | Play Store screenshots, banners, the app-download section | Playful and bright. Pastel gradient backgrounds, big centred headlines, glossy 3D props (purple NeuCoins, gift boxes, the NeuCard), phone mockups, the rainbow "N". |

**Personality in three words:** friendly, premium, rewarding. It's a fintech that wants to feel like a shopping treat.

---

## 2. Logo

- **Lockup:** a small "TATA" stacked above a larger "NEU", with the multicolour **"N" monogram** at the top right. The wordmark is black on light backgrounds and white on dark ("Negative" version).
- **The "N" on its own** appears as the NeuPass badge, on the NeuCoin and on the NeuCard.
- **Official file used on the site:** `Tata Neu - RGB - Identity - Negative.png` ([link](https://ik.imagekit.io/tatadigitalltd/Tata%20Neu%20-%20RGB%20-%20Identity%20-%20Negative_yRzSLW2jc.png)).

**Using it in the deck** (general good practice, since Tata's own rules aren't public):
- Use the official file. Never recolour, stretch, outline or redraw it.
- Keep clear space around it at least the height of the "N".
- White (negative) version on night slides; dark version on light slides.
- Minimum height on a slide: about 0.3 in.
- Put it in one consistent spot: title slide, plus small in the footer if you like.
- Add a small line on the title slide: *"Concept proposal for CaseCom 2026. Not affiliated with Tata Digital."*

---

## 3. Colour

### 3.1 Core UI colours (exact, from tataneu.com CSS)

| Token | Hex | Where Tata uses it | Use in the deck |
|---|---|---|---|
| `neu-purple` | **`#8800EC`** | "Login / Sign Up" button, links, active nav icon, primary buttons | Key numbers, the CTA, the active step, chart highlight |
| `neu-lavender-tint` | `#EFEAFB` | Soft selected/highlight surfaces | Highlight boxes, table header rows, chip backgrounds |
| `neu-lavender-200` | `#E6DEFF` | Secondary brand tint | Larger soft panels |
| `info-blue` | `#004591` | Text on the "Unlock offers, Get the App" banner | Rarely; info notes only |

### 3.2 Neutrals (exact)

| Token | Hex | Role on tataneu.com |
|---|---|---|
| `ink-900` | `#1A1A1A` | Headings, H1, button text |
| `ink-800` | `#2A2A2A` | Strong secondary text |
| `ink-700` | `#333333` | Secondary text |
| `ink-600` | `#4D4D4D` | **Body text** (most common text colour on the site) |
| `ink-500` | `#666666` | Muted text, captions |
| `line` | `#EAEAEA` | Search bar fill, secondary buttons, 1 px borders |
| `surface-2` | `#F5F5F5` | Subtle panels |
| `page` | `#FDFDFD` | Page background |
| `white` | `#FFFFFF` | Cards |

### 3.3 The logo gradient (sampled from the official "N")

The "N" runs left to right from **blue → violet → magenta → pink → coral → orange → amber**.

| Stop | Hex | Name |
|---|---|---|
| 0% | `#1F76FD` | Neu blue |
| 20% | `#7028FB` | Violet |
| 35% | `#C601CE` | Magenta |
| 50% | `#E70DA0` | Pink |
| 65% | `#FF3D5A` | Coral |
| 80% | `#FF692F` | Orange |
| 100% | `#FE9008` | Amber |

- **Short 3-stop version** for thin bars and small shapes: `#7028FB → #E70DA0 → #FE9008`.
- **Where to use it:** a 4–6 px accent bar, the NeuCoin icon, the Neu Nights wordmark, a progress ring. Never as a full-slide fill and never for body text.

### 3.4 Marketing pastels (sampled from the Play Store screenshots)

Every Play Store frame uses a **vertical gradient: saturated pastel at the top, fading to near-white at the bottom**.

| Name | Top | Middle | Bottom | Mood |
|---|---|---|---|---|
| Lavender | `#D6D0F4` | `#E3DFF8` | `#F5F3FD` | Default, rewards |
| Sky | `#C7E1F2` (deeper: `#A1CDE8`) | `#E5F0F9` | `#FFFFFF` | UPI, payments, morning |
| Apricot | `#FDD894` | `#FEE0AE` | `#FEEBCC` | Value, "your coins are powerful", evening |
| Orchid | `#E2AAF3` | `#EDC7F8` | `#FBF0FE` | Brands, cards |

**Nice coincidence for your journey slide:** Sky (morning) → Apricot (evening) → Night indigo (9 pm) maps a student's day straight onto Tata's own palette.

### 3.5 Deep tones (sampled)

| Token | Hex | Where it appears |
|---|---|---|
| `indigo-ink` | **`#1B024D`** | Headline text on Play Store frames (Tata doesn't use pure black there) |
| `neucard-plum` | `#3B2256` | NeuCard body (darker area) |
| `neucard-plum-light` | `#4D2D6A` | NeuCard body (lighter area) |
| `neucard-violet` | `#864AB2` | Highlights on the NeuCard |
| `pill-plum` | `#5A3E7C` | The "1 Tata NeuCoin = ₹1 Savings" pill |
| `neucoin-orchid` | `#B147B2` | The 3D NeuCoin |
| Headline highlight gradient | `#7928D2 → #CD27A9` | Gradient text on numbers like "50 Tata NeuCoins" |

### 3.6 Neu Nights night palette (proposal)

Built from Tata's darkest real tones so it still reads as Tata Neu.

| Token | Hex | Role |
|---|---|---|
| `night-bg` | `#1B024D` | Slide background (Tata's headline ink) |
| `night-surface` | `#3B2256` | Cards on night slides (NeuCard plum) |
| `night-raised` | `#4D2D6A` | Hover/selected cards, table header |
| `night-text` | `#FFFFFF` | Headlines and body |
| `night-muted` | `#D6D0F4` | Secondary text (lavender) |
| `night-accent` | `#B98BFF` | Purple text and links on dark. **New tint**: `#8800EC` is too dark to read on indigo |
| `win-amber` | `#FE9008` | Wins, prizes, the token, "unlocked" moments |
| `coral` | `#FF3D5A` | Secondary accent, used sparingly |

**Optional texture:** a few tiny white dots (stars) at 20–40% opacity on title and divider slides. Keep it subtle.

### 3.7 Contrast checks (WCAG)

| Text on background | Ratio | Verdict |
|---|---|---|
| `#8800EC` on `#FFFFFF` | 6.45 | ✅ Any size |
| `#8800EC` on `#EFEAFB` | 5.47 | ✅ Any size |
| White on `#8800EC` (button) | 6.45 | ✅ |
| `#4D4D4D` on `#FDFDFD` (body) | 8.31 | ✅ |
| `#666666` on white (captions) | 5.74 | ✅ |
| `#1B024D` on any of the four pastels | 9.7–13.3 | ✅ |
| White on `#1B024D` | 18.07 | ✅ |
| `#D6D0F4` on `#1B024D` | 12.21 | ✅ |
| `#B98BFF` on `#1B024D` | 7.05 | ✅ |
| `#FE9008` on `#1B024D` | 7.92 | ✅ Great for "win" numbers |
| `#FF3D5A` on `#1B024D` | 5.22 | ✅ |
| `#E70DA0` on white | 4.23 | ⚠️ Large text only (18 pt+) |
| `#8800EC` on `#1B024D` | 2.80 | ❌ Use `#B98BFF` instead |
| `#FE9008` on white | 2.28 | ❌ Never use amber as text on light slides |

### 3.8 Chart colours

- **Default rule: one colour points.** Highlight the series that matters in `#8800EC`; everything else in `#D6D0F4` (light) or `#BDBDBD` (grey).
- **If you need categories** (max 4): `#8800EC`, `#E70DA0`, `#FF692F`, `#1F76FD`.
- **On night slides:** highlight in `#FE9008` or `#B98BFF`; others in `#4D2D6A`.
- Gridlines `#EAEAEA` (light) / `#3B2256` (night). No 3D charts, no chart borders.

---

## 4. Typography

### 4.1 The font

- **Figtree** on every Tata Neu web surface (`FigtreeRegular`, `FigtreeSemiBold`, `FigtreeBold` loaded; Medium, Black and Italic exist but aren't loaded on the homepage).
- Fallback stack on the site: `Figtree, -apple-system, system-ui, sans-serif`.
- A custom font, `NeuKitFont`, also loads, most likely for icons.
- **Free on Google Fonts** (designed by Erik Kennedy, open licence): [fonts.google.com/specimen/Figtree](https://fonts.google.com/specimen/Figtree/about).

### 4.2 What the site actually uses

| Use | Size | Weight | Colour |
|---|---|---|---|
| H1 ("The power of the Tata ecosystem…") | 18 px / 24 px line | Bold | `#1A1A1A` |
| Body | 14–16 px | Regular | `#4D4D4D` |
| Buttons, links | 14 px / 20 px line | SemiBold | `#8800EC` or `#1A1A1A` |
| Nav labels | 12 px / 16 px line | SemiBold | `#4D4D4D` |
| Full scale seen | 12 · 14 · 16 · 18 · 20 · 24 px | | |

The UI is compact. The **marketing frames** are where headlines get big: 2–3 centred lines filling the top quarter of the frame.

### 4.3 Type scale for the deck (16:9, sizes in pt)

| Style | Size | Weight | Colour (light / night) | Notes |
|---|---|---|---|---|
| Hero number | 72–96 | Bold | `#8800EC` or gradient / `#FE9008` | One per slide, max |
| Slide title | 32 (min 28) | Bold | `#1A1A1A` / `#FFFFFF` | Max 2 lines, line spacing 1.1 |
| Eyebrow (kicker) | 12 | SemiBold, ALL CAPS, +1 pt spacing | `#8800EC` / `#B98BFF` | E.g. "THE DIAGNOSIS" |
| Lead / subtitle | 20 | Regular | `#4D4D4D` / `#D6D0F4` | One sentence |
| Card title | 18 | SemiBold | `#1A1A1A` / `#FFFFFF` | |
| Body | 14–16 | Regular | `#4D4D4D` / `#D6D0F4` | Line spacing 1.3 |
| Table text | 12–14 | Regular; header SemiBold | | |
| Footnote / source | 10 | Regular | `#666666` / `#D6D0F4` at 70% | Bottom left |

**Rules:** sentence case for titles (Tata's own UI headlines are sentence case). No italics, no underlines (except links). Never go below 10 pt.

### 4.4 Making the font work in PowerPoint / Google Slides

1. Download Figtree from Google Fonts and install **all** weights.
2. In PowerPoint on Windows, "Figtree SemiBold" may appear as its own font name. Pick it from the list instead of pressing Bold on "Figtree".
3. Embed fonts before sharing: *File → Options → Save → Embed fonts in the file* (Windows) or *PowerPoint → Preferences → Save → Embed fonts* (Mac).
4. In Google Slides, add it via *Font → More fonts → search "Figtree"*.
5. **Submit as PDF** if allowed. It locks the font, colours and layout.
6. If Figtree is impossible, use a geometric sans you have (Poppins or Montserrat look closest; Arial as last resort) and keep the sizes the same.

---

## 5. Layout patterns Tata uses

### 5.1 Website (desktop)

- **Header:** location picker on the left ("Borabazar Precinct, Mumbai" style), a wide **pill search bar** in the centre (`#EAEAEA`, rotating placeholder: "Search for Shoes / Headphones / Milk", gradient "N" inside it), a solid purple **"Login / Sign Up"** button and an avatar on the right.
- **Floating left nav rail:** a white rounded card with outline icons over labels: Home · More · NeuPass · NeuCard · Offers.
- **Hero:** a horizontal carousel of image-led banners (16 px radius). Photos with violet lighting; white bold copy over the bottom-left, e.g. "Get up to 10% Savings on all your shopping with NeuCard".
- **Tiles:** a bento-style grid of large image tiles (NeuPass, NeuCard, Finance, Electronics, Hotels), then "Handpicked for you" rails.
- **App download section:** a phone mockup in front of a **pink→orange gradient circle**, a pale lavender **Indian monument skyline** as line art behind it, and a QR code in a gradient-outlined box.
- **Bottom:** SEO paragraph, category and service link lists, social icons.

### 5.2 Website (mobile) and app

- **Bottom tab bar**: Home · More · NeuCard · Offers (active tab = filled purple icon + purple label).
- **App home** (from the phone mockup on the site): location + profile at the top, search bar, a **quick-action icon row** (Pay Bills, Recharge, Send Money, bigbasket), a **NeuPass tier card** (e.g. "LEGEND" with a gem, NeuCoins balance and an "Explore" button), then a **2-column tile grid** (Finance, Credit Cards, Electronics, Hotels) with 3D illustrations, and a bottom nav with a **dark centre Scan & Pay button**.
- Sticky soft banner at the bottom: "Unlock offers, Get the App" on light lavender-blue.

### 5.3 Marketing frames (Play Store)

Every frame follows the same recipe:
1. Pastel gradient background (section 3.4).
2. **Centred headline, 2–3 lines**, in indigo `#1B024D`, with the **key number in purple→pink gradient** ("**50 Tata NeuCoins** on your first Tata Neu UPI transaction").
3. Optional small **dark plum pill** below it ("1 Tata NeuCoin = ₹1 Savings").
4. A **phone mockup** filling the bottom 60–70%, sometimes with props spilling out of the frame (NeuCard, coins, gift boxes).
5. **White rounded callout boxes with a thin purple outline** pointing to features ("No limits on redeeming", "Earn & redeem across categories").
6. Partner strip at the very bottom (HDFC Bank | SBI Card) and a tiny "T&C apply".

**This recipe is perfect for your "Introducing Neu Nights" slide.**

---

## 6. Shape, spacing and elevation

| Property | Tata Neu value (exact) | Deck equivalent |
|---|---|---|
| Spacing unit | 8 px grid | Steps of 0.08 in (8 px at PowerPoint's 96 dpi) |
| Button radius | 8 px | ≈ 0.08 in |
| Secondary button / search radius | 12 px | ≈ 0.125 in |
| **Card radius** | **16 px** (most common card size) | ≈ 0.17 in |
| Large containers | 24 px, 32 px | ≈ 0.25–0.33 in |
| Avatars, icon wells | 50% (circle) | Circle |
| Border | 1 px `#EAEAEA` | 0.75 pt `#EAEAEA` |
| Card shadow | `0 1px 2px rgba(166,166,166,.3), 0 2px 6px 2px rgba(125,123,123,.15)` | Outer shadow, black, 85% transparency, 6 pt blur, 2 pt distance, 90° |
| Floating shadow (modals, hero) | `0 32px 64px -32px rgba(0,0,0,.2)` | Black, 80% transparency, 24 pt blur, 12 pt distance |
| Sticky bar shadow | `0 -4px 14px rgba(139,139,139,.33)` | Not needed in a deck |

**Rule:** shadows are almost invisible. If you can clearly see one, it's too strong. On night slides use no shadows; separate cards by colour (`#3B2256` on `#1B024D`).

**PowerPoint tip:** a rounded rectangle's corner scales with its size. Drag the yellow handle until the corner looks like ~0.17 in, then copy that shape instead of drawing new ones, so every card matches.

---

## 7. Icons and imagery

**Icons**
- Tata style: **outline, rounded ends, about 1.5 px stroke**, monochrome `#1A1A1A`; the active state is **filled purple**.
- Free look-alikes for the deck: Lucide, Phosphor (Regular), or Material Symbols Rounded (outline). Pick one set and stick to it.
- Put important icons in a 40–48 px circle of `#EFEAFB` (light) or `#3B2256` (night).

**Imagery Tata uses**
- **Glossy 3D props:** the purple NeuCoin with the gradient "N", purple gift boxes with orange ribbons, the deep-plum NeuCard.
- **Phone mockups** with black bezels, upright or slightly tilted.
- **Product photography** with violet/purple ambient light (earbuds, phones, hotel pools).
- **Brand logos in white circles**, arranged as a floating "bubble cloud" (Croma, Tata CLiQ, IHCL, Air India, BigBasket, Titan, Tanishq, Westside, Air India Express).
- **Line-art Indian monuments** in pale lavender as a background texture.

**For your deck**
- **Real Tata Neu screenshots** (for the diagnosis) go in a plain phone frame with a small source line: *"Source: Tata Neu app, Oct 2026"*.
- **Neu Nights mockups** should look native: Figtree, `#8800EC` CTA, 16 px white cards, the real bottom nav. That proves it fits *inside* the Tata Neu app, which the brief requires. **(proposal)** The home-screen entry card stays light; the game screen itself can go dark (night palette), since it's played at 9 pm.
- For 3D props (coin, token, moon, gift box), use free 3D icon packs or simple flat shapes with the gradient. Check each licence.
- Avoid stock photos of generic smiling students. Show phones, payments, chai, canteens, hostel rooms at night.

---

## 8. Components for the deck

| # | Component | Spec |
|---|---|---|
| 1 | **Eyebrow + title + lead** | 12 pt purple caps eyebrow → 32 pt bold title → 20 pt grey lead. Left-aligned, top-left of every content slide. |
| 2 | **Headline with highlight** | Title in ink; the key number or phrase in `#8800EC` (or the `#7928D2 → #CD27A9` gradient text fill). One highlight per title. |
| 3 | **Stat card** | White card, 16 px radius, hairline. Big number (48–64 pt Bold, purple) + 1-line label (14 pt grey) + optional 10 pt source. Use 3–4 in a row. |
| 4 | **Pill / chip** | Fully rounded. Light: `#EFEAFB` fill, `#8800EC` 12 pt SemiBold text. Dark: `#5A3E7C` fill, white text. Use for tags like "Native" / "Hand-off", "Open", "Suggestion". |
| 5 | **Callout tag** | White rounded box, 1 pt `#8800EC` outline, 12–14 pt text, connected to a mockup by a thin line. Straight from the Play Store frames. |
| 6 | **Tile / bento card** | 16 px radius cards in a 2- or 3-column grid; icon or 3D image top, SemiBold title, 1–2 lines of body. |
| 7 | **Phone mockup** | Black rounded bezel, screen ratio ~9:19.5. One phone per slide, max two for before/after. |
| 8 | **Step loop** | 4 numbered circles (Pay → Unlock → Play → Earn) joined by a thin line or arrow; active step in purple or amber. Each step: icon, 2–4 word label, 1 line of detail. |
| 9 | **Day-to-night timeline** | Horizontal band whose background moves Sky → Apricot → Night indigo; time stamps (9 am, 1 pm, 6 pm, 9:30 pm) as pills; "1 of 3 / 2 of 3 / 3 of 3" as progress dots; the 9:30 pm stop gets the amber glow. |
| 10 | **Table** | No vertical lines. Header row `#EFEAFB` (light) / `#4D2D6A` (night), SemiBold. Rows separated by 0.75 pt `#EAEAEA`. Highlight the key row with a purple left bar. |
| 11 | **Review / quote card** | Play-Store style: ★ rating, 1–2 line paraphrase in quotes, source line ("Play Store review, Aug 2026"). Use 2–3 for the diagnosis. |
| 12 | **Accent bar** | 4–6 px tall bar in the logo gradient, under the title or on the left edge of a key card. Max once per slide. |
| 13 | **Source footnote** | 10 pt `#666666`, bottom-left, above the footer line. |
| 14 | **Section divider** | Full-bleed pastel gradient (light sections) or night indigo (Neu Nights sections), big section number + title. |

---

## 9. Slide grid and master setup

**Canvas:** 16:9, 13.333 × 7.5 in (1280 × 720 px at PowerPoint's 96 dpi; export images at 1920 × 1080).

| Zone | Size |
|---|---|
| Side margins | 0.5 in |
| Top margin | 0.45 in |
| Title zone | top 1.4 in (eyebrow + title + lead) |
| Content zone | 1.6 in to 6.8 in from the top |
| Footer zone | bottom 0.35 in: source (left), "Neu Nights · CaseCom 2026" (centre, optional), page number (right) |
| Grid | 12 columns, 0.17 in (≈ 16 px) gutters |

**Masters to build:**
1. Title (night)
2. Section divider: light pastel and night versions
3. Content: light
4. Content: night
5. Big statement (one sentence, centred, 40–48 pt)
6. Two-column (text left, phone mockup right)
7. Full-bleed image / mockup
8. Appendix (dense, smaller type allowed: 12 pt)

**PowerPoint theme colours** (*Design → Variants → Colors → Customize Colors*):

| Theme slot | Hex |
|---|---|
| Text/Background – Dark 1 | `#1A1A1A` |
| Text/Background – Light 1 | `#FFFFFF` |
| Text/Background – Dark 2 | `#1B024D` |
| Text/Background – Light 2 | `#EFEAFB` |
| Accent 1 | `#8800EC` |
| Accent 2 | `#E70DA0` |
| Accent 3 | `#FF692F` |
| Accent 4 | `#1F76FD` |
| Accent 5 | `#FE9008` |
| Accent 6 | `#3B2256` |
| Hyperlink | `#8800EC` |
| Followed hyperlink | `#5A3E7C` |

**Theme fonts** (*Design → Variants → Fonts → Customize Fonts*): Heading **Figtree**, Body **Figtree**.

---

## 10. Suggested slide map for the Neu Nights deck

*Content comes from `neu-nights.md` (NN) and `neu-nights-marketing.md` (MKT). Trim to fit CaseCom's slide limit.*

| # | Slide | Theme | Layout & components | Content from |
|---|---|---|---|---|
| 1 | **Neu Nights** — "Turning chai payments into a nightly habit" | Night | Title master; gradient "N"-style wordmark; star texture; disclaimer line | — |
| 2 | Executive summary | Light | 4 stat cards: gap, feature, metric, cost (₹52/student/month) | NN "In one line" |
| 3 | What Tata Neu is today | Light | Two columns: "Native vs hand-off" table with pills + phone screenshot | NN §1 |
| 4 | **Diagnosis:** why it fails a 20-year-old | Light | 3 tiles (too serious · rewards don't reach students · no reason to return) + 2–3 review cards | NN §1 |
| 5 | **The core gap** | Light → pastel | Big statement slide, one sentence | NN §1 "core gap" |
| 6 | Introducing Neu Nights | Night | Play-Store-frame recipe: headline + phone mockup + callout tags | NN §2.1 |
| 7 | How it works | Night | 4-step loop: Pay → Unlock → Play → Earn | NN §2.1 |
| 8 | Rules & guardrails | Night | Table with highlighted rows; guardrail pills | NN §2.2, §2.7 |
| 9 | The rewards: everyday + rare prizes | Night | Stat cards (0.84% average, ₹34/month, 1-in-25 drink odds) + small odds table | NN §2.3, §2.4 |
| 10 | **The student's day** | Sky → apricot → night | Day-to-night timeline component | NN §3 |
| 11 | Getting students in | Light | 7 channel tiles (store screen, BigBasket, canteens, invite, fest, IPL, Croma) | MKT plan at a glance |
| 12 | Launch calendar | Light | Horizontal timeline Nov 2026 → Aug 2027 + "always on" band | MKT calendar |
| 13 | **Success metric** | Night | Hero metric card ("% of students opening Neu on 3+ days a week") + why-not-WAU note + supporting metrics + guardrails | NN §5 |
| 14 | Cost & what Tata gets back | Light | Cost table + 4 return tiles | NN §2.5, §2.6 |
| 15 | Risks & next steps | Light | Table with status pills (Open / Suggestion / Dependency) | NN §6 |
| 16 | Appendix: sources & assumptions | Light | Dense list, 12 pt allowed | NN & MKT sources |

### Brief coverage checklist

| The brief asks for | Where it lands |
|---|---|
| ONE core gap in the student journey | Slide 5 |
| The Diagnosis | Slides 3–4 |
| The Solution (one high-impact feature) | Slides 6–9 |
| The Journey | Slide 10 |
| The Metrics (primary success metric) | Slide 13 |
| Solution centred inside the Tata Neu app | Native-looking mockups on slides 6–7 |

Make the four required words (**Diagnosis, Solution, Journey, Metrics**) visible as eyebrows so judges can tick them off.

---

## 11. Voice, copy and naming

**How Tata writes (Play Store headlines):** number first, benefit second, 2–3 short lines. For example, *"Up to 5% Tata NeuCoins every time on Tata Neu UPI"*. Short, confident, no jargon.

**For the deck:**
- Titles are takeaways, not topics: *"Students pay 50+ times a month, but Neu rewards none of it"* beats *"Problem"*.
- One number per headline, highlighted.
- Quotes from users: paraphrase or keep under 15 words, always with the source.

**Spell brand names exactly**

| Write | Not |
|---|---|
| Tata Neu | TataNeu, Tata NEU, TATA neu |
| NeuCoins / Tata NeuCoins | Neu Coins, Neucoins |
| NeuPass (moving to "Tata Neu Rewards") | Neu Pass |
| NeuCard | Neu Card |
| Tata Neu UPI | Neu-UPI |
| BigBasket, BB Now, Croma, Tata CLiQ, Zudio, Westside | |

**Numbers:** use ₹, Indian units (lakh, Cr), e.g. "₹4,974 Cr loss", "5 Cr+ downloads", "1 NeuCoin = ₹1".

---

## 12. Do's and don'ts

| Do | Don't |
|---|---|
| Keep `#8800EC` for the one thing that matters on the slide | Colour every heading purple |
| Use the logo gradient as a thin accent | Fill whole slides or big shapes with the rainbow gradient |
| Use white space generously (Tata's site is very airy) | Fill every corner with icons |
| Keep shadows almost invisible | Use heavy drop shadows, bevels or 3D charts |
| Use real screenshots for "today" and native-looking mockups for Neu Nights | Mix in another app's UI style (e.g. GPay's) for your mockups |
| Paraphrase user reviews with a source line | Paste long review text |
| Keep text ≥ 12 pt on content slides | Shrink text to fit; cut words instead |
| Use amber `#FE9008` for wins on night slides | Use amber text on light slides (fails contrast) |
| Put `#B98BFF` for purple text on night slides | Put `#8800EC` text on indigo (unreadable) |

---

## 13. Tokens (for building the deck with code or another tool)

```json
{
  "font": { "family": "Figtree", "fallback": ["Poppins", "Montserrat", "Arial", "sans-serif"],
            "weights": { "regular": 400, "semibold": 600, "bold": 700 } },
  "color": {
    "light": {
      "primary": "#8800EC", "tint": "#EFEAFB", "tint2": "#E6DEFF",
      "ink900": "#1A1A1A", "ink600": "#4D4D4D", "ink500": "#666666",
      "line": "#EAEAEA", "surface2": "#F5F5F5", "page": "#FDFDFD", "card": "#FFFFFF"
    },
    "night": {
      "bg": "#1B024D", "surface": "#3B2256", "raised": "#4D2D6A",
      "text": "#FFFFFF", "muted": "#D6D0F4", "accent": "#B98BFF",
      "win": "#FE9008", "coral": "#FF3D5A"
    },
    "logoGradient": ["#1F76FD", "#7028FB", "#C601CE", "#E70DA0", "#FF3D5A", "#FF692F", "#FE9008"],
    "logoGradientShort": ["#7028FB", "#E70DA0", "#FE9008"],
    "headlineGradient": ["#7928D2", "#CD27A9"],
    "pastels": {
      "lavender": ["#D6D0F4", "#E3DFF8", "#F5F3FD"],
      "sky": ["#C7E1F2", "#E5F0F9", "#FFFFFF"],
      "apricot": ["#FDD894", "#FEE0AE", "#FEEBCC"],
      "orchid": ["#E2AAF3", "#EDC7F8", "#FBF0FE"]
    },
    "chart": { "highlight": "#8800EC", "muted": "#D6D0F4",
               "categorical": ["#8800EC", "#E70DA0", "#FF692F", "#1F76FD"] }
  },
  "radius": { "button": 8, "input": 12, "card": 16, "container": 24, "pill": 999 },
  "spacingUnit": 8,
  "typePt": { "hero": 80, "title": 32, "lead": 20, "cardTitle": 18, "body": 16, "small": 12, "eyebrow": 12, "footnote": 10 },
  "slide": { "widthIn": 13.333, "heightIn": 7.5, "marginIn": 0.5, "columns": 12, "gutterIn": 0.17 }
}
```

---

## 14. Caveats

- **Exact vs approximate.** UI colours, Figtree, type sizes, radii and shadows are exact (computed CSS, tataneu.com, 9 Oct 2026). Logo gradient stops, pastels and deep tones were sampled from images, so they may be off by a few shades.
- **Ignore `#0175C2`.** The site's `theme-color` meta tag is `#0175C2`, which matches Flutter's default template value. It's a leftover, not a brand colour.
- **Not Tata's:** the night palette's `#B98BFF` tint, the deck type scale, the grid, the slide map and the day-to-night idea are proposals.
- **Pages that didn't load:** the NeuPass page rendered empty in the browser, so the new "Tata Neu Rewards" tier visuals aren't covered.
- **Display lettering:** the italic purple "Experience" heading on the website is baked into an image; its font is unidentified. Stick to Figtree.
- **Trademarks:** the Tata Neu logo, NeuCoin and NeuCard are Tata's. Use them unaltered and only to identify the brand; add the "not affiliated" line.

---

## Sources

- [Tata Neu homepage](https://www.tataneu.com/) — inspected live: computed fonts, colours, radii, shadows, layout (9 Oct 2026)
- [Tata Neu logo file (Negative, RGB)](https://ik.imagekit.io/tatadigitalltd/Tata%20Neu%20-%20RGB%20-%20Identity%20-%20Negative_yRzSLW2jc.png) — gradient sampled
- [Tata Neu on Google Play](https://play.google.com/store/apps/details?id=com.tatadigital.tcp&hl=en_IN) — 8 store screenshots: pastels, headline style, props, callouts
- [Figtree on Google Fonts](https://fonts.google.com/specimen/Figtree/about) — font download and licence
