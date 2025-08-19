# **Aplicativo de Gestão de Treinos para Academias:** EvoFit

Trabalho de Experiencia do Usuário (UX) apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Experiência do Usuário e Front-End (CCP310) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel).

## Componentes do Grupo

- Lucas Belo Gaspardo
- Luís Guilherme Camillo Teixeira

## Resumo

O projeto consiste no desenvolvimento de uma aplicação voltada para frequentadores de academia e personal trainers, com o objetivo de registrar treinos, acompanhar a evolução física e gerar relatórios de desempenho. A solução busca melhorar a experiência do usuário por meio de uma interface simples, intuitiva e responsiva, permitindo a visualização de estatísticas e evolução de forma clara e motivadora.

## Introdução

Frequentadores de academia e personal trainers enfrentam, no dia a dia, a dificuldade de organizar treinos e acompanhar resultados de maneira prática e acessível. Muitas vezes, o controle de evolução física é feito em anotações manuais ou planilhas que não oferecem uma visão clara do progresso, o que pode gerar desmotivação e falta de engajamento. A aplicação proposta surge como uma solução para esse problema, ao oferecer uma plataforma digital capaz de centralizar os registros de treinos e disponibilizar relatórios de evolução, otimizando tanto a organização pessoal quanto o trabalho dos profissionais. O objetivo do sistema é disponibilizar um ambiente digital simples e intuitivo para o registro de treinos e acompanhamento da evolução física. A experiência que se pretende proporcionar aos usuários é motivadora, acessível e eficiente, incentivando a continuidade dos treinos e oferecendo feedbacks visuais claros sobre o desempenho.

## Publico Alvo

O público-alvo do projeto é formado por frequentadores de academia que desejam monitorar seus treinos e evolução física de forma organizada, além de personal trainers que necessitam gerenciar os treinos de diferentes alunos e analisar seus resultados de maneira prática. Ambos compartilham a necessidade de uma solução digital que torne esse processo mais eficiente, clara e motivadora.

### Personas

- Descreva as personas que irão interagir com a aplicação ou produto. Deixe claro suas principais caracteristicas e contextos sociais, econômicos e culturais.
- Quais informações sobre o usuário o serviço ou poduto deve guardar?

  - Persona primaira ...
  - Persona secundária ...
  - Outras personas ...

### Mapa de empatia

![Mapa de empatia](empatia.png)

- Determine o mapa de empatia[^1] de pelo menos uma persona primária e uma sercundária.
  - O que o usuário vê: aqui estamos falando do ambiente visual em que o usuário se encontra. Ou seja, o que ele efetivamente enxerga, as pessoas e objetos que estão ao seu redor. Isso ajuda a entender o contexto em que o usuário está inserido e as influências visuais que está recebendo.
  - O que o usuário ouve: neste quadrante, buscamos entender o que o usuário está ouvindo, os sons que o cercam e como eles influenciam suas ações.
  - O que o usuário diz e faz: aqui consideramos ações e comportamentos que o usuário apresenta durante sua interação com serviço ou poduto.
  - O que o usuário pensa e sente: neste quadrante, buscamos entender os pensamentos, sentimentos, emoções e percepções que o usuário tem em relação ao serviço ou poduto. Quais expectativas o usuário cria sobre o serviço ou poduto?
  Que tipo de serviço ou poduto mais agrada essa persona?
  - Dores: quando falamos sobre dores do usuário, estamos fazendo referência a quaisquer obstáculos, necessidades ou frustrações que o usuário possa experimentar ao tentar realizar uma tarefa ou alcançar um objetivo. Isso inclui, por exemplo, problemas de usabilidade, dificuldades de acesso ou outros desafios que podem afetar a experiência do usuário.
  - Ganhos: nesse caso estamos falando de quaisquer benefícios ou recompensas que o usuário possa experimentar ao utilizar o serviço ou poduto. Isso pode incluir economia de tempo ou facilidade de uso, por exemplo. Que desejos do usuário o serviço ou poduto satisfaz?

## Contexto de uso

