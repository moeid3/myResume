# 0xJoyBoy's security audits and findings
### Started since *Jan 1st, 2024*

##### Reach out to me on [Twitter](https://twitter.com/MudaMuda03) OR moeidmandegar2001@gmail.com.

***
Supported Languages: 
> - Solidity
# <a name="Private"></a>Private audit, Testing, Development Profile

| Name       | Date          | Language | Site                                    | Company                                   | Action                            | GitHub Link                                                                                     |


# <a name="Top"></a>Top public audits

| Audit Contest                | Date          | Language | Rank | Results                                                                       | Host      |
| ---------------------------- | ------------- | -------- | ---- | ----------------------------------------------------------------------------- | --------- |
| Althea Liquid Infrastructure | 2024-February | Solidity | 4st  | [Link](https://code4rena.com/audits/2024-02-althea-liquid-infrastructure#top) | Code4rena |
| Puffer-Boost | 2024-February | Solidity | N/A  | <!-- [Link](about::blank) --> (*Coming Soon*...)) | Immunefi |


# <a name="Competition"></a>Competition Profile

| Host         | Profile Name | Link                                                                |
| ------------ | ------------ | ------------------------------------------------------------------- |
| Hats.Finance | 0xJoyBoy03   | [Link](https://app.hats.finance/profile/0xJoyBoy03)                 |
| Codehawks    | 0xJoyBoy03   | [Link](https://www.codehawks.com/profile/cls0sr25x0003gpko8v1wmk5r) |
| Code4rena    | 0xJoyBoy03   | [Link](https://code4rena.com/@0xJoyBoy03)                           |
| Sherlock     | 0xJoyBoy03   | [Link](https://audits.sherlock.xyz/watson/0xJoyBoy03)               |
| Immunefi     | 0xJoyBoy03   | [Link](about::blank)               |

## H&M Findings

> Total H&M in competitions: 20

- 2024-03-Puffer-Boost [:link:](https://immunefi.com/bounty/pufferfinance-boost/)(Immunefi)
> - **Report** *Coming Soon*...


- 2024-03-PoolTogether [:link:](https://code4rena.com/audits/2024-03-pooltogether#top)(Code4rena)
> - **Report**: [:link:](https://code4rena.com/reports/2024-03-pooltogether)(PoolTogether Report)

- 2024-2-Althea Liquid Infrastructure [:link:](https://code4rena.com/audits/2024-02-althea-liquid-infrastructure#top)(Code4rena)
> - **Report**: [:link:](https://code4rena.com/reports/2024-02-althea-liquid-infrastructure)(Althea Report)
  

- 2024-04-06-puppy-raffle [:link:](https://www.codehawks.com/contests/clo383y5c000jjx087qrkbrj8)(CodeHawks)
> - There is a Reentrancy Attack in `refund` function [:link:]([Report](https://github.com/moeid3/Audits/blob/main/reports/2024-04-06-puppy-raffle.pdf))
> - There is a Denial of Services (DOS) in `enterRaffle` function [:link:]([Report](https://github.com/moeid3/Audits/blob/main/reports/2024-04-06-puppy-raffle.pdf))
> - Typecasting from uint256 to uint64 in PuppyRaffle.selectWinner() will Leads to overflow [:link:]([Report](https://github.com/moeid3/Audits/blob/main/reports/2024-04-06-puppy-raffle.pdf))
> - Potential Front-Running Attack in `selectWinner` and `refund` Functions [:link:]([Report](https://github.com/moeid3/Audits/blob/main/reports/2024-04-06-puppy-raffle.pdf))

- 2024-02-10-t-swap [:link:](about::blank)(CodeHawks)
> - Incorrect fee calculation in `TSwapPool::getInputAmountBasedOnOutput` [:link:]([Report](https://github.com/moeid3/Audits/blob/main/reports/2024-02-10-t-swap.pdf))
> - Lack of slippage protection in `TSwapPool::SwapExactOutput` function [:link:]([Report](https://github.com/moeid3/Audits/blob/main/reports/2024-02-10-t-swap.pdf))
> - `TSwapPool::sellPoolTokens` mismatches input and output tokens [:link:]([Report](https://github.com/moeid3/Audits/blob/main/reports/2024-02-10-t-swap.pdf))
> - In `_swap` function the extra tokens given to users after everty `swapcount` resulting in breaks the protocol invariant [:link:]([Report](https://github.com/moeid3/Audits/blob/main/reports/2024-02-10-t-swap.pdf))
