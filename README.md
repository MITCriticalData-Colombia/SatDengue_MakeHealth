# MakeHealth datathon [[Website](http://makehealthlatam.com/en/)]

## 1. Dengue satellite data 
Tabular data for Dengue can be downloaded in the following items

1. [Download](addheredata) 


## 2. Satellite images feature extraction with deep learning models

Satellite features for 164 images for Medellin can be downloaded here in `pickle` format. The shape for each file is given by the structure `(164, 100)`, where 100 represents the number of features obtained for each model. 

1. [Features 1 - Download](https://drive.google.com/file/d/1-6z54hbeRyQNDgKG_c1ZMYhadz8kVsha/view?usp=sharing): Feature extraction variation based on resnet50 pretrained on Imagenet - Extracted from Sentinel 2 in Medellin between 2015-2018
2. [Features 2 - Download](https://drive.google.com/file/d/1-LbFSHPsPac9uLlfVzkJvg4f8JobZfLJ/view?usp=sharing): Feature extraction variation based on vision transformers pretrained on Imagenet - Extracted from Sentinel 2 in Medellin between 2015-2018
3. [Features 3 - Download](Download): Obtained by model 3

For all models, find labels here: [Download](https://drive.google.com/file/d/1-RPe1OEqeqvrCedCSIXGRTN6XFYjzHfU/view?usp=sharing)

## 3. Satellite images dimensionality reduction with Variational Autoencoders

Satellite embeddings for 164 images of Medellin can be downloaded here in `pickle` and `csv` format. 
* `pickle`: The shape for each `pickle` file is given by the structure `(164, n_features)`, where n_features represents the number of features obtained for each model.
1. [Features 4 - Download](https://drive.google.com/file/d/1oqbrU0e_86bItrHFD7NA1CRWG0U7Jeqz/view?usp=sharing): Embeddings generated using a variational autoencoder with latent space of 100 (100 features) in pickle format - Extracted from Sentinel 2 in Medellin between 2015-2018
2. [Features 5 - Download](https://drive.google.com/file/d/1lal9d1U5_U268TaqQSrWSyAAauy0Ww-e/view?usp=sharing): Embeddings generated using a variational autoencoder with latent space of 200 (200 features) in pickle format - Extracted from Sentinel 2 in Medellin between 2015-2018

* `csv`: The shape for each `csv` file is given by the structure `(164, n_features + 1)`, where n_features represents the number of features obtained for each model and the extra column is the date of the image.
1. [Features 6 - Download](https://drive.google.com/file/d/17BSXuyThcOxuDSIjsNaHfxJivf1EF30-/view?usp=sharing): Embeddings generated using a variational autoencoder with latent space of 100 (100 features) in csv format - Extracted from Sentinel 2 in Medellin between 2015-2018
2. [Features 7 - Download](https://drive.google.com/file/d/1ERUx6ZWy6fw62xvGdI5CL2gbXa831Izs/view?usp=sharing): Embeddings generated using a variational autoencoder with latent space of 200 (200 features) in csv format - Extracted from Sentinel 2 in Medellin between 2015-2018
For all models, find labels here: [Download](https://drive.google.com/drive/folders/1osVDwwTHJ-lKLaNZtFee7SVB2SVQmZGE?usp=sharing)

## 4. Satellite images dimensionality reduction with principal component analysis (PCA)

Satellite embeddings for 164 images of Medellin can be downloaded here in `pickle` and `csv` format. 
* `pickle`: The shape for each `pickle` file is given by the structure `(164, n_features)`, where n_features represents the number of features obtained for each model.
1. [Features 8 - Download](https://drive.google.com/file/d/1r0r6tZP-D0Zb069iakch7LKj3fZq-xKL/view?usp=sharing): Embeddings generated using the first 100 principal components in pickle format - Extracted from Sentinel 2 in Medellin between 2015-2018
2. [Features 9 - Download](https://drive.google.com/file/d/1dHOCsWQ1ScaLIUETEVESvlU4QwpPjdr_/view?usp=sharing): Embeddings generated using the first 10 principal components in each band (120 features in total per image) in pickle format - Extracted from Sentinel 2 in Medellin between 2015-2018

* `csv`: The shape for each `csv` file is given by the structure `(164, n_features + 1)`, where n_features represents the number of features obtained for each model and the extra column is the date of the image.
1. [Features 10 - Download](https://drive.google.com/file/d/1X-OaYFbhocrhRC3i3OKRj8Pvhn0nENJ_/view?usp=sharing): Embeddings generated using the first 100 principal components in csv format - Extracted from Sentinel 2 in Medellin between 2015-2018
2. [Features 11 - Download](https://drive.google.com/file/d/1kS3uFR5GX6sUBRCaXDbwyY2SYxZDGZkm/view?usp=sharing): Embeddings generated using the first 10 principal components in each band (120 features in total per image) in csv format - Extracted from Sentinel 2 in Medellin between 2015-2018

For all models, find labels here: [Download](https://drive.google.com/drive/folders/1osVDwwTHJ-lKLaNZtFee7SVB2SVQmZGE?usp=sharing)

## 5. Dates
Array of tahes in `pickle` format of shape  `(164)`:
1. [dates - Download](https://drive.google.com/file/d/1w-P_WqRdy1iUSnCoaRH2-azeDUQROtSr/view?usp=sharing): Dates of each satellite image in pickle format.
