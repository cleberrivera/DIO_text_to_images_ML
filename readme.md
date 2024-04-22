# **Transformando Imagens em Texto no Azure ML**

#### 📌 Antes de tudo [clique aqui](https://azure.microsoft.com/pt-br/free/search/?ef_id=_k_CjwKCAjw_e2wBhAEEiwAyFFFo3RE7HE2-y1etoQbR5ZCAMuisChiKRd4zrBUFLYWzX6sBgB0OCxusRoChoMQAvD_BwE_k_&OCID=AIDcmmzmnb0182_SEM__k_CjwKCAjw_e2wBhAEEiwAyFFFo3RE7HE2-y1etoQbR5ZCAMuisChiKRd4zrBUFLYWzX6sBgB0OCxusRoChoMQAvD_BwE_k_&gad_source=1&gclid=CjwKCAjw_e2wBhAEEiwAyFFFo3RE7HE2-y1etoQbR5ZCAMuisChiKRd4zrBUFLYWzX6sBgB0OCxusRoChoMQAvD_BwE) para criar a sua conta na Microsoft Azure. 

#

- Primeiramente na aba **"Create Resource"** selecionamos **"AI + Machine Learning"** e no recurso **"Azure AI Services"** clicamos em **"create"**, assim será criado o resource group para utilizar a AI.

![azure](https://github.com/cleberrivera/DIO_text_to_images_ML/assets/132470980/11474921-e77c-4c05-95f3-4673d10012c2)

![create resource](https://github.com/cleberrivera/DIO_text_to_images_ML/assets/132470980/bfde0c11-cb9b-4903-8860-29bd38d45fb0)


#

- Em seguida no [portal da vision](https://portal.vision.cognitive.azure.com/gallery/featured) selecione o resource group já criado.

![select resource](https://github.com/cleberrivera/DIO_text_to_images_ML/assets/132470980/129b7260-0dde-402a-8071-cdbac8e148ca)


#

- Agora no menu do portal selecionamos **"Extract text from images"** e dentro desse serviço é possível realizar a extração.

![portal](https://github.com/cleberrivera/DIO_text_to_images_ML/assets/132470980/d78ba3ec-4098-4929-929b-80f04b69d39a)

![certificado](https://github.com/cleberrivera/DIO_text_to_images_ML/assets/132470980/7d72d28a-7a77-4bed-a712-16d705763f7d)

#

## <a title="Objetos" href="https://pt.piliapp.com/emoji/list/#objects" class="active">💡</a> Insights e Possibilidades

- Neste exemplo utilizei documentos pessoais como um certificado o qual testei a extração, porém a mesma pode ser utilizada para empresas que possuam documentos apenas em formato físico e queiram migrar esse conteúdo para o formato digital garantindo o armazenamento seguro da informação.

- Outro ponto importante seria na questão da organização em que a AI extrai o texto, pois é possível notar que a mesma acaba não organizando muito bem e para resolver tal problema podemos utilizar alguma AI generativa como o "**Copilot"** da "**Microsoft**" a fins de resolver esse problema escrevendo um prompt para garantir a organização de forma prática e rápida. 
#
## 🔎 Links de apoio:
- [AI Leitura de Texto](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html) 
#
![Microsoft Azure](https://img.shields.io/badge/MicrosoftAzure-000?style=for-the-badge&logo=MicrosoftAzure&logoColor=30A3DC)
