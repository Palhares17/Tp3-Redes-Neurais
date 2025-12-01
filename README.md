# Tp3-Redes-Neurais Vision Transformer - Otimização no CIFAR-10

Otimização do Vision Transformer (ViT) no CIFAR-10 através de ajustes de batch size e data augmentation.

### 🎯 Resultados
Melhor Acurácia: 98.63% (batch 128 + RandAugment + CutMix)
Paper Original: 99.50% (com 20× mais dados de pré-treinamento)
Diferença: Apenas -0.87%

### 🚀 Execução Rápida
Google Colab (Recomendado)

Abra Batch_ViT_treinamento.ipynb ou Augmentation_ViT_treinamento.ipynb
Configure GPU: Runtime → Change runtime type → GPU: A100 (Colab Pro recomendado)
Execute todas as células

### 👨‍💻 Autor
Matheus Silva Palhares
Ciência da Computação - UFV Campus Florestal
📧 matheusspalhares@ufv.br

### 📚 Referências
Dosovitskiy et al. (2021) - "An Image is Worth 16x16 Words" (ICLR)
Cubuk et al. (2020) - "RandAugment" (CVPR)
Yun et al. (2019) - "CutMix" (ICCV)
