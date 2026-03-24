# Bill of Materials — minRead PCB

**Pricing basis:** Buying qty × 5 units. Basically the context of a hobbyist building 5 boards, purchasing the minimum quantity available per line item.
Unit prices from DigiKey/Mouser (single cut-tape). Estimates only, verify before ordering. 

| Value / Comment | Qty | Designator(s) | Unit Price | Total (×5 boards) |
|-----------------|----:|---------------|----------:|------------------:|
| **Passives** | | | | |
| 0 (jumper) | 1 | R27 | $0.10 | $0.50 |
| 0.1u | 3 | C7, C33, C36 | $0.10 | $1.50 |
| 1n | 1 | C1 | $0.10 | $0.50 |
| 1u | 6 | C5, C8, C18, C19, C20, C22 | $0.10 | $3.00 |
| 4.7u | 12 | C2, C3, C9, C10, C11, C12, C13, C14, C15, C16, C17, C37 | $0.10 | $6.00 |
| 22u | 3 | C4, C6, C32 | $0.15 | $2.25 |
| 3 | 1 | R14 | $0.10 | $0.50 |
| 33 | 12 | R21, R22, R23, R24, R25, R26, R29, R30, R31, R32, R33, R34 | $0.10 | $6.00 |
| 82 | 1 | R37 | $0.10 | $0.50 |
| 1k | 1 | R16 | $0.10 | $0.50 |
| 1M | 3 | R1, R10, R12 | $0.10 | $1.50 |
| 5.1k | 2 | R2, R3 | $0.10 | $1.00 |
| 5.6k | 1 | R18 | $0.10 | $0.50 |
| 10k | 15 | R4, R5, R6, R7, R8, R9, R13, R15, R28, R39, R40, R41, R53, R54, R55 | $0.10 | $7.50 |
| 12k | 1 | R11 | $0.10 | $0.50 |
| 20k | 1 | R19 | $0.10 | $0.50 |
| 33k | 1 | R35 | $0.10 | $0.50 |
| 56k | 1 | R20 | $0.10 | $0.50 |
| 68k | 1 | R36 | $0.10 | $0.50 |
| 100k | 1 | R38 | $0.10 | $0.50 |
| **Inductors** | | | | |
| 10u (SRN3010) | 2 | L1, L2 | $0.85 | $8.50 |
| **Diodes** | | | | |
| MBR0530 | 5 | D1, D2, D4, D5, D6 | $0.29 | $7.25 |
| MBR0540 | 1 | D7 | $0.29 | $1.45 |
| TSD05CDYFR | 1 | CR1 | $0.55 | $2.75 |
| **Transistors / FETs** | | | | |
| BSS138 | 3 | Q4, Q5, Q6 | $0.33 | $4.95 |
| FS8205A | 1 | Q1 | $0.37 | $1.85 |
| IRLML6402 | 4 | Q2, Q3, Q7, Q8 | $0.55 | $11.00 |
| MMBT3904 | 1 | Q9 | $0.12 | $0.60 |
| **ICs** | | | | |
| AP2112K-3.3 | 1 | U3 | $0.22 | $1.10 |
| AP3012 | 1 | U2 | $0.62 | $3.10 |
| DW01A | 1 | U5 | $0.10 | $0.50 |
| ESP32-S3-WROOM-1 | 1 | U4 | $5.49 | $27.45 |
| MCP73832-2-OT | 1 | U7 | $0.76 | $3.80 |
| TPD4E1U06DBVR | 2 | U1, U6 | $0.42 | $4.20 |
| **Connectors** | | | | |
| FH34SRJ-24S-0.5SH | 1 | J2 | $1.85 | $9.25 |
| FH34SRJ-6S-0.5SH | 1 | J3 | $0.66 | $3.30 |
| Micro_SD_Card | 1 | J7 | $1.20 | $6.00 |
| USB_C_Receptacle | 1 | J1 | $0.88 | $4.40 |
| | | | | |
| **PCB Components Subtotal** | | | | **$136.20** |

---

## Additional Components (×5 units)

