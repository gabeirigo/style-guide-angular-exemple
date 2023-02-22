# **Conheça a estrutura geral do projeto { PROJETO }**

## **Estrutura de pastas**

Para facilitar sempre a manutenção e as futuras implementações de um projeto, é necessário que ele seja bem estruturado.

Esse é um exemplo de estrutura utilizando Angular baseado em três grande módulos: **core**, **features** e **shared**.

![estrutura de pastas](./Screenshot%202023-02-21%20234012.png)

&nbsp;

### **Core**

É o núcleo do projeto. Nela fica todo o conteúdo essencial para o funcionamento da aplicação.

![estrutura da pasta core](./Screenshot%202023-02-22%20002648.png)

&nbsp;

### **Features**

Contém todos os módulos da aplicação segmentados por funcionalidades. 

![estrutura da pasta core](./Screenshot%202023-02-22%20002930.png)


Cada funcionalidade possui uma estrutura básica:

 - Contém um arquivo de roteamento para possiblitar a implementação de *lazy load*;
 
 - Contém seus prórpios components;
 
 - Contém uma pasta shared onde ficará os components, services, interfaces e outras arquivos que serão compartilhados entre os componentes da funcionalidade;


![estrutura da pasta core](./Screenshot%202023-02-22%20004218.png)

&nbsp;

### **Shared**

Este é o módulo onde fica tudo que é compartilhado e reutilizado por toda a aplicação.

![estrutura da pasta core](./Screenshot%202023-02-22%20005230.png)

&nbsp;

&nbsp;

# **Boas Práticas - Clean Code**


## **Escrevendo bons nomes**

**Use nomes que revelem seu propósito.** Nomes são importantes no desenvolvimento de um software. Nomeamos variáveis, funções, classes... Por isso, devemos nomear tudo de forma clara. 

Veja um exemplo de um software de estratégias de Fórmula 1:

```typescript
    let t; //tempo de volta em segundos
```

Apesar de "t" não nos revelar nada, temos um comentário do lado que nos ajuda a entender o que se refere essa variável. 

Mas ao desenvolver o projeto, sempre que for utilizar essa variável, vai carregar a explicação do lado? Claro que não. Por isso, devemos colocar essa explicação no portador da informação, no nome. Veja alguns exemplos:

```typescript
    let tempoDeVoltaEmSegundos;
    let segundosDaVolta;
    let voltaEmSegundos;
```

Dessa forma, fica muito mais intuitivo, e em todo lugar que for utilizado essa variável, vai ficar claro do que se trata a informação.

>   O nome deve revelar **o porque existe, o que faz e como é usado**. Se um nome requer um comentário, então ele não revela seu propósito. **Nome, tal qual piada, se precisa ser explicado, é porque é ruim**.

&nbsp;
## **Estruturando suas funções**
texto sobre funções

&nbsp;
## **Comentários**
texto sobre comentários

&nbsp;
## **Formatação**
texto sobre comentários

&nbsp;
## **Objetos e estruturas de dados**
texto sobre objetos e estruturas de dados

&nbsp;
# **Boas Práticas - SOLID**
texto sobre SOLID

&nbsp;
# **Boas Práticas - Recomendações do Angular**
texto sobre recomendações do angular

&nbsp;
# **Design Patters: GOF**

Design patterns não são bala de prata. Por isso, conheça alguns design patterns e reflita o que faz sentido para a solução que procura.
