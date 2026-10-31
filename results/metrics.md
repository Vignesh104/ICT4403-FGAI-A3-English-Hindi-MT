| System                | Architecture    | Adaptation           |   BLEU |   chrF |   Params (M) |   Trainable (M) |   Train pairs |   Train time (min) |   Inference (s / 500 sent.) |   ms / sentence |
|:----------------------|:----------------|:---------------------|-------:|-------:|-------------:|----------------:|--------------:|-------------------:|----------------------------:|----------------:|
| Transformer (scratch) | encoder-decoder | trained from scratch |   5.14 |  24.86 |          9.4 |            9.42 |         50000 |               10.8 |                         5.7 |            11.4 |
| mT5-small (FT)        | encoder-decoder | full fine-tuning     |   6.69 |  26.28 |        300.2 |          300.18 |         50000 |               62.1 |                        19.2 |            38.3 |
| LLaMA-3.2-1B (3-shot) | decoder-only    | 3-shot prompting     |  10.22 |  34.14 |       1235.8 |            0    |             0 |                0   |                       165.2 |           330.4 |
| Gemma-3-1B (3-shot)   | decoder-only    | 3-shot prompting     |  13.52 |  38.88 |        999.9 |            0    |             0 |                0   |                       110.4 |           220.8 |

BLEU: `nrefs:1|case:mixed|eff:no|tok:intl|smooth:exp|version:2.6.0`  
chrF: `nrefs:1|case:mixed|eff:yes|nc:6|nw:0|space:no|version:2.6.0`  
GPU: Tesla T4
