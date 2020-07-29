### Curso básico de git para iniciantes

Curso oferecido no canal da [RBtech](https://www.youtube.com/channel/UCVEa_x1n5FwWrxH00MrDPzQ) no YouTube.
Playlist dos [vídeos](https://www.youtube.com/playlist?list=PLInBAd9OZCzzHBJjLFZzRl6DgUmOeG3H0)

Download do [Git](https://git-scm.com/docs).
Download do [Aptana Studio](https://github.com/aptana/studio3/releases), utilizado para criação das pastas e de arquivos para serem utilizados em todo o curso.

### Abaixo os comandos vistos nos 8 vídeos deste curso:

- **Aula 1: O que é Git e Controle de Versão**
  - **git config --global user.name “nome de seu usuário”:** Este comando definirá o seu usuário que realizará o controle de seus arquivos no Git.
  - **git config --global user.email “email de seu usuário”:** Este comando definirá o seu email que estará vinculado em seu usuário no Git.

- **Aula 2: Comandos básicos init, status, add e commit**
  - **cd <nome_pasta>:** Entra na pasta que deseja utilizar para manipulação de seus arquivos. E a partir de então a localização da pasta é alterada para a pasta informada. Pode utilizar **cd <caminho_completo>**, assim você entrará diretamente na pasta ao invés de ficar digitando uma a uma.
  - **cd .. :** Volta para a pasta anterior, ou seja, ele sai da pasta atual onde está informado na localização.
  - **clear:** Limpa toda a tela do Terminal para melhor visualização dos dados. Este comando não apaga nenhum outro comando já realizado, apenas limpa a tela.
  - **git init:** Cria um repositório na pasta atual de acordo com o informado no Terminal. Todos as alterações, modificações serão salvas neste repositório, e só a partir dele você consegue iniciar de fato seu projeto.
  - **git status:** Retorna o status atual de seu repositório. Ele mostrará o que foi modificado e o que tem de novo para adicionar no seu repositório.
  - **git add “nome do arquivo.extensão” | git add *.txt | git add . :** Adiciona arquivos na sua staged área para controle de versões do seu projeto. O comando **git add “nome do arquivo.extensão”** vai adicionar apenas o arquivo que foi informado na staged área do git. O comando **git add *.txt** adiciona todos os arquivos de extensão .txt *(pode utilizar qualquer extensão que estiver utilizando conforme seu projeto)*. O comando **git add .**, mais utilizado, adiciona todos os arquivos na staged área para iniciar o controle de versões do mesmo.
  - **git commit -m “mensagem do commit”| git commit –a –m “mensagem do commit”:** Comando de commitar, de salvar as mudanças no seu projeto. O **-m** do comando de commit refere-se a mensagem que você deve informar na hora de comitar. Utilizando o comando **git commit –a –m “mensagem do commit”** não há a necessidade de dar um **git add**, visto que o **-a** já adiciona e o git commit já comita toda a alteração realizada.

- **Aula 3: Visualizando alterações em arquivos ou commits anteriores**

- **Aula 4: Modificando último commit e removendo arquivos da staged área**

- **Aula 5: Trabalhando com tags e branches**

- **Aula 6: Utilizando o Git em conjunto com seu repositório remoto de rede**

- **Aula 7: Utilizando o Git em conjunto com o GitHub**

- **Aula 8: Como colaborar com Projetos Open Source através do GitHub**
