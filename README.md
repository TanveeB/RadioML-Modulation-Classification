RadioML Modulation Classification (Classical Pipeline)

Feature-based automatic modulation classification (AMC) on the RadioML 2016.10a benchmark, using filtering and hand-designed features instead of deep learning so every step can be explained.

Status: in progress. Data checks and filtering are done, feature extraction has started, and the classifier is not built. There is no accuracy result yet.

Dataset

RadioML 2016.10a: 11 modulations (8PSK, AM-DSB, AM-SSB, BPSK, CPFSK, GFSK, PAM4, QAM16, QAM64, QPSK, WBFM), 20 SNR levels from -20 to +18 dB (2 dB steps), 1000 examples per modulation and SNR, each 128 complex I/Q samples.

The dataset is not included in this repository because of its size. Download it from DeepSig (https://www.deepsig.ai/datasets):

data/RML2016.10a_dict.pkl
