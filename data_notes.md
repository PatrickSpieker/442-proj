## Data
### Columns
* year
* country from
* country to
* health attributes (of country to)
* type of aid (mil, econ)
* amount in inflation adjusted dollars

### Definitions
**Recipients of aid (Middle East + North Africa):**
* Algeria, Bahrain, Egypt, Iran, Iraq, Israel, Jordan, Kuwait, Lebanon, Libya, Morocco, Oman, Qatar, Saudi Arabia, Syria, Tunisia, UAE, West Bank/Gaza, Yemen

**Donors of aid (EU + United States):**
* All 28 countries in the EU

**Economic aid:** ODA, Total net

**Time span:** 2000 - 2015/16 (most recent good data)

### Files
| File name              | Contents                      | Source           | Notes        |
| ---------------------- | ----------------------------- | ---------------- | ------------ |
| mideast_nafrica.csv    | US aid, economic and military | USAID            |              |
| econ_oda_aid.csv       | EU and US aid, economic only  | stats.oecd.org   |              |

## Visualization
**Map:** recipient countries

**Sections around the map:** donor countries
* On selection, other donor countries fade out and the selected country's color fills

**Arrows:**
* Represent flow of aid in, filterable by type of aid
* or, flow of refugees out

**Color of countries on map:**
* Represent health index

*Both arrows and color of countries filterable into a one-to-many relationship between donors and recipient or vice-versa
