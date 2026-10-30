# India Landed Cost Estimator

A free interactive calculator that estimates the landed cost of goods sourced from India for the UK, EU, US, Australia and UAE. It breaks the total into freight, marine insurance, import duty, VAT or GST and customs clearance, and shows the result as a low to high range with a multiple of the FOB price.

**Live tool:** https://esthergonswork.github.io/Landed-Cost-Estimator/

Built for Rivexa buyers. Rates reviewed on 29 October 2026.

## What it covers

- **Destinations:** United Kingdom, European Union, United States, Australia and UAE
- **Categories:** apparel, home textiles, metal parts and castings, industrial machinery, electronics and plastic components
- **Shipment modes:** sea freight (LCL or FCL 20ft) and air freight
- **Optional freight quote:** enter a forwarder quote to replace the freight estimate
- **2026 trade rules:** India-UK CETA, India-Australia ECTA, India-UAE CEPA, EU standard duty (no FTA in force yet), US Section 301 and Section 232, and a CBAM note for EU metal imports

## How the estimate works

Landed cost is FOB value plus freight, marine insurance (0.8% of CIF), import duty (on CIF), VAT or GST (on CIF plus duty) and a flat customs clearance fee of $300. Where duty depends on the HS code, the tool shows a range.

## Embed it

```html
<iframe src="https://esthergonswork.github.io/Landed-Cost-Estimator/" width="100%" height="700" style="border:0" title="India Landed Cost Estimator"></iframe>
```

## Update the rates

Open `index.html` and find the `DUTY`, `VAT` and `FREIGHT` blocks near the top of the script. Edit the numbers and notes, commit the change and the live page refreshes within a couple of minutes. Update the "Rates reviewed" date in the page header at the same time.

## Built with

Plain HTML, CSS and JavaScript in one file, with no libraries. Styled in the Rivexa violet and teal, with Urbanist for text.

## Disclaimer

Estimates are indicative. Final figures come from your customs declaration and supplier quote. Duty rates follow the main tariff lines for each category and vary by HS code. Freight bands are planning assumptions. Confirm final figures with a licensed freight forwarder and customs broker before you place an order.
