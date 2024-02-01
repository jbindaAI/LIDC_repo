# ViT based bottleneck model on LIDC data
Repository consists on code needed to build classifier working on LIDC-IDRI dataset.
Solution is based on similar ConRad repository https://github.com/lenbrocki/ConRad developed by Lennart Brocki and Neo Christopher Chung.

Model is based on pretrained vision transformer model (ViT_b_16) and takes as input 32x32x32 crops from original LIDC scan volumes.

To run code:
1. Download LIDC-IDRI dataset from [LIDC-IDRI](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=1966254).
   I needed to download data and process it 100 hundred batches.
2. Run `Data_preparation.ipynb`. This notebook extract 32x32x32 crops from original LIDC-IDRI dataset. 
3. Run `FinetuneModel.ipynb`.
4.  TO DO
5.  TO DO
