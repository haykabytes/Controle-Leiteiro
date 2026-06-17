# Controle-Leiteiro

Visão geral:
Sistema digital de controle leiteiro para pequenos agricultores com acessibilidade por voz e interface simples para usuários com baixa alfabetização. 

Justiﬁcativa:
Este  projeto  nasceu  das  vivências  do  dia  a  dia  na  zona  rural  onde  cresci.  Meu  pai frequentemente precisava da minha ajuda para fazer os cálculos da produção de leite, ainda  assim,  havia diﬁculdade para saber ao certo quanto ia receber no ﬁnal do mês. Convivendo  com  os  agricultores  da  região,  percebi que essa diﬁculdade era comum a muitos. Apesar da globalização, ainda existe uma profunda exclusão social diante da tecnologia. Vivemos em um mundo cada vez mais conectado, mas as ferramentas digitais ainda não chegaram às pequenas parcelas marginalizadas da sociedade (especialmente às pessoas do campo, muitas delas sem familiaridade com dispositivos e aplicativos). Foi dessa realidade que nasceu a necessidade de fazer a diferença.
O Controle de Leite é a minha resposta a esse impasse: uma ferramenta pensada para quem mais precisa, que se adapta ao usuário. 

Problemática: 
Observando  a  realidade  de  muitos  pequenos  produtores  rurais,  é  possível  perceber problemas  recorrentes  no  controle  da  produção  leiteira.  Muitos  ainda  registram  as informações em papel ou dependem da memória, o que diﬁculta acompanhar a produção, estimar os ganhos do mês e controlar vacinas e tratamentos dos animais. Além disso, a falta de ferramentas simples e acessíveis torna esse gerenciamento ainda mais difícil. O Controle  de  Leite  foi  desenvolvido  para  atender  essa  necessidade  de  forma  prática e intuitiva. 

Funcionalidades e Acessibilidade: 
O sistema oferece as seguintes funcionalidades:
●  Registro de leite: salva a quantidade de leite produzida pelo produtor;
●  Cálculo  do  ganho  mensal:  estima  o  valor  a  receber  com  base  na  produção registrada e no preço do litro de leite; 
●  Cadastro de animais: armazena informações de cada animal do rebanho. 
●  Controle de vacinas e medicamentos: registra aplicações e alerta sobre próximas doses;
●  Reconhecimento de voz: permite inserir informações por comandos de voz. 
●  Leitura em voz alta: informa os resultados por áudio, facilitando o uso por pessoas com diﬁculdade de leitura.
●  Calendário de registros: exibe os dias em que a produção foi cadastrada; 
●  Alertas automáticos: avisa sobre pendências importantes relacionadas ao manejo do rebanho.

A interface foi projetada pensando em quem nunca usou um:
 ●  Botões grandes com ícones visuais (sem depender de leitura); 
 ●  Microfone em todos os campos principais (fala em vez de digitar); 
 ●  Leitura em voz alta dos resultados (o app fala o valor a receber); 
 ●  Calendário colorido  verde (dia registrado, sem precisar ler);
 ●  Alertas falados (avisa em voz alta sobre vacinas vencidas); 
 ●  Zero instalação (abre direto no celular pelo navegador). 
 
Tecnologias utilizadas:
HTML5: estrutura e semântica acessível; 
CSS3: design mobile-ﬁrst, responsivo, sem frameworks externos;
JavaScript Vanilla: lógica, cálculos e persistência de dados; 
Web Speech API:  reconhecimento de voz e síntese de fala nativas do navegador; 
localStorage: dados salvos no próprio celular, sem precisar de internet;
SQL / MySQL: modelo de banco de dados relacional (estrutura do backend).     

Modelo do Banco de Dados:
 
Animal (cadastro do rebanho com genealogia);
Ordenha_Diaria (produção diária de leite); 
Historico_Preco_Leite (preço do litro por período); 
Despesa (controle de gastos da fazenda); 
Tratamento (medicamentos por animal);
Vacinacao (vacinas com controle de próxima dose). 

Como usar
 Opção 1 — Direto no celular (sem instalar nada):
 1 - Acesse o link do projeto 
 2 - Toque no ícone do microfone  para falar em vez de digitar
 3 - Os dados ﬁcam salvos no celular automaticamente 
 
 Opção 2 — Rodar localmente:
 OBS: Não precisa de servidor, basta abrir o arquivo. 
 
 Impacto Social
 Este projeto foi desenvolvido com foco em inclusão digital no campo. A ideia central é que a  tecnologia  deve  se  adaptar  ao usuário — não o contrário. Um agricultor que nunca digitou  em  um  celular  consegue  usar  o  Controle  de  Leite  pelo  microfone,  ouvir  os resultados e saber exatamente quanto vai receber no ﬁnal do mês. A exclusão digital ainda é uma realidade para milhões de brasileiros. Este projeto é uma tentativa concreta de mudar isso(uma ferramenta de cada vez). 
 
Autora:
Desenvolvido com propósito social e experiência vivida para os agricultores brasileiros que produzem com dedicação e merecem ferramentas à altura do seu trabalho.
