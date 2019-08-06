<h1>Ifood</h1>

<h3>EDU</h3>
<ul>
<li>Os alunos podem ser filtrados pela busca das informações gerais ou por cada campo específico que são: nome, curso, matricula e status </li>
</ul>
Exemplos: 
 <blockquote> http://127.0.0.1:8000/api/student/?search=20161230011<br>
 http://127.0.0.1:8000/api/student/?name=Maria<br>
 http://127.0.0.1:8000/api/student/?course=Informática
</blockquote>
  
<h3>IFOOD</h3>
<ul>
<li>As solicitações funcionam da mesma forma, porém a pesquisa pelas informações gerais são com as informações dos campos: data, tipo da refeição e status. Já pelas informações específicas são pelos campos: aluno, data, tipo, estudante e professor. </li>
</ul>
Exemplos: 
 <blockquote> http://127.0.0.1:8000/api/request/?search=1<br>
 http://127.0.0.1:8000/api/request/?name=Nicolau<br>
 http://127.0.0.1:8000/api/request/?registration=20161230018<br>
 http://127.0.0.1:8000/api/request/?date=2019-05-19
</blockquote>


Para a solicitação da refeição é necessário preencher os seguintes campos: o tipo da refeição, os alunos que vão usufruir dela, a data e a justificativa para tal solicitação. 
