# Social Capital

A private, local-first visualization of your LinkedIn connections. Industries open into companies, and companies open into the people and titles inside them.

## Run it

Open `index.html` in a browser. Everything runs in the page, and your data is never uploaded.

1. Request your data from LinkedIn (Settings, Data privacy, Get a copy of your data) and choose Connections.
2. Drop `Connections.csv` onto the page, or the whole export zip. Zips, nested zips and gzip files all work.
3. Or press the demo button to try it with sample data.

Company logos load from public sources, so they only appear when the file is opened locally with internet access.

## What's inside

- **Map:** industry, company and people bubbles, plus a concentration panel.
- **Reach:** where your network can open doors.
- **Access:** a score per company.
- **Hiring:** recruiters, managers and executives by company.

## Limits

LinkedIn's export has no industry field, so industries come from keyword rules, which you can override. Settings are stored in your browser only.

## Roadmap

Adapters for more sources, a local MCP server, then an optional hosted version.
