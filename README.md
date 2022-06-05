# MakeHealth datathon [[Website](http://makehealthlatam.com/en/)]

## 1. Dengue satellite data 
Tabular data for Dengue can be downloaded in the following items

1. [Download](addheredata) 


## 2. Satellite features

Satellite features for 164 images for Medellin can be downloaded here in `pickle` format. The shape for each file is given by the structure `(164, 100)`, where 100 represents the number of features obtained for each model. 

1. [Features 1 - Download](https://drive.google.com/file/d/1-6z54hbeRyQNDgKG_c1ZMYhadz8kVsha/view?usp=sharing): Feature extraction variation based on resnet50 pretrained on Imagenet - Extracted from Sentinel 2 in Medellin between 2015-2018
2. [Features 2 - Download](https://drive.google.com/file/d/1-LbFSHPsPac9uLlfVzkJvg4f8JobZfLJ/view?usp=sharing): Feature extraction variation based on vision transformers pretrained on Imagenet - Extracted from Sentinel 2 in Medellin between 2015-2018
3. [Features 3 - Download](Download): Obtained by model 3

For all models, find labels here: [Download](https://drive.google.com/file/d/1-RPe1OEqeqvrCedCSIXGRTN6XFYjzHfU/view?usp=sharing)

## 3. Satellite embeddings

Satellite embeddings for 164 images of Medellin can be downloaded here in `pickle` and `csv` format. 
* `pickle`: The shape for each `pickle` file is given by the structure `(164, n_features)`, where n_features represents the number of features obtained for each model.
1. [Features 4 - Download](https://drive.google.com/file/d/1oqbrU0e_86bItrHFD7NA1CRWG0U7Jeqz/view?usp=sharing): Embeddings generated using a variational autoencoder with latent space of 100 (100 features) in pickle format - Extracted from Sentinel 2 in Medellin between 2015-2018
2. [Features 5 - Download](https://drive.google.com/file/d/1lal9d1U5_U268TaqQSrWSyAAauy0Ww-e/view?usp=sharing): Embeddings generated using a variational autoencoder with latent space of 200 (200 features) in pickle format - Extracted from Sentinel 2 in Medellin between 2015-2018

* `csv`: The shape for each `csv` file is given by the structure `(164, n_features + 1)`, where n_features represents the number of features obtained for each model and the extra column is the date of the image.
1. [Features 6 - Download](https://drive.google.com/file/d/17BSXuyThcOxuDSIjsNaHfxJivf1EF30-/view?usp=sharing): Embeddings generated using a variational autoencoder with latent space of 100 (100 features) in csv format - Extracted from Sentinel 2 in Medellin between 2015-2018
2. [Features 7 - Download](https://drive.google.com/file/d/1ERUx6ZWy6fw62xvGdI5CL2gbXa831Izs/view?usp=sharing): Embeddings generated using a variational autoencoder with latent space of 200 (200 features) in csv format - Extracted from Sentinel 2 in Medellin between 2015-2018

For all models, find labels here: [Download](https://drive.google.com/drive/folders/1osVDwwTHJ-lKLaNZtFee7SVB2SVQmZGE?usp=sharing)

## 3. Satellite dimensionality reduction (PCA)
