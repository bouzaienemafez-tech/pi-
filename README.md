# SCB Investor Gate

Public investor-facing dashboard for **SCB** (`Les Ciments de Bizerte`).

## Live links

- GitHub Pages: <https://bouzaienemafez-tech.github.io/pi-/>
- Repository: <https://github.com/bouzaienemafez-tech/pi->

## Purpose

This site turns the SCB project outputs into a clear investor decision gate. It summarizes:

- the financial deterioration of the company
- the stock market trajectory of the share price
- the predictive model outputs
- the final investor recommendation

## Files

- `index.html`: standalone dashboard ready to open in any browser
- `chart.umd.js`: local Chart.js bundle used by the dashboard

## Local preview

Open `index.html` in a browser, or run a local static server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000/
```

## Notes

- The site is intentionally static so it can run on GitHub Pages without a build step.
- The dashboard is written in French because it targets a Tunisian academic and investor audience.
