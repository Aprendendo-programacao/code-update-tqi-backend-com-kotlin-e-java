# Métodos e ferramentas ágil

## Framework Scrum

O Framework Scrum é uma das abordagens mais populares para o gerenciamento ágil de projetos e é amplamente utilizado na indústria de software, embora suas práticas possam ser aplicadas a vários tipos de projetos. O Scrum se baseia em princípios de empirismo, transparência e inspeção, que são fundamentais para seu funcionamento eficaz.

**Princípios:**

1. **Empirismo:** O Scrum se baseia em empirismo, o que significa que a tomada de decisão é fundamentada em observação e experiência. O ciclo PDCA (Plan, Do, Check, Act) é aplicado, onde o trabalho é planejado, executado, verificado e adaptado continuamente.

2. **Lean Thinking:** O Scrum também incorpora princípios do Lean Thinking, que visam eliminar desperdícios, otimizar o fluxo de trabalho e entregar valor ao cliente de maneira mais eficiente.

**Pilares:**

1. **Transparência**: Todas as informações relevantes são compartilhadas e visíveis para a equipe e as partes interessadas.

2. **Inspeção**: As equipes frequentemente inspecionam o progresso e o produto para identificar problemas o mais cedo possível.

3. **Adaptação**: Com base nas inspeções, a equipe ajusta seus planos e abordagem para maximizar o valor entregue.

![](./assets/scrum-visao-geral.png)

**Papéis:**

1. **Product Owner:** Responsável por representar os interesses do cliente ou do produto, definir as funcionalidades a serem desenvolvidas e priorizar o trabalho no Backlog do Produto.

2. **Scrum Master:** Facilitador do processo Scrum, ajuda a equipe a entender e seguir as práticas do Scrum, remove impedimentos e facilita a comunicação entre todos os envolvidos.

3. **Equipe de Desenvolvimento:** Os membros da equipe que realmente entregam o trabalho. São multifuncionais, auto-organizados e têm a responsabilidade de entregar um incremento de produto a cada Sprint.

**Artefatos:**

1. **Backlog do produto:** Uma lista priorizada de todos os itens que podem ser desenvolvidos no produto. É mantido pelo Product Owner.

2. **Backlog da sprint:** Uma seleção de itens do Backlog do Produto que a equipe se compromete a entregar durante uma Sprint.

3. **Incremento:** O produto potencialmente entregável no final de cada Sprint. Deve ser testado e integrado.

**Eventos:**

1. **Sprint:** Um período de tempo fixo (geralmente de 2 a 4 semanas) durante o qual a equipe trabalha para entregar o incremento.

2. **Reunião de planejamento da Sprint:** No início da Sprint, a equipe realiza uma reunião para selecionar os itens do Backlog do Produto a serem incluídos na Sprint e planejar o trabalho a ser feito.

3. **Daily scrum:** Uma reunião diária de no máximo 15 minutos, onde a equipe compartilha atualizações sobre o trabalho concluído no dia anterior, o que será feito no dia atual e discute quaisquer impedimentos.

4. **Revisão da sprint:** No final da Sprint, a equipe apresenta o incremento concluído ao Product Owner e a outras partes interessadas para revisão e feedback.

5. **Retrospectiva da sprint:** Uma reunião no final da Sprint em que a equipe revisa seu próprio desempenho e identifica melhorias para a próxima Sprint.

O Scrum é considerado um framework ágil em vez de uma metodologia ágil devido à sua natureza flexível e adaptável. Enquanto metodologias geralmente fornecem um conjunto rígido de regras e processos a serem seguidos, o Scrum oferece orientações de alto nível e um conjunto de papéis, eventos e artefatos que podem ser adaptados para atender às necessidades específicas de uma equipe ou organização. Isso permite que as equipes apliquem os princípios ágeis de forma personalizada, ajustando o Scrum para se adequar às suas circunstâncias únicas. Essa flexibilidade é uma das razões pelas quais o Scrum é amplamente adotado e valorizado por equipes em diferentes setores e contextos.

## Extreme Programming (XP)

Extreme Programming (XP) é uma abordagem ágil de desenvolvimento de software que se concentra em melhorar a qualidade e a eficiência da entrega de software. Ela foi criada por Kent Beck no final dos anos 90 e se tornou uma das metodologias ágeis mais populares.

O XP é conhecido por enfatizar práticas como desenvolvimento orientado a testes (TDD), integração contínua, programação em pares e feedback contínuo do cliente. Aqui estão alguns dos princípios e práticas-chave do XP:

1. **Desenvolvimento Orientado a Testes (TDD)**: Os desenvolvedores escrevem testes antes de escrever o código de produção. Isso garante que o código seja testado automaticamente e que novos recursos não quebrem os existentes.

2. **Integração contínua**: As alterações de código são integradas ao repositório principal várias vezes ao dia. Isso ajuda a evitar conflitos e identificar problemas rapidamente.

3. **Programação em pares**: Os desenvolvedores trabalham em pares, revisando o código um do outro. Isso promove a colaboração, compartilhamento de conhecimento e redução de erros.

4. **Interação próxima com o cliente**: O cliente ou representante do cliente está envolvido no processo de desenvolvimento, fornecendo feedback constante sobre os requisitos e prioridades.

5. **Refatoração**: O código é continuamente aprimorado para torná-lo mais simples, legível e eficiente.

6. **Design simples**: O XP valoriza o design simples e funcional em vez de criar soluções excessivamente complexas.

7. **Pequenas versões frequentes**: O software é entregue em pequenas versões funcionais, permitindo que o cliente comece a usá-lo mais cedo e forneça feedback valioso.

