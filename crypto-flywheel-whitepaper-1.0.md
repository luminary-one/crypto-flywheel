# The Crypto Flywheel Whitepaper

A rules-based digital asset allocation system designed to increase holdings and produce cashflow as markets rise and fall. Version 1.0, October 12, 2026. Educational material only. Nothing here is financial, investment, legal, or tax advice.

By Jake Call, Joshua Jagelman, and Konstantin Miunts. © 2026 Luminary Assets LLC. Licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

## 1. Summary

The Crypto Flywheel, or simply the Flywheel, is a rules-based digital asset allocation system designed to increase holdings and produce cashflow as markets rise and fall. It rests on one market thesis: the volatile digital assets it holds will appreciate over the long term and recover from major declines.

Capital has four jobs: to grow, to earn, to stay liquid, and to stay resilient. If you buy 1 BTC and its price doubles, your holding is worth twice as much, but you still own only 1 BTC. Holding it alone generates no cashflow. And if all your capital is invested in BTC, you have no stablecoins left to buy more when prices fall.

A Flywheel has three Layers. The Core holds digital assets selected for long-term ownership. The Engine uses stablecoins to accumulate more of those assets through market making as prices fall, then sells accumulated units as prices rise. Its liquidity positions can also earn trading fees. The Reserve holds stablecoins available to fund purchases, support the Engine, and protect the portfolio's borrowing position. The Engine is normally funded by borrowing against the Core, although it can operate without a loan. A written Plan governs how the Layers work together.

The Layers support one another so that the portfolio can pursue all four jobs. Staying liquid and staying resilient continue throughout the cycle, while growing and earning take priority in turn as the market changes (Sections 4 and 10). The underlying practices are familiar to investors in other markets (Section 2); decentralized finance provides the tools to combine them. Throughout, the paper uses BTC and one $100,000 portfolio as its example (Section 6); the model applies to any digital asset that meets the criteria in Section 9.

The Flywheel holds the price risk of assets such as BTC, alongside system risks such as liquidation when it borrows. Managing those risks is part of the design: the Plan sets a limit and a written response for each one before capital moves. If an asset does not recover from a major decline, the strategy can fail (Section 11).

## 2. The problem

A portfolio invested entirely in BTC rises and falls in value with its price, but holding BTC alone produces no cashflow and adds no units. It also leaves no stablecoins available to buy more BTC at lower prices. Bitcoin fell 85% from its 2013 peak, 83% from its 2017 peak, and 77% from its 2021 peak. It then fell 53% from its 2025 peak to a low in June 2026 [1]. Selling before a decline and buying back at lower prices offers one way to increase holdings, but it requires three decisions to go right: when to sell, when to buy back, and how much to trade.

### Established practices behind the Flywheel

The Flywheel combines several familiar investment practices: borrowing against assets rather than selling them, keeping cash available for opportunities, earning fees by providing liquidity, and managing a portfolio through written rules. Decentralized finance (DeFi) allows these practices to operate together, so one part of the portfolio can support another. The examples that follow illustrate the individual practices.

Many property investors borrow against property rather than selling it. Borrowing releases capital while the investor keeps the asset, although property can be slow to sell when cash is needed. The Flywheel applies the same principle to its Core, without the liquidity constraints of traditional finance (TradFi).

Some managed funds hold large cash reserves so they can buy assets during crises, when others may be forced to sell. The trade-off is that cash may earn comparatively little while it waits. The Flywheel's Reserve serves a similar purpose, but its stablecoins can keep earning in DeFi lending markets while they wait.

Market makers provide bids and offers, buying from sellers and selling to buyers. They earn from trading activity, but may accumulate more of an asset as its price falls and give up some gains as it rises. The Flywheel's Engine performs a related function with liquidity positions, but holds the units it accumulates until they reach the Plan's target, turning one side of the trade into growth.

Diversified portfolios seek a balance across different economic conditions, although they can still lose value when markets fall together. The Flywheel uses a written Plan to set its response to each market condition, so it can pursue all four jobs across the cycle rather than trade one off against another.

### What DeFi makes possible

DeFi allows investors to combine collateralized borrowing, automated market making, and interest earned on stablecoins within a single portfolio. Lending markets operate around the clock, allowing investors to borrow against eligible digital assets without waiting for a bank to open [2]. Concentrated liquidity positions automatically buy assets as prices fall and sell them as prices rise. They also earn fees when trades use their active liquidity [3], whether the market is rising, falling, or moving within a channel. Stablecoins deposited in lending markets can earn interest, provided there is sufficient liquidity to withdraw them when the Plan requires it.

