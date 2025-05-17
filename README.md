1. This code accompanies the paper "[Secure Time-Modulated Intelligent Reflecting Surface via Generative Flow Networks](http://eceweb1.rutgers.edu/%7Ecspl/materials/group/ZT/Asilomar2025__V0_.pdf)",
   by Z. Tao and A. Petropulu.

3. "GFN4SecureTM_IRS.ipynb" implements the proposed GFlowNet-based method for optimizing time modulation parameters in an OFDM TM-IRS system. "plotFigures.ipynb" is used to reproduce the figures presented in the paper.
   "tb_checkpoint_0dB.pth" contains the trained GFlowNet model, which can be loaded directly for inference or further use.

5. "results_data0.npz-results_data3.npz" contain the raw SER data used in the paper. Note: results_data4.npz is missing due to accidental overwriting.
   However, this is not critical, as similar results can be regenerated using the saved checkpoint (tb_checkpoint_0dB.pth) and the provided code.
