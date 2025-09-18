<img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExN2YyZWswZWw4bjZsbGV0bW91NTM0a3lodmdwamFwMjE2dHlobHBuciZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/odhIi5fppDIB99Z6kd/giphy.gif" width="200px" />

# Introdução a Qualidade de Software

## **Definição geral de qualidade**

- **Qualidade** = capacidade de um produto ou serviço de:
    1. **Realizar funções esperadas** (aspecto técnico).
    2. **Atender às expectativas do cliente** (percepção do usuário).
- Qualidade **depende do cliente, do contexto e da aplicação**.
- Conceito estendido inclui atributos técnicos, econômicos e sociais.

## **Definição aplicada a software**

- **Qualidade de software** = gestão de qualidade efetiva → produto útil → valor para desenvolvedor e usuário.
- **Objetivo da qualidade**: reduzir **defeitos** para evitar **falhas**.
    - Defeito ou bug é um erro presente no software mas que ainda não se manifestou necessariamente para o usuário.
    - Falha é quando o defeito se manifesta durante a execução e o software não atende ao esperado

## **Por que qualidade importa?**

- Software não é apenas “funcionar sem bugs”.
- Um software pode funcionar tecnicamente, mas ainda assim ser ruim para o usuário ou custoso para a empresa.
- Qualidade de software busca **produto confiável, útil e que gere valor**, minimizando custos de retrabalho e falhas externas.

## **Níveis de qualidade**

- **Qualidade intrínseca (nível técnico)**
    - Foca no **produto em si**, independente do contexto de uso.
    - Medida operacional: taxa de defeitos, confiabilidade.
    - Principais atributos:
        - Funcionalidade
        - Confiabilidade
        - Desempenho
        - Durabilidade
        - Tamanho / consumo de recursos
        - Flexibilidade
- **Qualidade abrangente (nível estendido)**
    - Combina **qualidade intrínseca + qualidade do processo + satisfação do cliente**.
    - Inclui também:
        - Preço, prazo, serviço pós-venda
        - Aspectos humanos e sociais (respeito ao meio ambiente, ética, posição na comunidade)

## **Custos da qualidade**

- Qualidade envolve **investimento**, e reduzir falhas custa menos que corrigir defeitos tarde.
- Categorias de custos:
    1. **Prevenção** → evitar defeitos (treinamento, boas práticas, design).
    2. **Avaliação** → descobrir defeitos (testes, revisões).
    3. **Falhas internas** → corrigir antes da entrega (retrabalho, refatoração).
    4. **Falhas externas** → corrigir após entrega (suporte, perda de reputação, multas).

## **Especificidades do desenvolvimento de software**

1. **Intangibilidade**
    - Software não é material, não se pode tocar nem medir fisicamente.
    - Isso torna difícil inspecionar o produto “visualmente” para verificar qualidade, diferentemente de um carro ou eletrodoméstico.
2. **Complexidade lógica**
    - Um sistema de software pode ter **milhares ou milhões de linhas de código**, interações complexas entre módulos e regras de negócio.
    - Pequenos erros podem gerar **grandes impactos**, aumentando a chance de defeitos.
3. **Facilidade de modificação**
    - Diferente de produtos físicos, software pode ser alterado rapidamente.
    - Isso é bom (agilidade), mas aumenta o risco de introduzir **novos defeitos** a cada mudança.
4. **Depreciação invisível**
    - Software não “gasta” fisicamente, mas pode se tornar obsoleto: incompatibilidade com novas tecnologias, frameworks, sistemas operacionais.
    - A qualidade não depende só do que funciona agora, mas da **manutenibilidade futura**.
5. **Dependência de requisitos**
    - Software só é bom se **atender ao que os usuários precisam**, que muitas vezes não está bem definido ou muda com o tempo.
    - Isso liga diretamente à qualidade percebida: um software tecnicamente perfeito pode ser inútil se não atender às necessidades do usuário.

## Qualidade de produto e de processo

Para garantir a qualidade é necessário garantir qualidade do produto e do processo tendo em vista que a qualidade do produto depende da qualidade do processo. Um bom processo não garante produto perfeito, mas reduz defeitos e retrabalho.

### Qualidade de produto VS qualidade de processo

- **Qualidade de produto:** atende aos requisitos; verificada por testes, inspeções e auditorias. Possui duas abordagens:
    - **Garantia de Qualidade (QA):** foco em **prevenir defeitos** por meio de processos, metodologias e boas práticas.
    - **Controle de Qualidade (QC):** foco em **detectar falhas e defeitos** no produto final.
- **Qualidade de processo:** assegura que o desenvolvimento seja consistente e eficiente. Possui as seguintes abordagens:
    - **Modelos de maturidade e capacidade;**
    - **Definição e padronização de processos;**
    - **Medição e melhoria contínua.**

### Avaliações de qualidade

- **Produto:** foco no “resultado final” → testes, inspeções, auditorias.
- **Processo:** foco no “como se chegou ao resultado” → auditorias, medições, análises de desempenho.
