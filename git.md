<h1>Git essencial</h1>
<hr>
<b>git status:</b> Exibe as alterações do projeto, mapeamento das alterações tais como arquivos monitorados e ou modificados. Também podemos dizer que é a diferença do que está enviado ao servidor ou salvo no projeto;
<br>
<b>git add</b> Adiciona um arquivo  específico, como também vários arquivos ao mesmo tempo.<br>
<b>git add .</b> Adiciona todos os arquivos do diretório atual.<br>
<h3>SALVANDO ALTERAÇÕES</h3>
<b>git commit arquivo -m "Mensagem informativa do commit"</b>  Salva as alterações do projeto, arquivos específicos ou diversos arquivos ao mesmo tempo.<br>
<b>git commit -a -m "Mensagem informativa do commit"</b>
<h3>ENVIANDO O CÓDIGO AO GITHUB</h3>
<b>git push</b> 
<h2>RECEBENDO AS MUNDANÇAS</H2>
<h3>git pull</h3>É comum também ter que sinconizar o local com as mudanças do remoto. Busca atualização, se encontradas serão unidas ao código atual.
<h2>CLONANDO REPOSITÓRIOS</H2>
<b>git clone url</b>
<h2>REMOVENDO ARQUIVOS</H2>
<b>git rm file</b>
<h2>VERIFICANDO ALTERAÇÕES POR MEIO DE LOG</H2>
<b> git log </b> exibe as movimentações da mais antiga para a mais atual
<h2>RENOMEANDO ARQUIVO</H2>
<b>git mv </b> Sintaxe identica ao mv do linux.
<h2>DESFAZENDO OPERAÇÕES</h2>
<b>git checkout file</b> retorna ao estado original, ou seja o estado que o arquivo se encontra no repositório.(rollback)
<h2>IGNORANDO ARQUIVOS E OU DIRETÓRIOS</h2>
<b>.gitigore</b>
<h2>DESFAZENDO TODAS AS ALTERAÇÕES</h2>
<b>git reset --hard branch</b> Resetas todas as mudanças feitas, commitadas e pendentes serão excluídas.
<hr>
<h1>Branches</h1>
<p>São ramificações de um projeto, ou seja a forma que o git separa a 'versao' do projeto. Todos a partit do branch main/master. Geralmente a cada nova feature do projeto fica em uma branch separada, após as sua alterações os branchs são unidos para chegar o código fonte final.</p>
<h2>Criando e visualizando os branchs</h2>
<p><b>git branch</b> Lista os branchs do projeto</p>
<p><b>git branch nome-do-branch</b> Cria um novo branch</p>
<h2>DELETANDO BRANCHES</h2>
<p>Não é comum deletar branchs. Geralmente se deleta quando é criado de maneira equivocada.</p>
<p><b>git branch --delete ou -d nome da branch</b>Apaga a branch.</p>
<h2>MUDANDO A BRANCH</h2>
<p><b>git checkout nomedabranch</b> muda de branch</p>
<h2>UNINDO  BRANCH (MERGE)</h2>
<p><b>git merge + nomedabranch </b> irá unir a branch que vc está atual mas setada no comando</p>
<p>Por exemplo, vc esta na branch main. o comando irá unir (executar o merge) da branch main + a branch do comando</p>
<h2>STASH</h2>
<p><b>git stash </b> Salva as modificações atuais, para prosseguir com uma outra abordagem de solução e não perder o código. Após o comando o branch será resetado para a sua versão de acordo com o repositório.</p>
<h2>STASH LIST</h2>
<p><b>git stash list</b>retorna os ids com as stash das stashs existentes</p>
<p><b>git stash apply id</b>recebe os dados salva da stash</p>
<p><b>git stash show -p id</b>Mostra as alterações da stash</p>
<h2>REMOVENDO A STASH</h2>
<p><b>git stash clear</b> Limpa totalmente as stash de um branch.</p>
<p><b>git stash drop id</b> Apaga somente a stash relativa a idss</p>
<h2>TAGS</h2>
<p><b>git tag -a nomedatag -m "msgdatag"</b> Cria tags nos branches, como se fosse um checkpoint de um branch. Utilizado para demarcar estágio do desenvolvimento de determinado recurso;</p>
<p><b>git show tagname</b> Verifica a tag</p>
<p><b>git checkout tagname</b> Alterna entre as tags</p>
<h2>ENVIANDO e COMPARTILHANDO AS TAGS</h2>
<p><b>git push origin tagname</b> Envia a tag pelo nome ao repositório</p>
<p><b>git push origin --tags</b> Envia todas as tags ao repositório</p>

<h1>CONFIGURANDO SSH NO WINDOWS</h1>
<p>Através do gitbash</p>
<p>Gerando par de chave a ser setado no GITHUB</p>
<p>ssh-keygen -t ed25519 -C n0cturn0.debian@gmail.com</p>
<p>Lenbrando que a chave que será setado no github é a chave pública</p>
<p>Inicializando o agent-ssh</p>
<p>No gitbash:</p>
<p>eval $(ssh-agent -s)</p>
<p>Devendo retornar uma mensagem com o número do id em execução</p>
<p>Passando a chave privada </p>
<p>ssh-add chave privada</p>

<h1>CONFIGURANDO GIT</h1>
<p>git config --global user.email "n0cturn0.debian@gmailcom"</p>
<p>git config --global name "Luiz Augusto"</p>

<h1>LISTANDO AS CONFIGURAÇÃO EXISTENTE DO GIT</h1>
<p>git config --list </p>

<h1>REFAZENDO AS CONFIGURAÇÃO EXISTENTE DO GIT</h1>

<p>git config --global --unset user.email</p>
<p>git config --global --unset name </p>


<h1>Problemas  push-set-upstream</h1>
<p>git push origin NOME DA BRANCH</p>









