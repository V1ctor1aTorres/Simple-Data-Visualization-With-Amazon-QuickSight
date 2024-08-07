# Visualização simples de conjuntos de dados usando Amazon S3 e Amazon QuickSight
[Tutorial: https://www.youtube.com/watch?v=4-8cXuZzKTg ](https://www.youtube.com/watch?v=4-8cXuZzKTg)
## Fazer download dos arquivos necessários:
- Conjunto de dados dos 50.000 produtos mais vendidos da Amazon em 2023
  <img src="">
- Arquivo de manifesto: utilizado para configurar a importação de dados.
   <img src="">

## Armazenar o conjunto de dados em um bucket do Amazon S3:
- Criar o bucket.
  <img src="https://github.com/V1ctor1aTorres/Simple-Data-Visualization-With-Amazon-QuickSight/blob/main/images/create_bucket.png">
- Fazer o upload do conjunto de dados e do arquivo de manifesto.
  <img src="https://github.com/V1ctor1aTorres/Simple-Data-Visualization-With-Amazon-QuickSight/blob/main/images/upload_manifest.png">

## Conectar o bucket com o Amazon QuickSight:
- Se regristrar no QuickSight para "free trial" caso ainda não tenha conta
  <img src="https://github.com/V1ctor1aTorres/Simple-Data-Visualization-With-Amazon-QuickSight/blob/main/images/QuickSight.png">
- Selecionar o bucket que você quer conectar ao QuickSight
  <img src="https://github.com/V1ctor1aTorres/Simple-Data-Visualization-With-Amazon-QuickSight/blob/main/images/select_bucket.png">
- No painel do QuickSight: datasets > new datasets > s3 > copiar a ulr do aquivo de manifesto e colar > criar um nome
  <img src="https://github.com/V1ctor1aTorres/Simple-Data-Visualization-With-Amazon-QuickSight/blob/main/images/manifest_url.png">

## Criar visualização dos dados:
- Utilizando o campo "brand" criamos uma visualização das marcas mais populares dentre os 50.000 produtos mais vendidos da Amazon.
  <img src="https://github.com/V1ctor1aTorres/Simple-Data-Visualization-With-Amazon-QuickSight/blob/main/images/marcas_mais_populares.png">

