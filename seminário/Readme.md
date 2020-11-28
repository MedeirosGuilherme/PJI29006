
# Roteiro do seminário de Projeto Integrador II, tratando dos capítulos I, II e III do livro Princípios de Análise e Projeto de Sistema com UML.


> Slide 1: Apenas a frase escrita e a explicação.

"*Coisas simples devem ser simples, e coisas complexas devem ser possíveis*", é com a frase de Alan Kay que o primeiro capítulo do livro "Princípios de Análise e Projeto de SIstema com UML" de Eduardo Bezerra começa, a frase pode soar pretensiosa por sí própria mas ao final da leitura do primeiro capítulo o significado dela fica bem claro para o leitor assim como a intenção de Bezerra à colocá-la aqui. É bem possível decorrer bastante sobre qualquer frase bem posicionada do livro, não é essa a intenção aqui, mas a frase de Kay vem bem à calhar porque ela introduz o primeiro tema do primeiro capítulo: A simplicidade.

> Slide 2: Imagens genéricas de empresa, organizações, gráficos etc.

A organização sempre foi parte importantíssima do processo do desenvolvimento econômico e/ou produção de qualquer coisa. Propriedade, mão de obra, maquinagem, capital, etc não alcançam seu potencial de produção enquanto não forem organizados e planejados para agirem de forma adequada. Um novo bem econômico surge na metade do século XX e se torna mais e mais importante com o passar dos anos, até se tornar o objetivo de mercado das maiores empresas do mundo: A informação.

Uma organização qualquer que possui mais informações sobre seu processo está em vantagem em relação à quem compete com ela e falha em perceber tal. A informação se torna tão importante formas de organizar (e torná-las simples de acessar) começam a ser pensadas, originando os chamados "sistemas de informações", um combinado de pessoas, dados, processos, interfaces, redes e tecnologias que interagem entre si com o objetivo de dar suporte as informações que fluem por uma organização.

> Slide 3: Imagem genérica de sistema de informação e sistema de software

Dentro de um sistema de informação, há um sistema de software que compreende os módulos funcionais de um programa que interagem entre si para executar uma tarefa. Todo o livro se baseia em teoria e técnica para a organização desse segmento de forma a simplificar e principalmente padronizar o jeito que compreendemos o funcionamento de softwares, assim como a forma que usuários interagem com o mesmo.

> Slide 4: Apenas escrito Modelagem de Sistemas de Software

### 1.1 Modelagem de Sistemas de Software

> Slide 5: Imagem genérica de Software, Imagem de palhoça na fila

Sistemas de software tem uma estranha capacidade de se tornarem complexos com o crescimento das linhas de código. O crescimento desordenado não é muito diferente do crescimento de uma cidade sem organização urbana, gera confusão, dificuldade de achar onde você está e o que faz pra chegar onde quer, deixa tudo bastante desagradável para se olhar e torna impossível que alguém com boas intenções comece a organização depois de tudo já estar mal feito. A analogia é boa e ela é minha, nem pertence ao autor do texto.

> Slide 6: Imagem de casinha de cachorro, casa de dois andares e edifício, com flecha ligando entre eles.

O texto apresenta uma analogia quase tão boa quanto a minha e dispõe a tarefa de construir uma casinha de cachorro: óbviamente nem todo mundo possui o talento ou a prática de construção, mas praticamente qualquer um pode construir uma casinha de cachorro com algumas ferramentas e um pouco de madeira junto de algum tutorial do YouTube. Fácil, simples, mão na massa e tá tudo pronto.

Já a construção de uma casa para você morar ao invés do seu cachorro pode ser um pouco mais complicado, é necessário imaginar quanto material você vai precisar, talvez dividir a obra em estágios e cumprir estágio por estágio separadamente, ver se tudo cabe no seu orçamento.

Por ultimo, a construção de um edifício de dezenas de andares é ainda mais complicada e precisa de diversas pessoas trabalhando coordenadamente para completar, é necessário fazer plantas complexas, organização de pessoa entre tantas outras coisas que eu não faço ideia nem por onde começar, mas definitivamente é mais complexo do que a construção da casinha de cachorro.

