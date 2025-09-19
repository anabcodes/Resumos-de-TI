<img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExN2YyZWswZWw4bjZsbGV0bW91NTM0a3lodmdwamFwMjE2dHlobHBuciZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/odhIi5fppDIB99Z6kd/giphy.gif" width="200px" />

# Qualidade do Produto de Software

## **🖥️ 1. Conceito de Qualidade de Produto de Software**

> Quando falamos de software, qualidade não é só não ter bugs; é sobre **entregar um produto que atenda às necessidades do usuário, dentro do prazo e do orçamento, e que seja confiável e utilizável**. Para empresas de TI, medir e gerenciar essa qualidade é essencial para reduzir retrabalho, aumentar a satisfação do usuário e garantir competitividade.
> 

### **1.1 Definição**

- **Qualidade de produto de software**: grau em que o software atende aos requisitos e expectativas do usuário.
- **Importante:** ela depende fortemente da **qualidade do processo de desenvolvimento**.
- **Como verificar:** através de **testes, inspeções e auditorias**.

### **1.2 Abordagens da qualidade de produto**

- **Garantia de Qualidade (QA):** prevenir defeitos através de boas práticas, processos e metodologias.
- **Controle de Qualidade (QC):** detectar falhas e defeitos no produto final.

## **🔄 2. Tipos de Qualidade no Ciclo de Vida**

> A qualidade de software precisa ser avaliada em diferentes momentos do ciclo de vida, para garantir que cada etapa contribua para um produto final confiável.
> 

| Tipo | O que mede | Pergunta-chave |
| --- | --- | --- |
| Qualidade de processo | Como o software foi desenvolvido (atividades, métodos, boas práticas) | “Foi construído corretamente?” |
| Qualidade interna | Propriedades do produto e artefatos durante o desenvolvimento | “Foi bem projetado?” |
| Qualidade externa | Qualidade observada na execução do software em ambiente de teste | “Passa nos testes?” |
| Qualidade em uso | Experiência do usuário final com o software | “Qual é a experiência do usuário?” |

## **⭐ 3. Atributos de Qualidade de Produto – ISO 25010**

> Para medir qualidade de forma objetiva, a **ISO 25010** define **oito atributos principais** (internos e externos) e atributos de qualidade em uso, criando uma referência padrão que empresas podem adotar e medir.
> 

### **3.1 Atributos internos e externos**

| Atributo | O que mede | Exemplo de aplicação |
| --- | --- | --- |
| Funcionalidade | Grau em que funções atendem às necessidades declaradas e implícitas | Software entrega todas as funcionalidades descritas nos requisitos |
| Eficiência | Uso de recursos e desempenho | Sistema responde rapidamente e consome pouca memória |
| Compatibilidade | Interação com outros sistemas | Sistema funciona bem em diferentes navegadores ou sistemas operacionais |
| Usabilidade | Facilidade de uso, aprendizado e operação | Usuário consegue completar tarefas sem treinamento extenso |
| Confiabilidade | Execução conforme esperado, mesmo em falhas | Sistema mantém dados corretos mesmo após erros de hardware |
| Segurança | Proteção de dados e acesso | Usuários não autorizados não podem acessar informações sensíveis |
| Manutenibilidade | Facilidade de modificar e evoluir o software | Correções e novas funcionalidades são aplicadas sem quebrar o sistema |
| Portabilidade | Transferência entre ambientes | Software pode ser instalado em diferentes sistemas sem grandes mudanças |

### **3.2 Atributos de Qualidade em Uso (ISO 25010)**

| Atributo | O que mede |
| --- | --- |
| Eficácia | Precisão e completude na realização das metas do usuário |
| Eficiência | Recursos gastos para alcançar essas metas |
| Satisfação | Percepção de prazer, conforto e confiança do usuário |
| Liberdade do risco | Redução de riscos econômicos, à saúde e ambientais |
| Cobertura de contexto | Aplicabilidade do software em diferentes cenários de uso |
| Flexibilidade | Capacidade de adaptação a novos contextos de uso |

## **📏 4. Métricas de Qualidade de Produto – ISO 25023**

