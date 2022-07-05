Image2Code é um pequeno utilitário java para converter imagens em uma matriz de bytes que pode ser usada como um bitmap na biblioteca Adafruit-GFX

# Guia do Usuario Original ( Em Meu Caso Não Obtive Sucesso, Logo a Seguir demonstrarei os erros e correções)

## Para Rodar
Abra o Terminal na Pasta do Image2Code e Rode o Comando /gradlew run

## Utilizando o Programa
1. Clique no botão "choose file". 
2. Copie o codigo gerado e cole em seu arduino sketch 
Exemplo: 
![image](https://user-images.githubusercontent.com/94911429/177403711-5c92e58b-ba99-4e94-b324-98c11584fd36.png)

## Dependencias para utilização do programa: 
1. Java: Se você não tem o Java Instalado, você pode achar ele neste link: https://www.java.com/en/download/
2. Gradle: O gradlew cuidará dessa dependência. Apenas execute o arquivo gradlew e ele baixara todas as dependências

#DEV guide:
This sub-project using Gradle to build. To build a runnable jar: ./gradlew jar 

## Possivel Erro 
Talvez você se depare com esse possivel erro 
![image](https://user-images.githubusercontent.com/94911429/177404717-c4952d2e-989a-498a-a12c-9e7d95e0a5f8.png)

A Solução que encontrei foi acessar o caminho: Img2Code\src\main\resources copiar o arquivo de imagem contido lá dentro e colar no caminho :Img2Code\src\main\java
neste mesmo caminho abri o terminal e executei o seguinte comando : java Image2Code.java

E obtive o resultado
![image](https://user-images.githubusercontent.com/94911429/177405452-e4ba2c2d-c4a5-4cfa-a5d3-17eb1283f95c.png)
