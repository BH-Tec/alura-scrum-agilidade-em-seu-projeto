# Anotações das aulas

## O que é o Scrum?

É um framework ágil e sua característica principal é trabalhar com time-boxes: caixas de tempo cujo tamanho, uma vez definido, não muda durante a Sprint atual.

## O que é uma Sprint?

É o time-box básico do Scrum. Ela é o tempo que o time tem para agregar valor para o usuário do projeto.

## O que perdemos ao escolher um mês de duração da Sprint, em vez de uma semana?

Quanto maior o Sprint, menos chances de feedback temos e, portanto, maior o risco de errarmos o que precisa ser feito.

## Qual o propósito da Review Meeting? Quem está presente nessa reunião?

Apresentar os resultados da sprint, elencando todos os itens efetivamente prontos e disponíveis ao usuário, de acordo com os critérios de aceitação. Nela, estão reunidos o time de desenvolvimento, o PO e os representantes do cliente.

## Ao avaliar o que foi feito, o cliente pode encontrar erros de entendimento, bugs ou mesmo ter ideias novas sobre o projeto. O que deve ser feito com essas novas informações do projeto?

O PO transformará as idéias em histórias e então serão inseridas no Product Backlog dentro da prioridade identificada.

## Imagine que o cliente encontrou um bug e o desenvolvedor, que está presente, sabe como corrigir. Ele deve corrigir na hora? O que você acha? Discuta os prós e os contras disso.

Não. pois tira o foco da reunião. Esse bug deve ser anotado e colocado no Backlog do Produto ou no Backlog da Sprint.

## Quais as vantagens você vê em trazer o usuário final na Review, em vez de apenas o cliente?

Trazendo o usuário para a reunião, podemos ver como ele utilizar o sistema e assim aprender, um pouco sobre o fluxo do processo. Além de uma validação de uma funcionalidade.

## O que é a Definição de Pronto de um projeto? Dê como exemplo uma boa definição de pronto para seu projeto atual.

A definição de pronto é uma sequência de passos pelo qual cada história precisa passar. Saíndo do "Não iniciado" para "Pronto".
Ex: Testes de integração -> Desenvolvimento -> Code Review -> Aprovando -> Pronto

## Para que serve a reunião de retrospectiva?

A retrospectiva é a oportunidade de promovermos melhorias no processo, na equipe e no andamento do projeto a ser desenvolvido.

## Esperamos obter ações de melhoria ao final de cada retrospectiva. Dê dois exemplos de ação para resolver ou reduzir o seguinte problema

### Existe uma área na empresa, externa ao time, responsável pelos deploys e o time precisa de mais rapidez nos deploys de homologação para conseguir passar a fase de "Aprovação em Homologação" de seu Critério de Pronto

Possíveis ações: Automatizar processo de deploy do ambiente de homologação para o ambiente de produção.

## No capítulo, falamos sobre um formato bem básico e simples de retrospectivas. Há ainda diversas outras atividades diferentes que podem ser aplicadas nessa reunião. Pesquise sobre o assunto! Escreva sobre uma atividade/formato que tenha te interessado e o link para a página que você encontrou.

A técnica WWW é a mais famosa e a mais utilizada para promover uma reunião de restropectiva.

O que significa o WWW: What Went Well (o que deu certo) e What Went Wrong (o que deu errado) na sprint.

Ela é divida em 2 momentos, onde o primeiro momento da reunião, cada membro da equipe anota em post-its os pontos positivos e pontos negativos da sprint. Já no segundo momento, cada membro da equipe apresenta os pontos positivos que levantou e apos são apresentados os pontos negativos para a equipe discutir.

Link: https://blog.myscrumhalf.com/tecnica-para-fazer-uma-reuniao-de-retrospectiva-no-scrum/

## Pesquise na internet e ache o texto do Norm Kerth conhecido como a diretiva primária de retrospectivas -- Retrospective Prime Directive. O que ela diz?

- "Independentemente do que descubramos, nós entendemos e realmente acreditamos que todos fizeram o melhor trabalho que podiam, dado o conhecimento na época, suas habilidades, os recursos disponíveis e a situação em jogo."

## Quais são as 3 perguntas que o time responde em um Daily Scrum?

O que você fez ontem?
O que você fará hoje?
Tem algum bloqueio?

## Para que fazemos o Daily Scrum e qual o timebox para essa reunião?

A daily scrum é uma reunião de no máximo 15 minutos para entender o que foi feito, o que irá fazer, e se tem algum bloqueio.

## Para que serve o planning meeting e qual a duração dessa reunião, assumindo um Sprint de uma semana?

O planning meeting server para entendermos os itens a serem feitos, planejarmos o que cabe no tempo disponível e definirmos a meta para o time nessa Sprint.
A reunião consome 5% do tempo da Sprint. Se a Sprint tem duração de 1 semana, essa reunião terá o tempo máximo de 2 horas.