> Slide 7: Imagem de um modelo de software

A construção de softwares é obviamente bastante diferente da construção civil, mas não deixa de ter similaridades. O grau de complexidade de um sistema cria a necessidade de maior organização e planejamento inicial.

A utilização de um modelo de projeto, uma planta ou esquema de funcionamento de algo, um ensaio sobre o produto final é bastante importante e tem consequências em várias fases do projeto.

> Slide 8: Escrito 1.Gerenciamento da complexidade 
> Imagem de algo bem complexo divido em partes simples

É bastante complexo para o ser humano ter noção de algo que envolva dezenas de funções ou etapas. Simplesmente não cabe nas nossas cabeças. Em um modelo é possível enxergar tudo isso e ter noção de onde você está/o que tem que fazer, além disso é possível organizar, dividir o modelo em regiões simples e conectadas, simplicidade o suficiente para um homo sapiens sapiens compreender que através de várias conexões criam um sistema complexo e funcional. A divisão agraria a simplicidade necessária para o desenvolvimento e produção.

> Slide 9: Escrito 2. Comunicação entre as pessoas envolvidas, 
> Imagem de gente conversando

Durante a construção do modelo há a comunicação entre os desenvolvedores e expectativas e noções erradas sobre o sistema podem ser levantadas e sanadas antes mesmo da primeira linha de código ser escrita, poupando tempo e recurso. Além disso, um modelo bem feito pode ser suficientemente carregado de informação para que duas pessoas envolvidas no projeto consigam fazer sua parte e conectar com a de um parceiro de desenvolvimento sem ter que realizar ajustes para a conexão. Duas pessoas em partes do mundo separadas podem trabalhar no mesmo produto e simplesmente colocar dois arquivos de código um do lado do outro que façam funcionar uma terceira aplicação que os utilizam, sem nunca terem conversado, apenas olhando para um modelo.


> Slide 10: Escrito 3. Redução dos custos no desenvolvimento,
> Imagem de prédio caindo

Pessoas sem planejamento cometem mais erros por não conhecerem corretamente o que devem fazer. É bem simples. Com o planejamento vem a clareza e menos recursos são utilizados. Modelos de sistemas são mais baratos de construir do que sistemas em sí, é melhor encontrar o problema durante a construção do modelo do que durante a construção do sistema em sí.

Imaginando novamente o exemplo do prédio, seria muito mais legal um engenheiro civil entender que um ferro de 2mm na fundação não segura um prédio de 20 andares durante a produção da planta do que durante a construção do prédio em sí.

> Slide 11: Um diagrama bem complicado

Em design de softwares o modelo mais utilizado é o diagramas. Os capítulos seguintes apresentarão uma porção de diagrams e formas diferentes de criá-los. A modelagem de sistemas de software consiste na utilização de notações gráficas e textuais com o objetivo de construir modelos que representam as partes essenciais de um sistema, considerando-se várias perspectivas diferentes e complementares.

> Slide 12: Uma imagem de POO, escrito POO

A orientação à objetos é um paradigma de programação, Thomas Kuhn (físico americano) designou as realizações científicas que geram modelos que orientam o desenvolvimento posterior das pesquisas exclusivamente na busca da solução para os problemas por elas sucitados de paradigma. Paradigma é um padrão consiso, uma maneira fechada e decisiva de olhar para algo. O autor do livro define um paradigma como *uma forma de abordar um problema*, conceito completamente equivocado ou no mínimo simplista. Um paradigma não está preocupado apenas com a forma de resolver um problema, mas sim uma forma de organizar um pensamento padronizado. Se um paradigma fosse uma forma de abordar um problema então qualquer forma de abordar um problema seria um paradigma, o que não é o caso.

> Slide 13: Imagem de Alan Kay, imagem de um tecido celular

De qualquer forma, muito além do equivoco do autor sobre o conceito de paradigma, Alan Kay (um dos inventores da programação orientada a objetos) imaginou um sistema de software que funcionasse como um ser vivo, onde cada célula fizesse apenas uma parte do processo que se conecta com outras e realizam o todo, se comportando como uma unidade autônoma e trocando mensagem entre sí. Kay estabeleceu alguns princípios da orientação a objetos.

