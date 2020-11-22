# Super-Resolution
 
Este repositório é dedicado ao código do meu Projeto Final sobre modelos de redes neurais para Super-Resolução de Imagem Única.
O código original foi implementado por Martin Krasser http://krasserm.github.io/2019/09/04/super-resolution/ e eu adicionei os arquivos de eval.

O código é feito para o ambiente jupyter notebook e precisa da tensorflow 2.0 ou maior instalada.

O arquivo Super Resolution.ipynb realiza o download do dataset e faz o treinamento do modelo EDSR. Os outros modelos são treinados nos seus arquivos de example.

Os arquivos de eval fazem a validação de seus respectivos modelos. Medindo MeanAbsoluteError, PSNR e SSIM de cada modelo.
