# Professional Network Visualiser

An interactive visualisation of my professional network built with Python and vis-network.js.

## What it does

- Maps every person in my network as a node, coloured by industry
- **Gold edges** = people I know directly
- **White dashed edges** = people I was introduced to, showing the chain of connection
- Click any node to open their LinkedIn profile directly
- Filter by industry, relationship type, who introduced me, or where we met

## Tech stack

- **Python** (pandas, hashlib, json) — data processing in Jupyter Notebook
- **Excel** — data source (`Network.xlsx`)
- **vis-network.js** — graph rendering
- **HTML/CSS/JavaScript** — self-contained output file

## How to run it

1. Clone the repo
2. Open `Network.ipynb` in Jupyter
3. Make sure `Network.xlsx` is in the same directory
4. Run all cells — this generates `final_network.html`
5. Open `final_network.html` in Chrome

Or just download `Network.html` and open it directly in Chrome — no setup needed.

## Background

I built this as my first data project to practise Python, data wrangling, and data visualisation. The idea came from wanting to actually see and explore my network rather than just scroll through LinkedIn connections.
