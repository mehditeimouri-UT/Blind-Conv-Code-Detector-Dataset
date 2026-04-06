# Blind Convolutional Code Detector Dataset

Dataset specifications (Table II) for blind convolutional code detection research paper. Fixed sequence length: **210,250 bits**. [Paper link]

## Code Configurations

| File | Description | Tests per Config |
|------|-------------|------------------|
| `Convolutional Codes.xlsx` | **551 conv codes**: 17 from Xu et al. (2025) [Sensors 25(4):1000] (15 for train/test) + 10 additional for evaluation; params (g1,g2,n). | 25 per (config,Eb/N0) |
| `Turbo Codes.xlsx` | **64 turbo codes**: identical constituent conv codes; puncturing pattern applied to 2n-k output bits (K,N,m). | 25 per (config,Eb/N0) |
| `BCH Codes.xlsx` | **232 BCH code configs**: *k* (info bits), *n* (codeword bits), *t* (error capability). | 10 (noiseless) |
| `Polar Codes.xlsx` | **16 polar code configs**: *E* (rate-matched length), *K* (info length). | 10 (noiseless) |
| `LFSR Primitive Polynomials.xlsx` | **64 LFSR configs**: degree and primitive generator polynomials. | 1 (noiseless) |
| `LSTM - Test Convolutional Codes.xlsx` | **LSTM baseline test configs** (15 of 17 from Xu et al. + 10 additional). | Per paper eval |

**Upload Excel files directly** to repo root or `data/` folder. Ready for paper citation [X]!
