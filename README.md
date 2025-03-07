# SPOTLITES
### Code for microscopy analysis in "Pooled tagging and hydrophobic targeting of endogenous proteins for unbiased mapping of unfolded protein responses"

### Associating tagged protein identities with high-resolution cell images
Sequencing by synthesis (SBS) images were collected at lower magnification to minimize experiment duration and data storage requirements. SBS information, which encodes the identity of the tagged protein in every cell, was subsequently mapped to information-rich higher magnification cell images as recorded in the associated jupyter notebook 'Tagged protein identification by cross-magnification image registration for SPOTLITES libraries,' using the [provided helper functions](helper_functions.py) and a conda environment comprising the packages recorded in [requirements.txt](requirements.txt)

### sgRNA sequence deconvolution from images
Reads were called and mapped to libraries of tagging sgRNAs using standard snakemake workflows for Optical Pooled Sequencing (OPS) as described in detail in Feldman, D., Funk, L. et al Nature Protocols (2022) and the associated GitHub repository [feldman4/OpticalPooledScreens](https://github.com/feldman4/OpticalPooledScreens).
