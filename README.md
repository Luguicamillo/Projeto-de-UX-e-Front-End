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

- Vê:
Seu ambiente inclui a faculdade, academia, redes sociais e grupos de treino. Observa constantemente propagandas de suplementos, aplicativos fitness e planos de treino online.

- Escuta:
Recebe influência de amigos da academia, professores, treinadores e também de influenciadores fitness no Instagram e YouTube.

- Fala e Faz:
Costuma compartilhar treinos nas redes sociais, comenta sobre evolução física com colegas, participa de desafios fitness. Demonstra disciplina, mas por vezes reclama da falta de tempo e dinheiro para investir em suplementos e treinos personalizados.
  
- Pensa e Sente:
Está motivado a melhorar seu condicionamento físico e autoestima. Preocupa-se em manter uma rotina equilibrada entre estudos, treinos e vida social. Sonha em participar de competições esportivas e conquistar um corpo saudável.

- Dores:
Falta de recursos financeiros para investir em planos avançados, dificuldade em manter consistência nos treinos por causa da rotina acadêmica. Ansiedade por resultados rápidos e frustração com platôs de desempenho.

- Ganhos:
Deseja conquistar evolução física visível, reconhecimento social, mais disposição no dia a dia e confiança pessoal. Também valoriza soluções acessíveis, práticas e que tragam economia de tempo (como aplicativos que organizam treinos).

## 🎯 Persona Primária – Carlos, 32 anos, Personal Trainer

- Vê:
Ambiente de academia, aplicativos fitness, redes sociais e propagandas de suplementos e equipamentos. Observa diariamente o desempenho e comportamento de seus alunos.

- Escuta:
Ouve feedbacks dos alunos sobre dificuldades e progressos, além de receber conselhos de outros profissionais de educação física. É influenciado por tendências de treino, metodologias modernas e colegas de profissão.

- Fala e Faz:
Orienta os alunos em treinos, recomenda hábitos saudáveis, participa de eventos esportivos e compartilha conteúdos motivacionais em redes sociais. Cobra disciplina, mas também busca manter os alunos motivados.

- Pensa e Sente:
Quer entregar treinos de qualidade e personalizados para seus alunos. Preocupa-se em manter sua reputação profissional e fidelizar clientes. Sente frustração quando não consegue acompanhar a evolução de cada aluno de forma prática. Deseja otimizar tempo e aumentar a satisfação dos alunos.

- Dores:
Falta de ferramentas integradas para monitorar progresso de vários alunos ao mesmo tempo, dificuldade de manter o engajamento de quem desiste fácil, sobrecarga de trabalho ao criar treinos individualizados manualmente.

- Ganhos:
Deseja praticidade para organizar treinos, registrar desempenho e acompanhar evolução. Busca reconhecimento profissional, retenção de alunos e mais tempo livre para captar novos clientes.


## 🎯 Persona Secundária – Marcos, 45 anos, Gestor de Academia

- Pensa e Sente:
Preocupa-se em manter a academia competitiva, organizada e lucrativa. Quer fidelizar clientes e melhorar a experiência do aluno. Sente pressão com custos, concorrência e cobrança por resultados financeiros.

- Escuta:
Ouve reclamações e elogios de clientes, recebe feedbacks de instrutores e sugestões de sócios/acionistas. É influenciado por tendências de mercado fitness e por consultores de negócios.

- Vê:
Ambiente da academia, relatórios de gestão, concorrentes, propagandas de aplicativos de controle e fidelização de clientes. Vê instrutores e alunos utilizando diferentes ferramentas e espera soluções que unifiquem dados.

- Fala e Faz:
Conversa com instrutores e recepcionistas sobre desempenho da academia, analisa relatórios financeiros, participa de reuniões e avalia o nível de satisfação dos clientes. Não acessa sistemas todos os dias, mas verifica informações estratégicas de tempos em tempos.

- Dores:
Dificuldade em integrar informações de diferentes áreas (financeiro, treino, matrícula). Preocupação com a rotatividade de alunos e com o custo de sistemas complexos. Falta de tempo para acompanhar tudo em detalhe.

- Ganhos:
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

FORMULARIO:
- Aplicar formulários online (Google Forms ou Microsoft Forms) direcionados a alunos e personal trainers. As perguntas devem ser curtas e objetivas, a fim de aumentar a taxa de resposta. Essa abordagem permite alcançar um grande número de usuários em pouco tempo, além de facilitar a análise estatística dos resultados, identificando padrões de comportamento e priorizando as funcionalidades mais desejadas antes do desenvolvimento.
Link para o formulário de coleta de dados: https://docs.google.com/forms/d/e/1FAIpQLSey7zVvIZTDgCrE-tinJU1m5FGTARI0DfIm8nPG-cIcTUDxlw/viewform?usp=dialog