## Que artefato o Product Owner já deve ter preparado antes mesmo de entrar na Planning Meeting? Como é essa preparação?

O PO verifica as histórias mais prioritárias do projeto, confirmando o entendimento delas com o cliente, melhorando sua clareza, quebrando grandes funcionalidades em partes menores que já agreguem valor para o cliente, etc.

## Com base no que estudamos nestas últimas videoaulas, você conseguiria descrever em linhas gerais como é usualmente, o processo da reunião de planejamento (sprint planning)?

O P.O. começa explicando o product backlog, priorizando de acordo com a necessidade do cliente, e é feita a escolha das tarefas a serem desenvolvidas na sprint.

## Como o Scrum não se limita a projetos de software, vamos exercitar esse pensamento fora da caixa: nosso projeto aqui é a sua casa dos sonhos! Escreva uma história que descreva sua Sala de Estar, sem esquecer de seguir o formato da história que vimos em aula: comece pelo porquê, siga se identificando e termine, aí sim, com o que você quer na sua sala. Para isso, complete o template abaixo:

[Resposta](nota1.txt)

## Considere a seguinte história: Mesinha retrátil Para... ter onde colocar petiscos sem medo de que alguém vá pisar neles Eu, como... morador que gosta de receber visitas Quero... uma mesinha central que fica escondida na maior parte do tempo, mas emerge do chão quando necessário. Lembrando que tarefas são subitens técnicos de uma história, quebre essa história em tarefas que poderiam ser desenvolvidas preferencialmente paralelamente por membros do time.

mesa central em si;
mecanismo para esconder a mesa;

## Qual a diferença entre problemas e impedimentos? Dê um exemplo de cada!

Problema é uma dificuldade que desafia a capacidade de solucionar de alguém. Já impedimento é uma circunstância ou conjunto de circunstânciaque impossibilitam alguém de exercer regularmente suas funções

Problema: estamos há 3 sprints sem bater a meta por bugs que aparecem no meio do caminho.
Impedimento: o setor de infra não responde nossos pedidos (tentamos e-mail e conversa cara-a-cara) e precisamos de acesso ao serviço apto pra prosseguir.

## De que forma você, como Scrum Master, poderia tratar o seguinte impedimento? Impedimento: o setor de infra não responde nossos pedidos (tentamos e-mail e conversa cara-a-cara) e precisamos de acesso ao serviço xpto para prosseguir

Eu como Scrum Master, como não tivemos respostas através de e-mail e conversa cara-a-cara, escalonaria para o responsavél pelo setor de TI. Ou estabelecer um acordo (algo semelhante a um Acordo de Nível de Serviço - SLA - Service Level Agreement) de como serão as comunicações entre projeto e infra para que, na próxima ocasião que for aberta uma solicitação, fique claro para ambos os times como fazer o pedido, com qual antecedência, e quais seriam os prazos de resposta esperados para cada solicitação feita.

## Qual a diferença entre um cliente e um product owner?

O cliente é o solicitante, a pessoa ou figura que faz a sugestão do projeto. O product owner é o responsável pelo projeto dentro da empresa.

## A principal função do Product Owner é manter o Product Backlog devidamente atualizado. De que formas ele faz isso?

Gerenciando o backlog
Fazendo a comunição entre equipe, cliente e outras áreas
Gerencia o tempo, orçamento e meta do projeto
Supervisona o desenvolvimento do projeto


## Note que a história abaixo é bastante inchada e é possível entregar valor para o usuário com bem menos do que o proposto nessa enorme história, ou, como preferimos chamar, desse épico. Sala de Estar Para... receber meus amigos para degustar queijos e vinhos com conforto Eu, como... morador Quero... uma sala de estar de 20m², com carpete de madeira, grandes almofadas soltas pelo chão, uma mesinha central retrátil, uma mini adega para 6 vinhos e sistema de som ambiente. Um bom Product Owner quebraria o épico, antes do planning, em histórias menores e mais fáceis de estimar! Escreva os títulos das histórias menores que conseguimos tirar do épico acima.

Sala básica com almofadas
Mesinha central retrátil
Mini adega
Sistema de som ambiente

## O grupo de desenvolvimento é apenas uma parte do time no Scrum: além deles, há ainda P.O. e Scrum Master. Quais especialistas compõem um grupo de desenvolvimento usual em uma empresa?

Desenvolvedores, arquitetos, DBAs, analistas de testes (geral)

## Por que os papéis de Scrum Master e Product Owner não podem ser ocupados pela mesma pessoa?

Eles possuem papéis destistos e complementares que, se ocupados pela mesma pessoa, acarretariam em uma sobrecarga e um abandono de certas funções

## Como você entende hoje o conceito de Melhoria Contínua, discutido neste capítulo e no curso como um todo?

É uma prática adotada por diversas empresas que visa atingir, ininterruptamente, resultados cada vez melhores
