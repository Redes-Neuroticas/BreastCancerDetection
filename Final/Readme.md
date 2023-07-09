# Detecção de Câncer de Mamas - Grupo Redes Neuróticas

# Arquivos-Fonte
Os arquivos-fonte na pasta são os seguintes:
- Análise exploratória e geração de datasets em treino/validação
  - Analise_Exploratoria.ipynb
  - data_exploration.ipynb
  - Separação - Base de Dados.ipynb

- Geração do baseline
  - Baseline I - VGG16.ipynb
  - Baseline II - ResNet50.ipynb
  - baseline.ipynb

- Extração de características
  - Extracao de Caracteristicas - ConvNeXtXLarge.ipynb
  - featureextract_resnet50.ipynb
  - Random Forest + ConvnextXlarge.ipynb
  - randomforest_resnet50.ipynb

- Data augumentation
  - convNext_data_aug.ipynb
  - data_aug_brightness.ipynb
  - data_aug_pipeline.ipynb
  - resnet50_data_aug.ipynb

- Explicabilidade
  - explainability_baseline_resnet50.ipynb
  - explainability_baseline_vgg16.ipynb

- Kaggle
  - KaggleSubmissionNotebook.ipynb

- Utilitário
  - utils.ipynb

# Assets
Os assets podem ser baixados de https://drive.google.com/drive/folders/1kSEnpvCAzpsrx3S145tFDo9SPAYMBxpj,
que contém os seguintes arquivos:
```
- base de imagens
   +- df_val_split.parquet - Parquet do dataframe de validação
   +- df_train_split.parquet - Parquet do dataframe de treinamento
   +- baseline.zip - Imagens PNG separadas em treino, validação e teste
- models
   +- baseline_vgg16.h5 - Modelo VGG-16 usado no primeiro baseline
   +- baseline_resnet50.h5 - Modelo ResNet-50 usado no segundo baseline
- features_preprocess
   +- convnextXLarge_train.parquet
   +- convnextXLarge_val.parquet
   +- convnextXLarge_test.parquet
   +- features_train_hist.json
   +- features_test_hist.json
   +- features_validation_hist.json
```
