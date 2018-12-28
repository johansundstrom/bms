# BMS
Mina noteringar om BMS
* Kortslutningsström får ej förekomma Isc
* Temperatur på batterier bör övervakas >0C <45C

## Batterier
* Vanliga batterier är 18650 (18mm diameter, 65mm hög)
* Flera kemiska varianter - Li-PO, LiFePO4, LiFeYPO4, LiCoO2, LiMnNiCo and LiMnO4 Lithium-Ion
* Lithiumbatterier bör ej understiga 2,5V eller överstiga 4,2V - SoC
* Fulladdat batteri anses vara 90% då 100% över lång tid minskar dess livslängd
* Laddning under 30% minskar också livslängden
* max konstant strömuttag vs puls strömuttag
* Flat top (CID) eller 


## Laddning med övervakning
* Viktiga parametrar att ha koll på
* Överspänning OV, underspänning UV
* Laddström 
* Passiv laddning
* Aktiv laddning - 
* Över tid blir celler olika kraftiga - om en cell blir 5% sämre än de övriga så slås alla celler ut fortare

## Kretsar
https://www.renesas.com/eu/en/doc/datasheet/isl94203.pdf


## Jämförelser

| Chemistry | Lithium Cobalt Oxide | Lithium Manganese Oxide | Lithium Nickel Manganese | Lithium Iron Phosphate | Lithium Nickel Cobalt Aluminum Oxide | Lithium Titanate |

| Short form | Li-cobalt | Li-manganese | NMC | Li-phosphate | Li-aluminum | Li-titanate |
|Abbreviation | LiCoC2 (LCO) | LiMn2O4 (LMO) | LiNiMnCoO2 (NMC) | LiFePo4 (LFP) | LiNiCoAlO2 (NCA) | Li2TiO3 (LTO) |

Nominal voltage

3.60V

3.70V (3.80V)

3.60V (3.70V)

3.20, 3.30V

3.60V

2.40V

Full charge

4.20V

4.20V

4.20V (or higher)

3.65V

4.20V

2.85V

Full discharge

3.00V

3.00V

3.00V

2.50V

3.00V

1.80V

Minimal voltage

2.50V

2.50V

2.50V

2.00V

2.50V

1.50V (est.)

Specific Energy

150–200Wh/kg

100–150Wh/kg

150–220Wh/kg

90–120Wh/kg

200-260Wh/kg

70–80Wh/kg

Charge rate

0.7–1C (3h)

0.7–1C (3h)

0.7–1C (3h)

1C (3h)

1C

1C (5C max)

Discharge rate

1C (1h)

1C, 10C possible

1–2C

1C (25C pule)

1C

10C possible

Cycle life (ideal)

500–1000

300–700

1000–2000

1000–2000

500

3,000–7,000

Thermal runaway

150°C (higher when empty)

250°C (higher when empty)

210°C(higher when empty)

270°C (safe at full charge)

150°C (higher when empty)

One of safest 
Li-ion batteries

Maintenance

Keep cool; store partially charged; prevent full charge cycles, use moderate charge and discharge currents

Packaging (typical)

18650, prismatic and pouch cell

prismatic

18650, prismatic and pouch cell

26650, prismatic

18650

prismatic

History

1991 (Sony)

1996

2008

1996

1999

2008

Applications

Mobile phones, tablets, laptops, cameras

Power tools, medical devices, powertrains

E-bikes, medical devices, EVs, industrial

Stationary with high currents and endurance

Medical, industrial, 
EV (Tesla)

UPS, EV, solar street lighting

Comments

High energy, limited power. Market share has stabilized.

High power, less capacity; safer than Li-cobalt; often mixed with NMC to improve performance.

High capacity and high power. Market share is increasing. Also NCM, CMN, MNC, MCN

Flat discharge voltage, high power low capacity, very safe; elevated self-discharge.

Highest capacity with moderate power. Similar to Li-cobalt.

Long life, fast charge, wide temperature range and safe. Low capacity, expensive.
