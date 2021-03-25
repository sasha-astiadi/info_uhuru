
# Investment

```mermaid
graph TB

    Investor ---> money[Money Flow]
    money ---> InvestmentHW[HW Investment 60%]
    money ---> GoldReserve[Gold Reserve For Future Opex 30%]
    money ---> Opex[Operational Costs 10%]
```

- Investor owns TFT (vesting over 5 years, first year standstill)
- And gets warrants on shares of company in case TFT goes below certain value.
- Compatible with sharia banking principles.


```mermaid
graph TB


    Investors ---> Loan_Uhuru[per Investor<br>Investment 1-50m USD<br>Max 500m USD]
    Loan_Uhuru ---> backed[backed by shares of Uhuru company<br>in case TFT < 0.8 * starting price]
    backed ---> GoldReserve[Gold/Cash Reserves]
    backed ---> Hardware[hardware capex]
    backed ---> Business[Cloud Business / Revenue]    
    Investors ---> TFTreturn[Own TFT = 1.2x investment value, vesting 5Y ] 

    TFTreturn ---- potential[TFT goes up in line with growth grid, 10x achievable]
```

- legally the investment is
  - pre-purchase of cloud capacity
  - warrants on shares in case TFT goes below certain price
  - cloud capacity can be bought/sold by means of token called TFT
- what if investor cannot invest in such a structure
  - special purpose investment vehicle (SPIV) is created which allows 1 or more investors to invest in a tax optimized structure which will hold the TFT and warrants.
  - the SPIV will get exit after 5 years, by or selling the structure, IPO or capital decrease