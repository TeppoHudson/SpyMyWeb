
Para utilizar o script configure os parametros necess�rios no arquivo de configura��o "config.cfg", ap�s isto, execute o "servidorWeb Logs.py" e logo em seguida o "packetExtractor.py", para executar um teste do zero aconselha-se copiar o conteudo de default.html dentro de index.html


-"packetExtractor.py": L� o arquivo pacotes.txt e extrai os pacotes referentes a imagens, e utilizando do Full Request URI e do urllib � efetuado o download da imagem. Ap�s cada download, a imagem � aberta e enviada anexada a um cabe�alho POST.

-"servidorWeb Logs.py": Espera por requisi��es GET ou POST, sendo que nesta �ltima, a imagem recebida ser� gravada com o nome original da url e a cada nova imagem recebida a p�gina index.html � atualizada para exibi-la; e tamb�m um log � criado mostrando como foi o processo de recebimento dos pacotes.

