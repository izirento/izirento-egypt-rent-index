# Egypt: rent and landlord rules index 2026

Open, source-linked data on residential rent and landlord obligations in Egypt: deposits, rent increases, termination notice, lease terms, registration and landlord duties, with a primary-source link for every value.

- Version: 1.0
- Facts checked: 2026-11-04
- Author: Leonid Gorok
- Project site: [izirento.com](https://izirento.com)
- Related: [UK Rent & Landlord Obligations Index 2026](https://izirento.com/en-gb/research/data/uk-rents-and-landlord-duties-index), [UK repository](https://github.com/izirento/izirento-uk-rent-index), [catalog of country repositories](https://github.com/izirento/izirento-rent-index-international)
- Licence: CC BY 4.0 (see [`LICENSE`](LICENSE) and [`LICENSE.md`](LICENSE.md)). Laws and official statistics are cited, not copied.

## Disclaimer

The data is provided as is, without any liability. We only collect and organise what the official sources publish. Laws change and local rules differ: always check each value against the primary source linked next to it before relying on it. This is information, not legal advice.

## Scope and limits

The text read is Law No. 164 of 2025 on old residential and non-residential leases (English text on a government repository). It does not cover new leases under the Civil Code, and implementing decisions were not checked.

## Key facts

| Topic | Field | Value | Source |
| --- | --- | --- | --- |
| tenancy_law | Scope | Law No. 164 of 2025 applies to premises leased for residential purposes, and premises leased to natural persons for non-residential purposes, under Law 49 of 1977 and Law 136 of 1981 (Art. 1). It is a transitional law for old leases, not a general tenancy code. | [Presidency of the Republic of Egypt (published on the Information and Decision Support Center repository)](https://dspace.id.com.eg/items/d0810511-aa56-462c-8dc7-e9b28b3aab3d/full) |
| lease_term | End of old leases | Residential lease contracts under the law terminate seven years after the law takes effect; leases to natural persons for non-residential use terminate after five years, unless the parties agree an earlier end (Art. 2). | [Presidency of the Republic of Egypt (published on the Information and Decision Support Center repository)](https://dspace.id.com.eg/items/d0810511-aa56-462c-8dc7-e9b28b3aab3d/full) |
| rent_control | New legal rent (residential) | From the first monthly rent after the law takes effect, the legal rent in prime areas is twenty times the current legal rent, with a minimum of EGP 1,000; in moderate and economic areas it is ten times, with minimums of EGP 400 (moderate) and EGP 250 (economic). Until governorate committees finish classifying areas, tenants pay EGP 250 a month and later pay any difference in instalments (Art. 4). | [Presidency of the Republic of Egypt (published on the Information and Decision Support Center repository)](https://dspace.id.com.eg/items/d0810511-aa56-462c-8dc7-e9b28b3aab3d/full) |
| rent_control | New legal rent (non-residential) | The legal rent of premises leased to natural persons for non-residential use becomes five times the current legal rent (Art. 5). | [Presidency of the Republic of Egypt (published on the Information and Decision Support Center repository)](https://dspace.id.com.eg/items/d0810511-aa56-462c-8dc7-e9b28b3aab3d/full) |
| rent_increase | Annual increase | The rents set under Arts. 4 and 5 rise every year at a rate of 15 percent (Art. 6). | [Presidency of the Republic of Egypt (published on the Information and Decision Support Center repository)](https://dspace.id.com.eg/items/d0810511-aa56-462c-8dc7-e9b28b3aab3d/full) |
| termination | Early eviction grounds | Besides the grounds in Art. 18 of Law 136 of 1981, the tenant must vacate when the Art. 2 period ends, or earlier if the premises have been left closed for more than one year without justification, or if the tenant owns another suitable unit for the same purpose; the landlord may ask the summary judge for an eviction order (Art. 7). | [Presidency of the Republic of Egypt (published on the Information and Decision Support Center repository)](https://dspace.id.com.eg/items/d0810511-aa56-462c-8dc7-e9b28b3aab3d/full) |
| deposit | Deposit cap | (empty) | [Presidency of the Republic of Egypt (published on the Information and Decision Support Center repository)](https://dspace.id.com.eg/items/d0810511-aa56-462c-8dc7-e9b28b3aab3d/full) |

## العربية

**مصر.** بيانات مفتوحة عن الإيجار والتزامات المؤجر: التأمين، وزيادة الأجرة، ومدد الإخطار، وعقد الإيجار، مع رابط المصدر الرسمي لكل قيمة.

*تُقدَّم البيانات كما هي ودون أي مسؤولية. نكتفي بتنظيم ما تنشره المصادر الرسمية. القوانين تتغير: يرجى التحقق من كل قيمة في المصدر الأصلي المرتبط.*

Details: see the table above and `sources.md`.

## Files

| File | Content |
| --- | --- |
| `egypt_rent_landlord_rules_2026.csv` | One row per fact, with source URL, optional cross-check URL and check date |
| `sources.md` | Every field with publisher and links, plus fields left empty and notes |
| `LICENSE`, `LICENSE.md` | CC BY 4.0 legal code; attribution and source statements |
| `CITATION.cff` | Citation metadata |

## Field dictionary

| Field | Meaning |
| --- | --- |
| `country_code, country` | Code and name |
| `topic` | Group: tenancy_law, deposit, rent_increase, rent_control, termination, contract_form, registration, rent_payment, landlord_duties, rent_level_change and similar |
| `field` | Specific item |
| `value` | The fact in our own words; empty where no verified figure was found |
| `source_publisher` | Body that publishes the source |
| `source_url` | Link to the primary source |
| `cross_check_url` | Second source actually read, if any |
| `checked_on` | Date the source was read |
| `note` | Scope, language of the source or caveat |

## Method

1. Each value comes from a primary source: the statute on the official legal portal, a government service page or a statistics office dataset. Where a second official or institutional page confirms it, that link is in `cross_check_url`.
2. Values are written in our own words. Nothing is estimated or calculated; where no verified value exists the cell is empty and the reason is given in `sources.md`.
3. Where a statute is translated or summarised from another language, the original-language text prevails.

## Citation

Gorok, L. (2026). *Egypt: rent and landlord rules index 2026* (Version 1.0) [Data set]. IziRento. https://github.com/izirento/izirento-egypt-rent-index

## Attribution

Sources are listed in `sources.md` and in `LICENSE.md`.
