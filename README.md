# 0xJoyBoy's security audits and findings
### Started since *Jan 1st, 2024*

![0xJoyBoy logo](https://s30.picofile.com/file/8474889318/0xJoyBoy03_LE_auto_x2.jpg)

##### Reach out to me on [Twitter](https://twitter.com/MudaMuda03) OR moeidmandegar2001@gmail.com.

***
Supported Languages: 
> - Solidity
> - Sway


# <a name="Top"></a>Top public audits

| Audit Contest                | Date          | Language | Rank | Results                                                                       | Host      |
| ---------------------------- | ------------- | -------- | ---- | ----------------------------------------------------------------------------- | --------- |
| Althea Liquid Infrastructure | 2024-February | Solidity | 4th  | [Link](https://code4rena.com/audits/2024-02-althea-liquid-infrastructure#top) | Code4rena |
| Puffer-Boost | 2024-February | Solidity | 28th  | [Link](https://immunefi.com/bounty/pufferfinance-boost/) | Immunefi |


# <a name="Competition"></a>Competition Profile

| Host         | Profile Name | Link                                                                |
| ------------ | ------------ | ------------------------------------------------------------------- |
| Hats.Finance | 0xJoyBoy03   | [Link](https://app.hats.finance/profile/0xJoyBoy03)                 |
| Codehawks    | 0xJoyBoy03   | [Link](https://www.codehawks.com/profile/cls0sr25x0003gpko8v1wmk5r) |
| Code4rena    | 0xJoyBoy03   | [Link](https://code4rena.com/@0xJoyBoy03)                           |
| Sherlock     | 0xJoyBoy03   | [Link](https://audits.sherlock.xyz/watson/0xJoyBoy03)               |
| Immunefi     | 0xJoyBoy03   | [Link](about::blank)               |

## H&M Findings

> Total H&M : 20 + 1 (Insights)

- 2024-03-Puffer-Boost (26th rank of the best web3 protocols) [:link:](https://immunefi.com/bounty/pufferfinance-boost/)(Immunefi)
> - **Report**: [:link:](https://drive.google.com/file/d/1HawWp2fFWAO6a2brQObDago45AOBCLkm/view?usp=sharing&utm_source=immunefi)(Puffer Booster Report)


- 2024-03-PoolTogether [:link:](https://code4rena.com/audits/2024-03-pooltogether#top)(Code4rena)
> - **Report**: [:link:](https://code4rena.com/reports/2024-03-pooltogether)(PoolTogether Report)
> - [H-01] Any fee claim lesser than the total yieldFeeBalance as a unit of shares is lost [:link:](https://code4rena.com/reports/2024-03-pooltogether#h-01-any-fee-claim-lesser-than-the-total-yieldfeebalance-as-unit-of-shares-is-lost-and-locked-in-the-prizevault-contract)

- 2024-2-Althea Liquid Infrastructure [:link:](https://code4rena.com/audits/2024-02-althea-liquid-infrastructure#top)(Code4rena)
> - **Report**: [:link:](https://code4rena.com/reports/2024-02-althea-liquid-infrastructure)(Althea Report)
> - [H-01] Holders array can be manipulated [:link:](https://code4rena.com/reports/2024-02-althea-liquid-infrastructure#h-01-holders-array-can-be-manipulated-by-transferring-or-burning-with-amount-0-stealing-rewards-or-bricking-certain-functions)
> - [M-02] Malicious users can prevent holders from claiming their rewards [:link:](https://code4rena.com/reports/2024-02-althea-liquid-infrastructure#m-02-malicious-users-can-prevent-holders-from-claiming-their-rewards-during-a-reward-cycle-by-skipping-it)
  

- 2024-04-06-puppy-raffle [:link:](https://www.codehawks.com/contests/clo383y5c000jjx087qrkbrj8)(CodeHawks)
> - There is a Reentrancy Attack in `refund` function [:link:]([Report](https://github.com/moeid3/Audits/blob/main/reports/2024-04-06-puppy-raffle.pdf))
> - There is a Denial of Services (DOS) in `enterRaffle` function [:link:]([Report](https://github.com/moeid3/Audits/blob/main/reports/2024-04-06-puppy-raffle.pdf))
> - Typecasting from uint256 to uint64 in PuppyRaffle.selectWinner() will Leads to overflow [:link:]([Report](https://github.com/moeid3/Audits/blob/main/reports/2024-04-06-puppy-raffle.pdf))
> - Potential Front-Running Attack in `selectWinner` and `refund` Functions [:link:]([Report](https://github.com/moeid3/Audits/blob/main/reports/2024-04-06-puppy-raffle.pdf))

- 2024-02-10-t-swap [:link:](about::blank)(CodeHawks)
> - Incorrect fee calculation in `TSwapPool::getInputAmountBasedOnOutput` [:link:]([Report](https://github.com/moeid3/Audits/blob/main/reports/2024-02-10-t-swap.pdf))
> - Lack of slippage protection in `TSwapPool::SwapExactOutput` function [:link:]([Report](https://github.com/moeid3/Audits/blob/main/reports/2024-02-10-t-swap.pdf))
> - `TSwapPool::sellPoolTokens` mismatches input and output tokens [:link:]([Report](https://github.com/moeid3/Audits/blob/main/reports/2024-02-10-t-swap.pdf))
> - In the `_swap` function the extra tokens given to users after every `swapcount` resulting in breaks the protocol invariant [:link:]([Report](https://github.com/moeid3/Audits/blob/main/reports/2024-02-10-t-swap.pdf))
