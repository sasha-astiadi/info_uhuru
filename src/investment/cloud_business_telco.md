

# Telco Biz Model

```mermaid
graph TB
    ThreeFold[ThreeFold Public Grid <BR>Cloud Capacity<BR>no sales effort for Telco] 
    ThreeFold ---> TELCO[TELCO REVENUE]
    TELCO_1[TELCO Digital Twin Customer] ---->  TELCO
    TELCO_2[TELCO EDGE Cloud Customer] ----> TELCO

    TELCO --30-40%--->MARGIN[MARGIN]

    TELCO --10-20%--->COSTSALES[direct cost of service<BR>bandwidth, power, ops]
    TELCO --50%--->COSTHW[rental cost cloud capacity IHS]

```

## revenue streams

Possible estimates of how business shifts over years

```mermaid
pie title Year 1 Revenue Split
    "EDGE Cloud" : 50
    "TFGrid Public" : 50
    "Digital Twin" : 0
```

```mermaid
pie title Year 2 Revenue Split
    "EDGE Cloud" : 40
    "TFGrid Public" : 40
    "Digital Twin" : 20
```

```mermaid
pie title Year 3 Revenue Split
    "EDGE Cloud" : 30
    "TFGrid Public" : 20
    "Digital Twin" : 50
```

|  | Edge Cloud  | Digital Twin  | Public Grid  |
|---|---|---|---|
| description | storage,compute, network capacity  |   |  |