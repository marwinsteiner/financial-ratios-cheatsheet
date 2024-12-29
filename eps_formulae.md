# EPS Calculation Methods

## 1. Basic EPS with Bonus Issue/Split/Reverse Split

The basic formula is:

$\text{BasicEPS} = \frac{\text{Net Profit attributable to ordinary shareholders}}{\text{Weighted average shares} \times \text{Adjustment factor}}$

Where the adjustment factor is:

$\text{Adjustment factor} = \frac{\text{Pre-event number of ordinary shares}}{\text{Post-event number of ordinary shares}}$

*Note: All periods must be adjusted as if the event occurred at the beginning*

## 2. Basic EPS with Full Price Issue/Buyback

$\text{Weighted Average Shares} = (N_1 \times \frac{T_1}{T}) + (N_2 \times \frac{T_2}{T})$

Where:
- $N_1$ = Number of shares before change
- $N_2$ = Number of shares after change
- $T_1$ = Time period before change
- $T_2$ = Time period after change
- $T$ = Total time period

Then:

$\text{BasicEPS} = \frac{\text{Net Profit attributable to ordinary shareholders}}{\text{Weighted Average Shares}}$

## 3. Basic EPS with Rights Issue

First calculate Theoretical Ex-Rights Price (TERP):

$\text{TERP} = \frac{(P_m \times S_b) + (P_r \times S_n)}{S_t}$

Where:
- $P_m$ = Market price before rights
- $S_b$ = Shares before rights
- $P_r$ = Rights price
- $S_n$ = New shares
- $S_t$ = Total shares after rights

Then calculate the adjustment factor:

$\text{Adjustment Factor} = \frac{\text{Market price before rights}}{\text{TERP}}$

Finally:

$\text{Weighted Average Shares} = (S_{pre} \times AF \times T_f) + (S_{post} \times (1-T_f))$

Where:
- $S_{pre}$ = Pre-rights shares
- $AF$ = Adjustment factor
- $T_f$ = Time fraction
- $S_{post}$ = Post-rights shares

## 4. Diluted EPS

$\text{Diluted EPS} = \frac{\text{Adjusted Net Profit}}{\text{Adjusted Weighted Average Shares}}$

Where:
- Adjusted Net Profit = Net Profit + Post-tax effects of convertible securities
- Adjusted Shares = Weighted average shares + Potential ordinary shares

### Dilution Test:

$\text{Individual Dilution} = \frac{\text{Earnings Effect per Security}}{\text{Number of Additional Shares}}$

Compare with Basic EPS:
- If Individual Dilution > Basic EPS → Exclude
- If Individual Dilution < Basic EPS → Include

### Required Disclosures:
1. Basic and diluted EPS on income statement
2. Amounts used as numerators
3. Weighted average shares used as denominators
4. Reconciliation of numerators to net profit
5. Description of all potentially dilutive instruments
