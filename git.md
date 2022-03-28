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
<p><b>git checkout nomedabranch</b>muda de branch</p>