Without clear rules, these tools also introduce risks:

- Borrowing: Increasing debt as asset prices rise can leave a portfolio carrying too much debt against collateral valued near a market high. When prices fall, the collateral loses value while the debt remains, bringing liquidation closer.
- Chasing yield: Moving capital into whichever protocol offers the highest return can increase exposure to riskier markets or leave funds unavailable when they are needed.
- Spending reserves too early: Buying too aggressively at the beginning of a decline can exhaust the Reserve before prices reach their lowest levels.

The Flywheel combines these tools within a single portfolio, using a written Plan to govern borrowing, liquidity provision, and the use of reserve capital. Because every part runs on DeFi protocols, it is a DeFi Flywheel: each Layer feeds another on-chain, without a bank or broker in between.

[Figure 1. Four familiar investment practices and their Flywheel counterparts]

## 3. What makes a Flywheel

Borrowing, providing liquidity, or holding a reserve does not on its own make a portfolio a Flywheel. A portfolio qualifies as a Flywheel only when it passes all five of the following checks:

- [ ] It grows: its assets gain value when prices rise, and the portfolio accumulates more units when prices fall.
- [ ] It earns: its positions are designed to earn trading fees or lending income in rising, falling, and channeling markets. Earnings may be withdrawn as cashflow or reinvested. The amount depends on trading volume, active liquidity, and prevailing rates.
- [ ] It stays liquid: capital is accessible when the Plan requires it.
- [ ] It stays resilient: the portfolio is designed to withstand declines without selling long-term Core holdings, with an available Reserve and borrowing kept within the Plan's limits.
- [ ] It runs all three Layers under a written Plan: the Core, the Engine, and the Reserve work together under a Plan that sets the Thresholds to monitor, specifies the response to each, and is revised as the market view changes.

### Core terms

*Table 1. Core terms*

| Term | Meaning |
| --- | --- |
| Units | Asset holdings measured in units, such as 0.6 BTC |
| Layers | The three parts of a Flywheel |
| Core | Holds long-term digital assets and eligible collateral |
| Engine | Accumulates as prices fall, sells inventory as prices rise, and earns trading fees |
| Reserve | Holds stable assets available when the Plan needs them |
| Role | What a position is set to do: Accumulation, Growth, or Distribution |
| Accumulation | A role below the price, buying as it falls |
| Growth | A role around the price, trading in either direction |
| Distribution | A role above the price, selling units as it rises |
| Plan | The investor's written decisions (Section 5) |
| Horizon | The period covered by the Plan before the next decision |
| Objectives | Results the Flywheel is intended to achieve, expressed in measurable terms |
| Ratio | The split of the investor's own capital between Core and Reserve |
| Threshold | A price or level with a pre-agreed response |
| Market view | The investor's estimates of the cycle's potential low and high |
| Target | The intended return on accumulated units, set before purchase |
| Earnings | Trading fees and staking or lending rewards |
| Cashflow | Money distributed to the investor |
| Turbo | A smaller, riskier allocation to reach targets sooner without jeopardizing the main Flywheel |

## 4. The three Layers

Each Layer has a different job. The Core holds assets chosen for long-term ownership. The Engine accumulates units as prices fall, sells trading inventory as prices rise, and earns fees from trades. The Reserve keeps stable assets available for purchases and loan support. The Plan connects these jobs and sets limits on the risks they create.

*Table 2. Each Layer's primary job, what it needs alone, and support from another Layer*

| Layer | Primary job | On its own | How another Layer helps |
| --- | --- | --- | --- |
| Core | Maintains long-term exposure to the asset | Ownership alone generates no income | The Engine and Reserve can earn income |
| Engine | Accumulates units and earns trading fees | Trading inventory is sold at planned targets | The Core retains long-term exposure |
| Reserve | Keeps stable capital available | Usually earns less than volatile assets in a strong rise | Can buy additional units at lower prices |

The Flywheel's resilience depends on the three Layers working together under a written Plan. The Reserve provides capital during market declines, borrowing is limited to account for a deep fall, and the Plan specifies what action to take when each Threshold is reached.

### How the Layers feed each other

New cash enters through the Reserve, while digital assets already owned enter the Core. In a Flywheel that borrows, a loan against the Core funds the Engine. Without borrowing, only the Reserve funds the Engine. During a deep decline, the Reserve also buys units for the Core.

