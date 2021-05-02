# Desafio Go

## Descrição

Esse desafio é muito empolgante principalmente se você nunca trabalhou com a linguagem Go!
Você terá que publicar uma imagem no docker hub. Quando executarmos:

docker run <seu-user>/codeeducation

Temos que ter o seguinte resultado: Code.education Rocks!

Se você perceber, essa imagem apenas realiza um print da mensagem como resultado final, logo, vale a pena dar uma conferida no próprio site da Go Lang para aprender como fazer um "olá mundo".

Lembrando que a Go Lang possui imagens oficiais prontas, vale a pena consultar o Docker Hub.

3) A imagem de nosso projeto Go precisa ter menos de 2MB =)

Dica: No vídeo de introdução sobre o Docker quando falamos sobre o sistema de arquivos em camadas, apresento uma imagem "raiz", talvez seja uma boa utilizá-la.

Divirta-se

## Como validar o desafio

1. Executar o comando `docker run celsopires/codeeducation` para rodar a imagem que está no Docker Hub.
2. Verificar a mensagem `Code.education Rocks!` no terminal.
3. Executar `docker images | grep celso` e veificar que o tamanho da imagem celsopires/codeeducation:latest é 1,95MB.

### Lembretes

1. O nome do executável codeeducation foi definido através do comando `go mod init celsopires/codeeducation`.
2. Para gerar o executável usei o comando `go install`.