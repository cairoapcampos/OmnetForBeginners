# OmnetForBeginners
Resumo básico dos recursos do simulador OMNet++

## **Cap 1 - Introdução**

1- Trocar de workspace:

* File -> Switch Workspace -> Other

Obs: Ao trocar, o omnet++ reiniciará com o novo workspace.

2- Alterar perpectiva para a de simulação (Organização das janelas da IDE no modo de simulação):

* Window -> Perspective -> Open Perspective -> Simulation

3- Alterar licença dos novos arquivos gerados:

Window -> Preferences -> "OMNeT++" -> License

4- Criar um novo projeto no OMNET++

* File -> New -> OMNet++ Project;
* Na janela "New OMNet++ Project" definir nome do projeto;
e deixe marcado "Support C++ Development" para que módulos simples possam ser criados.

5- Definir Referências do projeto (Definir projetos aos quais o novo projeto faz referência)

* No "Project Explorer" selecionar o projeto e clicar com botão direito;
* No menu de contexto do projeto, clicar em "Properties";
* Na opção "Project References" marcar os projetos de referencia existentes no Project Exolorer.

## **Cap 2 - Editar Arquivos NED**

6- Criar um arquivo NED no projeto

* Selecionar o projeto,
* File -> New -> Network Description File (NED),
* Poderá ser criado um arquivo NED vazio, com um módulo simples/composto ou uma rede.

7- Pasta de origem de arquivos NED

* No "Project Explorer" selecionar o projeto e clicar com botão direito;
* No menu de contexto do projeto, clicar em "Properties";
* Clicar na opção "OMNet++" e depois em "NED Source Folders". A pasta do projeto que será a origem deve ser escolhida.

Obs: A pasta de origem padrão é a pasta raiz do projeto.

8- Edição do arquivo NED no modo gráfico:

[![How to Create new simulation Project in OMNeT++](http://img.youtube.com/vi/L2FLoL3wngE/0.jpg)](http://www.youtube.com/watch?v=L2FLoL3wngE "How to Create new simulation Project in OMNeT++")

## **Cap 3 - Editando Arquivos INI**

9- Criar um arquivo ini no projeto

* Selecionar o projeto,
* File -> New -> Initialization File (Ini),
* Selecinar "Empty Ini File" e depois definir a rede criada no arquivo NED.

## **Cap 4 - Editando Arquivos de mensagens**

10- Criação de mensagens

* Selecionar o projeto,
* File -> New -> Message Definition (msg),
* Selecinar "Empty Message File" ou um modelo existente.

## **Cap 5 - Desenvolvimento C ++**

11- Teclas de Atalho:

* Desfazer: (Ctrl + Z)
* Refazer: (Ctrl + Y)
* Alternar entre um código fonte e seu header file: (Ctrl + TAB)
* Recuo correto (Identação): (Ctrl + I)
* Localizar e substituir: (Ctrl + F)
* Exlibir lista de teclas de atalho: (Ctrl + Shift + L)
* Sugestão sobre variaveis, nomes de tipos, etc: (Ctrl + ESPAÇO)
* Pressionar F3 ou segurar a tecla Ctrl e clicar em um identificador irá pular para a definição/declaração do mesmo.
* Comentar/descomentar linhas selecionadas: (Ctrl + /)

12- Construir (compilar um projeto):

* No "Project Explorer" selecionar o projeto e clicar com botão direito;
* No menu de contexto do projeto, clicar em "Build Project";

Ou 

* No "Project Explorer" selecionar o projeto;
* Clicar no menu "Project" e depois clicar em "Build Project".

13 - Compilar todos os projetos existentes no "Project Explorer":

* Pressionar Ctrl + B

ou 

* Clicar no menu "Project" e depois clicar em "Build All".

13- Limpar compilação do projeto:

* No "Project Explorer" selecionar o projeto e clicar com botão direito;
* No menu de contexto do projeto, clicar em "Clean Project";

14- Diminuir tempo de compilação desativando recursos de projeto não utilizados (Ex: Recursos do inet):

* Clicar no Menu "Project" e depois clicar na opção "Properties";
* Na janela que será aberta selecionar no menu lateral, a opção "OMNet++" e depois em "Project Features";
* Marcar/Desmarcar as caixas dos recursos para ativá-los/desativá-los.

## Cap 6 - Ativação e Debugging (Depuração)

15- Executar o projeto

* No "Project Explorer" selecionar o projeto, pasta, arquivo ini ou arquivo NED;
* Clicar no botão "Run";

ou

* No "Project Explorer" selecionar o projeto e clicar com botão direito;
* Run As -> OMNet++ Simulation

Obs: A pasta selecionada deve contem um arquivo ini ou NED.

16- Depurar o projeto

* No "Project Explorer" selecionar o projeto, pasta, arquivo ini ou arquivo NED;
* Clicar no botão "Debug";

ou

* No "Project Explorer" selecionar o projeto e clicar com botão direito;
* Debug As -> OMNet++ Simulation


Obs: A pasta selecionada deve contem um arquivo ini ou NED.

## **Cap 7 - O Ambiente de execução gráfico Qtenv e Cap 8 - O Ambiente de execução gráfico Tkenv**

17- Alterar ambiente gráfico utilizado para rodar a simulação

* Na seta ao lado do botão "Run", escolher a opção "Run Configurations";
* No campo "User interface", selecionar Qtenv, Tkenv ou Cmdenv.

18- Tipos de execução da simulação em Qtenv e Tkenv

* Step - Execução somulação paso a passo;
* Run (or Normal Run) - Possui animação da mensagem
* Fast Run - Pode ser até 10 vezes mais rápido que o tipo de execução "Normal Run", porém a animação da mensagem é desabilitada.
* Express Run - A simulação é executada aproximadamente na mesma velocidade que com o Cmdenv, além disso todo o rastreamento é desativado e o log do módulo não é gravado.
* Run Until - Você pode executar a simulação até um tempo de simulação especificado, número de evento ou até uma mensagem específica for entregue ou cancelada.

