# BlueHorizon
## Crowdsourcing para a retirada de lixo dos oceanos
<p>A BlueHorizon está engajada no desenvolvimento de um projeto voltado à preservação e limpeza dos oceanos por meio da tecnologia e na promoção de um futuro sustentável por meio do crowdsourcing.</p>
<p>Para isso, será desenvolvido um aplicativo/site para a retirada de lixo das praias e oceanos - mas não é a BlueHorizon que vai fazer a retirada, apenas fará o intermédio e receberá o lixo, quem retirará são os voluntários. No aplicativo, o voluntário pode ver algumas matérias sobre o assunto, acompanhar seu perfil, seu progresso e o dinheiro disponível para sacar.</p>

## E mais:
<p>De um lado, tem-se empresas engajadas na preservação dos oceanos e que querem financiar o projeto e incentivar os voluntários. Do outro lado, tem-se voluntários que trabalham na retirada de lixo dos oceanos/praias e que recebem um determinado valor para isso.</p>
<p>Ao mesmo tempo em que se garante um futuro limpo ao retirar o lixo dos oceanos, também é garantido aos voluntários o recebimento de dinheiro pelo seu esforço e cuidado. Dessa forma, a BlueHorizon tem a missão de contribuir com a limpeza dos oceanos por meio da união coletiva.</p>
<p></p><br>

## Nosso time 2TDSPF:
#### 1. Douglas Magalhães de Araujo - 552008

#### 2. Gustavo Argüello Bertacci - 551304

#### 3. Luiz Fillipe Farias - 99519

#### 4. Rafaella Monique do Carmo Bastos - 552425
<p></p><br>

## Vídeo do funcionamento do app
...
<p></p><br>

## Como rodar a aplicação na VM

<p>1. Faça o login no Docker com o comando (opcional): </p>

#### docker login

![image](https://github.com/rafaellabastos/gs-bluehorizon-devops/assets/126570094/d459a257-2882-4279-80f8-6213035683b9)
<br>

<p>2. Faça o download da imagem do docker com o comando: </p> 

#### docker pull luizffarias/bluehorizon-spring-gs:v1.0

![image](https://github.com/rafaellabastos/gs-bluehorizon-devops/assets/126570094/4dba6bbd-1481-4be4-aae6-2ffb031ac44c)
<br>

<p>3. Verifique se a imagem foi corretamente instalada com: </p>

#### docker images

![image](https://github.com/rafaellabastos/gs-bluehorizon-devops/assets/126570094/25867bdb-1dd0-4053-9b3c-5486a1894743)
<br>

<p>4. Rode a imagem dentro de um container utilizando a porta 80 com o comando: </p> 

#### docker run --name NomeDoContainer -p 80:80 luizffarias/bluehorizon-spring-gs:v1.0

![image](https://github.com/rafaellabastos/gs-bluehorizon-devops/assets/126570094/d812f825-59d3-4bb3-b8e3-c26d739943d4)

<p>5. Teste os endpoints da API através de plataformas de monitoramento de APIs como postman ou através do Swagger</p>

![image](https://github.com/rafaellabastos/gs-bluehorizon-devops/assets/126570094/0d507f78-7414-4dd5-9815-3dadac9a196f)



