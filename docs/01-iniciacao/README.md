# Iniciação

> A fase de iniciação, em gerência de projetos, é o estágio que estabelece as bases para o sucesso do empreendimento. 
> Durante essa etapa, os objetivos definidos, identificando-se suas metas, escopo, partes interessadas (*stakeholders*) e restrições. 
> É o momento em que a viabilidade do projeto é avaliada, analisando-se recursos necessários, riscos potenciais e benefícios esperados.
> Nesta etapa é elaborado o Termo de Abertura do Projeto (TAP).
> Essa fase serve como um alicerce estratégico, proporcionando uma compreensão abrangente do que o projeto busca alcançar e delineando as diretrizes que orientarão as etapas subsequentes. 
> O sucesso na fase de iniciação contribui significativamente para a eficácia do gerenciamento de projetos como um todo.

# Estrutura do Documento

- [Fase de Iniciação](#iniciação)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Critérios de Sucessos](#critérios-de-sucesso)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos Preliminares](#requisitos-preliminares)
- [Partes Interessadas](#partes-interessadas)
- [Estimativa de Custo e Prazo](#estimativa-de-custo-e-prazo)
  - [Estimativa de Custo](#estimativa-de-custo)
  - [Estimativa de Prazo](#estimativa-de-prazo)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
- [Documentos](#documentos)
  - [Declaração de Escopo](#declaração-de-escopo)
  - [Registro de Partes Interessadas](#registro-de-partes-interessadas)
  - [Termo de Abertura do Projeto (TAP)](#termo-de-abertura-do-projeto-tap)

# Introdução

O setor agropecuário enfrenta desafios significativos que impactam a eficiência e a produtividade das fazendas. Entre esses desafios, destacam-se a gestão eficaz do gado, o monitoramento da saúde animal, a alimentação adequada e o controle da produtividade. A falta de ferramentas tecnológicas avançadas para o gerenciamento de fazendas limita a capacidade dos produtores rurais de responder de maneira rápida e eficaz a esses desafios, afetando não só a saúde e o bem-estar dos animais, mas também a lucratividade do negócio.

## Problema

A ausência de um sistema integrado para o gerenciamento eficiente do gado nas fazendas resulta em dificuldades de acompanhamento e controle da saúde, alimentação e produtividade dos animais. Isso não apenas compromete o bem-estar animal, mas também reduz a eficiência operacional e a rentabilidade das fazendas. Além disso, a falta de dados precisos e em tempo real sobre cada animal dificulta a tomada de decisões baseada em informações concretas, o que pode levar a intervenções tardias em questões de saúde ou a ineficiências na gestão dos recursos da fazenda.

## Objetivos

**Objetivo Geral:**

Desenvolver um sistema de gerenciamento de gado para fazendas, denominado Boi Control, que utilize tecnologias inovadoras para otimizar as operações diárias, melhorar o monitoramento da saúde, da alimentação e da produtividade do gado, e suportar decisões agrícolas baseadas em dados.

**Objetivos Específicos:**

1. Implementar funcionalidades para o monitoramento em tempo real da saúde e da alimentação do gado, utilizando sensores e dispositivos IoT.
2. Desenvolver uma interface de usuário intuitiva para permitir que os fazendeiros acompanhem a produtividade e o bem-estar de cada animal.
3. Integrar análises de dados e relatórios para facilitar a tomada de decisões baseadas em informações precisas e atualizadas.
4. Avaliar o impacto da implementação do sistema nas operações da fazenda, na eficiência produtiva e na rentabilidade.

# Especificações do Projeto

O Boi Control será desenvolvido com o foco em atender às necessidades específicas do setor agropecuário, incorporando tecnologias de ponta para a gestão eficiente do gado. Este sistema abrangerá funcionalidades críticas como monitoramento em tempo real, gestão de alimentação e saúde, análise de produtividade, e suporte à tomada de decisão baseada em dados. Utilizaremos estudos de caso, ferramentas de gerenciamento agrícola e consultas a especialistas para garantir que nosso sistema seja tanto teoricamente sólido quanto praticamente aplicável.

## Critérios de Sucesso

1. Implementação eficaz de funcionalidades de monitoramento em tempo real para saúde e alimentação do gado.
2. Aumento na eficiência operacional das fazendas usuárias do sistema.
3. Melhoria no bem-estar e na produtividade do gado, comprovada por dados coletados pelo sistema.
4. Satisfação dos usuários com a interface e a usabilidade do sistema.
5. Decisões agrícolas mais informadas e baseadas em dados, resultando em melhor gestão dos recursos e aumento da rentabilidade.

## Histórias de Usuários

| EU COMO...          | QUERO/PRECISO...                                | PARA...                                              |
|---------------------|-------------------------------------------------|------------------------------------------------------|
| Fazendeiro          | Monitorar a saúde do meu gado em tempo real     | Intervir prontamente em qualquer problema de saúde   |
| Gerente de fazenda  | Acompanhar a alimentação do gado                | Garantir uma nutrição adequada e balanceada          |
| Técnico agropecuário| Acessar relatórios detalhados sobre a produtividade do gado | Identificar áreas para melhoria na gestão da fazenda |
| Administrador       | Configurar alertas para variações na saúde do gado | Ser notificado imediatamente sobre quaisquer riscos  |


## Requisitos Preliminares

> Os requisitos preliminares fornecem uma visão inicial do escopo, funcionalidades-chave e as expectativas a serem atendidas.

### Requisitos Funcionais

A tabela a seguir apresenta os requisitos funcionais do projeto Boi Control, derivados das histórias de usuários.

| ID    | Descrição do Requisito                                              | Prioridade |
|-------|----------------------------------------------------------------------|------------|
|RF-001 | Permitir o registro de gado no sistema                              | ALTA       |
|RF-002 | Monitorar em tempo real a saúde do gado através de sensores IoT     | ALTA       |
|RF-003 | Gerar alertas para variações na saúde ou comportamento do gado      | ALTA       |
|RF-004 | Oferecer um dashboard com informações detalhadas sobre o gado       | ALTA       |
|RF-005 | Permitir o cadastro de informações sobre alimentação do gado        | ALTA       |
|RF-006 | Integrar análise de produtividade do gado                           | MÉDIA      |
|RF-007 | Permitir a configuração de notificações para o gerente da fazenda   | MÉDIA      |
|RF-008 | Fornecer relatórios de produtividade e saúde do gado                | MÉDIA      |
|RF-009 | Facilitar a gestão de inventário de alimentos e medicamentos        | MÉDIA      |
|RF-010 | Suportar a identificação individual de cada animal no sistema       | ALTA       |

### Requisitos Não Funcionais

A tabela a seguir apresenta os requisitos não funcionais do projeto Boi Control.

| ID     | Descrição do Requisito                                             | Prioridade |
|--------|---------------------------------------------------------------------|------------|
|RNF-001 | O sistema deve ser responsivo e acessível em dispositivos móveis   | ALTA       |
|RNF-002 | O tempo de resposta para as funcionalidades críticas deve ser inferior a 2 segundos | ALTA |
|RNF-003 | Deve garantir a segurança dos dados através de criptografia e autenticação segura | ALTA |
|RNF-004 | O sistema deve ser capaz de operar 24/7, com uma disponibilidade de 99,9% | ALTA     |
|RNF-005 | Deve oferecer uma interface intuitiva e fácil de usar, com um design agradável | MÉDIA    |

### Restrições

A tabela a seguir apresenta as restrições do projeto Boi Control.

| ID    | Descrição da Restrição                                              | Impacto   |
|-------|----------------------------------------------------------------------|-----------|
|RE-001 | O sistema deve ser implementado dentro de 6 meses                    | ALTA      |
|RE-002 | O orçamento para o desenvolvimento não deve exceder R$ 100.000,00    | ALTA      |
|RE-003 | A solução deve ser compatível com as principais plataformas móveis (iOS e Android) | MÉDIA  |
|RE-004 | Deve-se utilizar apenas tecnologias de código aberto para o desenvolvimento | MÉDIA  |
|RE-005 | A equipe de desenvolvimento é composta por no máximo 5 membros       | MÉDIA     |

# Partes Interessadas

A identificação das partes interessadas é essencial para o sucesso do projeto Boi Control. Abaixo estão listadas as principais partes interessadas, suas expectativas, nível de influência e importância para o projeto:

- **Fazendeiros (Clientes)**: Buscam melhorias na gestão do gado e aumento da produtividade. Alto nível de influência e importância.
- **Desenvolvedores do Sistema**: Responsáveis pela criação e manutenção do Boi Control. Médio nível de influência, alta importância.
- **Fornecedores de Hardware e IoT**: Provedores das tecnologias necessárias para monitoramento do gado. Médio nível de influência, média importância.
- **Especialistas em Agropecuária**: Consultores para as funcionalidades e precisão dos dados. Baixo nível de influência, alta importância para a validação do conteúdo.
- **Investidores**: Fornecem os recursos financeiros necessários. Alto nível de influência e importância para a viabilidade do projeto.
- **Órgãos Reguladores**: Garantem que o sistema esteja em conformidade com as normas agropecuárias. Baixo nível de influência, média importância.

# Estimativa de Custo e Prazo

## Estimativa de Custo

A seguir, apresenta-se uma estimativa preliminar dos custos associados ao desenvolvimento e implementação do sistema Boi Control. Os valores são hipotéticos e servem como uma base para a elaboração do orçamento.

| Item de Custo            | Descrição                        | Qtd. horas | Valor / hora (R$) | Valor total (R$) |
|--------------------------|----------------------------------|------------|-------------------|------------------|
| Recursos Humanos         | Desenvolvedores, designers, etc. | 1200       | 50                | 60.000           |
| Hardware                 | Sensores IoT, servidores, etc.   | N/A        | N/A               | 20.000           |
| Serviços de Rede         | Internet, VPN, etc.              | N/A        | N/A               | 5.000            |
| Hospedagem e Nuvem       | AWS, Google Cloud, etc.          | N/A        | N/A               | 15.000           |
| Software de terceiros    | Licenças de software             | N/A        | N/A               | 10.000           |
| Serviços e treinamento   | Capacitação da equipe            | N/A        | N/A               | 8.000            |
| **Total Geral**          |                                  |            |                   | **118.000**      |

### Notas:
- Os valores acima são estimativas e podem variar conforme o avanço do projeto e a obtenção de orçamentos mais detalhados.
- A estimativa de custo não inclui despesas pós-implementação, como manutenção contínua e atualizações do sistema.


## Estimativa de Prazo

......  COLOQUE AQUI O SEU TEXTO ......

> A estimativa de prazo orienta tanto o cliente quanto a equipe de desenvolvimento do projeto em termos do tempo necessário para a conclusão do projeto como um todo. 
> Esta estimativa possibilita a criação de um cronograma realista e viável, permitindo o planejamento adequado das fases do projeto, alocação de recursos de maneira eficiente e antecipação de eventuais desafios.
> Uma estimativa precisa orienta a execução do projeto, contribui para a gestão de expectativas e para o estabelecimento de metas alcançáveis.

> Indique:
> * Prazo previsto (em horas) 
> * Data de início
> * Data de término

# Metodologia

......  COLOQUE AQUI O SEU TEXTO ......

> Nesta parte do documento, você deve apresentar a metodologia adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, a divisão de papéis e tarefas e as ferramentas empregadas.
>
> Coloque detalhes sobre o processo utilizado e a implementação do Framework Scrum seguido pelo grupo. 
> O grupo deverá gerenciar as tarefas utilizando o GitHub Project para acompanhar o andamento do projeto, a execução das tarefas e o status de desenvolvimento da solução.
> 
> **Links Úteis**:
> - [Github Project](https://docs.github.com/en/issues/planning-and-tracking-with-projects/creating-projects/creating-a-project)
> - [O que é o GitHub Projects? | Guia de Iniciantes](https://www.youtube.com/watch?v=vxYTpsFKdiQ&ab_channel=JulioArruda)
> - [Introduction to GitHub Project Boards](https://www.youtube.com/watch?v=idZyqNIrt84&list=PLiO7XHcmTslc5hGrbnnmHIb0SeJLTpOEu&ab_channel=MickeyGousset)
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0)

## Divisão de Papéis

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente a divisão de papéis e tarefas entre os membros do grupo.
> Indique as responsabilidades de cada membro do grupo no projeto.

## Ferramentas

......  COLOQUE AQUI O SEU TEXTO - SIGA O EXEMPLO DA TABELA ABAIXO  ......

> Liste as ferramentas empregadas no desenvolvimento do projeto, justificando a escolha delas, sempre que possível.
> Todas as ferramentas utilizadas devem ser listadas.
> Qualquer tipo de ferramenta que for utilizada para construção de um artefato deve ser identificada, uma vez que podem ser necessárias alterações.
> A necessidade de uso de licenças e possíveis custos relacionados devem ser indicados.

| Ambiente              | Plataforma         | Link de Acesso             | Justificativa |
|-----------------------|--------------------|----------------------------|---------------|
| Quadro Kanban         | Github             | https://github.com/XXXXXXX | Centralização e organização do projeto no próprio repositório. |
| Repositório de código | GitHub             | https://github.com/XXXXXXX |               |
| Protótipo Interativo  | MavelApp ou Figma  | https://figma.com/XXXXXXX  |               |
| Documentos Textuais   | LibreOffice Writer | N/A                        |               |
| Planilhas e Gráficos  | Google Planilhas   | https://docs.google.com/   |               |
| EAP / WBS             | | | |
| Cronograma do Projeto | | | |
| Matriz RACI           | | | |

# Documentos

> Esta seção deve ser utilizada para armazenamento e listagem dos documentos e artefatos produzidos durante as aulas.
> Atualize os documentos nos respectivos links.

## Declaração de Escopo

> Você deve preencher o seguinte documento:
- [Declaração de Escopo](artefatos/declaracao-escopo.docx)

## Registro de Partes Interessadas

> Você deve preencher o seguinte documento:
- [Registro de Partes Interessadas](artefatos/registro-partes-interessadas.xlsx)

## Termo de Abertura do Projeto (TAP)

> O Termo de Abertura do Projeto (TAP) representa o ponto de partida oficial para o empreendimento. 
> Ele sintetiza de maneira clara e concisa os objetivos, escopo, partes interessadas envolvidas, entregas esperadas, cronograma preliminar e recursos necessários para a execução bem-sucedida do projeto. 
> O TAP funciona como um contrato inicial entre a equipe do projeto e as partes interessadas, estabelecendo as bases para uma compreensão compartilhada dos propósitos e limites do projeto. 
> Ao delinear esses elementos de forma detalhada, o Termo de Abertura do Projeto (TAP) fornece uma direção sólida para orientar as atividades subsequentes, facilitando a gestão eficaz do projeto desde o início até o encerramento. 
> Essa documentação garante a clareza, alinhamento e comprometimento de todos os envolvidos, contribuindo assim para o sucesso do projeto.

> Você deve preencher o seguinte documento:
> - [Termo de Abertura do Projeto](artefatos/termo-abertura-projeto.docx)