A aplicação será utilizada principalmente em ambientes de academias, estúdios de treino personalizado ou até mesmo em casa, já que muitos usuários também realizam atividades físicas fora de estabelecimentos formais. Esses ambientes são caracterizados pela prática de exercícios físicos, pela presença de equipamentos de musculação, aeróbicos e funcionais, além da interação entre alunos e personal trainers. O contexto social envolve tanto pessoas que buscam qualidade de vida, saúde e estética corporal, quanto profissionais que trabalham com o acompanhamento físico e dependem de ferramentas que facilitem sua rotina. Do ponto de vista econômico e cultural, trata-se de um público diversificado, que vai desde alunos que utilizam academias populares até aqueles que frequentam estabelecimentos de maior padrão, mas que compartilham a mesma necessidade de organização e acompanhamento de resultados.

Antes de iniciar a interação, o sistema deve guardar informações básicas sobre o usuário, como cadastro pessoal, treinos anteriores, exercícios realizados e histórico de evolução, de forma que a experiência seja contínua e personalizada. No momento em que o usuário acessa o serviço, normalmente o ambiente já estará em funcionamento, com treinos em andamento, pessoas utilizando os equipamentos e personal trainers acompanhando alunos, de modo que a aplicação deve estar preparada para ser acessada rapidamente, oferecendo praticidade e agilidade no registro ou na consulta de dados. Assim, o sistema se insere de forma natural na rotina, sem atrapalhar a dinâmica do ambiente, mas servindo como um apoio fundamental para a organização e o acompanhamento da evolução física.

## Jornada do usuário

A jornada do usuário começa no momento em que ele tem o primeiro contato com a aplicação, seja por indicação de um amigo, sugestão de um personal trainer ou busca por uma forma prática de organizar seus treinos. O primeiro passo é realizar o cadastro no sistema, inserindo informações básicas como nome, idade, peso e objetivos pessoais. Esse momento marca a entrada do usuário na plataforma e representa o início de sua experiência.

A partir daí, o usuário é conduzido à configuração inicial, onde pode registrar ou selecionar um treino sugerido. Se for um aluno de academia, ele cadastra os exercícios recomendados por seu instrutor; se for um personal trainer, ele pode criar e gerenciar diferentes treinos para seus alunos. Essa fase de desenvolvimento da tarefa é marcada pela interação frequente com a aplicação, pois a cada sessão de treino o usuário registra os exercícios realizados, ajusta cargas, séries e repetições, além de acompanhar as anotações sobre sua evolução.

Com o tempo, a experiência vai se tornando mais rica. O usuário passa a visualizar no dashboard gráficos e estatísticas que mostram sua progressão, seja em aumento de força, resistência ou mudanças físicas. Esse acompanhamento gera motivação e reforça a utilidade do sistema. Nos momentos em que deseja analisar seu desempenho de forma mais detalhada, o usuário pode acessar relatórios de progresso que consolidam suas informações em períodos semanais ou mensais.

A jornada termina, de forma cíclica e contínua, quando o usuário conclui um ciclo de treino ou atinge uma meta definida, o que pode levá-lo a reiniciar o processo com novos objetivos. Dessa maneira, a aplicação acompanha não apenas uma tarefa pontual, mas toda a evolução do usuário ao longo de sua trajetória, tornando-se uma ferramenta indispensável para o acompanhamento físico tanto de alunos quanto de personal trainers.

## Análise de concorrência

- Pesquise serviços ou podutos existentes atualmente que possam realizar o objetivo deste projeto.
- Selecione pelo menos 3 serviços ou podutos diferentes.
- Em relação aos concorrentes, respondam as seguintes perguntas?
  - Existe plataforma similar que atende o mesmo mercado e funcionalidades? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?

## Coleta de dados

## Modelo de tarefas

## Design

- Pense nas características de Affordances do seu serviço ou poduto. 
    - Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto deste serviço ou poduto. Qual a importância e pontos a serem considerados se você quiser vender esse serviço ou poduto?

### Prototipação em baixo nível (papel)
#### Avaliação heurística

### Prtotipação em médio nível (Figma)
#### Avaliação heurística

### Prtotipação em alto nível (React)
#### Avaliação heurística

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>

<!-- TODOs:
- Add exemplos
 -->

