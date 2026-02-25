
# Arquitetura AI Native

A força inevitável da teoria do caos foi instaurada de maneira silenciosa na engenharia de software, as big techs estão redefinindo a forma de se construir software novamente, na última década as startups ditavam seus próprios ritmos e regras.

Agora, essas irão mergulhar em uma situação desconhecida, a cultura de produto ganhará protagonismo, o desenvolvedor que apenas escreve código rápido e de forma elegante deixará de ser valorizado como antes.

A situação tem nome e sobrenome, agentes de código autônomos. Dessa forma, separei 4 pontos que podem ser aplicados para manter a competição equilibrada.

1. **Arquitetura como impulsionador de inovação**

	Para se alcançar o avanço da inteligência artificial é preciso discutir como arquitetura está relacionada à forma como sua organização estará posicionada a médio prazo, pois as tecnologias e situações aqui citadas já são realidade em algumas empresas. 
	
	O ideal é imaginar e segmentar a sua estrutura tecnológica em duas categorias de sistemas:
	
	a. **Sistemas estruturantes:**
	Todos aqueles que governam, viabilizam e sustentam os sistemas aplicacionais, como plataformas de gerenciamento de infraestrutura, sistemas de governança, monitoramento, deploys, features de segurança e gateways.
	
	b. **Sistemas aplicacionais:**
	Aplicações que entregam features a clientes internos e externos mas não sustentam nenhuma estrutura ou definição tecnológica.

2. **Platform Engineering: Sistemas produtizáveis e replicáveis**

	A arquitetura empregada em cada sistema a ser criado pode ser um desafio, tanto pelo excesso de burocracia quanto a falta, pois no excesso, os desenvolvedores tendem a resistir aos processos para se acelerar o desenvolvimento, temendo depender de muitas camadas de arquitetura, pecando pela falta, criando sistemas sem padronização, sem planejamento de infraestrutura, segurança ou desenvolvimento.
	
	Sendo assim, uma das possíveis estratégias aplicáveis para construir sistemas dentro da arquitetura organizacional, mas sem muita burocracia é justamente produtizar a mesma, por exemplo, criando templates replicáveis para microsserviços de API REST em múltiplas linguagens, já com as dependências homologadas que o seu desenvolvedor pode precisar, ambientes configurados, repositórios estruturados, pipelines e controle de governança.

3. **IA como usuário**

	Uma realidade que já começa a surgir em muitos repositórios e organizações é a taxa de linhas de código geradas por agentes de desenvolvimento, dessa forma, indiretamente, a inteligência artificial surge com um papel tanto de usuário desses sistemas como um catalisador da inovação, sendo assim, devemos planejar nossa arquitetura como produto já pensando que ela também será consumida por esses agentes.
	
	Pensando no próprio exemplo que apresentei de templates de microsserviços, podemos criar arquivos de instruções para os agentes, atualmente, já existem alguns padrões começando a ser seguidos no mercado, como o `agents.md`, `.github/copilot-instructions.md` ou `.instructions.md`
	
	Irei aprofundar sobre cada um deles em um artigo posterior, porém, todos eles são usados para criar instruções a serem consumidas pelas IAs ao interagir com aquele repositório, logo se enviesa-se a forma como o agente irá reagir ao prompt do desenvolvedor de maneira específica para esse microsserviço, basicamente um "RAG injetado".

4. **Engenharia de software como pilar de inovação**

	A cultura de startup na última década devido a necessidade de "errar rápido e corrigir rápido" afrontou e revolucionou de maneira brusca as mais variadas teorias e modelos de engenharia de software, como Cascata, Espiral e Desenvolvimento Ágil, e não ironicamente, isso de certa forma já era previsto pela Lei de Conway que propõe que os “Sistemas refletem a estrutura de comunicação das organizações que os constroem” conforme proposto por Conway em _How Do Committees Invent?_ (1968)
	
	Porém, isso trouxe benefícios e malefícios dos mais variados como a alta agilidade de desenvolvimento, mas também um certo preconceito com arquitetura justamente por entender que ela é uma área concorrente e um empecilho para as áreas de produto que regem a inovação em muitas empresas de tecnologia.
	
	Entretanto, com a atual capacidade da inteligência artificial, podemos revisitar a engenharia de software, justamente vendo as organizações como "Sistemas Complexos Adaptativos" pois agora mais do que nunca antes visto, os projetos serão como seres vivos que evoluem e se adaptam, mas que podem seguir regras dadas por nós e cabe a arquitetura definir essas regras, limites para não cairmos além da "borda do caos".


Os 4 pontos citados não são apenas colocações individualizadas, elas são apenas um composto de algo maior, AI Native, que definiu novos arquétipos profissionais na fase que iniciamos da engenharia de software, muitos já conhecidos: Platform Engineer, Cloud Architect, Data Engineer e entre outros específicos, pois o trabalho da engenharia deixa de ser escrever software e passa a definir sistemas capazes de produzir software.

Como na biologia, na arquitetura AI Native há uma evolução natural da forma de produzir sistemas. Antes, soluções surgiam como células isoladas de código, orientadas por requisitos funcionais e restrições técnicas específicas. Agora, a plataformização passa a se comportar como um organismo multicelular, capaz de reorganizar suas próprias estruturas para transformar ideias em produtos.
