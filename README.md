# IITM-ASR-challenge-gramvaani

The challenge is available at https://github.com/anish9208/gramvaani_hindi_asr#gramvaani_hindi_asr .

The baseline model's performance on Gram vaani 5h dev set:

|Model Type|Framework|Hyper-params |Test Set |WER|CER|LM|
|---|---|---|---|---|---|---
|Conformer|ESPnet| 12 layers ; kernel size 15 ; nbpe: 1000|dev_5h|34.8|19|Not used|

The final results obtained after running the model with the following parameters are:

|Model Type|Framework|Hyper-params |Test Set |WER|CER|LM|
|---|---|---|---|---|---|---
|Conformer|ESPnet| 12 layers ; kernel size 15 ; nbpe: 400|dev_5h|31.4|15.6|Not used|
