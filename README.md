> **Imani Beckett**, *"Optimizing Random Forest Hyperparameters: A Theoretical and Empirical Analysis of Variance Scaling,"*  
> submitted to the **IEEE International Conference on Big Data (IEEE BigData 2025)**.

---

Overview

Random Forests (RFs) are widely used for prediction, yet principled guidance on hyperparameter selection is limited.  
This study derives and validates a **variance-based scaling law** linking dataset structure (n/p ratio) to the optimal ratio of trees and features (\( n_{tree}/m_{try} \)).  

Key findings:
- Real-world datasets show a **quadratic relationship** between \( n/p \) and \( n_{tree}/m_{try} \).
- Synthetic datasets without correlated features do **not** exhibit this trend.
- Theoretical derivations explain this via ensemble variance reduction and effective feature count.
