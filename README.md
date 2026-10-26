# CraftBar

**Your nutrition. Your decision. Your CraftBar.**

CraftBar is the business case our team built in two days at the **Career Evolution Games Week 2026**, a career training programme organised by the **Max Planck Society in Leipzig** (October 2026). Our task was to develop a product idea, size its market, build a financial plan and pitch it.

**▶ Live app demo:** https://&lt;your-github-username&gt;.github.io/craftbar/ *(enable GitHub Pages, see below)*

<p align="center">
  <img src="assets/pitch-title.png" alt="CraftBar pitch title slide: 'Your nutrition. Your decision. Your CraftBar.' with the product box in the centre and four icons: locally produced ingredients, fibers from restored ecosystems, re-claim control, 80000 subscribers in 5 years and EBIT 10.5 M" width="820">
</p>

*Title slide of our pitch.*

## The idea

A protein bar should be a healthy snack. But even with every ingredient listed on the back, it is hard to really know what you are putting into your body. If you want a fast, convenient and healthy snack today, you have to give up control over your nutrition and simply trust the producer.

**Not with us.** CraftBar takes the production of the bar from the factory to your home: it is a **kit to craft your own complete nutrition bar at home in 5 minutes**. Reclaim control over your nutrition, with quick convenience on your terms.

Target group at launch: **Gen Z in Germany**, a generation that deeply believes in combining health with convenience.

## The product

<p align="center">
  <img src="assets/craftbar-box.jpg" alt="The CraftBar weekly box: seven bar moulds, a bag of seasonal nut and seed mix and a bag of fruit-and-bean cream" width="380">
</p>

*Product visual of the weekly box (AI-generated image).*

### What is in the box

One weekly box makes **seven bars**:

| Part | What it is |
|---|---|
| **Nut and seed mix** | Rolled oats with a seasonal blend of European nuts and seeds, for example almonds, walnuts, hazelnuts, pistachios, pumpkin, sunflower, flax and hemp seeds. |
| **Fruit-and-bean cream** | A cream that carries what nuts can't, changing with the season: apple & borlotti bean (autumn), pear & chestnut (winter), strawberry & cannellini bean (spring), apricot & chickpea (summer). |
| **Seven reusable moulds** | Press the mixture into the moulds. Store the bars right in the mould or take them with you. |

### How it works

1. **Tell the app what you need.** Choose your diet and the nutrients you are short on.
2. **Get a tailored recipe.** The app picks the nut and seed blend and the cream for your needs and the current season.
3. **Craft your bars** at home in 5 minutes.
4. **Share** your recipe in the community.

### Nutrition

- Recommended amounts of all **macronutrients**.
- A **complete plant-based amino acid profile**.
- Naturally present **selenium, zinc and iron**, which support the immune system and energy levels. This benefits vegan customers in particular.

## Sustainability

- **Locally produced ingredients**, sourced directly from European producers.
- **Seasonal:** nuts fresh from the harvest and a cream that changes with the season.
- **Fibres from restored ecosystems.**
- **Plant-based** ingredients.
- **Reusable moulds.**

## What we did in two days

| Step | What we did |
|---|---|
| **Problem & product** | Defined the customer problem, designed the box and the app concept. |
| **Market sizing** | Estimated the German market with **two independent methods**: (1) diet groups, i.e. vegans and vegetarians, and (2) how often people eat vegetarian alternatives, based on the forsa *Ernährungsreport 2025* survey tables and population projections for 2030. |
| **Business model** | Weekly subscription box at **€20.99**; direct, local sourcing for a target **gross margin of 60 %**. |
| **Benchmarking** | Anchored growth and adoption assumptions in real-world comparables (yfood, Huel, KoRo, mymuesli, Feed., NielsenIQ launch data). |
| **Scenario analysis** | Combined 2 market-sizing methods × 4 drivers (start customers, boxes per customer, growth, spill-over to older generations) into **32 scenarios** to test how robust the plan is. |
| **App demo** | Built a clickable app prototype: calorie calculator, "craft your bar" recipe builder and community feed. |
| **Pitch** | Pitched the case. |

### Market and demographics (Germany, 2030)

We start in Germany, one of Europe's largest consumer markets.

Demographic data by generation, used for both market-sizing methods:

