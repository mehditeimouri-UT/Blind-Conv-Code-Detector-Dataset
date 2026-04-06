# Blind Convolutional Code Detector Dataset

Dataset specifications (Table II) for blind convolutional code detection research paper. Fixed sequence length: **210,250 bits**. 

## Code Configurations

| File | Description |
|------|-------------|
| `Convolutional Codes.xlsx` | **551 conv codes**: params rate and generator polynomials. |
| `Turbo Codes.xlsx` | **64 turbo codes**: identical constituent conv codes (n,k,KL); puncturing pattern applied to 2n-k output bits. |
| `BCH Codes.xlsx` | **232 BCH code configs**: *k* (info bits), *n* (codeword bits), *t* (error capability). |
| `Polar Codes.xlsx` | **16 polar code configs**: *E* (rate-matched length), *K* (info length). |
| `LFSR Primitive Polynomials.xlsx` | **64 LFSR configs**: degree and primitive generator polynomials. |
| `LSTM - Test Convolutional Codes.xlsx` | **LSTM baseline test configs** (15 of 17 from Xu et al. + 10 additional). |
