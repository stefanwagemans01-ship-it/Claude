# FineBites — Sales acquisition reference

This is the single source of truth for the weekly automated prospect-scan routine. Read this in full before doing anything else.

## What FineBites is (for use inside email bodies, do not change these facts)

FineBites is a Dutch, oven-baked (not fried), plant-based snack made from pea protein: 48 grams of protein and 13 grams of fiber per 150-gram bag, Nutri-Score A, and a fully transparent ingredient list. Two flavors: Paprika, and Pepper/sea salt/garlic. Produced at an IFS and BRCGS certified facility. Founder: Stefan Wagemans, a food technologist (Wageningen University & Research). Website: www.finebites.eu (NL) / finebites.eu/en (EN). FineBites is preparing its first production run and is looking for launch partners.

**Never say or imply:** "compromise" / "zonder concessies" (forbidden framing — the correct framing is "you no longer have to choose between nutritious and tasty"), "small brand" / "early-stage brand" as a self-description, "healthy" (use "nutritious"/"voedzaam" instead), any specific production/manufacturing location, "high-oleic" (say "rich in omega-9" instead).

## The exact email template — use word for word, only the personalized hook changes

### Dutch version (for Dutch companies)

```
Onderwerp: FineBites: [korte, specifieke aansluiting bij het haakje]

Beste [Bedrijf]-team,

Mijn naam is Stefan Wagemans, oprichter van FineBites. Wij bieden een in de oven gebakken, plantaardige snack aan op basis van erwteneiwit: 48 gram eiwit en 13 gram vezels per zak van 150 gram, Nutri-Score A, en een volledig transparante ingrediëntenlijst. Geproduceerd bij een IFS- en BRCGS-gecertificeerde faciliteit.

[PERSONALIZED HOOK — see rules below]

We zijn de eerste productie aan het voorbereiden en op zoek naar de juiste partners om de lancering mee vorm te geven en een lange termijn relatie op te bouwen.

Ik ben benieuwd of FineBites past bij [Bedrijf] en of er interesse is voor een kennismaking. Bijgevoegd vind je de product specificaties en op www.finebites.eu kan je de visie en missie van FineBites vinden.

Ik kijk er naar uit om van jullie te horen.
```

(Do not add a closing/signature — that is added automatically by the mailbox-side script. Do not write "Met vriendelijke groet," or a name/phone/logo yourself.)

### English version (for German/Belgian companies where Dutch is not appropriate — use business English, do not invent a German translation)

```
Subject: FineBites: [short, specific tie to the hook]

Dear [Company] team,

My name is Stefan Wagemans, founder of FineBites, a Dutch brand. We make an oven-baked, not fried, savoury snack from pea protein: 48 grams of protein and 13 grams of fiber per 150-gram bag, a Nutri-Score A rating in the EU, and a fully transparent ingredient list, produced at an IFS and BRCGS certified facility. Two flavors: Paprika and Pepper, sea salt, garlic.

[PERSONALIZED HOOK — see rules below]

We are preparing our first production run and looking for the right retail partners to help shape the range from an early stage.

I've attached our product sheet with full nutritional values, ingredients and certifications, and our full range is at finebites.eu/en. I'd welcome your feedback: whether you'd be interested in an introduction, whether FineBites is something you'd consider, and whether it fits your assortment strategy.

I am looking forward to hearing from you.
```

(Signature added automatically, don't duplicate. Use "fiber" not "fibre". No Nutri-Score as the headline argument for markets that don't use it, mention it only as "in the EU".)

## The personalized hook — hard requirement, not optional

Every hook must cite a **concrete, current (published within roughly the last 12 months), verifiable fact** about the specific prospect — a named initiative, a percentage, a report, a program, a product launch — with enough specificity that a reader would recognize it as real research, not a template. Then it must **explicitly tie that fact back to a specific FineBites attribute**. Never just assert that something "fits" without showing why.

- ✗ Weak: "Jullie duurzaamheidsinzet spreekt me aan. FineBites past daar goed bij."
- ✓ Strong (real example used before): "Apenheul is volledig overgestapt op vegetarische kroketten (85% minder CO2 dan de vleesvariant) en een plantaardige, palmolievrije softijsvariant (27% minder CO2). FineBites past direct in die richting: 100% plantaardig op basis van erwteneiwit, in de oven gebakken in plaats van gefrituurd."

## What counts as a good prospect (need at least 2 of these 4)

1. A concrete, recent, documented initiative around plant-based protein, fiber, or "healthier"/more sustainable snacking or food sourcing — a named program, a percentage target, a product reformulation, a sustainability report finding. Generic "we care about health" language does NOT count.
2. Demonstrable openness to smaller/emerging brands (an incubator program, a stated preference for local/independent producers, or simply being a mid-size company rather than a hard-gated major chain).
3. Category fit: savory snacks/chips, or adjacent (sports nutrition, health food, hospitality/catering, gift/hamper assortments, zoo/attraction-park food service, office catering).
4. An actually findable, legitimate contact channel (a real email found on the company's own site, or a real supplier/procurement form). No channel = do not draft an email for it, just note the company as a lead needing manual follow-up.

**Known hard blockers, do not pitch these or spend time on them:** any company with a stated minimum-annual-revenue requirement for direct suppliers that a first-year startup cannot plausibly meet (e.g. requirements around €1,000,000+), formal-tender-only discounters, or any company already in `known-companies.json` (see below).

## Contact-email methodology (strict)

**Never invent an email address.** Only use an address you can point to on the company's own website (a contact page, a press page, a supplier/procurement page). If you cannot find one, do not fabricate a plausible-looking one — instead note the company as "no verified channel found" and skip drafting an email for it (list it in the report as a lead for the human to follow up on manually).

If a general/info@ address is the only one you can find, it is acceptable to use it, but say so explicitly in your report (general inbox, not a dedicated procurement contact) so expectations are set correctly.

## Geographic + language scope

Focus on the Netherlands, Belgium, and Germany. Use the Dutch template for Dutch (and Flemish-Belgian) companies. Use the English template for German companies and French-speaking Belgian companies (do not write a German-language email unless you are highly confident in the translation quality — default to English business correspondence, which is normal practice for B2B outreach into Germany).

## Avoiding duplicates

Read `known-companies.json` in this repo before searching. Do not draft a new email for any company already in that list. After you finish this run, update `known-companies.json` yourself by appending the names of any NEW companies you drafted an email for this week (read it, add to the JSON array, write it back, commit it along with your report).
