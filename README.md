# Scraping-RA
 Scraping de dados do Reclame Aqui utilizando a biblioteca Botcity.
 Ao final do código é enviado uma requisição POST para a plataforma N8N

 # Forma de instalação:
 Após o clone do repositório, faça a instalação dos requirements "pip install -r requirements.txt". Após isso, verifique o seu google chrome se está atualizado com a versão do chromedriver.
 Para que seja enviado as informações coletadas para a plataforma n8n, será necessário criar um arquivo .env tendo o link de webhook no método post da seguinte maneira: "url_wh = https://n8n/webhook-test/path-do-webhook"

 Se desejar utilizar para outras maneiras o resultado, será necessário apenas alterar o último campo do código.