# Medical-Image-Segmentation-with-UNet++


# Data 
The data used for this project consists of 2,620 scanned film mammography studies part of the CBIS-DDSM (Curated Breast Imaging Subset of DDSM) [1] which is an updated and standardized version of the Digital Database for Screening Mammography (DDSM). 
There are 5 data files to consider:
- calc_case_description_test_set.csv
- calc_case_description_train_set.csv
- mass_case_description_test_set.csv
- mass_case_description_train_set.csv
- CBIS-DDSM-All-doiJNLP-zzWs5zfZ.tcia
The calc_case csv's refers to the description of calcifications in the breast while the mass_case csv's refer to massifications found. The images regarding the mamographies are retrieved throught NBIA Data Retriver. The instructions to download and use the NBIA data retrive followed by downloading TCIA images can be found in the following link [2].




# References
- Dataset: [1] Sawyer-Lee, R., Gimenez, F., Hoogi, A., & Rubin, D. (2016). Curated Breast Imaging Subset of Digital Database for Screening Mammography (CBIS-DDSM) [Data set]. The Cancer Imaging Archive. https://doi.org/10.7937/K9/TCIA.2016.7O02S9CY
- [2] https://wiki.cancerimagingarchive.net/display/NBIA/Downloading+TCIA+Images#DownloadingTCIAImages-DownloadingtheNBIADataRetriever
- https://pydicom.github.io/pydicom/stable/old/getting_started.html
- 
