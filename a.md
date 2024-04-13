We investigated the sensitivity of DelayAdapter to various UDA algorithms across all datasets, using Negative Log Likelihood as a measure, similar to our approach in Figures 7 and 8. We present the results in tables because the differences are difficult to discern in plot forms. We **compare these results to seven baseline performances (Naive + Safe + 5 advanced baselines)**.

Here are the DelayAdapter performances with different UDA algorithms on the Criteo dataset:

| DANN     | ADDA     | CDAN     | MCD      | MDD      |
| -------- | -------- | -------- | -------- | -------- |
| 0.404143 | 0.407602 | 0.403023 | 0.413440 | 0.401441 |

For Criteo, MDD achieved the best results, outperforming 7/7 baselines. **CDAN and DANN also exceeded 7/7 baselines, while ADDA surpassed 6/7**. MCD, although the least effective among the five, still outperformed 5/7 baselines.

Next, we present DelayAdapter's performance on the Taobao dataset:

| DANN     | ADDA     | CDAN     | MCD      | MDD      |
| -------- | -------- | -------- | -------- | -------- |
| 0.055401 | 0.055844 | 0.055715 | 0.056021 | 0.055679 |

Here, **DANN, MDD, CDAN, and ADDA beat 7/7 baselines**. MCD, despite being the least successful, beat 5/7 baselines.

Lastly, the performance on the Tencent dataset:

| DANN     | ADDA     | CDAN     | MCD      | MDD      |
| -------- | -------- | -------- | -------- | -------- |
| 0.111972 | 0.112335 | 0.112022 | 0.112865 | 0.112110 |

DANN is the top performer, exceeding 7/7 baselines. **CDAN, MDD, and ADDA also beat 7/7 baselines**, with MCD lagging but beating 3/7 baselines.

In short, all tested UDA methods deliver competitive and often superior results.
