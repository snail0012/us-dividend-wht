US Dividend Withholding Tax Rates by Country — 2026 edition
Publisher: DivAtlas — https://www.divatlas.com/us-dividend-tax-rates-by-country/

WHAT THIS IS
Dividend withholding tax rates for every jurisdiction with a US income tax
treaty in force, plus the no-treaty and terminated-treaty cases — 65 treaty
jurisdictions and 19 non-treaty entries, 84 rows in all. Every rate is the
general (portfolio) treaty rate: the rate that applies to an individual
investor holding ordinary shares of a US company. It is NOT the direct
dividend rate for corporate shareholders above an ownership threshold, NOT
the rate for REIT distributions (several treaties handle those separately),
and NOT automatic — treaty eligibility and limitation-on-benefits terms
decide whether you qualify, and a valid Form W-8BEN is what tells your broker
to apply it.

SOURCE
Compiled from IRS Tax Treaty Table 1 (Rev. May 2023), column 6 (Dividends —
Paid by U.S. Corporations, General):
https://www.irs.gov/pub/irs-lbi/tax-treaty-table-1.pdf
Treaty status labels checked against the IRS income tax treaties A-to-Z list:
https://www.irs.gov/businesses/international-businesses/united-states-income-tax-treaties-a-to-z
Last verified: September 3, 2026

FIELD DEFINITIONS (CSV header row; JSON rows carry the same values under
slightly shorter keys: country / iso2, plus source fields in metadata)
country_name            Jurisdiction display name
country_iso2            ISO 3166-1 alpha-2 code (also the row anchor on the page)
rate_type               Always "portfolio_general"
dividend_wht_rate_pct   US dividend withholding rate, percent
treaty_in_force         yes / no
treaty_status           in_force | none | terminated | suspended.
                        "none" covers signed-but-not-yet-in-force cases too
                        (2026: Croatia); note that the non-treaty entry counts
                        quoted by DivAtlas (19 this edition) include the
                        terminated and suspended rows
notes                   DivAtlas editorial note. Punctuation is limited to
                        colons and semicolons (no em dashes) so the field is
                        safe to embed or re-export downstream
source_table            Always "IRS Tax Treaty Table 1"
source_rev              IRS revision of that table (this edition: Rev. May 2023)
last_verified           Date the row was last re-checked against the source

FILES
us-dividend-wht-2026.csv / .json — this edition, archived permanently
us-dividend-wht-latest.csv / .json — always points at the current edition
(on https://www.divatlas.com/data/). CSV files carry a UTF-8 BOM so they
open cleanly in Excel.

EDITION RULE
The dated files are a fixed snapshot: once published, they are never
overwritten. Corrections and new data write only to the latest files and
to the next year's dated edition.

LICENSE
The rates themselves are facts published by the US Internal Revenue Service
and are not mine to license. The compilation here — the structure, the ISO
codes, the notes and the version history — is released under CC0 1.0
(https://creativecommons.org/publicdomain/zero/1.0/): use it for anything,
commercial or not, with no permission needed. A citation is appreciated
because it lets readers trace a number back to its source, not because I
require one.

CITE THIS DATASET
DivAtlas (2026). US Dividend Withholding Tax Rates by Country, 2026 edition.
Compiled from IRS Tax Treaty Table 1 (Rev. May 2023); verified September 3, 2026.
https://www.divatlas.com/us-dividend-tax-rates-by-country/
Archived edition (fixed snapshot):
https://www.divatlas.com/data/us-dividend-wht-2026.csv