> Slide 14: Escrito: Princípios da orientação a objetos e escrito cada um deles:

1. Qualquer coisa é um objeto
2. Objetos realizam tarefas por meio de requisição de serviços a outros objetos
3. Cada objeto pertence a uma determinada classe, uma classe agrupo objetos iguais
4. A classe é um repositório para comportamento associado ao objeto
5. Classes são organizadas em hierarquias.

> Slide 15: Modelagem de sistemas em POO: Modelo de classes UML

A orientação a objetos visualiza um sistema de software como uma coleção de agentes conectados. Cada objeto realiza tarefas especificas interagindo com outros objetos. Antes da orientação a objetos, o paradigma mais utilizado em programação era a programação estruturada, que visualiza um programa e o estrutura de forma completamente diferente.

Se a maneira de programar é diferente, a maneira de modelar também é. Entretanto, a programação orientada a objetos tem muita proximidade da forma com que seres humanos realizam tarefas cotidianas. Por isso, muitas vezes é mais fácil (por afinidade) modelar dessa forma, deixando o código e a estrutura do software mais fácil de compreender.

> Slide 16: Imagem de Classes e objetos

O mundo é formado de coisas. A frase é bem genérica, mas é verdade. Cada coisa que existe no mundo que o ser humano conhece possui um nome, e normalmente agrupamos as coisas por proximidade. Identificamos formas de agrupar os seres vivos (taxonomia) pela forma e função que cada ser vivo realiza. Nesse paradigma de progamação, coisas são denomidadas objetos, seria um pouco menos eloquente chamar de POC programação orientado a coisas, mas o significado é o mesmo. Coisas semelhantes realizam funções semelhantes, e são agrupadas como as mesmas coisas, assim funciona em programação.

> Slide 17: imagem Modelos de carro

A abstração superior que categoriza um conjunto de objetos semelhante damos o nome de classe. Todas as instâncias diferentes de um objeto que pertencem a mesma classe realizam funções próximas e se comportam de maneira semelhante, mas não são necessariamente iguais.

Existem dezenas de modelos de carros diferentes, carros que podem ou não ter características diferentes, todos são carros, mas evidentemente um VolksWagen Fusca é bastante diferente de uma Ferrari Spider. Ambos são objetos diferentes da classe carro, e quando você olha pra ambos você percebe que são carros, mesmo considerando as diferenças.

A classe á abstração das características relevantes de um grupo de coisas.

> Slide 18: Escrito Operação, mensagem e estado, imagem de um músculo humano em dois estados diferentes

Operação é o nome dado a uma ação que um objeto sabe realizar quando requisitado. Também são chamadas de métodos, e objetos muito frequentemente sabem realizar diversos métodos diferentes e não os executam aleatoriamente, mas sim apenas quando pedidos. Esses pedidos são estímulos que são passados que o objeto reconhece como um pedido específico para uma operação específica, a esses estímulos damos o nome de mensagem. Operações frequentemente modificam atributos de um método, mudando o estado onde eles se encontram. Estados podem ser modificados por métodos do próprio objeto ou de objetos distintos.
A orientação à objetos é tão próxima da realidade que os exemplos são simples de pensar, um cérebro (objeto 1) manda uma mensagem (estímulo elétrico) à um músculo pedindo para que aconteça uma mudança de estado, que ele passe de relaxado para contraído. Nessa situação, todos os procedimentos de uma chamada de método entre dois objetos estão bem descritos e explicados.

> Slide 19: Abstração, imagem do auto retrato de Pablo Picasso

A abstração é a simplificação de um conceito de forma a preservar apenas as características mais importantes e que mais definem uma coisa, ignorando os aspectos menos importantes ou relevantes no nosso contexto. É um procedimento importantíssimo para a humanidade, já que compreender algo interamente é impossível, sem a abstração não poderíamos descrever nada sem passar a eternidade tentando a descrever.

