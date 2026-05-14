
# 🇮🇳 India Tax Calculator — Old vs New Regime



A single-file, zero-dependency tax calculator pre-filled with your payslip for FY 2025–26.



## Features



- **Live verdict** — instantly shows which regime saves you more money

- **Monthly ↔ Yearly toggle** — switch salary inputs between monthly and annual

- **Sliders for every variable** — 80C, home loan interest/principal, HRA rent, 80D, NPS

- **80C cap warning** — alerts when your investments exceed ₹1,50,000

- **HRA auto-calculation** — metro/non-metro toggle, calculates exemption correctly

- **Section 24(b)** — home loan interest capped at ₹2,00,000 (old regime)

- **87A rebate** — applied automatically (old: ₹5L limit, new: ₹12L limit)

- **Surcharge + 4% cess** included in final tax numbers



## Usage



Just open `index.html` in any browser — no build step, no npm, no dependencies.



```bash

git 
clone <your-repo-url>

open 
index.html

```



## Pre-filled values (6 LPA sample)



| Component | Monthly |

|---------------------|----------|

| Basic | ₹25,000 |

| HRA | ₹10,000 |

| Flexible Allowance | ₹8,000 |

| Communication | ₹1,000 |

| LTA | ₹2,000 |

| Food Coupon | ₹1,000 |



## Tax Slabs Used



### Old Regime

| Income | Rate |

|--------|------|

| Up to ₹2.5L | 0% |

| ₹2.5L – ₹5L | 5% |

| ₹5L – ₹10L | 20% |

| Above ₹10L | 30% |



### New Regime (FY 2025–26 post-Budget)

| Income | Rate |

|--------|------|

| Up to ₹4L | 0% |

| ₹4L – ₹8L | 5% |

| ₹8L – ₹12L | 10% |

| ₹12L – ₹16L | 15% |

| ₹16L – ₹20L | 20% |

| ₹20L – ₹24L | 25% |

| Above ₹24L | 30% |





---



## Example: 6 LPA Salary (₹6,00,000/year)



**Assumptions:**

- No deductions (no 80C, HRA, etc.)

- Standard payslip split



### Old Regime

1. Up to ₹2.5L: 0%

2. ₹2.5L–₹5L: 5% of ₹2.5L = ₹12,500

3. ₹5L–₹6L: 20% of ₹1L = ₹20,000

4. **Total before rebate:** ₹32,500

5. 87A rebate (income ≤ ₹5L): 
**Not applicable**

6. 4% cess: ₹1,300

7. **Total tax:** ₹33,800



### New Regime

1. Up to ₹4L: 0%

2. ₹4L–₹6L: 5% of ₹2L = ₹10,000

3. 87A rebate (income ≤ ₹7L): 
**₹10,000**

4. **Net tax:** ₹0



**Result:**

- Old Regime: ₹33,800 tax

- New Regime: ₹0 tax (after rebate)



---



## Disclaimer



This calculator is for estimation purposes only. Consult a CA for filing.
