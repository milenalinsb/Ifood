<h1>Ifood</h1>

<h2> Esse readme foi implementado no projeto em que fiz parte durante o estágio no Garagem, do IFPB. </h2>
<p> Desenvolvemos uma aplicação, o IFood, o que atendia a necessidade de otimizar as requisições de refeições feitas pelos professores para os alunos e turmas que necessitassem desse auxilio quando estivessem que se manter no campus para realização de atividades extras. Essa requisição feita pelo professor é encaminhada à CAEST e, quando confirmada, é repassada para a cantina.</p>
<p>As informações dos alunos e dos professores foram herdados da API mantida pelo campus no SUAP.</p>
<p>Abaixo estão descritos alguns filtros utilizados na aplicação e estão divididos entre tipos de pesquisar para filtrar pelos alunos, que é a aplicação EDU e filtrar pelas requisições que é a aplicação IFOOD</p>

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


Para fazer um POST no endpoint de Request os parâmetros necessários são: o tipo da refeição, os alunos que vão usufruir dela, a data e a justificativa para tal solicitação. E os parâmetros opcionais são: o avaliador e a justicativa do mesmo.