ENTREVISTA:
- Realizar entrevistas semi-estruturadas com frequentadores de academia e personal trainers. O objetivo é aprofundar pontos que dificilmente aparecerão em formulários, como motivações, frustrações e expectativas emocionais. Gerando assim, coleta informações qualitativas profundas, permite entender emoções, dores e expectativas que não aparecem em questionários e gera insights para funcionalidades diferenciadas (por exemplo, relatórios para mostrar evolução de alunos para gestores).
    1. Como você organiza seus treinos hoje? (Para personal: como organiza os treinos de seus alunos?)
    2. Já usou algum aplicativo ou sistema para ajudar nisso? O que funcionou bem e o que atrapalhou?
    3. Quais são as maiores dificuldades que você encontra na sua rotina de treino/gestão?
    4. O que mais te motiva a manter a disciplina? Como gostaria de visualizar a evolução (gráficos, relatórios, comparativos, estatísticas)?
    5. Durante o treino (ou no trabalho do personal), o que tornaria mais prático registrar ou consultar informações?
    6. Se pudesse criar a função perfeita para esse aplicativo, qual seria?
    7. O que faria você desistir de usar o EvoFit?
    8. O que faria você recomendar esse aplicativo para colegas/alunos?

Estudos de Campo (Observação):
- Observar o comportamento dos usuários diretamente no ambiente de treino, acompanhando como os alunos registram suas atividades (em papel, celular ou de memória) e como os personal trainers gerenciam múltiplos alunos simultaneamente. O objetivo é identificar problemas práticos, como: dificuldade em utilizar o celular entre séries, falta de tempo para registrar todas as informações durante o treino e necessidade de gráficos rápidos e claros para feedback.
Esse método permite verificar o que o usuário realmente faz — e não apenas o que relata —, revelando barreiras de usabilidade no contexto real de uso. Além disso, fornece dados essenciais para o desenvolvimento de uma interface mais intuitiva e ágil.
    
## Modelo de tarefas

### Método GOMS baseado na experiência do aluno.

### GOAL 0: Registrar uma série de exercício no EvoFit (app mobile)

#### GOAL 1: Inserir repetições

- METHOD 1.A: Usar teclado virtual numérico
(SEL. RULE: campo não está pré-preenchido ou usuário prefere digitar)

- OP. 1.A.1: Tocar campo “Reps”

- OP. 1.A.2: Digitar número de repetições

- OP. 1.A.3: Confirmar entrada

- METHOD 1.B: Usar botões de incremento (+/–)
(SEL. RULE: usuário prefere evitar digitação e valores estão próximos ao anterior)

- OP. 1.B.1: Tocar botão “+” ou “–” até atingir reps desejadas

#### GOAL 2: Inserir carga

- METHOD 2.A: Usar teclado virtual numérico
(SEL. RULE: campo vazio ou valor distante do anterior)

- OP. 2.A.1: Tocar campo “Carga”

- OP. 2.A.2: Digitar número da carga (kg)

- OP. 2.A.3: Confirmar entrada

- METHOD 2.B: Usar botões de incremento (+/–)
(SEL. RULE: usuário prefere ajustar rapidamente a partir da última carga usada)

- OP. 2.B.1: Tocar botão “+” ou “–” até valor desejado

#### GOAL 3: Concluir a série

- METHOD 3.A: Botão “Concluir Série”

- OP. 3.A.1: Tocar botão “Concluir Série”

- OP. 3.A.2: Observar mensagem de feedback (“Série registrada!”)

#### Regras de Seleção (Selection Rules)

- Se o usuário já usou o mesmo exercício antes → preferir METHOD B (incrementos).

- Se é a primeira vez ou mudança grande de valor → preferir METHOD A (digitação).

- Sempre concluir com METHOD 3.A.


####GOAL 1: Acessar a seção de estatísticas

- METHOD 1.A: Usar menu inferior de navegação
(SEL. RULE: usuário sabe onde está o ícone “Estatísticas” na barra inferior)

- OP. 1.A.1: Tocar o ícone “Estatísticas” na barra inferior

- OP. 1.A.2: Aguardar abertura da tela de estatísticas

- METHOD 1.B: Usar card/atalho na Home
(SEL. RULE: usuário está na Home e deseja ir rápido via atalho)

- OP. 1.B.1: Identificar atalho ou resumo “Estatísticas rápidas”

- OP. 1.B.2: Tocar no atalho

- OP. 1.B.3: Aguardar abertura da tela completa de estatísticas

#### GOAL 2: Selecionar tipo de estatística

- METHOD 2.A: Usar tabs superiores
(SEL. RULE: estatísticas estão organizadas em abas, ex.: “Semana | Mês | Evolução”)

- OP. 2.A.1: Tocar na aba desejada

- OP. 2.A.2: Observar mudança de conteúdo

