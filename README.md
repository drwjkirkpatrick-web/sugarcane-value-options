# Turning Sugarcane Waste into Value

A grounded research paper on extracting value from sugarcane bagasse and other
mill by-products — with Hawaii's 150-year sugar industry as the worked case
study, and Kenya's current situation as the target.

**Deliverable:** [`paper/sugarcane_value_options.pdf`](paper/sugarcane_value_options.pdf)
— 17 pages, 68 cited sources, LaTeX source included.

## What's in it

- **What Hawaii actually did** — bagasse cogeneration sold to the grid (the
  reason the plantation survived as long as it did, and the reason it closed
  when the power contract was amended), molasses-to-rum, the failed
  fibre-to-ethanol attempt on Kaua'i, and what replaced sugar on the land.
- **Kenya's documented starting point** — 38 MW already installed across six
  mills, Mumias's 26 MW grid export and why it stopped, the 3,000 TCD → 15 MW
  economics, the new 50,000-acre estate targeting 13 M litres of ethanol and
  25 MW, and the Sugar Act 2024 by-product compensation change.
- **13 conversion routes**, each with evidence, requirements, and an honest
  read: briquettes/carbonised fuel, black soldier fly larvae, ruminant feed,
  anaerobic digestion, biochar, 2G bioethanol, sugarcane wax/policosanol,
  board & composites, mushrooms, vermicompost, activated carbon, poultry
  litter, and PHA bioplastics.
- **A comparison table** ranking routes by capital, technical risk, time to
  cash, and fit for a fibre supplier rather than a mill owner.
- **The four failure modes** — seasonality, pretreatment cost, no buyer, and
  feedstock ownership — each drawn from a documented case.
- **A suggested order of enquiry** that buys information cheaply before
  committing capital.

## Grounding

Every figure is attributed to a retrieved source with a numbered inline
citation. Sources were registered in a citation ledger at retrieval time
(`citations/ledger.json`), and where a verbatim supporting sentence was
captured, it is quoted beneath its URL in the paper's Sources section. Claims
that could not be grounded are marked `[unverified]`.

## Layout

```
paper/
  sugarcane_value_options.tex   LaTeX source
  sugarcane_value_options.pdf   compiled paper
  sources_block.tex             generated from the ledger (not hand-typed)
citations/
  ledger.json                   retrieval ledger: id -> url -> quotes
research/
  pages/                        fetched page text (evidence base)
  batch*.json                   raw search results per topic
```

## Rebuilding

```bash
cd paper
pdflatex -interaction=nonstopmode sugarcane_value_options.tex
pdflatex -interaction=nonstopmode sugarcane_value_options.tex
```

## Caveat

This is a literature and document survey, not engineering due diligence. Yield
figures come from studies in other countries and climates and transfer
imperfectly; financial figures are indicative categories. No route has been
costed for a specific site, water supply, transport distance, or tariff.
