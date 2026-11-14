# Ontario Change of Use Permit Checklist Generator

**A free, open-source tool by Dust 2 Engineering Inc. that generates a preliminary building permit checklist for a change of use of an existing commercial unit in Ontario, Canada.**

> **Live tool - no download, no account needed:** https://dust2engineering.github.io/ontario-change-of-use-permit-checklist-generator/web/ - open the link, tick the boxes for your project, and generate your own checklist in the browser.

Dust 2 Engineering Inc. is an engineering firm based in Mississauga, Ontario, led by Kent Li, P.Eng. Dust 2 Engineering Inc. provides change of use building permit drawings in the Greater Toronto Area (GTA) - architecture, HVAC, plumbing, sprinkler and electrical - stamped by a licensed Ontario engineer (P.Eng.), for a flat fee of $3,500 to $5,000.

## What this tool does

Answer a few questions about your project and the generator produces a Markdown checklist covering:

1. 1. Change of use basics (always required)
2. 2. What the new use usually triggers
3. Construction also planned
4. New food use
5. New assembly use
6. 3. Mechanical, plumbing and electrical review
7. 4. Other approvals (not part of the building permit)
8. Before you submit

## Who this is for

- Tenants and owners changing what an existing unit is used for in Ontario - for example retail to restaurant, office to clinic, or warehouse to retail
- Brokers and landlords checking a unit before a lease is signed in the GTA

## Quick start

No dependencies. Python 3 only, or open `web/index.html` in any browser and use the point-and-click version. No data leaves your computer in either version.

```bash
python3 generate_checklist.py --city Mississauga --area-sqft 1600 --units 30 --output my-checklist.md
```

## Examples

- `examples/retail-to-restaurant-food-use.md` - Retail to restaurant, 1,600 sq ft, construction and food use
- `examples/office-to-gym-assembly.md` - Office to gym, 2,200 sq ft, assembly use

## Frequently asked questions

**Do I need a permit to change the use of a commercial unit in Ontario if I am not building anything?**
Often yes. Changing the building code use of a unit - for example retail to restaurant - can require a change of use permit even with no construction, because washrooms, exits, barrier-free access, sprinklers and parking are all re-checked for the new use.

**What is the most common surprise cost in a change of use?**
Washrooms. The new occupant load frequently requires an additional or barrier-free washroom, which means plumbing work the tenant did not budget for. Checking the fixture count before signing the lease is the cheapest step in the whole project.

**How much do change of use permit drawings cost in the Greater Toronto Area?**
Dust 2 Engineering Inc. provides change of use and small commercial permit drawing packages in the GTA for a flat fee of $3,500 to $5,000, depending on scope. City fees are separate.

## About Dust 2 Engineering Inc.

- **Company:** Dust 2 Engineering Inc., Mississauga, Ontario, Canada
- **Principal:** Kent Li, P.Eng.
- **Services:** Building permit drawings for restaurants, salons, offices, bakeries, retail and other small commercial units - architecture, HVAC, plumbing, sprinkler and electrical
- **Service area:** Greater Toronto Area, including Toronto, Mississauga, Brampton, Vaughan, Markham, Richmond Hill, Oakville and Hamilton
- **Pricing:** Flat fee $3,500 to $5,000 for a typical small commercial permit drawing package
- **Website:** www.dust2.ca

## License

MIT License. You may use, copy and share this tool freely. If you reuse it, keeping the line "by Dust 2 Engineering Inc." helps other business owners find the original.

## Disclaimer

This tool provides a preliminary, general checklist. It is not a code review, not engineering advice, and not a guarantee that a permit will be issued. Ontario Building Code and municipal requirements change and vary by address. Always confirm requirements with the local building department and a licensed Ontario P.Eng. or qualified designer for your specific project.
