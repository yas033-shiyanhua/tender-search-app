# Tender Search App

Find US government and school tenders you are actually qualified to bid on.

**Live demo:** https://muse.ai/s/tender-search-prototype-xzxh6xu28gl9qxt/v5TwIQP0G5AHKPrLOX58FLGNH6QOvVLh4qOlbkAoaO8

## What it does

- **Step 0 — Who you are:** US status (citizen / green card / other + country) and whether you hold a US company (LLC / Corp), asked first.
- **Step 1 — Qualification checklist:** US company → EIN → SAM.gov → SBA → US-made / Berry → ISO 9001 → bond → past performance. Tap `?` next to any item to see how to get it, what it costs, and what it unlocks.
- **Your pool:** a lit blue bubble shows the tenders you can bid on now. Grey bubbles show the bigger pools you could reach by adding one or two qualifications — tap a bubble to see what is missing.
- **Near-miss only:** tenders missing 1–2 qualifications are shown as near-miss, with the pool gain if you add that qualification. Tenders missing 3+ are hidden — showing them would be meaningless.
- **Tender cards:** title + Due date (MM/DD/YYYY). Tap to expand: buyer, type, what is needed, what is missing, price / quantity (shown only if published, otherwise "not published — see solicitation attachments"), and a source link with a copy-link button.
- **EN / 中文 toggle** at the top — one language at a time, no mixed lines.

## Who it is for

Small factories and suppliers — starting with fabric / textiles (towels, apparel, uniforms, flags) — who want to sell to US schools, universities, and government buyers. Other categories (construction, IT, food, cleaning, etc.) use the same logic with different category and qualification lists.

## Important — read this

- **US company ≠ US-made.** A US LLC lets you bid as a US entity, but goods made in China are still not US-made. Berry Amendment / Buy American tenders need US-made goods.
- **This app does not submit bids.** Government tenders need a real company, SAM.gov registration, signatures, and sometimes bonds. The app finds, filters, and drafts — a human reviews and submits.
- **For reference only, no legal liability （仅供参考，不具法律责任）.** Qualification help, tax / tariff estimates, and bid guidance are reference information, not legal advice.
- **Price / quantity:** many tenders do not publish a price or quantity in the listing. The quantity is in the solicitation attachments, or the contract is unit-price / indefinite-quantity. Check the solicitation and ask questions before the questions deadline.

## Try it

Open `index.html` in a browser. No build step, no server, no account — it is a single self-contained HTML file with 8 real seed tenders.

## Status

Phase 1 prototype (Nov 2026). Not yet built: bid-price / tax calculator, AI bid drafting, accounts / login, live daily tender updates.
