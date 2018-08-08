<h1># Stocks WT</h1>

Dashboard de investimentos, que permite acompanhar de maneira gráfica a variação dos mercados selecionados em determinado
período de tempo. Possibilita a manutenção e acompanhamento de diferentes mercados.


<h3>Requisitos funcionais</h3>
<strong>RF1.</strong> O sistema deve permitir que os usuários efetuar o cadastro, login, manutenção do perfil e recuperar a senha;
<br><strong>RF2.</strong> O sistema deve permitir a visualização do dashboard, com informações gráficas e textuais de mercados previamente cadastrados;
<br><strong>RF3.</strong> O sistema deve permitir a manutenção de mercados acompanhados pelo usuário no dashboard, mediante a sigla correspondente;
<br><strong>RF4.</strong> O sistema deve apresentar no dashboard, um gráfico de linhas permitindo a aplicação de filtros por período.
     Os período podem ser, 1 dia, 1 semana, 1 mês, 3 meses, 6 meses, 1 ano, 5 anos, data início e data fim;
<br><strong>RF5.</strong> O sistema deve apresentar no dashboard, caixas com os mercado monitorados contendo a sigla, nome, variação em % e em valores;
<br><strong>RF6.</strong> O sistema deve apresentar no gráfico do dashboard, 1 linha para cada mercado acompanhado pelo usuário, mostrando a variação no período;
<br><strong>RF7.</strong> O sistema deve apresentar na tela as informações mais atualizadas disponíveis para os mercados acompanhados pelo usuário;
<br><strong>RF8.</strong> Os filtros aplicados no dashboard, devem refletir tanto no gráfico como nas caixas dos mercados acompanhados;

<h3>Requisitos não funcionais</h3>
<strong>RNF1.</strong> Nas caixas do dashboard, o sistema deve apresentar as variações dos mercados utilizando respectivamente as cores
      verde, preta e vermelha para apresentar as variações positivas, neutras e negativas;
<br><strong>RNF2.</strong> A atualização periódica das informações no dashboard deve utilizar preferencialmente webSocket para evitar o consumo de recursos
      do servidor
<br><strong>RNF3.</strong> A interface do sistema deve ser responsiva, possibilitando o acesso a diferentes dispositivos;
<br><strong>RNF4.</strong> O sistema deve ser compatível com os principais navegadores, seguindo os pradrões de compatibilidade da W3C;
<br><strong>RNF5.</strong> O sistema deve ser construído utilizando a arquitetura em camadas, padrão MVC, permitindo separar dados, interface e lógicas do negócio;
<br><strong>RNF6.</strong> O sistema deve disponibilizar webServices, para permitir a integração com sistemas terceiros;

<h3>Regras de negócio</h3>
<strong>RN1.</strong> A login no cadastros dos usuários deve ser o email;
<br><strong>RN2.</strong> Não podem existir 2 usuários cadastrados com o mesmo email;
<br><strong>RN3.</strong> A utilização de webSocket para a atualização dos dados no dashboard, evita requisições ao servidor e transfere o processamento
     para a máquina do usuário, estabelecendo uma comunicação em 2 vias entre cliente e servidor;


<h3>Fluxo principal</h3>
<br>1. Usuário efetua o cadastro;
<br>2. Usuário efetua o login;
<br>3. Usuário visualiza os mercados previamente cadastrados na sua dashboard;
<br>4. Usuário opta por selecione determinado período para visualização a variação dos mercado no período desejado;
<br>5. Sistema apresenta no dashboard, de maneiura gráfica e textual, a variação dos mercados no período selecionado;

<h4>Screenshot</h4>

<a href="https://postimg.cc/image/r586fl6kx/" target="_blank">
<img src="https://postimg.cc/image/r586fl6kx/" alt="kanban"/>
</a>

<a href='https://s8.postimg.cc/5it5yk80l/etoro_markets.png' target='_blank'>
     <img src='https://s8.postimg.cc/5it5yk80l/etoro_markets.png' border='0' alt='etoro_markets'/>
</a>
<br/><br/>
