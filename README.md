# Partner Availability Solution

An interactive solution build for sharing real-time inventory availability with distributors and resellers through EDI and a partner portal, built on the Microsoft stack (Dynamics 365 Supply Chain Management, Inventory Visibility, Dataverse, Power Pages, Logic Apps and Power BI).

The scenario uses fictional companies: Kestrel Printing Systems (manufacturer), NorthStar Distribution and Meridian Supply (distributors), Pinnacle POS Solutions and Harbor Retail Tech (resellers).

## What it shows

| Tab | Purpose |
|---|---|
| Overview | The challenge, the outcome, the four-layer approach and who each company is |
| Architecture | Sources, availability, rules and outlets, with what each part does |
| Application stack | The same design on Dynamics 365 SCM, Business Central, NetSuite and SAP |
| Live engine | Naive per-SKU counting versus a shared parts pool for kits and conversions |
| Who sees what | Distributor, reseller and internal views of the same numbers |
| EDI 846 | An X12 004010 846 generated live from the engine |
| Build pieces | Configuration and code for each layer |
| Delivery plan | Fourteen-week plan with a pilot |
| Tests | Ten control tests that run against the engine |

## Run it

It is a single self-contained file. Open `index.html` in any browser, or publish it with GitHub Pages:

1. Push this folder to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. The site appears at `https://<your-username>.github.io/<repository-name>/` within a minute or two.

Each tab has its own link, for example `.../#engine` or `.../#edi`.