| Generation | Population 2030 | Vegan | Vegetarian | Eat veg. alternatives daily | Eat veg. alternatives often (incl. daily) |
|---|---:|---:|---:|---:|---:|
| **Gen Z** | 14,400,000 | 6 % | 14 % | 14 % | 56 % |
| Gen Y | 17,400,000 | 3 % | 5 % | 12 % | 43 % |
| Gen X | 17,500,000 | 1 % | 5 % | 8 % | 35 % |
| Boomers | 17,200,000 | 1 % | 5 % | 4 % | 17 % |

Resulting market size in potential customers:

| Generation | Method 1: vegans + vegetarians | Method 2: daily consumers of veg. alternatives |
|---|---:|---:|
| **Gen Z (core target)** | 2,880,000 | 2,016,000 |
| Gen Y | 1,392,000 | 2,088,000 |
| Gen X | 1,050,000 | 1,400,000 |
| Boomers | 1,032,000 | 688,000 |
| Older generations total (Y + X + Boomers) | 3,474,000 | 4,176,000 |

*Sources: diet shares and consumption frequency from forsa, Ernährungsreport 2025, Ergebnisse einer repräsentativen Bevölkerungsbefragung; population projections for 2030 are team data (Gen Z: Eurostat EUROPOP2025). Older generations enter the model only through a spill-over effect from Gen Z.*

### Key figures from the pitch

| | |
|---|---|
| Price | €20.99 per weekly subscription box |
| Gross margin | 60 % (target) |
| Subscribers | 10,000 in year 1 · about 80,000 after 5 years |
| EBIT | €10.5 million projected after 5 years |

### Financial model

<p align="center">
  <img src="assets/ebit-base-case.png" alt="Line chart of EBIT per year from Y1 (2030) to Y12 (2041), base case; EBIT turns positive in Y3" width="600">
</p>
<p align="center">
  <img src="assets/ebit-scenario-band.png" alt="Line chart of EBIT per year across 32 scenario combinations: worst, 25th percentile, median, 75th percentile and best, with break-even line" width="600">
</p>

*EBIT per year in the base case (top) and across all 32 scenarios (bottom), from our financial model.*

## The app demo

The demo is a single, self-contained HTML file in [`docs/index.html`](docs/index.html). No build step, no backend; it runs in any browser and on phones.

- **Calorie calculator:** estimates daily energy and macro needs and how many bars fit in.
- **Craft your bar:** pick your diet and the nutrients you are short on; the app builds a seasonal recipe and shows nutrients per bar, ingredient shares and allergens.
- **Community:** sample posts, likes, and sharing a recipe card to social media.
- **Seasons:** switch the season at the top. The recommended nuts and cream change, and the app colours shift gently with it (spring: pea and strawberry; summer: apricot and pistachio; autumn: apple and walnut; winter: chestnut and oat). Layout and controls stay the same, so there is nothing new to learn.

Community posts are sample content and nutrient values are rounded from public food-composition tables for illustration.

## How we used AI

Our slides, recipes and market information were supported by AI. We used it in two ways:

**1. Information collection.** AI assistants helped us find comparable companies and their growth figures, data from the forsa survey tables, population projections and launch benchmarks. Every assumption in our model has a real-world source, listed next to each input in the spreadsheet. We checked the sources and decided which numbers to use.

**2. Demo creation.** Instead of static mock-ups, we built a **working, clickable app** with an AI coding assistant, so the product can be tried rather than just described. The product visual of the box was also generated with AI.

## Repository structure

```
craftbar/
├── README.md            this file
├── assets/              title slide, product visual and financial charts used in this README
└── docs/
    ├── index.html       the app demo (served by GitHub Pages)
    └── .nojekyll
```

## Publishing the demo with GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under *Build and deployment*, choose **Deploy from a branch**, branch `main`, folder `/docs`.
4. After a minute the demo is live at `https://<your-github-username>.github.io/craftbar/`.

## Team

Created by Group 1 at the Career Evolution Games Week 2026, Max Planck Society, Leipzig.

| Name | Institute |
|---|---|
| Gewei Cao | Max Planck Institute for the Study of Crime, Security and Law, Freiburg |
| Mira Erhart | Max Planck Institute of Psychiatry, Munich |
| Elyès Gaaloul | Max Planck Institute for Terrestrial Microbiology, Marburg |
| Luisa Gensch | Max Planck Institute for Meteorology, Hamburg |
| Andres Tangarife-Escobar | Max Planck Institute for Biogeochemistry, Jena |
| Laura von Selzam | Max Planck Institute for the Science of Light, Erlangen |
