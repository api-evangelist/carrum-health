# Carrum Health

Carrum Health operates a value-based Centers of Excellence (COE) platform that connects self-insured employers and their members with a curated national network of surgical, cancer and substance-use-care providers under upfront bundled payments. Founded in 2014, Carrum pairs a member-facing mobile and web application with a care-navigation team, so members move through a full episode of care with no deductibles, co-pays or surprise bills, and a 30-day warranty on each procedure.

**API posture:** Carrum Health publishes no public developer program — no developer portal, no documentation host, no OpenAPI/AsyncAPI/GraphQL definition, no SDKs, no CLI and no MCP server. The member application is backed by five internet-facing REST services (`core-service`, `care-service`, `message-service`, `price-service`, `upload-service`) whose `/api-docs` surfaces exist but answer HTTP 401 with an HTTP Basic challenge. `core-service` serves a real but **empty** A2A agent registry at `/.well-known/agents.json`.

- https://carrumhealth.com/
- https://my.carrumhealth.com/
- https://trust.carrumhealth.com/
- https://github.com/carrumhealth
- https://forgeglobal.com/carrum-health_stock/
