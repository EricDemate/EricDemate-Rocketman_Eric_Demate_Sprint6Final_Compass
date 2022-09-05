![Banner](https://user-images.githubusercontent.com/64226050/188412615-a9d66c0b-e441-4896-a4bf-e06c36bf7969.png)

## Instalação Newman


Para instalar o Newman sem seu computador utilize os seguintes procedimentos:
<br><br>
Para instalação do Newman você deve digitar em um Terminal de comando:

<br>

1º comando:
```
npm install -g newman
```
2º comando:
```
npm install -g newman-reporter-htmlextra
```
3º comando:
```
npm install -g newman-reporter-html
```
4º comando:
```
npm install -g newman-reporter-htmlextra
```
<br>

## Exportação arquivos Postman

Após ter realizado a instalação dos pacotes, você deverá exportar os arquivos de Collections e Environments do Postman como mostra as figuras abaixo:


Environments:

![img](https://user-images.githubusercontent.com/64226050/188417119-ec1a7f9c-7b32-449a-972a-e90f8c886869.png)



Collections:

![img](https://user-images.githubusercontent.com/64226050/188416858-f34df843-22b1-4d59-8973-9bdd47ddc4f8.png)

!ATENÇÃO
Ambos serão salvos com extensão (arquivo.json)

## Executando o Newman

Agora para finalizar e obter o arquivo gerado pelo Newman você deverá abrir um terminal na pasta que salvou os arquivos anteriormente, e executar o seguinte codigo.

```
newman run arquivoCollection.json -e arquivoEnvironment.json -n 4 -r htmlextra
```
**ATENÇÃO NOVAMENTE!**

arquivoCollection.json e arquivoEnvironment.json são os teus arquivos!

## eeeeeee.....VUALÁ!!! A mágica está pronta! ##

![img](https://user-images.githubusercontent.com/64226050/188420128-d38fd2cd-9ccc-4a8b-b6aa-6854fb4e95b3.png)
____

![Banner](https://user-images.githubusercontent.com/64226050/188371378-9f12963c-251c-405f-94a0-f46624065097.png)


