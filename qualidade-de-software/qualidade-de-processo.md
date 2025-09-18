<img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExN2YyZWswZWw4bjZsbGV0bW91NTM0a3lodmdwamFwMjE2dHlobHBuciZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/odhIi5fppDIB99Z6kd/giphy.gif" width="200px" />

# Qualidade do Processo de Software


## **Objetivos da Qualidade de Processo**

- Requisitos mais claros
- Custos e prazos controlados
- Defeitos detectados e corrigidos cedo

## **Como Melhorar a Qualidade de Processo**

- Usar ferramentas adequadas
- Adotar metodologias modernas (ágil, DevOps)
- Aplicar boas práticas reconhecidas
- **Melhoria é gradual e custosa**

## **Avaliação da Qualidade**

- **Inspeção:** análise visual de produtos
- **Teste:** execução do software comparando com resultados esperados
- **Auditoria:** avaliação independente de produtos e processos

## **Engenharia de Processo de Software**

- **Fases:** estabelecer infraestrutura → planejar → implementar/alterar → avaliar
    - **Infraestrutura:** equipe, ferramentas, recursos, apoio da gerência
    - **Definição do processo:** frameworks de ciclo de vida, modelos detalhados, métodos de definição
    - **Medição:** coleta de dados para identificar pontos fortes e fracos, apoiar melhoria contínua

## Modelos Descritivos VS Prescritivos

- **Modelo de processo prescritivo:** representa **como os processos deveriam ocorrer**, baseado em modelos conceituados (ex.: Scrum, Cascata) ou idealizados pela própria empresa. É o guia ou padrão que a organização deseja seguir.
- **Modelo de processo descritivo:** representa **como os processos realmente ocorrem na prática**, registrando o que de fato acontece, independentemente de qualquer modelo conceituado.

## Processos Prescritivos

### Representação de processos prescritivos

- **Manual de Processo**
    - Documento que descreve detalhadamente o processo, respondendo às dúvidas dos executores (o que fazer, pré-requisitos, responsabilidades, produtos gerados, como saber se a tarefa está concluída, templates etc.).
    - Conteúdo básico: atividades, produtos de trabalho, papéis envolvidos.
    - Conteúdo opcional: recursos, exemplos, instruções detalhadas, dicas.
    - Estrutura flexível, mas normalmente inclui introdução, definições, visões do processo, fluxos de controle e produtos, papéis, decomposição hierárquica, referências e apêndices.
    - Questões de usabilidade: consistência, atualização, design agradável e acessibilidade.
- **Guia Eletrônico de Processo**
    - Similar ao manual, mas gerado por ferramentas de modelagem de processos.
    - Permite navegar facilmente pelos caminhos do processo, capturar a estrutura em rede, baixar templates, criar áreas de discussão e gerar diferentes visões para diferentes papéis.
    - Pode ser gerado de forma estática ou sob demanda.

### Estratégias de implantação

- **Big-bang:** toda a organização adota o novo processo de uma vez, incluindo projetos em andamento. Grande sobrecarga.
- **Fases:** adoção gradual, começando por projetos selecionados. Treinamento e coaching são limitados.

### **Pilotagem e maturidade**

- Projetos piloto ajudam a testar o processo antes do uso geral.
- Avaliar se o processo atende objetivos, se está documentado corretamente e se é aplicável em outros cenários.

### **Operação**

- Uso do processo e monitoramento de seus efeitos.

### **Problemas comuns**

- Manuais incompletos ou detalhados demais.
- Definições vagas, interfaces mal definidas, falta de sanções.

### Modelos de Processos Prescritivos