8. **Estimativas Ágeis**: Em vez de estimativas detalhadas, o XP usa estimativas ágeis, como "pontos de história", para medir o esforço necessário para concluir as tarefas.

O XP é adequado para projetos em que os requisitos podem mudar com frequência e onde a colaboração próxima com o cliente é essencial. Ele promove a transparência, qualidade e adaptabilidade, tornando-o uma escolha popular para equipes de desenvolvimento de software.

## Kanban

O Kanban foi criado no Japão nas fábricas da Toyota nas décadas de 1940 e 1950. Seu desenvolvimento está intrinsecamente ligado aos princípios do _Lean Manufacturing_, um sistema de produção focado na redução de desperdícios e na melhoria contínua. O termo "kanban" significa "cartão visual" em japonês. Originalmente, o Kanban era um sistema físico que usava cartões para controlar o fluxo de peças em uma linha de produção. Cada cartão representava uma unidade de produção e era usado para solicitar a reposição de peças quando necessário. Esse sistema permitia que a Toyota mantivesse um estoque mínimo e respondesse rapidamente às mudanças na demanda.

O Kanban é amplamente utilizado em equipes ágeis de desenvolvimento de software, suporte de TI, gerenciamento de projetos e em muitos outros contextos para gerenciar e otimizar o trabalho de forma eficiente.

### Principais características

1. **Visualização do Fluxo de Trabalho**: O Kanban utiliza um quadro visual para representar o fluxo de trabalho. Cada etapa do processo é representada por uma coluna no quadro, e as tarefas são representadas por cartões ou post-its que se movem entre as colunas à medida que o trabalho avança.

2. **Limitação de Trabalho em Andamento (WIP)**: Uma das características mais distintivas do Kanban é a limitação de WIP. Isso significa que cada coluna no quadro tem um limite estrito de quantas tarefas podem estar em andamento ao mesmo tempo. Isso ajuda a evitar a sobrecarga de trabalho e a manter um fluxo constante.

3. **Focus na Demanda do Cliente**: O Kanban é orientado pela demanda do cliente. As tarefas só são iniciadas quando há uma demanda real, evitando assim a superprodução.

4. **Melhoria Contínua**: O Kanban promove a melhoria contínua do processo. À medida que a equipe trabalha com o sistema, são identificados gargalos e oportunidades de otimização. Essas melhorias são implementadas gradualmente.

### Quadro Kanban

O Quadro Kanban é o coração do sistema e representa o fluxo de trabalho da equipe. Os principais conceitos incluem:

1. **Colunas**: Cada coluna no quadro representa uma etapa do processo, como "A fazer", "Em andamento" e "Concluído". As colunas podem ser personalizadas para se adequar ao processo específico da equipe.

2. **Cartões**: Os cartões representam tarefas individuais. Cada cartão contém informações sobre a tarefa, como descrição, responsável e prazo.

3. **Limites de WIP**: Cada coluna tem um limite de quantos cartões podem estar nela ao mesmo tempo. Isso evita a sobrecarga de trabalho e mantém o fluxo constante.

4. **Puxar vs. Empurrar**: O Kanban é um sistema "puxado" em oposição a um sistema "empurrado". Isso significa que as tarefas só são iniciadas quando há capacidade disponível na coluna seguinte, em vez de serem empurradas para a próxima etapa automaticamente.

### OKR

OKR (_Objectives and Key Results_) é um sistema de gerenciamento de desempenho amplamente adotado em empresas e organizações para definir e acompanhar metas e resultados. Ele foi popularizado por empresas como Google e Intel e é utilizado para alinhar equipes e indivíduos aos objetivos estratégicos da organização.

**Componentes**:

1. **Objetivos (Objectives)**: Os objetivos são **descrições concisas e qualitativas** que definem o que a organização deseja alcançar em um determinado período. Eles devem ser inspiradores, ambiciosos e específicos.

2. **Resultados-Chave (Key Results)**: Os resultados-chave são **metas** atreladas a métricas quantitativas e específicas que indicam o progresso em direção aos objetivos. Eles são _SMART_, ou seja, mensuráveis, alcançáveis e relevantes e temporais para o objetivo. Cada objetivo pode ter vários resultados-chave associados.

**Principais características**:

1. **Simplicidade**: O OKR é projetado para ser simples e fácil de entender. Cada equipe ou indivíduo define um pequeno número de objetivos (geralmente de 3 a 5) com alguns resultados-chave para cada um.

2. **Transparência**: Os OKRs são frequentemente compartilhados com toda a organização. Isso promove a transparência e ajuda na construção de um ambiente de colaboração.

3. **Foco em Resultados**: O sistema coloca grande ênfase em resultados mensuráveis e tangíveis. Isso ajuda a evitar a armadilha de simplesmente completar tarefas sem atingir os resultados desejados.

4. **Agilidade**: O OKR é flexível e pode ser adaptado rapidamente à medida que as circunstâncias mudam. Ele é frequentemente definido em ciclos curtos, como trimestres.

**Benefícios**:

1. **Alinhamento**: OKRs garantem que todos na organização estejam trabalhando na mesma direção, alinhados com os objetivos estratégicos.

2. **Foco**: Eles ajudam as equipes a se concentrarem nas prioridades críticas e evitarem distrações.

3. **Responsabilização**: OKRs são públicos e todos são responsáveis por seu cumprimento. Isso promove a responsabilidade individual e coletiva.

4. **Feedback e aprendizado**: A medição contínua do progresso permite que as equipes aprendam com seus sucessos e fracassos e façam ajustes conforme necessário.

O OKR é uma ferramenta poderosa para aumentar a eficácia organizacional, mas sua implementação bem-sucedida requer disciplina e compromisso em todos os níveis da organização. É uma abordagem flexível que se adapta a uma variedade de contextos e setores.