A abstração, é um processo que pode ser dividido em princípios mais simples, o encapsulamento, o polimorfismo, a generalização e a composição.

> Slide 20: Encapsulamento, imagem motorista acelerando, imagem de um encapsulamento genérico

Objetos não precisam conhecer completamente todos os funcionamentos uns dos outros para que os métodos possam funcionar. O conceito de encapsulamento é simplesmente isolar em capsulas todos os objetos diferentes e fazer com que cada um converse com o outro apenas através de suas interfaces. 
Um objeto 1 manda uma mensagem com requisição e interage com a interface de um objeto 2 que realiza uma operação e retorna alguma informação de resultado para o objeto 1, através de sua interface de retorno.
Em termos de exemplo, é como um motorista freiando um veículo. É completamente desnecessário saber se o veículo possui freio à disco ou à tambor, ou se o carro possui ABS, ou como é o funcionamento específico de cada freio, ou como é a física da frenagem para poder freiar. O motorista apenas aperta o pedal do freio e recebe a informação que o carro desacelerou através de seus sensores de inércia. O motorista e o carro são objetos encapsulados que utilizam um ao outro sem compreender necessariamente o que cada um faz, essa simplificação faz com que o conceito de encapsulamento seja parte do processo de abstração.

> Slide 21: Polimorfismo, imagem genérica de polimorfismo, imagem de figuras geométricas

Polimorfismo é a capacidade de objetos diferentes compreenderem uma mesma mensagem de maneira aquém de seus contextos. Um objeto 1 manda uma mensma mensagem para objetos 2 e 3, e cada um dos dois realiza operações razoavelmente (mas não necessariamente) distintas, mesmo com o conteúdo da mensagem sendo o mesmo.
O exemplo mais clássico de polimorfismo é uma mensagem chamada "desenhe-se" dada por um objeto à figuras geométricas diferentes, cada uma fará um processo diferente! Um círculo começará do centro e desenhará pelo raio, um triângulo ligará 3 pontos, um retângulo ligará quatro, e assim por diante. Todos trarão resultados distintos, mesmo recebendo a mesma ordem.
É uma maneira de simplificar a recepção e compreensão de mensagem.

> Slide 22: Generalização, imagem de um carro e uma moto

Também chamada de Herança, é mais uma forma de abstração que simplifica objetos distintos por pertencerem a mesma categoria de objetos, mas não serem iguais. Eles possuem características semelhantes que herdam da categoria superior, mas possuem obrigatoriamente características distintas que fazem com que necessitem ser separados em objetos diferentes. Além disso, objetos podem herdar características de objetos que herdaram características de outros objetos e assim sucessivamente, isso faz com que existam hierarquias de objetos que herdam características entre sí.
Um exemplo clássico é o de dois objetos, carro e moto, ambos herdando características de veículos. Ambos possuem rodas, mas os carros possuem quatro e as motos possuem apenas duas. Ambos possuem bancos, apesar de terem características completamente diferentes. Ambos podem acelerar ou freiar. Entretanto, apenas o carro possui um teto, porta malas, entre outras especificações. Ambos são veículos, definitivamente, mas são diferentes o suficiente para serem considerados objetos diferentes


> Slide 23: Composição, imagem de um livro aberto, imagem de um átomo

É a abstração por dividir objetos em partes mais simples que são outros objetos. Por exemplo, livros são objetos compostos de outros objetos como páginas, capas, etc. Páginas são compostas de parágrafos, que são compostos por linhas e assim por diante. Claro que o contexto vai ditar até onde é necessário aprofundar e dividir em subcategorias ou dividiríamos todos os objetos em quarks, o que definitivamente não é necessário. Apesar de que se formos tratar do objeto molécula, podemos sim dizer que esta é dividida em átomos, que são divididos em hádrons e léptons, cada um desses é divididos em quarks e nesse contexto sim essa subdivisão é necessária.

> Slide 24: Linguagem de Modelagem Unificada (UML), imagem de um diagrama UML

