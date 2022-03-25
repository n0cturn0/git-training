<h2>Git</h2>
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