When a bear-market Accumulation position converts its stablecoins into volatile assets, the Plan requires those units to be withdrawn from the liquidity position and deposited as additional collateral. Although pledged as collateral, the units remain identifiable as Engine inventory intended for sale at the Plan's target. The Plan must specify how to release that collateral and manage the loan without letting the health factor fall below its minimum. The health factor and loan-to-value ratio (LTV) are related measures, but they are not interchangeable.

The Plan determines whether earnings and sales proceeds buy additional units, fund the Engine, refill the Reserve, or are paid out as cashflow (Section 8). These flows connect the Layers. Without them, the portfolio would consist of separate positions rather than an integrated Flywheel, and would lose what each Layer gives the others.

[Figure 2. How the Layers feed one another inside the Plan]

### The Core

The Core is measured in units as well as dollars. If BTC doubles in price, the dollar value of a fixed BTC holding doubles, but the number of BTC stays the same. The Core holds long-term units and, in a Flywheel that borrows, provides collateral for the loan (Section 7). Assets used as collateral must be accepted by the lending market. The case for holding them should also rest on more than an expectation that someone else will pay a higher price (Section 9).

Long-term Core units are held for the Plan's Horizon, not sold simply to rebalance the portfolio. Units accumulated by the Engine serve another purpose: they can strengthen collateral during a recovery but typically remain designated for sale at the Plan's target. When those units are pledged, any sale must be coordinated with the lending position. At the end of the Horizon, the Plan determines whether the long-term Core is sold or held for another period. Some Flywheels may instead prioritize keeping accumulated units indefinitely, using trading fees and limited sales to maintain loan health.