A notação definida para a UML (principalmente por Grady Booch, James Rumbaugh e Ivar Jacobson) é uma união de diversas notações preexistentes, com modificações feitas para torná-la mais clara. É uma linguagem visual para modelar sistemas orientados a objetos, e caracteriza classes, objetos, métodos, atores, etc e como eles interagem entre sí. É o projeto de software 101 que independe até mesmo da linguagem de programação (desde que esta se adeque à orientação a objetos). Esses diagramas podem observar um sistema à partir de perspectivas diversas, os autores da UML sugerem cinco visões interdependentes desse sistema:

> Slide 25: Diagrama de caso de uso, imagem de um 

Visão de casos de uso: Descreve o sistema de um ponto de vista externo como um conjunto de interações entre o sistema e os agentes externos ao sistema. Esta visão é criada em um estágio inicial e direciona o desenvolvimento das outras visões do sistema. 

> Slide 26: Diagrama de projeto, imagem de um

Enfatiza as características do sistema que dão suporte, tanto estrutural quanto comportamental, às funcionalidades externamente visíveis do sistema

> Slide 27: Diagrama de implementação

Abrange o gerenciamento de versões do sistema, construídas pelo agrupamento de módulos e subsistemas.

> Slide 28: Diagrama de implantação, imagem de um

Corresponde à distribuição física do sistema em seus subsistemas e à conexão entre essas partes

> Slide 29: Diagrama de proceso

Enfatiza as características de concorrência, sincronização e desempenho do sistema.

> Slide 30: Diagrama UML

Cada diagrama UML oferece uma dimensão do que está sendo projetado e dependendo do contexto, um diagrama pode não oferecer informação relevante ou necessária. Por exemplo, se o sistema estiver instalado em um ambiente computacional de processador único, não há necessidade da visão de implantação.

Os diagramas definidos pela UML podem ser vistos na figura, e são uma porção deles. Cada um oferecendo uma visão diferente, entretanto, como pode ser visto, existem tantos tipos de diagramas diferentes que fica difícil escolher seu favorito.
De fato, essa foi a crítica que a versão 2.0 da UML recebeu relativa ao aumento de diagramas propostos, são tantos e tão específicos que o diagrama muitas vezes oferece tão pouca informação que ele se torna irrelevante, atualmente sendo 16 diagramas no total.

> Slide 31: Desenvolvimento de Software - Imagem genérica de um desenvolvedor de software

Qualquer pessoa que tenha tido qualquer experiência com desenvolvimento de software sabe que não é tarefa simples de ser realizada. O processo de desenvolvimento de software é uma tentativa de facilitar ou pelo menos padronizar essa tarefa de forma a deixá-la mais simples e sistemática. 

> Slide 32: Atividades típicas de um processo de desenvolvimento: Imagem genérica processo de desenvolvimento de software

O processo é definido porém aberto, existem obviamente várias maneiras de se abordar uma problemática e várias tarefas necessárias à serem feitas antes, durante e depois da codificação. Entretanto, algumas tarefas são sempre (ou quase sempre) certeiros e necessários, alguns deles serão tratados nos próximos slides..

> Slide 33: Levantamento de requisisto, imagem genérica

Está atrelada à compreensão do problema. Tem objetivo de encontrar e compreender melhor a problemática, assim como garantir a unificação entre a visão dos usuários interessados e dos desenvolvedores.

> Slide 34: Tipos de requisito
**Definem-se alguns tipos de requisitos diferentes como:**

1. **Requisitos funcionais: Definem a funcionalidade do sistema.**

2. **Requisitos não funcionais: Declaram as características de qualidade que o sistema deve possuir e que estão relacionadas as suas funcionalidades.**

3. **Requisitos normativos: Declaram as restrições impsotas sobre o desenvolvimento do sistema como plataforma tecnológica, aspectos legais, regras de negócio, etc.**

O documento de requisitos é um acordo entre cliente e desenvolvedor, ele garante o que o software deve prover e um software bem desenvolvido é, basicamente, um software que atende aos requisitos definidos nessa sessão. Entretanto, é praticamente impossível pensar em todos os detalhes à priori ao desenvolvimento da aplicação, por isso, é normal haver mudanças acordadas entre usuário e desenvolvedor.

