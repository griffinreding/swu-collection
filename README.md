# SWU Collection

A one-page search for my Star Wars: Unlimited collection. Type a card name to see each variant I own and how many of each.

My coworkers often want to trade cards and I'm tired of manually checking every time. 

- `index.html`: the whole site (no build step).
- `inventory.txt`: my collection export (CSV: `count,name,subtitle,set,number,variant,...`).

## Updating the inventory

Replace `inventory.txt` with the new export (keep the same filename) and push.
On GitHub you can do this in the browser: open the repo → **Add file → Upload files** → drop the new file renamed to `inventory.txt` → **Commit**. The site updates within a minute or two.

## Running locally

    python3 -m http.server 8000   # then open http://localhost:8000
