# Uncertainty-aware Pseudo Label Refinery for Entity Alignment (WWW,2022)

## Datasets

The datasets are from [GCN-Align](https://github.com/1049451037/GCN-Align), [JAPE](https://github.com/nju-websoft/JAPE), [RSNs](https://github.com/nju-websoft/RSN) and load the pre-trained word embeddings, please download the zip file from (https://nlp.stanford.edu/data/glove.6B.zip) and choose "glove.6B.300d.txt" as the word vectors.



* ent_ids_1: ids for entities in source KG;
* ent_ids_2: ids for entities in target KG;
* ref_ent_ids: entity links encoded by ids;
* triples_1: relation triples encoded by ids in source KG;
* triples_2: relation triples encoded by ids in target KG;
* name.json: translated entity name


## Environment

* Python = 3.6
* Keras = 2.2.5
* Tensorflow = 1.14.0
* jupyter
* Scipy
* Numpy
* tqdm
* numba


## Running

* run *main.py*

> Due to the instability of embedding-based methods, it is acceptable that the results fluctuate a little bit (±1%) when running code repeatedly.

> If you have any questions about reproduction, please feel free to email to lijia92@bit.edu.cn.


## Acknowledgement

We refer to the codes of these repos: [keras-gat](https://github.com/danielegrattarola/keras-gat), [GCN-Align](https://github.com/1049451037/GCN-Align), [MRAEA](https://github.com/MaoXinn/MRAEA), [AliNet](https://github.com/nju-websoft/AliNet). 
Thanks for their great contributions!
