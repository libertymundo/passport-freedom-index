# Passport Freedom Index 2027

Which passport gives you the most freedom? The Passport Freedom Index scores 198 passports on five things that decide how free a passport holder is: where they can travel, how they're taxed, whether the citizenship can be taken away, what the issuing state will do for them, and how much personal liberty they have at home.

Most passport rankings count visa-free destinations and stop there. On that measure Singapore comes first with 192 destinations. On this index it ranks 54th. The United States passport opens 179 destinations and ranks 65th, because it scores 0 for financial freedom: US citizens are taxed on citizenship wherever they live.

**Interactive version with adjustable weighting:** https://www.libertymundo.com/passport-freedom-index

- Publisher: [Liberty Mundo](https://www.libertymundo.com/passport-freedom-index)
- Edition: 2027 (scores as of 16 October 2026)
- Passports: 198
- Licence: CC BY 4.0
- DOI: [10.5281/zenodo.24221846](https://doi.org/10.5281/zenodo.24221846)

## Top 10 passports for freedom

| Rank | Passport | Freedom Score | Mobility | Financial | Citizenship | Protection | Liberty | Visa-free |
|---|---|---|---|---|---|---|---|---|
| 1 | Poland | 89.0 | 100 | 50 | 100 | 90 | 100 | 183 |
| 2 | Monaco | 88.0 | 90 | 100 | 75 | 45 | 100 | 176 |
| 3 | Bahamas | 88.0 | 90 | 100 | 100 | 20 | 100 | 159 |
| 4 | Italy | 87.7 | 100 | 50 | 100 | 77 | 100 | 186 |
| 5 | Luxembourg | 87.0 | 100 | 50 | 100 | 70 | 100 | 185 |
| 6 | Belgium | 87.0 | 100 | 50 | 100 | 70 | 100 | 185 |
| 7 | Portugal | 87.0 | 100 | 50 | 100 | 70 | 100 | 184 |
| 8 | Malta | 87.0 | 100 | 50 | 100 | 70 | 100 | 184 |
| 9 | Czechia | 87.0 | 100 | 50 | 100 | 70 | 100 | 184 |
| 10 | Slovenia | 87.0 | 100 | 50 | 100 | 70 | 100 | 183 |

## Files

| File | Contents |
|---|---|
| `passport-freedom-index-2027.csv` | All 198 passports, five pillar scores, Freedom Score and visa-free count |
| [Methodology report (PDF)](https://doi.org/10.5281/zenodo.24221846) | Scoring rules and full ranking as a report, archived with the dataset on Zenodo |

## Columns

| Column | Type | Meaning |
|---|---|---|
| `rank` | integer | Position by Freedom Score, 1 is best |
| `passport` | text | Issuing country or territory |
| `freedom_score` | decimal, 0 to 100 | Weighted average of the five pillars |
| `mobility` | integer, 0 to 100 | Visa-free travel plus freedom-of-movement bloc bonus |
| `financial_freedom` | integer, 0 to 100 | Tax system attached to the citizenship |
| `citizenship_security` | integer, 0 to 100 | How hard the citizenship is to lose, and whether you can hold another |
| `state_protection` | integer, 0 to 100 | Consular reach and the state's stance on extraditing its own nationals |
| `personal_liberty` | integer, 0 to 100 | Civil liberties, conscription and exit controls |
| `visa_free_destinations` | integer | Destinations the passport reaches without a prior visa |

## How the score is built

Each passport gets five pillar scores from 0 to 100. The Freedom Score is the weighted average.

| Pillar | Weight | How it's scored |
|---|---|---|
| Mobility | 40% | Visa-free destinations divided by 195, times 100, plus up to 8 points for membership of a freedom-of-movement bloc (EU/EEA, Mercosur, GCC). Capped at 100. |
| Financial freedom | 20% | Based on the tax system the citizenship ties you to. Zero income tax 100, territorial 85, residence-based 50, citizenship-based 0. Minus 20 for an exit tax, minus 10 for a wealth tax. |
| Personal liberty | 20% | Civil liberties: high 100, moderate 55, low 15. Minus 15 for conscription, minus 50 where citizens need an exit visa or permit to leave. |
| Citizenship security | 10% | Starts at 100. Minus 45 for high revocation risk or 20 for moderate, minus 25 for a dual-citizenship ban, minus 15 where renunciation is blocked or punitively expensive. |
| State protection | 10% | Consular reach: large 65, moderate 45, small 20. Plus 12 to 35 where the state refuses to extradite its own nationals. Minus 50 for sanctioned or pariah states. |

`freedom_score = 0.40 x mobility + 0.20 x financial_freedom + 0.20 x personal_liberty + 0.10 x citizenship_security + 0.10 x state_protection`

The weights above are Liberty Mundo's defaults. The interactive version lets you set your own: https://www.libertymundo.com/passport-freedom-index

## Full ranking

| Rank | Passport | Freedom Score | Mobility | Financial | Citizenship | Protection | Liberty | Visa-free |
|---|---|---|---|---|---|---|---|---|
| 1 | Poland | 89.0 | 100 | 50 | 100 | 90 | 100 | 183 |
| 2 | Monaco | 88.0 | 90 | 100 | 75 | 45 | 100 | 176 |
| 3 | Bahamas | 88.0 | 90 | 100 | 100 | 20 | 100 | 159 |
| 4 | Italy | 87.7 | 100 | 50 | 100 | 77 | 100 | 186 |
| 5 | Luxembourg | 87.0 | 100 | 50 | 100 | 70 | 100 | 185 |
| 6 | Belgium | 87.0 | 100 | 50 | 100 | 70 | 100 | 185 |
| 7 | Portugal | 87.0 | 100 | 50 | 100 | 70 | 100 | 184 |
| 8 | Malta | 87.0 | 100 | 50 | 100 | 70 | 100 | 184 |
| 9 | Czechia | 87.0 | 100 | 50 | 100 | 70 | 100 | 184 |
| 10 | Slovenia | 87.0 | 100 | 50 | 100 | 70 | 100 | 183 |
| 11 | Croatia | 87.0 | 100 | 50 | 100 | 70 | 100 | 183 |
| 12 | Slovakia | 87.0 | 100 | 50 | 100 | 70 | 100 | 182 |
| 13 | Latvia | 87.0 | 100 | 50 | 100 | 70 | 100 | 182 |
| 14 | Iceland | 87.0 | 100 | 50 | 100 | 70 | 100 | 179 |
| 15 | Romania | 86.6 | 99 | 50 | 100 | 70 | 100 | 177 |
| 16 | Bulgaria | 86.6 | 99 | 50 | 100 | 70 | 100 | 177 |
| 17 | Uruguay | 86.4 | 86 | 75 | 100 | 70 | 100 | 153 |
| 18 | Saint Kitts and Nevis | 85.6 | 89 | 100 | 80 | 20 | 100 | 157 |
| 19 | Germany | 85.0 | 100 | 30 | 100 | 90 | 100 | 186 |
| 20 | Brazil | 84.6 | 94 | 50 | 100 | 100 | 85 | 168 |
| 21 | Ireland | 84.5 | 100 | 50 | 100 | 45 | 100 | 185 |
| 22 | Liechtenstein | 84.5 | 100 | 50 | 100 | 45 | 100 | 180 |
| 23 | Chile | 84.5 | 97 | 50 | 100 | 57 | 100 | 174 |
| 24 | Costa Rica | 84.4 | 76 | 85 | 100 | 70 | 100 | 148 |
| 25 | Switzerland | 84.0 | 100 | 40 | 100 | 90 | 85 | 185 |
| 26 | Greece | 84.0 | 100 | 50 | 100 | 70 | 85 | 184 |
| 27 | Estonia | 84.0 | 100 | 50 | 100 | 70 | 85 | 184 |
| 28 | Lithuania | 84.0 | 100 | 50 | 100 | 70 | 85 | 183 |
| 29 | Panama | 84.0 | 75 | 85 | 100 | 70 | 100 | 147 |
| 30 | Cyprus | 83.6 | 99 | 50 | 100 | 70 | 85 | 178 |
| 31 | Argentina | 83.3 | 94 | 40 | 100 | 77 | 100 | 168 |
| 32 | Spain | 83.0 | 100 | 20 | 100 | 90 | 100 | 186 |
| 33 | France | 83.0 | 100 | 20 | 100 | 90 | 100 | 185 |
| 34 | Netherlands | 83.0 | 100 | 20 | 100 | 90 | 100 | 185 |
| 35 | United Kingdom | 82.1 | 94 | 50 | 80 | 65 | 100 | 183 |
| 36 | Sweden | 82.0 | 100 | 30 | 100 | 90 | 85 | 186 |
| 37 | New Zealand | 81.7 | 93 | 50 | 100 | 45 | 100 | 182 |
| 38 | Japan | 80.9 | 96 | 30 | 75 | 90 | 100 | 187 |
| 39 | Grenada | 80.2 | 83 | 85 | 80 | 20 | 100 | 147 |
| 40 | Saint Lucia | 80.2 | 83 | 85 | 80 | 20 | 100 | 146 |
| 41 | Finland | 80.0 | 100 | 30 | 100 | 70 | 85 | 186 |
| 42 | Denmark | 80.0 | 100 | 30 | 100 | 70 | 85 | 185 |
| 43 | Austria | 80.0 | 100 | 30 | 100 | 70 | 85 | 184 |
| 44 | Canada | 79.7 | 93 | 30 | 100 | 65 | 100 | 181 |
| 45 | San Marino | 78.9 | 86 | 50 | 100 | 45 | 100 | 167 |
| 46 | Barbados | 78.8 | 92 | 50 | 100 | 20 | 100 | 164 |
| 47 | Trinidad and Tobago | 78.5 | 85 | 50 | 100 | 45 | 100 | 150 |
| 48 | Norway | 78.0 | 100 | 20 | 100 | 70 | 85 | 185 |
| 49 | Hungary | 78.0 | 100 | 50 | 100 | 70 | 55 | 183 |
| 50 | Australia | 77.7 | 93 | 30 | 80 | 65 | 100 | 182 |
| 51 | Saint Vincent and the Grenadines | 77.6 | 89 | 50 | 100 | 20 | 100 | 158 |
| 52 | Nauru | 77.6 | 64 | 100 | 100 | 20 | 100 | 124 |
| 53 | Andorra | 76.8 | 87 | 50 | 75 | 45 | 100 | 170 |
| 54 | Singapore | 76.2 | 98 | 85 | 75 | 45 | 40 | 192 |
| 55 | Antigua and Barbuda | 75.8 | 87 | 100 | 80 | 20 | 55 | 155 |
| 56 | Israel | 75.5 | 85 | 50 | 100 | 45 | 85 | 166 |
| 57 | South Korea | 75.4 | 96 | 30 | 75 | 65 | 85 | 187 |
| 58 | Vatican City | 75.3 | 77 | 50 | 100 | 45 | 100 | 151 |
| 59 | Mauritius | 75.3 | 77 | 50 | 100 | 45 | 100 | 150 |
| 60 | Malaysia | 74.6 | 94 | 85 | 75 | 45 | 40 | 183 |
| 61 | Paraguay | 74.4 | 81 | 85 | 100 | 70 | 40 | 142 |
| 62 | Dominica | 72.8 | 82 | 50 | 80 | 20 | 100 | 145 |
| 63 | Guatemala | 72.2 | 68 | 85 | 100 | 70 | 55 | 132 |
| 64 | Seychelles | 72.0 | 80 | 85 | 100 | 20 | 55 | 156 |
| 65 | United States | 71.8 | 92 | 0 | 85 | 65 | 100 | 179 |
| 66 | Macau | 71.7 | 73 | 85 | 100 | 45 | 55 | 142 |
| 67 | Taiwan | 71.6 | 69 | 50 | 100 | 70 | 85 | 135 |
| 68 | Vanuatu | 70.8 | 47 | 100 | 100 | 20 | 100 | 92 |
| 69 | Peru | 70.0 | 80 | 50 | 100 | 70 | 55 | 141 |
| 70 | United Arab Emirates | 69.5 | 100 | 100 | 15 | 80 | 0 | 187 |
| 71 | Samoa | 68.8 | 67 | 50 | 100 | 20 | 100 | 130 |
| 72 | Marshall Islands | 68.4 | 66 | 50 | 100 | 20 | 100 | 128 |
| 73 | Botswana | 68.3 | 42 | 85 | 100 | 45 | 100 | 82 |
| 74 | Hong Kong | 68.1 | 89 | 85 | 80 | 45 | 15 | 173 |
| 75 | Mexico | 68.1 | 81 | 50 | 100 | 77 | 40 | 157 |
| 76 | Tuvalu | 67.6 | 64 | 50 | 100 | 20 | 100 | 125 |
| 77 | Tonga | 67.2 | 63 | 50 | 100 | 20 | 100 | 122 |
| 78 | Namibia | 67.1 | 39 | 85 | 100 | 45 | 100 | 76 |
| 79 | Palau | 66.4 | 61 | 50 | 100 | 20 | 100 | 119 |
| 80 | Brunei | 66.1 | 84 | 100 | 75 | 20 | 15 | 163 |
| 81 | Serbia | 66.0 | 70 | 50 | 100 | 70 | 55 | 136 |
| 82 | Georgia | 65.7 | 63 | 85 | 75 | 80 | 40 | 122 |
| 83 | El Salvador | 65.6 | 69 | 50 | 100 | 70 | 55 | 134 |
| 84 | Belize | 65.6 | 59 | 50 | 100 | 20 | 100 | 100 |
| 85 | Jamaica | 65.3 | 52 | 50 | 100 | 45 | 100 | 86 |
| 86 | Ukraine | 65.2 | 73 | 50 | 100 | 80 | 40 | 143 |
| 87 | Honduras | 64.4 | 66 | 50 | 100 | 70 | 55 | 129 |
| 88 | Kuwait | 64.3 | 57 | 100 | 55 | 80 | 40 | 96 |
| 89 | South Africa | 64.1 | 54 | 30 | 100 | 65 | 100 | 106 |
| 90 | Montenegro | 64.0 | 65 | 50 | 100 | 70 | 55 | 127 |
| 91 | North Macedonia | 64.0 | 65 | 50 | 100 | 70 | 55 | 127 |
| 92 | Moldova | 63.4 | 61 | 50 | 100 | 80 | 55 | 119 |
| 93 | Bosnia and Herzegovina | 62.8 | 62 | 50 | 100 | 70 | 55 | 121 |
| 94 | Albania | 62.8 | 62 | 50 | 100 | 70 | 55 | 120 |
| 95 | Maldives | 62.2 | 48 | 100 | 100 | 20 | 55 | 94 |
| 96 | Cape Verde | 61.7 | 43 | 50 | 100 | 45 | 100 | 69 |
| 97 | Micronesia | 61.6 | 49 | 50 | 100 | 20 | 100 | 96 |
| 98 | Solomon Islands | 61.6 | 49 | 50 | 100 | 20 | 100 | 95 |
| 99 | Bolivia | 61.6 | 49 | 85 | 100 | 70 | 40 | 80 |
| 100 | Ghana | 61.3 | 42 | 50 | 100 | 45 | 100 | 67 |
| 101 | Nicaragua | 61.0 | 65 | 85 | 80 | 70 | 15 | 126 |
| 102 | Colombia | 60.5 | 75 | 40 | 100 | 45 | 40 | 131 |
| 103 | Ecuador | 60.4 | 56 | 50 | 100 | 70 | 55 | 93 |
| 104 | Mongolia | 60.2 | 33 | 50 | 100 | 70 | 100 | 64 |
| 105 | Qatar | 59.5 | 65 | 100 | 55 | 80 | 0 | 112 |
| 106 | Saudi Arabia | 59.0 | 55 | 100 | 40 | 100 | 15 | 91 |
| 107 | Kiribati | 58.2 | 63 | 50 | 100 | 20 | 55 | 123 |
| 108 | China | 57.3 | 72 | 50 | 55 | 100 | 15 | 141 |
| 109 | Oman | 57.3 | 52 | 100 | 55 | 80 | 15 | 86 |
| 110 | Guyana | 57.1 | 54 | 50 | 100 | 45 | 55 | 89 |
| 111 | Zambia | 56.5 | 35 | 85 | 100 | 45 | 55 | 69 |
| 112 | Bahrain | 55.2 | 53 | 100 | 30 | 80 | 15 | 87 |
| 113 | Lebanon | 55.2 | 23 | 85 | 100 | 80 | 55 | 45 |
| 114 | Kosovo | 54.8 | 42 | 50 | 100 | 70 | 55 | 81 |
| 115 | Eswatini | 54.8 | 37 | 85 | 100 | 20 | 55 | 72 |
| 116 | Benin | 54.8 | 42 | 50 | 100 | 70 | 55 | 66 |
| 117 | Senegal | 54.0 | 40 | 50 | 100 | 70 | 55 | 62 |
| 118 | Fiji | 53.5 | 45 | 50 | 100 | 45 | 55 | 88 |
| 119 | Togo | 53.2 | 38 | 50 | 100 | 70 | 55 | 58 |
| 120 | Indonesia | 53.1 | 39 | 50 | 75 | 90 | 55 | 76 |
| 121 | Uganda | 53.1 | 44 | 50 | 100 | 45 | 55 | 70 |
| 122 | Burkina Faso | 52.8 | 37 | 50 | 100 | 70 | 55 | 57 |
| 123 | Ivory Coast | 52.8 | 37 | 50 | 100 | 70 | 55 | 56 |
| 124 | Papua New Guinea | 52.7 | 43 | 50 | 100 | 45 | 55 | 84 |
| 125 | Kenya | 52.7 | 43 | 50 | 100 | 45 | 55 | 69 |
| 126 | Turkey | 52.4 | 61 | 50 | 80 | 100 | 0 | 118 |
| 127 | Dominican Republic | 52.4 | 36 | 50 | 100 | 70 | 55 | 71 |
| 128 | Morocco | 52.3 | 37 | 50 | 85 | 80 | 55 | 72 |
| 129 | Suriname | 52.2 | 48 | 50 | 100 | 20 | 55 | 78 |
| 130 | Angola | 52.0 | 25 | 85 | 100 | 70 | 40 | 48 |
| 131 | Timor-Leste | 51.8 | 47 | 50 | 100 | 20 | 55 | 92 |
| 132 | Sierra Leone | 51.5 | 40 | 50 | 100 | 45 | 55 | 62 |
| 133 | Madagascar | 51.2 | 33 | 50 | 100 | 70 | 55 | 65 |
| 134 | Tanzania | 51.0 | 45 | 50 | 75 | 45 | 55 | 73 |
| 135 | Mali | 50.6 | 39 | 50 | 100 | 70 | 40 | 60 |
| 136 | Malawi | 50.3 | 37 | 50 | 100 | 45 | 55 | 73 |
| 137 | Niger | 50.2 | 38 | 50 | 100 | 70 | 40 | 58 |
| 138 | Nigeria | 49.9 | 31 | 50 | 100 | 65 | 55 | 44 |
| 139 | Tunisia | 49.8 | 37 | 50 | 100 | 70 | 40 | 72 |
| 140 | Gambia | 49.8 | 42 | 50 | 100 | 20 | 55 | 67 |
| 141 | Guinea | 49.8 | 37 | 50 | 100 | 70 | 40 | 56 |
| 142 | Venezuela | 49.6 | 59 | 50 | 80 | 80 | 0 | 116 |
| 143 | Gabon | 49.6 | 29 | 50 | 100 | 70 | 55 | 56 |
| 144 | Mozambique | 49.4 | 36 | 50 | 100 | 70 | 40 | 70 |
| 145 | Armenia | 49.2 | 33 | 50 | 100 | 80 | 40 | 64 |
| 146 | Liberia | 49.1 | 34 | 50 | 100 | 45 | 55 | 51 |
| 147 | Philippines | 48.7 | 33 | 50 | 100 | 45 | 55 | 65 |
| 148 | Kyrgyzstan | 48.4 | 31 | 50 | 100 | 80 | 40 | 60 |
| 149 | Lesotho | 48.2 | 38 | 50 | 100 | 20 | 55 | 74 |
| 150 | Sao Tome and Principe | 47.5 | 30 | 50 | 100 | 45 | 55 | 59 |
| 151 | Guinea-Bissau | 47.3 | 37 | 50 | 100 | 45 | 40 | 56 |
| 152 | Mauritania | 47.1 | 29 | 50 | 75 | 70 | 55 | 56 |
| 153 | India | 46.6 | 29 | 50 | 75 | 65 | 55 | 56 |
| 154 | Russia | 46.2 | 58 | 50 | 80 | 50 | 0 | 113 |
| 155 | Comoros | 45.9 | 26 | 50 | 100 | 45 | 55 | 51 |
| 156 | Haiti | 45.9 | 26 | 50 | 100 | 45 | 55 | 51 |
| 157 | Rwanda | 44.3 | 42 | 50 | 100 | 45 | 15 | 67 |
| 158 | Sri Lanka | 43.9 | 21 | 50 | 100 | 45 | 55 | 41 |
| 159 | Thailand | 43.8 | 42 | 50 | 100 | 70 | 0 | 82 |
| 160 | Burundi | 43.2 | 33 | 50 | 100 | 70 | 15 | 49 |
| 161 | Palestine | 43.1 | 19 | 50 | 100 | 45 | 55 | 38 |
| 162 | Bangladesh | 43.1 | 19 | 50 | 100 | 45 | 55 | 37 |
| 163 | Djibouti | 43.0 | 25 | 50 | 75 | 45 | 55 | 49 |
| 164 | Central African Republic | 42.5 | 25 | 50 | 100 | 45 | 40 | 49 |
| 165 | Pakistan | 41.9 | 16 | 50 | 100 | 45 | 55 | 32 |
| 166 | Kazakhstan | 41.5 | 40 | 50 | 75 | 80 | 0 | 78 |
| 167 | Bhutan | 41.3 | 27 | 50 | 75 | 20 | 55 | 53 |
| 168 | Cuba | 40.8 | 32 | 50 | 100 | 80 | 0 | 62 |
| 169 | Zimbabwe | 40.7 | 33 | 50 | 100 | 45 | 15 | 65 |
| 170 | Nepal | 40.2 | 18 | 50 | 75 | 45 | 55 | 35 |
| 171 | Vietnam | 39.6 | 29 | 50 | 100 | 80 | 0 | 56 |
| 172 | Jordan | 39.6 | 29 | 50 | 100 | 80 | 0 | 56 |
| 173 | Cameroon | 39.6 | 24 | 50 | 100 | 70 | 15 | 47 |
| 174 | Republic of the Congo | 39.6 | 24 | 50 | 100 | 70 | 15 | 46 |
| 175 | Azerbaijan | 39.5 | 35 | 50 | 75 | 80 | 0 | 68 |
| 176 | Algeria | 39.2 | 28 | 50 | 100 | 80 | 0 | 55 |
| 177 | Tajikistan | 39.2 | 28 | 50 | 100 | 80 | 0 | 54 |
| 178 | Libya | 39.0 | 20 | 50 | 100 | 80 | 15 | 39 |
| 179 | Cambodia | 38.8 | 27 | 50 | 100 | 80 | 0 | 53 |
| 180 | DR Congo | 38.8 | 22 | 50 | 100 | 70 | 15 | 43 |
| 181 | Uzbekistan | 38.7 | 33 | 50 | 75 | 80 | 0 | 65 |
| 182 | Egypt | 38.4 | 26 | 50 | 80 | 100 | 0 | 50 |
| 183 | Equatorial Guinea | 38.3 | 27 | 50 | 100 | 45 | 15 | 53 |
| 184 | Chad | 37.8 | 27 | 50 | 100 | 70 | 0 | 52 |
| 185 | Yemen | 37.4 | 16 | 50 | 100 | 80 | 15 | 31 |
| 186 | Laos | 37.2 | 23 | 50 | 100 | 80 | 0 | 45 |
| 187 | Iraq | 37.0 | 15 | 50 | 100 | 80 | 15 | 29 |
| 188 | Belarus | 36.6 | 39 | 50 | 80 | 30 | 0 | 77 |
| 189 | Turkmenistan | 36.3 | 27 | 50 | 75 | 80 | 0 | 53 |
| 190 | South Sudan | 36.1 | 29 | 50 | 100 | 45 | 0 | 41 |
| 191 | Somalia | 34.3 | 17 | 50 | 100 | 45 | 15 | 33 |
| 192 | Ethiopia | 33.8 | 22 | 50 | 75 | 45 | 15 | 42 |
| 193 | Myanmar | 33.1 | 24 | 50 | 55 | 80 | 0 | 47 |
| 194 | Iran | 25.4 | 21 | 50 | 40 | 30 | 0 | 40 |
| 195 | Afghanistan | 23.3 | 12 | 50 | 55 | 0 | 15 | 24 |
| 196 | Syria | 22.2 | 13 | 50 | 40 | 30 | 0 | 26 |
| 197 | North Korea | 19.2 | 18 | 50 | 15 | 5 | 0 | 36 |
| 198 | Eritrea | 11.1 | 19 | 0 | 15 | 20 | 0 | 38 |

## Licence and citation

The data is published under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Republish it, chart it, build on it. Credit Liberty Mundo and link to https://www.libertymundo.com/passport-freedom-index

Cite as:

> Liberty Mundo, Passport Freedom Index 2027, libertymundo.com/passport-freedom-index. https://doi.org/10.5281/zenodo.24221846

## About

[Liberty Mundo](https://www.libertymundo.com) publishes guides to second citizenship, overseas residency, offshore companies and asset protection.
