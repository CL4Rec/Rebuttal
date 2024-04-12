

# Experiment Results

## ML-1M

|                                     | Recall@20  | NDCG@20    | Recall@50  | NDCG@50    |
| ----------------------------------- | ---------- | ---------- | ---------- | ---------- |
| LightGCN                            | 0.2680     | 0.2670     | 0.4310     | 0.3137     |
| +rand                               | 0.2791     | 0.2752     | 0.4451     | 0.3235     |
| +rand +cons                         | 0.2820     | 0.2764     | 0.4489     | 0.3252     |
| +rand +cons +ac                     | 0.2832     | 0.2801     | 0.4470     | 0.3276     |
| +rand +cons +ac +adv (Full Version) | **0.2901** | **0.2821** | **0.4581** | **0.3321** |

## Yelp

|                                     | Recall@20  | NDCG@20    | Recall@50  | NDCG@50    |
| ----------------------------------- | ---------- | ---------- | ---------- | ---------- |
| LightGCN                            | 0.1001     | 0.0614     | 0.1814     | 0.0850     |
| +rand                               | 0.1075     | 0.0666     | 0.1947     | 0.0920     |
| +rand +cons                         | 0.1131     | 0.0701     | 0.2002     | 0.0955     |
| +rand +cons +ac                     | 0.1180     | 0.0737     | 0.2083     | 0.1000     |
| +rand +cons +ac +adv (Full Version) | **0.1191** | **0.0744** | **0.2108** | **0.1010** |

# Further Analysis

The experimental results demonstrate a consistent improvement in recommendation performance with the gradual incorporation of the modules proposed in our paper, compared to the backbone model. The synergy of these modules culminates in RGCL's exceptional performance, underscoring the unique contribution of each component.