# Implementação - APD

Algoritmo desenvolvido para aceitar como entrada:  1 - APD (de acordo com o usuário) , 2 - cadeias para teste de acordo com o usuário. Como saída, identifique se a cadeia fornecida pelo usuário é ou não aceita.

O repositorio contem 5 itens, sendo eles:
    
    APDs = Pasta com APDs para testes.
    
    JFLAP7.1.jar = Arquivo executavel para criar ou exibir os APDs.
    
    jflap-pda2utfpr.py = Algoritmo para conversão do .jff para txt para ser usado para o teste.
    
    README.MD = Intruções de uso e observações.
    
    StackAuto.py = Algoritmo para realizar o teste se a cadeia vai ser aceita ou não no determinado APD.

Para funcionamento é dividido em 3 etapas:

1:

    Criação ou abertura do APD atraves do JFLAP7.1.jar.

2:

Para converter o arquivo .jff para .txt para ser executado no StackAuto.py, estando na pasta do algoritmo vamos digitar:
    
     jflap-pda2utfpr.py APDs/"arquivo JFLAP".jff APDs/"arquivo JFLAP".jff.txt
 
Dentro da pasta APDs vai ser criado um arquivo já convertido, mas na pasta raiz vai ser criar o teste.txt onde vai ser ele que vai ser usado para executar o teste.

3:

Para realizar o teste agora vamos executar o comando:
    
    StackAuto.py teste.txt "Cadeia de entrada"

Ao rodar esse algoritmo é mostrado se esta aceitando por pilha vazia ou estado de aceitação, ou seja se é aceita ou não.


  Autores: Jan Carlos dos Santos Silva e Jefter Roberto Mota Targino