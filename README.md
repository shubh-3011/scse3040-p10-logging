# SCSE3040 Practical 10 - Logs You Can Actually Search

**Student:** Shubh Om Yadav
**Roll number:** s24cseu0529
**Batch:** B.Tech. CSE - Batch 2024-2028 (Semester 5)
**Date of laboratory session:** 14 November 2026

Submission PDF: [SCSE3040_P10_s24cseu0529.pdf](SCSE3040_P10_s24cseu0529.pdf)

## Contents

- `P10-logging/P10.ipynb` - the executed notebook, with every cell and output visible.
- `P10-logging/work/service.log` - 42 JSONL events produced by the notebook.
- `data/delivery_times.csv` - the shared 600-row delivery dataset used by the practical.

## Privacy

No real telephone number, name or address is stored in the log. The
customer-identifying event uses the hashed `customer_ref` value only.

## Reproduce

```bash
cd P10-logging
jupyter nbconvert --to notebook --execute P10.ipynb --inplace
```