> Slide 35: Análise de Requisitos, imagem genérica

Também é considerada parte da engenharia de requisitos, o processo de análise é basicamente o ato de desmembrar um sistema em seus componentes e estudar como eles funciona e analisar se as necessidades do cliente serão atendidas com o sistema proposto atual.

A fase de análise pode ser subdividida em duas sub fases, a análise de negócio, onde são identificados e modelados os objetos da problemática que farão parte do sistema a ser desenvolvido, e a análise da aplicação, em que o analista verifica os objetos de análise que não fasem parte da problemática, ou seja, que passam despercebidos até pelos usuários, normalmente estão atrelados a algum componente interno à aplicação.

> Slide 36: Projeto, imagem genérica

A fase de projeto é dividida em duas fases bem específicas: O projeto da arquitetura e o projeto detalhado.

A primeiro define-se em distribuir as classes e objetos relacionados do sistema em subsistemas que compreendem todas as funções do projeto, assim como distribuir esses sitemas para cada recurso de hardware disponível, ou seja, identificar os sistemas que devem ser distribuídos e verificar onde eles devem rodar.

A segunda é o modelo de classes do projeto em sí. O projeto do software em sí e realizar diagramas de como o sfotware é disposto sem se preocupar muito com o hardware.


> Slide 37: Implementação, imagem genérica

É onde o sistema é codificado, onde acontece a tradução do planejamento para código.

> Slide 38: Testes, imagem genérica

É o ato de testar, o nome diz por sí. É o ato de botar o que foi produzido para rodar e tentar identificar erros. Esses testes devem ser feitos considerando toda e qualquer parte do sistema, desde a definição e disposição das classes, verificar interfaces, entradas e retornos de dados, verificar se os dados retornados estão corretos e fazem sentido, verificar a coordenação e a integralização do hardware com o software desenvolvido,e tc.

> Slide 39: Implantação, imagem genérica

Onde o sistema é empacotado, distribuído e instalado no ambiente dos usuários. Essa fase também é encarregada de qualquer funcionalidade que venha antes do uso, como treinamento dos usuários, escrita dos manuais, carregamento de dados, etc.

> Slide 40: A equipe, imagem genérica

É impossível para um profissional só conhecer com excelência necessária tudo especificamente envolvido no desenvolvimento de um produto. Uma equipe deve ser montada onde cada um possui suas virtudes e deveres, onde cada indivíduo tem autonomia para dar uma escapada e ajudar em uma outra fase do projeto, mas deve se concentrar em seus próprios domínios.

> Slide 41: Gerente de projeto

É quem coordenada as atividades, cria orçamento, estratégias, prazos, gerencia as equipes de desenvolvimento, acompanha as atividades, verifica recursos alocados, escalona a equipe, contrata profissionais, etc.

> Slide 42: Analista

É quem possui conhecimento do domínio do negócio, da área em que o produto será aplicado. Devem ter boa comunicação para conversar com os especialistas do domínio, com objetivo de entender as necessidades dos clientes.

> Slide 43: Projetista

É um profissional da área de programação que deve avaliar se as soluções cabem dentro do problema resultante da análise e gerar as especificades de uma solução computacional detalhada. Existem projetistas de cada área de um software, interface, banco de dados, etc.

> Slide 44: Arquitetos de Software

Ele compõe o software em mini camadas, toma as decisões neste sentido da estruturação do produto.

> Slide 45: Programadores

É quem escreve o código. Simples. É quem implementa o que foi planejado. O texto decorre prolixamente sobre essas informações tentando diferenciar os programadores de analistas, quando a diferença é bastante óbvia e é possível identificar pela definição de cada uma das atividades empenhadas por esses profissionais.
Uma empresa pode ter programadores em mais de um linguagem, o que é óbvio, já que linguagem de programação são coisas complexas e dificilmente uma pessoa será especialista em várias delas.

> Slide 46: Especialistas do domínio 

Também conhecido como especialista de negócio, ele é quem é entrevistado pelo analista para retirar os requisitos do sistema.

