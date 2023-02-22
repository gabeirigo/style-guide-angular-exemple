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

 - Contém um arquivo de roteamento para possiblitar a implementação de lazy load;
 
 - Contém seus prórpios components;
 
 - Contém uma pasta shared onde ficará os components, services, interfaces e outras arquivos que serão compartilhados entre os componentes da funcionalidade;


![estrutura da pasta core](./Screenshot%202023-02-22%20004218.png)

&nbsp;

### **Shared**

Este é o módulo onde fica tudo que é compartilhado e reutilizado por toda a aplicação.

![estrutura da pasta core](./Screenshot%202023-02-22%20005230.png)

&nbsp;

&nbsp;

# **Boas Práticas**

## **Clean Code**

### **Escrevendo bons nomes**
Texto aqui

### **Estruturando suas funções**
Texto aqui
