# Plataforma de desenvolvimento

## Compilação

O __compilador__ empregado para a construção do programa de teste da biblioteca simuladora do RISC_V foi o __gcc 7.3.0__ (padrão do Linux Ubuntu 18.04).

Para sua compilação foi utilizada o seguinte padrão:

```
$ gcc <arquivos> -W -Wall -g -pedantic -o <nome_do_programa>
```

Mais informações da forma como os códigos foram compilados, por favor, consultar o arquivo Makefile. Para a compilação do programa, basta estar no diretório dos arquivos de código juntamente com o arquivo makefile e executar pelo terminal:

```
$ make
```
Para executar o programa depois da compilação:

```
$ ./test
```

## Plataforma SO

> O desenvolvimento desse código foi
> feita por meio do sistema
> operacional Linux, distribuição
> Ubuntu 18.04 LTS

## IDE de desenvolvimento

A IDE utilizada para a realização desse projeto foi o __Visual Studio Code__ para distribuições Debian, versão __1.33.1__