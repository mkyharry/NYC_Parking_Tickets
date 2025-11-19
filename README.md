NYC Parking Tickets & Tows vs Holidays (2019–2024)
This notebook uses real NYC Open Data + the NYPD Tow Report (2020) to explore:

Do parking tickets increase around major holidays (Thanksgiving, Christmas, July 4, etc.)?
Are there consistent patterns across multiple years?
Do city-tow counts show any similar patterns (for 2020)?
Can we statistically detect higher enforcement around holidays?
⚠️ Important caveats

NYC law prohibits formal ticket quotas; pay/bonus structures are not public here.
This notebook cannot prove officer/tow operator motivation or bonuses.
What we can test: correlations between time of year / holidays and ticket / tow volume.
We’ll:

Pull daily ticket counts for FY 2020–2024 from:
Parking Violations Issued – Fiscal Year 2020 (p7t3-5i9s)
FY 2021 (kvfd-bves)
FY 2022 (7mxj-7a6y)
FY 2023 (869v-vr48)
FY 2024 (pvqr-7yc4)
Summarize counts by calendar day
Build holiday-centered plots (A)
Compute z-scores & run a regression with a holiday-window dummy (B)
Load the NYPD Tow Report – Removal of Vehicles Obstructing Traffic (2020) Excel and look at monthly tow counts vs holidays (C)
All analysis here is descriptive and exploratory, not legal or HR evidence.