[Figure 3. Core units are held for the Horizon; units the Engine accumulates are sold at the Plan's target]

### The Engine

The Engine can use concentrated liquidity positions (CLPs) [3], as this paper's examples do, or any other instrument that performs the same function within the Plan's rules. An Accumulation position exchanges stablecoins for a volatile asset as its price moves down through the selected range. At the lower boundary, the position holds only the volatile asset. If liquidity is left in place, a recovery through that same range sells the units back into stablecoins.

The Plan therefore sets a rule for each position before it opens. In a bear-market Accumulation position, the investor withdraws the accumulated assets and deposits them as collateral. A Growth or Distribution position may remain active to trade in the other direction. CLPs earn fees only when swaps pass through their active liquidity.

For example, before opening a bear-market Accumulation position, the Plan records its price range, borrowed amount, minimum health factor, exit condition, and intended selling range. When the lower boundary is reached, the investor removes liquidity, deposits all accumulated units as collateral, and checks the health factor before considering another loan. Units earmarked for sale move into a Distribution position only when enough collateral can be released, or debt repaid, without breaching the Plan. If prices turn upward before the lower boundary is reached, the Plan follows a separate rule for a partially filled position.

A CLP buys and sells according to price movements, regardless of the investor's intention. Each position therefore has a defined role based on where its range sits relative to the current price: Accumulation below the price, funded with stablecoins to buy during a decline; Growth around the price, buying and selling in either direction, against a stablecoin or between two volatile assets; or Distribution above the price, holding units to sell into a rise.

[Figure 4. CLP roles across accumulation, growth, and distribution]

### The Reserve

The Reserve holds stable assets that the Plan can access when needed. Its lending markets should be chosen for depth and reliable liquidity. The right to request a withdrawal at any time is of little use if the market cannot meet it. The Plan therefore limits exposure to positions with redemption delays, withdrawal queues, or additional market risk. The Reserve may earn income, but its primary purposes are liquidity and resilience.

The Reserve's main job is to fund purchases during a decline. It also has two supporting roles:

1. Cover interest when earnings are insufficient.
2. Repay debt in a Flywheel that borrows, but only when an extreme decline threatens the loan (Section 7).

The Plan sets the Reserve's target size near the top of the cycle and the price declines, measured from the all-time high, at which it will buy in stages. These levels follow the investor's estimate of how far prices could fall. In a Flywheel that borrows, the Plan also retains part of the Reserve for debt repayment in an extreme decline. If the Reserve has bought down to that protected amount by the cycle low, it has fulfilled its purchase role. Units bought during the decline add to the assets available as collateral.

### Execution standards

Every Flywheel transaction requires execution standards. These specify how private keys are stored, how transactions are checked before signing, which protocols are approved, what must be monitored, and how to respond in an emergency. Execution standards are not a Layer, but they help protect what the Layers hold. Losing a private key can make every asset it controls inaccessible, and every on-chain transaction incurs costs (Section 11).

## 5. The Plan

The Plan records the investor's decisions before capital moves and is revised when market evidence changes the investor's view. It sets the Horizon, Objectives, Ratio, and Thresholds, together with the response to each Threshold (Table 1). When the Horizon ends, the Plan determines whether to begin another Horizon, carrying or repaying any outstanding loan, or to sell the holdings and repay the loan in full. A setting chosen for one job must not prevent the other three from being fulfilled. The settings throughout this paper are illustrative.

### The market view

The Plan records the investor's estimate of the cycle's likely low and high. The expected low helps determine when the Reserve buys, how much debt the portfolio can carry through a deep decline, and the number and size of CLP entries across the cycle. The expected high helps set selling targets, generally below that estimate to allow for an imperfect forecast. These estimates are working assumptions, not prices the Flywheel must predict exactly. When the evidence changes, the investor updates the Plan and its Thresholds before opening new positions.

The view concerns the possible price range, not the timing of a market turn. The Plan need not predict when a fall will end or a rise will begin. Positions trade as prices pass through their ranges, and written signals identify market conditions after they begin (Section 10). The Plan can change as new evidence emerges without abandoning the long-term appreciation thesis on which the strategy rests.

## 6. A $100,000 Flywheel

The following $100,000 example is used throughout the paper. Assume BTC trades at $100,000, below an all-time high of $125,000. The Plan sets a 60:40 Ratio for the investor's own capital; borrowing sits outside that Ratio. At the start, $60,000 buys 0.6 BTC for the Core, while $40,000 remains in the Reserve as stablecoins. The example Flywheel then borrows $12,000 against the Core, an initial LTV of 20%, and places the borrowed stablecoins in Accumulation positions spanning BTC prices from $100,000 down to $64,000.

*Table 3. The example at the start*

| Part | Holding or obligation | Value |
| --- | --- | ---: |
| Core | 0.6 BTC | $60,000 |
| Engine | Borrowed stablecoins | $12,000 |
| Reserve | Stablecoins | $40,000 |
| Loan | Debt secured by the Core | −$12,000 |
| Net value | Investor equity | $100,000 |

The Engine puts the borrowed $12,000 into Accumulation positions across the $100,000–$64,000 range. As BTC falls through that range, stablecoins are exchanged progressively for BTC. At $64,000, the bottom of the range, the $12,000 has become 0.15 BTC, acquired at an average price of $80,000 before trading costs. At that point, the Plan requires the investor to remove the liquidity and deposit the accumulated BTC as collateral. If liquidity remained in the original range, a recovery would sell that BTC back into stablecoins. If BTC turns upward before reaching $64,000, the position may still hold both assets, and the Plan's partial-fill rule applies.

### The split drifts

The Ratio is a target, not a fixed split. At $85,000 per BTC, the original Core holding is worth $51,000 and the Reserve remains at $40,000, making the Core–Reserve split approximately 56:44. As prices fall further, the Plan uses the Reserve to buy BTC in stages, moving the split back toward 60:40. During a rise, sales from the Engine, earnings, and new capital can refill the Reserve. Because the original 0.6 BTC is not sold simply to rebalance, restoring the target Ratio after a deep decline may take more than one cycle.

[Figure 5. Core and Reserve allocation as the BTC price changes (illustrative)]

Holding stablecoins in the Reserve reduces the portfolio's initial exposure to a BTC decline. If BTC fell 40% to $60,000 before the Reserve bought anything, the illustrated portfolio would be worth $73,000, down 27%, after accounting for the Engine's accumulated BTC and the $12,000 debt. Once the Reserve buys more BTC, the portfolio owns more units and becomes more sensitive to subsequent price declines.

### Setting a return target

The Flywheel sets a target return for units accumulated by the Engine before they are sold. That target determines the intended selling price. If the Engine acquires 0.15 BTC for $12,000, the average cost is $80,000 per BTC. A 40% target sets an intended average selling price of $112,000. The market determines whether and when that price is reached.

*Table 4. Setting the intended sale price*

| Item | Calculation | Amount |
| --- | --- | ---: |
| Units to sell | Acquired during the decline | 0.15 BTC |
| Average price paid | $12,000 ÷ 0.15 BTC | $80,000 |
| Target | Set in the Plan | 40% |
| Intended average sale price | $80,000 × 1.4 | $112,000 |
| Profit before costs | 0.15 × ($112,000 − $80,000) | $4,800 |
| Total sale proceeds | 0.15 × $112,000 | $16,800 |

A Distribution CLP can sell the 0.15 BTC across a range chosen to produce an intended average sale price of approximately $112,000. In the idealized example, the sale brings in $16,800: $12,000 of initial capital and $4,800 of profit before fees, interest, and other costs. The actual result depends on the range and the trades executed within it.

[Figure 6. Average acquisition price, target sale price, and an illustrative selling range]

### Time and return

Increasing the target from 40% to 50% raises the intended sale price from $112,000 to $120,000. It does not change the amount originally invested, how the units were accumulated, or the initial loan. Under the Flywheel's long-term appreciation thesis, the simplest way to pursue a higher return on those units is to wait for a higher price. That may require a longer holding period.

Return on investment and annualized return are different measures: a larger gain can still produce a lower annualized return if it takes much longer to realize. Waiting also extends market exposure and borrowing costs, so the Plan specifies both a selling target and the conditions under which waiting remains reasonable. The target is normally set below the investor's estimate of the next high. For example, a target of $112,000 can still be reached if a projected $130,000 high falls about 14% short. Previous cycles illustrate how long the wait for a new high can be.

[Figure 7. Time from BTC cycle highs to the next recovery, using daily closes]

The Flywheel spreads purchases across lower price levels and sales across higher ones instead of relying on a single entry or exit. It can therefore realize gains at planned prices rather than trying to identify the market's exact top. The positions execute those trades according to their ranges, reducing the need to make decisions in the middle of a sharp move.

### Reaching the target sooner

The Plan cannot make prices rise sooner, but it can reduce the price required to meet a target. Accumulating units at lower prices reduces the average acquisition cost, while earnings counted toward the target reduce the profit that the eventual sale must produce.

An established Flywheel may also use a limited Turbo allocation, ideally funded by surplus earnings, to pursue additional gains in riskier digital assets outside its main positions. If Turbo produces $600 in realized profit toward the Engine's $4,800 target, the remaining BTC sale must contribute $4,200, reducing its intended average selling price to $108,000. If the Turbo position becomes worthless, the allocated capital is lost but the Flywheel remains intact along with its original targets. Any failure of the Turbo allocation should have minimal adverse impact on the Core, Engine, and Reserve.

## 7. Borrowing

Borrowing is the normal way to fund a Flywheel designed to accumulate assets during market declines, although the basic model can operate without it. Borrowing against eligible Core assets supplies the Engine with stablecoins without selling long-term holdings. As prices fall, Accumulation positions convert those stablecoins into more units of the volatile asset. Once withdrawn from the CLPs and deposited in a lending market, the units become additional collateral. A Flywheel without borrowing follows the same trading rules but must fund its Engine from the Reserve. In a Flywheel that borrows, falling prices reduce the value of existing collateral while allowing borrowed stablecoins to purchase more collateral units.

The example starts with a $12,000 loan, or 20% of the Core's opening value. That is the initial LTV, not necessarily a continuing 20% limit: LTV changes with collateral value even if the debt is unchanged. The Plan therefore sets separate debt limits for different stages of the market, a minimum health factor, a stress price at which the borrowing position must remain viable, and conditions for further borrowing. Each new loan must pass those tests after allowing for a deeper decline.

Without limits, the Flywheel would be exposed to the borrowing risk described in Section 2. Interest also varies with lending-market rates. At an illustrative rate of 5% a year, a $12,000 loan costs $600 annually before compounding, which the health factor must accommodate. Borrowing introduces liquidation risk as well as additional buying capacity.

The health factor measures the distance to liquidation. It equals the value of collateral multiplied by the lending market's liquidation threshold, divided by the outstanding debt. If it falls below 1.0, the lending market can liquidate collateral to repay debt [2]. Assuming an 80% threshold and no accrued interest or other changes, the example starts at $60,000 × 0.8 ÷ $12,000 = 4.0. With only the original 0.6 BTC as collateral, the liquidation price would be $25,000 per BTC, a 75% decline from the initial $100,000 price.

A falling BTC price has two effects. It reduces the dollar value of the existing collateral while converting borrowed stablecoins in the Engine into additional BTC. Once those units have been withdrawn and deposited as collateral, they improve the health factor relative to a loan backed only by the original BTC holding.

At $64,000, the original 0.6 BTC is worth $38,400. Adding the Engine's 0.15 BTC raises total collateral to $48,000. With the debt unchanged at $12,000 and an 80% liquidation threshold, the health factor is 3.2 rather than 2.56 without the additional BTC. It remains below the initial 4.0. Further borrowing could fund another Accumulation range, but only after the Plan tests the larger debt against a deeper fall. The Reserve remains available to repay debt at the emergency Threshold set in the Plan.

[Figure 8. Buy ranges, selling targets, and illustrative liquidation prices]

A Flywheel that borrows uses leverage. The Plan distinguishes that leverage from borrowing without limits by setting debt constraints before capital moves, maintaining a Reserve to support the loan, and specifying a response at each Threshold. Lending-market parameters are public and enforced on-chain, and the portfolio's health factor can be monitored continuously.

## 8. Earnings and cashflow

The Flywheel earns trading fees when swaps use a CLP's active liquidity, along with rewards or interest from other positions. Price movement alone does not create trading fees; a trade must occur. Earnings can buy additional Core units, compound in the Engine, refill the Reserve, or be paid to the investor as cashflow. The Plan sets their priority as market conditions change, provided the portfolio continues to meet its borrowing limits.

Gains from selling accumulated units can be used in the same ways. In the example, selling 0.15 BTC at an average price of $112,000 produces $4,800 of profit before costs. The Plan may distribute that profit, buy more Core units, or refill the Reserve. Earnings received as units can move directly into the Core or be converted into stablecoins for the Reserve. During declines, the Plan can emphasize accumulation; during rises, it can emphasize restoring the Reserve and paying cashflow.

[Figure 9. Earnings and gains flow to the Core, Engine, Reserve, or investor]

## 9. Choosing digital assets

The Flywheel's growth thesis applies to the volatile assets it buys and holds. They need a credible prospect of appreciating over the long term and recovering from major declines. Stable assets serve a different purpose. Stablecoins provide purchasing power: the Reserve and Engine use them to acquire volatile assets as prices fall, then convert units back into stablecoins as prices rise. This cycle depends on stablecoins preserving their dollar value and remaining redeemable, not on their prices appreciating.

The examples use BTC because it has the longest record against the criteria below: higher cycle highs and higher cycle lows over more than one market cycle, deep liquidity, and demand that does not rest on price expectations alone. Large market capitalization or one exceptional cycle is not enough. Other digital assets, such as ETH or SOL, and tokenized real-world assets [4] can also be used. A shorter or less consistent record calls for smaller positions, less borrowing, and a larger Reserve.

Whatever assets it holds, the portfolio must still pass the checks in Section 3.

### Asset assessment

An asset needs a reason to appreciate beyond the hope that someone else will buy it at a higher price. The stronger it is against the following four criteria, the more capital the Plan may reasonably allocate to it:

1. Its markets have enough depth to buy and sell positions, including collateral liquidations during a decline.
2. It is scarce and has held value over several years and more than one market cycle.
3. Demand comes from actual use, such as payments, settlement, or collateral, rather than price expectations alone.
4. If new tokens can still be issued, holders are rewarded from revenue, through payouts, buybacks, burns, or staking rewards funded by that revenue, not only with new tokens that dilute existing holders.

A tokenized asset is assessed twice: first for the asset it represents, then for the token itself, including its issuer, redemption arrangements, and on-chain liquidity. The lower assessment governs its suitability.

No asset is excluded by name. A well-established asset such as BTC can support a larger Core position and a more conservative loan. A smaller, more volatile asset generally calls for less borrowing and a larger Reserve. Its declines may be deeper, its history may not reveal its worst drawdown, and its market may lack enough liquidity for collateral sales under stress. An asset whose only investment case is an expected price increase provides little reason to expect recovery after a major decline.

The amount allocated to each asset is a separate decision. It should reflect the investor's conviction, informed by knowledge and experience, and remain within the loss the investor can bear.

## 10. Across the market cycle

The Plan defines a signal for each market condition and the response that follows. The table gives representative signals only; a usable assessment of market structure requires analysis beyond the scope of this paper.

*Table 5. Signals and responses by market condition*

| Condition | Signal | Response |
| --- | --- | --- |
| Turning down | Price moves below its 50-week average | Opens Accumulation positions below the price |
| Falling | Price remains below the average and well below its high | Positions accumulate the asset; the Reserve buys in stages |
| Channeling | Price moves repeatedly within an established range | The Engine earns fees when trades use its active liquidity; the Plan checks the range |
| Turning up | Price closes above its 50-week average for consecutive weeks | Opens Growth positions and sells designated units at their targets |
| Rising | Price makes new highs | Sells designated units at their targets and replenishes the Reserve |

[Figure 10. How capital's four jobs work across each market condition (illustrative)]

Liquidity and resilience are maintained at every point in the cycle, while growth and earnings take priority in turn: Engine fees and Reserve interest as the market turns down, accumulation during a fall, fee income while prices move within a channel, renewed growth as prices turn up, and sales that restore the Reserve during a rise. Because the Reserve buys in stages on the way down and is replenished on the way up, the Flywheel does not need to identify the exact bottom or top. A signal may prove premature, leading to a higher average purchase price or an early use of Reserve capital. The remaining rules still govern the portfolio.

## 11. Risk

Owning a volatile digital asset carries substantial price risk. The Flywheel retains that risk and adds other risks through liquidity positions, borrowing, and on-chain execution. The risk table groups them into nine categories, together with the measures intended to limit them. Two deserve particular attention because neither can be eliminated by the design: divergence and failure of an asset to recover.

*Table 6. Risks and planned controls*

| Risk | Potential outcome | Planned control |
| --- | --- | --- |
| Market risk | Prices fall further, or the target takes years to reach | A Horizon covering at least a full cycle |
| Recovery risk | An asset never recovers from a fall | Asset selection and position sizing (Section 9) |
| Divergence risk | A liquidity position underperforms simply holding the initial assets | Range rules turn it into accumulation in a decline and distribution in a rise; fees may offset the rest |
| Borrowing risk | Liquidation, or interest that earnings cannot cover | Debt limits, minimum health factor, and Reserve support |
| Smart contract risk | A contract, price feed, or bridge fails, or withdrawals freeze | Protocol review and diversification |
| Issuer risk | A stablecoin loses its peg, or a token cannot be redeemed | Asset assessment (Section 9) |
| Custody risk | Keys are lost, or a bad transaction is signed | Execution standards (Section 4.5) |
| Execution risk | Fees, slippage, gas, and mistakes across many parts | Fewer planned transactions and staged implementation |
| Behavior risk | An emotional decision leads to a premature action and a loss | Pre-agreed responses in the Plan |

### Risks the design cannot remove

Divergence loss, also called impermanent loss, is the difference between the value of a liquidity position and the value of simply holding the assets originally deposited into it. Used deliberately, divergence is how the Engine works: an Accumulation position diverges into the asset as prices fall, and a Distribution position diverges into stablecoins as prices rise. In the $100,000 example, the Engine starts with $12,000 in stablecoins. When BTC reaches $64,000, the Accumulation position holds 0.15 BTC worth $9,600, or $2,400 less than the original stablecoins would be worth. That is the divergence from holding the initial deposit, before fees. The Flywheel has also accumulated 0.15 BTC it did not previously own, which is the point of the position.

If the investor withdraws those units and BTC later returns to $80,000, they are worth $12,000; above that price, their value exceeds the original stablecoin amount. If the position remains active during the recovery, it instead sells BTC back into stablecoins, producing a different result. Divergence can widen or narrow as prices move, and trading fees may offset some or all of it.

Recovery is the second risk. The model assumes its volatile assets will recover after major declines. If an asset does not, the Engine may continue buying it, the Reserve may be spent on it, and the loan becomes harder to maintain. Asset selection and position sizing cannot guarantee recovery, but they can limit the amount of capital exposed to a permanent loss.

## 12. Assessing a Flywheel

A Flywheel should be assessed as a whole portfolio over a full cycle, against the Plan's Objectives and capital's four jobs. The assessment should establish whether it added units, paid the planned cashflow, kept the Reserve accessible when needed, and withstood declines without selling long-term Core holdings. During a fall, measure the units accumulated and their purchase prices. During a rise, measure sales proceeds and how much the Reserve has been refilled. Cashflow may be paid in either phase, although the model expects more of it during rises, when accumulated positions are sold at a gain.

## 13. Building on the model

The Flywheel is a model rather than a single prescribed portfolio. This paper describes its principles. A Flywheel design turns those principles into a repeatable strategy, and an investor's Plan applies that design to a particular portfolio, market view, and objectives. Investors can therefore use the same model without holding identical positions or taking identical risks.

*Table 7. The model, a design, and a portfolio*

| Level | What it is | Documented in |
| --- | --- | --- |
| The model | The four jobs, five checks, three Layers, and the Plan | This whitepaper |
| A design | A named way of running the model | The Flywheel Design Template |
| A portfolio | A running Flywheel for one investor | The Flywheel Plan Template |

### What a Flywheel can be used for

The model can be adapted to different investor objectives. A Flywheel focused on accumulating units emphasizes the Core; one designed for cashflow emphasizes the Engine; and one used as a liquid treasury emphasizes the Reserve. The table illustrates these different priorities rather than prescribing settings.

*Table 8. What a Flywheel can be used for*

| Aim | Where capital sits | Engine positions | Use of earnings and gains |
| --- | --- | --- | --- |
| More units | Mostly in the Core, with a loan funding the Engine | Accumulation positions below the price | Additional units for the Core |
| Cashflow from holdings | Existing holdings in the Core | Growth and Distribution positions that sell into rising prices | Cashflow to the investor |
| Liquid treasury | Mostly in the Reserve, with little or no borrowing | Small Growth positions around the price | Back into the Reserve |

## Credits

Jake Call created the DeFi Flywheel, the concept from which this model grew, first sketching it in December 2024. Joshua Jagelman wrote the *Bluechip Flywheel White Paper* [5], on which this paper builds. Konstantin Miunts helps architect the strategy and puts it into practice for BuildrWealth's clients.

## Disclosures

The authors hold BTC, ETH, SOL, HYPE, and other digital assets, and run Flywheels with their own capital. Through BuildrWealth, all three are paid to put the strategy into practice for clients. No protocol, issuer, or project named in this paper paid to be included or reviewed it before publication.

## Sources

1. BTC/USD daily closing prices, Bitstamp public market data, January 2013 to September 2026.
2. Aave, [Liquidations](https://aave.com/docs/concepts/liquidations), protocol documentation: the health factor and the liquidation threshold.
3. Hayden Adams, Noah Zinsmeister, Moody Salem, River Keefer, and Dan Robinson, [*Uniswap v3 Core*](https://uniswap.org/whitepaper-v3.pdf), March 2021: concentrated liquidity.
4. [RWA.xyz](https://app.rwa.xyz/), data on tokenized real-world assets, including treasury bills, commodities, and funds.
5. Joshua Jagelman, *Bluechip Flywheel White Paper*, version 1.1, July 2026, unpublished manuscript.

## Disclaimer

This paper is educational material, not financial, investment, legal, or tax advice. Nothing in it recommends trading, lending, staking, bridging, borrowing against digital assets, providing liquidity, or using any particular protocol. Luminary Assets LLC, which publishes as Luminary One, is not a fund or a licensed financial adviser and does not take custody of client assets.

The Flywheel has no token. Luminary Assets LLC does not issue or sell any token, coin, or security connected with it, and nothing in this paper is an offer to buy or sell any asset. A record of this paper on a blockchain marks its publication only: it is not offered for sale and carries no claim to returns.

The Flywheel is a rules-based digital asset allocation system designed to increase holdings and produce cashflow as markets rise and fall. It is a model, not a product, and no return is guaranteed. All rates, targets, scenarios, and examples are illustrative. Actual outcomes depend on market prices, liquidity, borrowing costs, earnings, protocol choice, smart contract and stablecoin failures, execution, taxes, regulation, and investor decisions. They may differ substantially from the results shown here.

Digital assets can lose most or all of their value. Collateralized loans can be liquidated. Engine positions may earn nothing, earn less than expected, or perform worse than holding the assets outright. Stablecoins can lose their peg. Tokenized real-world assets depend on issuers, custodians, and redemption arrangements and may not be redeemable for the value of the underlying assets. A Turbo allocation carries greater risk and can lose its value without improving the portfolio's return. Lending markets, exchanges, bridges, wallets, and price feeds can be hacked, stop withdrawals, or fail unexpectedly.

The model depends on its volatile assets appreciating over the long term and recovering from major declines. If they do not, the strategy can fail. A Flywheel can lose money, accumulate no additional units, pay no cashflow, or have collateral liquidated. Historical market cycles and hypothetical models do not establish what will happen next. Seek independent advice before acting, and do not invest in anything you cannot understand and monitor.

## License

Luminary Assets LLC holds the rights in this paper and licenses it under the [Creative Commons Attribution 4.0 International license (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). It may be copied, shared, and adapted, including commercially, provided appropriate credit is given, the license is linked, and changes are disclosed. The license covers the paper's text and figures, but not the names or logos.

Credit it as: *The Crypto Flywheel Whitepaper*, version 1.0, by Jake Call, Joshua Jagelman, and Konstantin Miunts, © 2026 Luminary Assets LLC, licensed under CC BY 4.0.

## Version history

| Version | Date | What changed |
| --- | --- | --- |
| 1.0 | October 12, 2026 | First version |
