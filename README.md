# guia-git
GUIA SEM IMAGENS

Guia para criar e subir arquivos em seu repositório GIT

Após criar sua conta e fazer login execute os passos a seguir :
1)	criar um repositório no SITE do git hub :
clicar no símbolo “+” 
  
2)	escolher a opção “new repository” :
 
3)	preencher o nome, escolher se quer público ou privado e clicar em “Create repository” :
 
4) clica com o botão direito na pasta onde quer iniciar o projeto;
escolher a opção :"git bash here"
 

Vai aparecer esta tela :
 

OBS: após cada comando digitado apertar a tecla”enter”
5) Configurar usuário, na janela que acabou de abrir :
 	git config --global user.email "seuemail@provedor.com"
 	git config --global user.name "seu nome de usuário do github"
 

6) iniciar o git com comando “git init” :

 

7) saber os status dos arquivos com o comando “git status”, os arquivos em vermelhos quer dizer que foram alterados e não foram adicionados para commit :

  

8) Adicionar os arquivos com o comando “git add .” ou “git add –all(são dois sinais de menos ‘-‘ anted do add)” 

9) para verificar se os arquivos estão prontos para subir digite novamente o comando “git status” :

 
 Se estão todos com a cor verde quer dizer que estão prontos para serem “commitados”
10) Fazer o commit, digite o comando “git commit -m ‘seu comentário’ “colocar um comentário com informações úteis do que está sendo implantado :

 

11) Adicione uma origem remota (neste caso será o repositório que acabamos de criar), clicar no símbolo    da página do repositório que criamos :
 

12) executar o comando “git remote add origin” e apertar o botão “insert” para colar a URL copiada :
 

13) e por último executar o comando “git push -u origin master”, se tudo ocorrer certo teremos está tela de confirmação : 
14) e nosso repositório terá esta cara, com os nomes dos arquivos, nome do commit e data de upload :
 

