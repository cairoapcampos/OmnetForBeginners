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

8- Edição do arquivo NED no modo gráfico

* Olhar vídeo e exemplo "Titoc 1 - Criação Grafica NED"