| Nome do Modelo | Tipo | Definição | Quando Usar | Prós | Contras |
| --- | --- | --- | --- | --- | --- |
| **Cascata (Waterfall)** | Linear / Sequencial | Modelo tradicional, divide o projeto em fases sequenciais: requisitos → design → implementação → testes → manutenção | Projetos com requisitos bem definidos e estáveis | Simples, fácil de entender; etapas claras | Pouca flexibilidade; difícil lidar com mudanças; feedback tardio |
| **Modelo em V** | Linear / Verificação e validação | Extensão do Cascata que associa cada fase de desenvolvimento a uma fase de teste correspondente | Projetos críticos que exigem testes rigorosos | Destaca testes desde o início; melhora a confiabilidade | Pouco flexível; documentação extensa |
| **Prototipação (Prototyping)** | Iterativo | Desenvolvimento de protótipos rápidos para esclarecer requisitos antes da implementação final | Quando os requisitos não estão claros | Feedback rápido do usuário; ajuda a definir requisitos | Pode gerar expectativas irreais; foco excessivo no protótipo |
| **Incremental** | Iterativo / Modular | Projeto é desenvolvido em partes (“incrementos”) que são entregues e testadas separadamente | Projetos grandes que podem ser entregues em partes | Entregas rápidas; fácil incorporar mudanças | Integração entre incrementos pode ser complexa |
| **Spiral (Espiral)** | Iterativo / Risco-centrado | Combina desenvolvimento iterativo com análise de riscos em cada ciclo | Projetos grandes e complexos, com alto risco | Gerenciamento de riscos; flexível; permite refinamento contínuo | Complexo; exige planejamento detalhado |
| **Ágil / Scrum** | Iterativo / Adaptativo | Desenvolvimento iterativo e incremental com foco na colaboração, valor do cliente e flexibilidade | Projetos com requisitos dinâmicos ou inovadores | Flexível; foco no valor do cliente; equipes auto-organizadas | Menos documentação formal; depende da maturidade da equipe |
| **RUP (Rational Unified Process)** | Iterativo / Orientado a casos de uso | Processo estruturado baseado em melhores práticas, centrado em casos de uso e iterativo | Projetos corporativos de médio/grande porte | Estruturado; adaptável; baseado em melhores práticas | Complexo; exige ferramentas e treinamento |
|  |  |  |  |  |  |

## Processos Descritivos

### Como gerar um modelo descritivo?

**Fase 1: Set-Up**

1. **Definir objetivos e escopo** – Quem vai usar, quais processos incluídos/excluídos, expectativas.
2. **Definir esquema de modelagem** – Conceitos básicos (atividades, papéis, produtos de trabalho) e nível de detalhamento.
3. **Selecionar formalismos de modelagem** – Notação gráfica ou textual, formal ou informal, granularidade fina ou grossa.
4. **Selecionar ou adaptar ferramentas** – Para apoiar a modelagem, armazenar e gerar representações alternativas.

**Fase 2: Execução**

1. **Elicitar informações** – Coletar dados sobre atividades, papéis, produtos, relacionamentos; fontes: entrevistas, workshops, observação.
2. **Criar o modelo de processo** – Revisar e refinar com os participantes continuamente.
3. **Analisar o modelo** – Verificar completude, consistência e comportamento.
4. **Analisar o processo** – Rastrear desempenho, identificar fraquezas, ajustar processo e modelo conforme necessário.

### Riscos de modelos descritivos

1. **Resistência dos participantes:** pessoas envolvidas no processo podem **não colaborar** ou reagir negativamente à modelagem.
    1. **Por que acontece?**
        1. Medo de serem julgadas por falhas ou limitações do processo.
        2. Percepção de que o processo é **uma forma de controle ou imposição**.
        3. Acham o processo **burocrático**.
        4. Não enxergam valor na iniciativa de documentar/modelar processos.
    2. **Como mitigar?** Tornar os executores **“donos” do processo**, ou seja, envolvê-los e fazer com que participem ativamente das decisões sobre como o processo é documentado e aplicado.
2. **Relatos imprecisos:** as pessoas podem fornecer informações **distorcidas ou incompletas** sobre como o processo realmente funciona.
    1. **Por que acontece?**
        1. Para se proteger (“não quero parecer que errei”).
        2. Esquecimento de detalhes.
        3. Tendência a **idealizar o processo**, dizendo que funciona melhor do que realmente funciona.
    2. **Como mitigar?** Coletar informações **de maneira redundante**, ou seja, de várias fontes: entrevistas, observações, análise de artefatos, workshops, etc.
3. **Subestimar investimentos necessários:** modelar processos consome tempo, recursos e esforço. Além disso, a modelagem pode **gerar mudanças nos processos**, aumentando os custos.
    1. **Como mitigar?** Planejar adequadamente a iniciativa, considerando tempo, custo e recursos necessários.
4. **Subestimar a complexidade do modelo:** processos podem ter muitas entidades e relacionamentos, tornando o modelo muito complexo.
    1. **Risco:** se você tentar detalhar demais, pode perder o foco ou tornar o modelo inútil na prática.
    2. **Como mitigar?** focar **no nível de detalhe suficiente** para atingir os objetivos da modelagem, sem exagerar na precisão.