| Item | Unit Price | Total (×5) | Notes |
|------|----------:|----------:|-------|
| PCB fabrication (bare, no PCBA) | ~$1.00 | ~$5.00 | JLCPCB 2-layer prototype, 5 boards for ~$5 shipped (price varies with board size; tariffs may apply) |
| GoodDisplay e-ink display | $25.00 | $125.00 | Assumed fixed price |
| 650mAh 3.7V LiPo battery | $8.50 | $42.50 | Hobbyist single-unit pricing (e.g. Adafruit/SparkFun style); JST PH connector. **This can effectively be mitigated by salvaging a healthy re-chargable 3.7V battery.** |
| **Additional Subtotal** | | **$172.50** | |

---

## Estimated Unit Cost (÷ 5)

| Cost Category | Total (×5) | Per Unit |
|---------------|----------:|--------:|
| PCB components | $136.20 | $27.24 |
| PCB fabrication | $15.00 | $3.00 |
| E-ink display | $125.00 | $25.00 |
| LiPo battery | $42.50 | $8.50 |
| **Grand Total** | **$318.70** | **$63.74** |


## Optional Module Savings
 
### Option A — Omit Frontlight Module
 
The following 14 components are exclusively part of the optional frontlight circuit and can be omitted if the display is used without a frontlight:
 
| Ref | Value / Part | Unit Price | Total (×5) |
|-----|-------------|----------:|----------:|
| J3 | FH34SRJ-6S-0.5SH (FPC connector) | $0.66 | $3.30 |
| U2 | AP3012 (boost converter) | $0.62 | $3.10 |
| L2 | 10u SRN3010 (inductor) | $0.85 | $4.25 |
| Q7 | IRLML6402 | $0.55 | $2.75 |
| Q5 | BSS138 | $0.33 | $1.65 |
| Q6 | BSS138 | $0.33 | $1.65 |
| Q9 | MMBT3904 | $0.12 | $0.60 |
| D7 | MBR0540 | $0.29 | $1.45 |
| R37 | 82Ω | $0.10 | $0.50 |
| R39 | 10k | $0.10 | $0.50 |
| R40 | 10k | $0.10 | $0.50 |
| R41 | 10k | $0.10 | $0.50 |
| C9 | 4.7u | $0.10 | $0.50 |
| C12 | 4.7u | $0.10 | $0.50 |
| **Frontlight subtotal** | | **$4.35/unit** | **$21.75** |
 
**Without frontlight:** Grand total drops from $309.20 → **$287.45** → **$57.49 per unit** (saving ~$4.35/unit)
 
---
 
### Option B — Omit Battery Protection Circuit (Pre-protected LiPo)
 
If using a LiPo battery with built-in protection circuitry, the following 5 components can be omitted:
 
| Ref | Value / Part | Unit Price | Total (×5) |
|-----|-------------|----------:|----------:|
| U5 | DW01A (battery protection IC) | $0.10 | $0.50 |
| Q1 | FS8205A (dual N-ch MOSFET) | $0.37 | $1.85 |
| Q8 | IRLML6402 | $0.55 | $2.75 |
| R16 | 1k | $0.10 | $0.50 |
| C7 | 0.1u | $0.10 | $0.50 |
| **Battery protection subtotal** | | **$1.22/unit** | **$6.10**

# **CAUTION: Only omit these components if your LiPo battery already includes over-charge, over-discharge, and short-circuit protection. Using an unprotected cell without this circuit is a safety risk.**
 
**Without battery protection circuit:** Grand total drops from $309.20 → **$303.10** → **$60.62 per unit** (saving ~$1.22/unit)
 
---
 
### Option A + B Combined
 
Omitting both the frontlight module and the battery protection circuit:
 
| | Total (×5) | Per Unit |
|--|----------:|--------:|
| Base grand total | $309.20 | $61.84 |
| − Frontlight module | −$21.75 | −$4.35 |
| − Battery protection circuit | −$6.10 | −$1.22 |
| **Reduced total** | **$281.35** | **$56.27** |

Enclosure (3D printed) cost excluded, Shipping costs excluded, PCB assembly cost excluded.
PCBA service may cost more/less depending on promotion. PCBA service is recommended to be done on the back side only to reduce cost, as there are only 4 SMD switches on the front side.
Prices are estimates as of March 2026. DigiKey tariffs on China-origin parts may significantly affect component costs.
