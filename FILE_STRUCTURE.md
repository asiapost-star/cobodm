# SUNSEMI Official Website - File Structure

## Root Directory
```
sunsemi-official/
├── index.html                          # Smart redirect page (IP-based)
├── FILE_STRUCTURE.md                   # This file
│
├── en/                                 # English site (to be developed)
│   └── (pending)
│
└── ja/                                 # Japanese site
    ├── index.html                      # Homepage
    │
    ├── fcob-led/                       # Product overview
    │   ├── index.html                  # Product category list
    │   │
    │   ├── single-color/               # Single Color Series
    │   │   ├── index.html              # Category page (5 products)
    │   │   ├── 320d-24v-5mm.html       # Product detail
    │   │   ├── 320d-24v-8mm.html       # Product detail
    │   │   ├── 320d-24v-8mm-color.html # Product detail
    │   │   ├── 480d-24v-5mm.html       # Product detail (pending)
    │   │   └── 480d-24v-8mm.html       # Product detail (pending)
    │   │
    │   ├── cct/                        # CCT Series (pending)
    │   │   └── index.html
    │   │
    │   ├── rgb-series/                 # RGB Series (pending)
    │   │   └── index.html
    │   │
    │   ├── mini-size/                  # Mini Size Series (pending)
    │   │   └── index.html
    │   │
    │   ├── high-efficiency/            # High Efficiency Series (pending)
    │   │   └── index.html
    │   │
    │   ├── high-power/                 # High Power Series (pending)
    │   │   └── index.html
    │   │
    │   ├── long-run/                   # Long Run Series (pending)
    │   │   └── index.html
    │   │
    │   ├── side-emitting/              # Side Emitting Series (pending)
    │   │   └── index.html
    │   │
    │   ├── waterproof/                 # Waterproof Series (pending)
    │   │   └── index.html
    │   │
    │   ├── everywhere-cut/             # Everywhere Cut Series (pending)
    │   │   └── index.html
    │   │
    │   ├── short-cut/                  # Short Cut Series (pending)
    │   │   └── index.html
    │   │
    │   ├── pixel-spi/                  # Pixel SPI Series (pending)
    │   │   └── index.html
    │   │
    │   └── pixel-dmx/                  # Pixel DMX Series (pending)
    │       └── index.html
    │
    ├── technical/                      # Technical documentation
    │   ├── index.html                  # Technical top page (pending)
    │   ├── pse-guide/
    │   │   └── index.html              # PSE compliance guide
    │   ├── installation/               # Installation guide (pending)
    │   │   └── index.html
    │   └── faq/                        # Technical FAQ (pending)
    │       └── index.html
    │
    ├── applications/                   # Application examples (pending)
    │   └── index.html
    │
    ├── company/                        # Company information (pending)
    │   ├── index.html                  # Company overview
    │   ├── quality/                    # Quality management (pending)
    │   │   └── index.html
    │   ├── privacy/                    # Privacy policy (pending)
    │   │   └── index.html
    │   └── terms/                      # Terms of use (pending)
    │       └── index.html
    │
    ├── downloads/                      # Download center (pending)
    │   └── index.html
    │
    ├── news/                           # News (pending)
    │   └── index.html
    │
    └── contact/                        # Contact form
        └── index.html
```

## Completed Files

### Phase 1: Core Structure (Completed)
1. `/index.html` - Smart redirect page with IP-based detection
2. `/ja/index.html` - Japanese homepage with mega menu
3. `/ja/fcob-led/index.html` - Product category overview

### Phase 2: Single Color Series (Completed)
4. `/ja/fcob-led/single-color/index.html` - Category page with 5 product cards
5. `/ja/fcob-led/single-color/320d-24v-8mm.html` - Product detail page example

### Phase 3: Technical & Contact (Completed)
6. `/ja/technical/pse-guide/index.html` - PSE compliance guide
7. `/ja/contact/index.html` - Contact form

## Pending Files (To Be Developed)

### Product Category Pages (12 categories)
- `/ja/fcob-led/cct/index.html`
- `/ja/fcob-led/rgb-series/index.html`
- `/ja/fcob-led/mini-size/index.html`
- `/ja/fcob-led/high-efficiency/index.html`
- `/ja/fcob-led/high-power/index.html`
- `/ja/fcob-led/long-run/index.html`
- `/ja/fcob-led/side-emitting/index.html`
- `/ja/fcob-led/waterproof/index.html`
- `/ja/fcob-led/everywhere-cut/index.html`
- `/ja/fcob-led/short-cut/index.html`
- `/ja/fcob-led/pixel-spi/index.html`
- `/ja/fcob-led/pixel-dmx/index.html`

### Product Detail Pages (4 more for single-color)
- `/ja/fcob-led/single-color/320d-24v-5mm.html`
- `/ja/fcob-led/single-color/320d-24v-8mm-color.html`
- `/ja/fcob-led/single-color/480d-24v-5mm.html`
- `/ja/fcob-led/single-color/480d-24v-8mm.html`

### Technical Pages
- `/ja/technical/index.html`
- `/ja/technical/installation/index.html`
- `/ja/technical/faq/index.html`

### Company Pages
- `/ja/company/index.html`
- `/ja/company/quality/index.html`
- `/ja/company/privacy/index.html`
- `/ja/company/terms/index.html`

### Other Pages
- `/ja/applications/index.html`
- `/ja/downloads/index.html`
- `/ja/news/index.html`

### English Site
- `/en/index.html` (and all corresponding English pages)

## Design System

### Colors
- Primary: #1a237e (deep blue)
- Primary Light: #3949ab
- Secondary: #c9a227 (gold accent)
- Background: #f5f5f5
- Text: #333
- Text Light: #666

### Typography
- Font Family: Noto Sans JP
- Weights: 400, 500, 700

### Components
- Mega Menu: 520px width, dual-column
- Product Cards: 320px min-width, hover lift effect
- Spec Icons: 4-icon grid per card
- PSE Status: Orange badge (educational language)

## SEO Title Format
```
[Category/Model]｜FCOB LED｜SUNSEMI
```

## Language Rules
- Source code: No Chinese characters
- Japanese text: Hiragana, Katakana, Kanji
- HTML comments: English only
- PSE descriptions: Educational ("対象外", "自主確認")