> A ISO 25023 **complementa a ISO 25010**, explicando **como medir cada atributo de qualidade**. Ela não define métricas prontas para todos os casos, mas oferece **um modelo de criação de métricas adaptável ao contexto da empresa ou do projeto**.
> 

### **4.1 Estrutura de uma métrica segundo ISO 25023**

1. **Atributo de qualidade**: qual característica da ISO 25010 está sendo medida.
2. **Objetivo da métrica**: por que medir esse atributo.
3. **Questão de medição**: pergunta que a métrica deve responder.
4. **Fórmula / Método de cálculo**: como calcular a métrica.
5. **Medidas necessárias**: valores que precisam ser coletados.
6. **Foco**: interno (código/artefatos) ou externo (execução/uso).
7. **Interpretação**: como entender o resultado obtido.

### **4.2 Exemplo aplicado – Métrica de Completude Funcional**

1. **Atributo de qualidade**: Funcionalidade → Completude funcional.
2. **Objetivo**: Avaliar se todas as funções especificadas nos requisitos foram implementadas.
3. **Questão de medição**: Quão completa é a implementação do software em relação aos requisitos funcionais?
4. **Fórmula**:
    - `Cobertura de implementação = (Nº de funções implementadas / Nº de funções especificadas) × 100`
5. **Medidas necessárias**:
    - A = número de funções especificadas nos requisitos.
    - B = número de funções implementadas corretamente.
6. **Foco**: Externo (avaliado na execução, verificando se as funções estão realmente disponíveis e corretas).
7. **Interpretação**:
    - Resultado próximo de 100% → alta completude.
    - Resultado baixo → funções faltando ou não implementadas corretamente.

**Exemplo prático:**

- Requisitos especificam **20 funções**.
- O software implementou corretamente **18 funções**.
- Cobertura de implementação = (18 / 20) × 100 = **90%**.
- **Interpretação:** O sistema tem boa cobertura funcional, mas ainda faltam 2 funções para estar completo.

### **4.3 Observações**

- Métricas podem ser **adaptadas**, mas sempre devem ter **objetivo claro e forma de cálculo definida**.
- Para atributos compostos (ex: compatibilidade → coexistência e interoperabilidade), é recomendado criar **métricas separadas para cada subatributo**, pois cada um mede aspectos distintos.

## **💻 5. Métricas de Código e Orientadas a Objetos**

> Além das métricas de qualidade de produto baseadas em ISO, desenvolvedores de software usam **métricas de código e OO** para medir complexidade, manutenibilidade e coesão, diretamente aplicáveis durante o desenvolvimento.
> 

### **5.1 Métricas básicas de código**

| Métrica | O que mede | Aplicação prática |
| --- | --- | --- |
| Fan-in | Nº de funções que chamam uma função | Impacto de mudanças: muitas funções dependem dela → mais cuidado ao modificar |
| Fan-out | Nº de funções chamadas por uma função | Complexidade de manutenção da função |
| LOC | Número de linhas de código | Código maior = potencialmente mais complexo e difícil de manter |
| Complexidade Ciclomática | Nº de caminhos de execução | Ajuda a planejar testes e prever dificuldade de entendimento |
| Profundidade de aninhamento | Estruturas internas aninhadas | Código muito aninhado = difícil de entender e testar |

### **5.2 Métricas para sistemas OO (Chidamber-Kemerer)**

| Métrica | O que mede | Aplicação prática |
| --- | --- | --- |
| DIT | Profundidade da herança | Maior profundidade = mais difícil de compreender |
| NOC | Nº de subclasses diretas | Indica reuso ou complexidade hierárquica |
| CBO | Acoplamento entre classes | Maior acoplamento = mais difícil de manter |
| LCOM | Falta de coesão entre métodos | Baixa coesão = classe menos organizada |
| WMC | Nº de métodos ponderados pela complexidade | Classe muito complexa → atenção ao teste e manutenção |
| RFC | Métodos potencialmente invocados | Avalia complexidade e impacto de mensagens recebidas pela classe |

**Aplicação prática:**

- Durante a codificação, um desenvolvedor pode **usar essas métricas para decidir refatorações, planejar testes ou avaliar risco de mudanças**.
- Ex: classe com CBO muito alto → reduzir dependências para facilitar manutenção.
