---
layout: default
title: Comandos no Terminal
nav_order: 2
---

# Comandos no Terminal

{: .no_toc }

<details open markdown="block">
  <summary>
    Tabela de Conteúdo
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---

## Simplificando o Terminal

Os comandos em um terminal funcionam como instruções para o computador. Aqui está uma explicação simplificada:

* **Terminal:** É um interpretador de comandos que permite que você instrua o computador a realizar operações específicas, como copiar um arquivo ou iniciar a execução de um programa.
* **Comando:** Qualquer entrada no terminal a ser executada é chamada de comando. Você pode executar no terminal tanto comandos que retornam apenas texto quanto comandos de programas com interface gráfica de usuário (GUI).
* **Execução de Comandos:** Para executar comandos, você digita o comando no terminal e pressiona a tecla `Enter`.
* **Argumentos e Opções:** Um comando pode ter argumentos e opções (também chamadas de flags). Os argumentos são informações adicionais que você fornece ao comando para realizar uma tarefa específica. As opções modificam o comportamento do comando.
{: .mb-8 }

## Estrutura de um Comando

Aqui estão alguns exemplos abstratos de como um comando no terminal pode ser estruturado:

1. **Comando Simples:**
    ```yaml
    comando
    ```
    Neste exemplo, `comando` é o comando que você deseja executar.
    {: .mb-6 }

2. **Comando com Argumentos:**
    ```yaml
    comando [argumento1] [argumento2]
    ```
    Aqui, `comando` é o comando que você deseja executar, e `argumento1` e `argumento2` são argumentos adicionais que você está passando para o comando.
    {: .mb-6 }

3. **Comando com Opções:**
    ```yaml
    comando -opção
    ```
    Neste exemplo, `comando` é o comando que você deseja executar, e `-opção` é uma opção que modifica o comportamento do comando.

    {: .note }
    Alguns comando utilizam uma mistura de `-opção` e/ou `--opção`, sempre procure a documentação do comando na internet caso tenha dúvida.
    {: .mb-6 }

4. **Comando com Argumentos e Opções:**
    ```yaml
    comando -opção [argumento1] [argumento2]
    ```
    Aqui, comando é o comando que você deseja executar, `-opção` é uma opção que modifica o comportamento do comando, e `argumento1` e `argumento2` são argumentos adicionais que você está passando para o comando.

### Por exemplo:
{: .no_toc }

```bash
dir /w C:\
```

Neste exemplo, dir é o comando para listar arquivos, `/w` é uma opção que diz ao comando para exibir os arquivos e diretórios em um formato mais amplo, e `C:\` é o argumento que diz ao comando onde listar os arquivos. Este comando irá listar os arquivos e diretórios na raiz do drive `C:`.

{: .important }
> Lembre-se, o terminal é uma ferramenta poderosa e deve ser usado com cuidado. Como diz a famosa frase: *"Com grandes poderes, vêm grandes responsabilidades"*.
{: .mb-8 }

## Caminhos

Os caminhos no sistema operacional são usados para especificar a localização de um arquivo ou diretório no sistema de arquivos. No Prompt de Comando do Windows, você pode navegar pelos caminhos do sistema usando comandos específicos. Aqui está uma explicação simplificada:

1. **Diretório Raiz:**
No Windows, cada unidade de disco tem seu próprio diretório raiz, como `C:\`, `D:\`, etc.

2. **Diretórios e Subdiretórios:**
Diretórios (ou pastas) podem conter subdiretórios. Por exemplo, `C:\Users\NomeDoUsuario\Documents` representa o diretório `Documents` dentro do diretório `NomeDoUsuario`, que está dentro do diretório `Users` no disco `C:`.

3. **Nomes Compostos:**
Se um diretório ou arquivo tem um nome composto (com espaços), você deve colocar o nome entre aspas. Por exemplo, `cd "C:\Users\Nome Composto\Documents"`.

4. **Caminho Absoluto vs Caminho Relativo:**
Um caminho absoluto começa a partir do diretório raiz, enquanto um caminho relativo começa a partir do diretório atual. Por exemplo, se o diretório atual é `C:\Users\NomeDoUsuario`, o comando `cd Documents` (um caminho relativo) terá o mesmo efeito que `cd C:\Users\NomeDoUsuario\Documents` (um caminho absoluto).
{: .mb-8 }

## Comandos Básicos

1. **`cd` e `cd ..`:**

    O comando `cd` (Change Directory) é usado para mudar o diretório atual no terminal. Por exemplo, `cd Documents` mudará o diretório atual para o diretório `Documents`. O comando `cd ..` é usado para voltar ao diretório pai do diretório atual.
    {: .mb-6 }

2. **`dir` e `ls`:**

    O comando `dir` (no Windows) ou `ls` (no Linux) é usado para listar os arquivos e subdiretórios dentro do diretório atual.
    {: .mb-6 }

3. **`mkdir`:**
    
    O comando `mkdir` (Make Directory) é usado para criar um novo diretório. Por exemplo, `mkdir NovoDiretorio` criará um novo diretório chamado `NovoDiretorio` no diretório atual.
    {: .mb-6 }

4. **`mv`:**

    O comando `mv` (Move) é usado para mover ou renomear arquivos e diretórios. Por exemplo, `mv arquivo1.txt arquivo2.txt` renomeará o arquivo `arquivo1.txt` para `arquivo2.txt`.
    {: .mb-6 }

5. **`echo` e Tubulações `>>`:**
    
    O comando `echo` é usado para exibir uma linha de texto. Por exemplo, `echo "Olá, Mundo!"` exibirá "Olá, Mundo!" no terminal. A tubulação `>>` é usada para redirecionar a saída de um comando para um arquivo. Por exemplo, `echo "Olá, Mundo!" >> arquivo.txt` adicionará a linha "Olá, Mundo!" ao final do arquivo `arquivo.txt`.

&nbsp;

{: .note }
Lembre-se, estes são apenas exemplos abstratos. Os comandos, argumentos e opções reais que você usará dependem do que você deseja realizar no terminal. Sempre consulte a documentação ou use o comando `help` (no Windows) ou consulte a internet para obter informações sobre um comando específico.

{: .note }
Alguns comandos podem funcionar da mesma maneira tanto no **Windows** quanto no **Linux**.