> Slide 47: Ciclo de vida

O ciclo de vida é a capacidade de um código ser duradouro e continuar resolvendo problemas conforme o tempo passa, assim como a sua capacidade de ser facilmente modificado de forma a manter sua usabilidade e abrangência.

> Slide 48: Modelo de ciclo de vida iterativo e Incremental

Contrário ao sistema de cascatas que era utilizado antes, este modelo cria ciclos de desenvolvimento como podem ser vistos na figura, onde requisitos são levantados, são realizadas as análises, o projeto é criado, implementado, testado e implantado, e somente aí um analista levantará novos requisitos para que eles possam ser adicionados a aplicação.

Isso faz com que o código tenha que ser estruturado de uma forma que permita essa adição, um software completamente fechado torna impossível a adição de qualquer coisa e tem sua longevidade comprometida.

Para isso, o bom uso de diagramas é necessário. Em um modelo de ciclo de vida iterativo e incremental, os artefatos de softwares construídos com uso da UML evoluem à medida que as iterações do processo são realizadas.

Cada novo conjunto de requisitos necessita a aprimoração do diagrama do projeto já implantado anterior.

> Slide 49: Prototipagem

É a elaboração do projeto com apenas algumas das especificações reconhecidas e com a abertura para implementação de novas, é através do protótipo que as validações com clientes e especialistas de negócio acontecerão.

> Slide 50: Mecanismos de uso geral

Este capítulo se ateve a explicar o que são mecanismos de uso geral, apesar de não explicar exatamente o que eles são no geral até agora, ele apenas detalha quais são e o que são alguns deles:

Apenas depois de ler o texto dos exemplos ficou compreensível que são tipos de figuras/gráficos que podem ser usados em diagramas UML. Recursos que são de uso para facilitar a compreensão dos diagramas. 

> Slide 51: Estereótipos -> Usar exemplo do próprio texto

São figuras e/ou textos que dão a ideia daquilo que está sendo usado. Estão entre eles, por exemplo, o muro com fogo, que é super reconhecido como um firewall. Ao ser colocado em um diagrama, explicações maiores não são necessárias considerando que quem trabalhará com o diagrama sabe o que é um firewall.

O uso desses recursos obviamente dependem do contexto e quem utilizará o diagrama deve conhecer cada um desses estereótipos.

> Slide 52: Notas explicativas -> Usar exemplo do próprio texto

É uma nota que esclarece algo. Alguma figura ou parte do diagrama que ficou sem clareza e necessita de uma explicação maior pode ser enriquecido com uma nota explicativa. Normalmente tem a forma que pode ser vista na imagem, de um papel com uma dobra em cima, mas qualquer outro tipo pode ser utilizado se acordado entre as partes do desenvolvimento.

> Slide 53: Etiquetas valorada

São utilizadas para garantir propriedades não pré definidias para determinados elementos de diagramas. Dar um valor a uma variável para exemplificar uma transação, por exemplo.

> Slide 54: Restrições:

Como UML é basicamente um conjunto de padrões que facilitam a universalização da produção de diagramas para a produção e desenvolvimento de software, cada signo gráfico possui um significado bem definido que é implícito para quem estudou o tema.

As restrições permitem estender ou alterar a semântica natural de um elemento gráfico. Ela deve ser obviamente acordada entre as partes e, levando em consideração que o livro é bem peculiar na definição de cada pequeno padrão de cada entidade do projeto de sistemas com UML, é curioso que ele defina que tudo possa ser modificado através de apenas essa aplicação. Mas o meu entendimento do que foi colocado é esse, que ele restringe o funcionamento de um simbolismo de diagrama, modificando-o.

> Slide 55: Pacotes

O símbolo utilizado é o de uma pasta com aba, e serve para agrupar elementos que possuam alguma relação. Pacotes podem inclusive conter outros pacotes e por aí vai.

> Slide 56: OCL

É a linguagem de restrição de objetos. É utilizada para definir expressões de navegação entre objetos, expressões lógicas, condições, etc.

Fim





