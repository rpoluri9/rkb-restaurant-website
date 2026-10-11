# RKB Restaurant Website

The public website for **RKB Restaurant** — the web-design companion to the
[restaurant-order-system](https://github.com/rpoluri9/restaurant-order-system)
Python + SQL backend.

## What it shows

- **Full menu** — Non-Veg (chicken, mutton, lamb, fish, biryanis),
  Veg (sambar, rice, dal, roti, ...), and a Kids Menu
  (plain/crispy/chocolate dosa, chicken nuggets, puri, chapathi, noodles) —
  every dish priced $10–$100
- **Live table bill** — add dishes, change quantities with +/− controls,
  watch the bill update: 25% family discount on bills above $200,
  then GST 10% + state tax 6% + sales tax 4%
- **Order journey demo** — move an order through
  placed → kitchen → preparing → ready → served
- **Customer-care delay flow** — polite "10 to 15 more minutes" notice
  with customer response buttons
- **Python + SQL architecture blueprint** of the backend system

## Tech

Pure HTML + CSS + JavaScript in a single self-contained file (`index.html`) —
no build step, no backend. Fully responsive: mobile, tablet, laptop, desktop.

## Run it

Just open `index.html` in a browser, or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Note

This is a static design demo / portfolio piece. The bill calculator and order
demo run entirely in the browser and save nothing.
