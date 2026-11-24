# visual-network

A private, local-first visualization of your LinkedIn connections. Industries open into companies, and companies open into the people and titles inside them.

## Run it

Open `index.html` in a browser. Everything runs in the page, and your data is never uploaded.

1. Request your data from LinkedIn (Settings, Data privacy, Get a copy of your data) and choose Connections.
2. Drop `Connections.csv` onto the page. `Positions.csv` and `Education.csv` are optional and add your own history.
3. Or press the demo button to try it with sample data.

Company logos load from public sources, so they only appear when the file is opened locally with internet access.

## What's inside

- **Map:** industry, company and people bubbles, plus a concentration panel.
- **Communities:** your LinkedIn groups and alumni networks, with eras and connection waves as extra views.
- **Reach:** where your network can open doors.
- **Access:** a score per company.
- **Hiring:** recruiters, managers and executives by company.

## Limits

LinkedIn's export has no industry field and does not show which connections share a group with you. Industries come from keyword rules, which you can override, and groups come from keywords or a member list you paste in. Settings are stored in your browser only.

## Roadmap

Adapters for more sources, a local MCP server, then an optional hosted version.
