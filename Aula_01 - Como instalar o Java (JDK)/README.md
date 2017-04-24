# Como instalar o Java (JDK) e configurar as variáveis de ambiente.

### Agenda do Tutorial
  - Introdução
  - O que é o JDK
  - Download do Java (JDK)
  - Instalação do Java (JDK)
  - Variáveis de Ambiente
    - Configurando as Variáveis de Ambiente no WINDOWS
  - Testando a configuração do ambiente
  - Na Próxima Aula

### Introdução
Este artigo irá ajudá-lo a realizar o Download, a Instalação e a configuração do Java no seu sistema operacional. 

### O que é JDK
Java Development Kit (JDK) significa Kit de Desenvolvimento Java. Este pacote é disponibilizado pela Oracle, e nele vem todo o ambiente necessário para a criação e execução dos aplicativos java. 
O Java JDK é composto pelo compilador e pelas bibliotecas (API’s).

### Download do JDK
Faça o download do pacote no site da Oracle pelo seguinte endereço: [Java Download][oracle]

Ao Acessar o link mencionado, existirá 2 opções de Download.
- Selecione a opção com a imagem descritiva: `JAVA PLATFORM (JDK)`

Isto fará ser apresentada todas as opções de versões para download disponíveis.
- Selecione o Radio Button `Accept License Agreement` que aceita as condições de licença e clique sobre o JDK adequado para a arquitetura da sua máquina e sistema operacional.

### Instalação do Java (JDK)
Realize o download e execute o aplicativo de instalação, aceitando o diretório de instalação sugerido e selecionando a opção Next até a finalização da instalação.

### Variáveis de Ambiente
Devemos agora, configurar as variáveis de ambiente do nosso Sistema Operacional
* JAVA_HOME
* CLASSPATH
* Path

### Configurando as Variáveis de Ambiente no WINDOWS
- No painel de controle do Windows, acesse o menu `Configurações avançadas do sistema`.
- Em seguida, selecione a aba `Avançado` da janela apresentada e nesta aba, a opção `Variáveis de
Ambiente`.

Na interface apresentada poderemos configurar as 3 variáveis de ambiente citadas acima.

- Primeiramente, vamos criar a variável `JAVA_HOME` selecionando o botão NOVO para variáveis do sistema.

Crie esta variável, colocando como valor o diretório onde foi instalado o JDK no computador.
- Como próximo passo devemos criar a variável `CLASSPATH` com o seguinte valor:
```sh
.;% JAVA_HOME%
```
- Agora voce deverá editar a variável `PATH` para adicionar a variável:
```sh
%JAVA_HOME%
```
Pronto, neste momento você terá seu ambiente pronto para iniciar o desenvolvimento na plataforma Java.

### Testando a configuração do ambiente
Entre em uma janela DOS e digite:
```sh
java –version
```
Verifique se é apresentada a versão do JDK que você instalou.

### Na Próxima Aula
* Aprenda a realizar o download de uma IDE de Desenvolvimento Java e inicie seu progresso profissional jovem Padawan.

### `Mestre Jeldai!`
> "Esteja atento à Força do Java, meu jovem Padawan."

[oracle]: <http://www.oracle.com/technetwork/java/javase/downloads/index.html>
   
