 
Universidade Federal de Viçosa
Departamento de Engenharia Agrícola

Desafio Mapeamento Digital no QGIS
04, 05 e 06 de agosto de 2021

Autor: Prof. Domingos Sárvio Magalhães Valente

1.	Informações gerais
Esse banco de dados contém 3 arquivos tipo shapefile: Contorno.shp, Desafio.shp e Dados.shp  no sistema de projeção WGS 84 UTM 23S. 
-O arquivo Contorno.shp é um polígono do talhão. 
-O arquivo Dados.shp é um shapefile tipo pontos (71 pontos). A tabela de atributos do arquivo Dados.shp contém 4 colunas: ID do ponto, coordenadas x e y, e o atributo. 
-O arquivo Desafio.shp também é um shapefile de pontos (10 pontos). Na tabela de atributos do arquivo Desafio.shp contém os atributos ID e as coordenadas x e y dos pontos. 


2.	Objetivo do desafio
Sua tarefa é fazer a predição dos 10 pontos do arquivo shapefile "desafio.shp". Preencher o seguinte formulário (link abaixo) e enviar. 
https://forms.gle/boeffRRKd9NvhtHT7

3.	Regras
Você poderá enviar somente uma única vez, ok?
Utilize as informações que julgar necessárias para fazer as predições dos 10 pontos
O formulário tem o ID de cada ponto que deverá ser o mesmo ID do ponto do arquivo Desafio.shp.
Prazo de envio: até 06/08 (sexta-feira) as 12 horas (meio dia de Brasília).
O vencedor será anunciado no último dia do desafio (dia 06/08) durante a live no Youtube.
O ganhador deverá estar presente no momento do anúncio. Se não estiver, a premiação passará para o próximo colocado. Assim por diante, até encontrar alguém presente.

4.	Dicas
Tente interpolar utilizando o plugin Smart-Map.
Após a interpolação, você poderá utilizar a ferramenta do QGIS (add raster values to points). Essa ferramenta irá adicionar os valores dos pixels do raster (mapa interpolado) no shapefile "Desafio.shp". Após isso você terá os valores para cada ponto. Basta digitar no formulário o valores para cada ID correspondente no shapefile, e enviar.


Boa sorte!
Sárvio Valente