- METHOD 2.B: Usar filtros/dropdown
(SEL. RULE: usuário quer personalizar período ou métrica específica)

- OP. 2.B.1: Tocar no campo de filtro (ex.: “Últimos 30 dias”)

- OP. 2.B.2: Selecionar opção na lista

- OP. 2.B.3: Confirmar filtro aplicado

#### GOAL 3: Interpretar gráfico ou dado

- METHOD 3.A: Visualizar gráfico de barras

- OP. 3.A.1: Examinar valores dos grupos musculares ou treinos por semana

- METHOD 3.B: Visualizar gráfico de linha

- OP. 3.B.1: Examinar progressão ao longo do tempo (ex.: supino, peso corporal)

- METHOD 3.C: Consultar resumo numérico

- OP. 3.C.1: Ler indicadores principais (ex.: treinos concluídos, tempo médio, aderência %)

#### Regras de Seleção (Selection Rules)

Se o usuário está na Home e vê o atalho → usar METHOD 1.B.

Se prefere acessar sempre via menu → usar METHOD 1.A.

Se quer visão geral → usar METHOD 2.A (abas).

Se busca período específico ou detalhe → usar METHOD 2.B (filtros).

O tipo de visualização depende do dado: comparações → gráfico de barras; evolução → gráfico de linha; status imediato → resumo numérico.

### Método GOMS baseado na experiência do professor.

### GOAL 0: Atribuir um treino a um aluno

#### GOAL 1: Acessar lista de alunos

- METHOD 1.A: Menu “Alunos” na barra inferior
(SEL. RULE: personal está na Home ou em outra tela, e prefere navegação pelo menu)

- OP. 1.A.1: Tocar ícone “Alunos”

- OP. 1.A.2: Aguardar abertura da lista

- METHOD 1.B: Atalho na Home (alunos recentes)
(SEL. RULE: aluno está entre os últimos treinados)

- OP. 1.B.1: Identificar card do aluno na Home

- OP. 1.B.2: Tocar no card

#### GOAL 2: Selecionar aluno

- METHOD 2.A: Pesquisa por nome

- OP. 2.A.1: Tocar campo de busca

- OP. 2.A.2: Digitar nome

- OP. 2.A.3: Selecionar aluno da lista

- METHOD 2.B: Scroll na lista

- OP. 2.B.1: Rolar lista até o aluno

- OP. 2.B.2: Tocar no card

#### GOAL 3: Atribuir treino

- METHOD 3.A: Usar botão “Atribuir Treino”

- OP. 3.A.1: Tocar botão “+ Atribuir treino”

- OP. 3.A.2: Escolher treino da biblioteca

- OP. 3.A.3: Confirmar atribuição

####Regras de Seleção

- Se o aluno aparece logo na Home → usar METHOD 1.B.

- Se a lista é longa → usar METHOD 2.A (busca).

- Sempre concluir com METHOD 3.A.

### Método GOMS baseado na experiência do gestor.

### GOAL 0: Consultar relatório de ocupação da academia

#### GOAL 1: Acessar painel de gestão

- METHOD 1.A: Menu “Gestor”
(SEL. RULE: gerente logado com permissão de administrador)

- OP. 1.A.1: Tocar ícone/menu “Gestor”

- OP. 1.A.2: Aguardar painel abrir

#### GOAL 2: Selecionar relatórios

- METHOD 2.A: Atalho “Relatórios” no painel
(SEL. RULE: relatórios aparecem na primeira seção do painel)

- OP. 2.A.1: Tocar card “Relatórios”

- METHOD 2.B: Scroll até seção “Relatórios”
(SEL. RULE: seção não está visível de imediato)

- OP. 2.B.1: Rolar tela

- OP. 2.B.2: Tocar card “Relatórios”

#### GOAL 3: Consultar relatório de ocupação

- METHOD 3.A: Abrir relatório de ocupação semanal

- OP. 3.A.1: Tocar opção “Ocupação”

- OP. 3.A.2: Visualizar heatmap (picos por horário)

- OP. 3.A.3: Interpretar dados

#### Regras de Seleção

- Se relatórios já visíveis → usar METHOD 2.A.

- Se precisar navegar mais → usar METHOD 2.B.

-Sempre finalizar com METHOD 3.A.

## Design

- Pense nas características de Affordances do seu serviço ou poduto. 
    - Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto deste serviço ou poduto. Qual a importância e pontos a serem considerados se você quiser vender esse serviço ou poduto?



### Prototipação em baixo nível (papel)
#### Avaliação heurística

[Esboço paginas.pdf](https://github.com/user-attachments/files/22220287/Esboco.paginas.pdf)

### Prtotipação em médio nível (Figma)
#### Avaliação heurística

### Prtotipação em alto nível (React)
#### Avaliação heurística

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>

<!-- TODOs:
- Add exemplos
 -->























