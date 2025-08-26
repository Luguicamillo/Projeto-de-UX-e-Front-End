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

## Persona primária – Frequentador de academia e Personal Trainer

Nome fictício (aluno): Mariana, 27 anos, Analista de Marketing

Contexto: Rotina corrida entre trabalho, estudos de pós-graduação e vida social.

Necessidades: Registrar treinos de forma prática, visualizar evolução física de maneira clara e motivadora, manter consistência nos treinos mesmo com pouco tempo disponível.

Objetivos: Melhorar condicionamento físico, ter relatórios simples e acompanhamento visual que incentive a continuidade.

Nome fictício (personal trainer): Ricardo, 34 anos, Personal Trainer autônomo

Contexto: Atende em diferentes academias e em treinos particulares. Gerencia em média 20 alunos com diferentes objetivos e necessidades.

Necessidades: Centralizar registros de treinos, acompanhar resultados individuais, apresentar relatórios claros aos alunos.

Objetivos: Otimizar tempo, oferecer atendimento profissional e personalizado, aumentar engajamento e satisfação dos alunos.

## Persona secundária – Gestor da academia

Nome fictício: Carla, 41 anos, Gerente de Academia

Contexto: Responsável pela gestão de uma unidade com cerca de 300 alunos e 10 profissionais.

Necessidades: Monitorar estatísticas gerais, analisar métricas de engajamento, gerenciar cadastros, integrar informações com sistemas administrativos.

Objetivos: Melhorar a gestão da academia, aumentar retenção de alunos, oferecer suporte eficiente aos profissionais.
  
## Persona negativa – Usuário ocasional e desengajado

Nome fictício: Bruno, 22 anos, Estudante universitário

Contexto: Frequenta a academia de forma muito esporádica, sem acompanhamento de um profissional, regularidade ou compromisso com treinos. Usa a academia apenas de forma social ou eventual.

Necessidades: Não busca acompanhamento de evolução, nem registros detalhados de treinos, pois sua prioridade não é desempenho físico ou disciplina.

Comportamento: Pouco interessado em métricas de desempenho ou relatórios. Prefere improvisar os exercícios no momento, sem seguir planos ou rotinas estruturadas.

Motivo de exclusão: Esse tipo de usuário não aproveitaria as funcionalidades do EvoFit e dificilmente encontraria valor agregado no sistema, já que não possui interesse em organização, disciplina ou acompanhamento de evolução física.


### Mapa de empatia

![Mapa de empatia](empatia.png)

## 🎯 Persona Primária – João, 28 anos, universitário de Educação Física
     Interessado em saúde, bem-estar e performance.
- 👉 Vê:
Seu ambiente inclui a faculdade, academia, redes sociais e grupos de treino. Observa constantemente propagandas de suplementos, aplicativos fitness e planos de treino online.

- 👉 Escuta:
Recebe influência de amigos da academia, professores, treinadores e também de influenciadores fitness no Instagram e YouTube.

- 👉 Fala e Faz:
Costuma compartilhar treinos nas redes sociais, comenta sobre evolução física com colegas, participa de desafios fitness. Demonstra disciplina, mas por vezes reclama da falta de tempo e dinheiro para investir em suplementos e treinos personalizados.
  
- 👉 Pensa e Sente:
Está motivado a melhorar seu condicionamento físico e autoestima. Preocupa-se em manter uma rotina equilibrada entre estudos, treinos e vida social. Sonha em participar de competições esportivas e conquistar um corpo saudável.

- 👉 Dores:
Falta de recursos financeiros para investir em planos avançados, dificuldade em manter consistência nos treinos por causa da rotina acadêmica. Ansiedade por resultados rápidos e frustração com platôs de desempenho.

- 👉 Ganhos:
Deseja conquistar evolução física visível, reconhecimento social, mais disposição no dia a dia e confiança pessoal. Também valoriza soluções acessíveis, práticas e que tragam economia de tempo (como aplicativos que organizam treinos).

## 🎯 Persona Secundária – Marcos, 45 anos, Gestor de Academia

-👉 Pensa e Sente
Preocupa-se em manter a academia competitiva, organizada e lucrativa. Quer fidelizar clientes e melhorar a experiência do aluno. Sente pressão com custos, concorrência e cobrança por resultados financeiros.

-👉 Escuta
Ouve reclamações e elogios de clientes, recebe feedbacks de instrutores e sugestões de sócios/acionistas. É influenciado por tendências de mercado fitness e por consultores de negócios.

-👉 Vê
Ambiente da academia, relatórios de gestão, concorrentes, propagandas de aplicativos de controle e fidelização de clientes. Vê instrutores e alunos utilizando diferentes ferramentas e espera soluções que unifiquem dados.

-👉 Fala e Faz
Conversa com instrutores e recepcionistas sobre desempenho da academia, analisa relatórios financeiros, participa de reuniões e avalia o nível de satisfação dos clientes. Não acessa sistemas todos os dias, mas verifica informações estratégicas de tempos em tempos.

-👉 Dores
Dificuldade em integrar informações de diferentes áreas (financeiro, treino, matrícula). Preocupação com a rotatividade de alunos e com o custo de sistemas complexos. Falta de tempo para acompanhar tudo em detalhe.

-👉 Ganhos
Deseja ter relatórios claros e acessíveis rapidamente, para tomar decisões mais ágeis. Quer aumentar retenção de alunos, reduzir custos operacionais e ter uma visão geral da academia sem precisar gastar horas analisando dados.

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










