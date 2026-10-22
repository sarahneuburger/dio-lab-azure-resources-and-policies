# :dizzy: Gerenciamento de Recursos e Políticas no Azure

O gerenciamento de recursos no Microsoft Azure é realizado por meio de ferramentas de governança que ajudam as organizações a controlar, monitorar e padronizar ambientes em nuvem. Esses recursos permitem garantir conformidade, segurança, organização e uso adequado da infraestrutura.

## :pencil: Gerenciamento de Recursos no Azure

Os recursos do Azure podem ser organizados em uma estrutura hierárquica composta por:

- Assinaturas (Subscriptions)
- Grupos de Recursos (Resource Groups)
- Recursos individuais
- Grupos de Gerenciamento (Management Groups)

Essa organização facilita o controle administrativo, a aplicação de regras corporativas e o gerenciamento dos ambientes em larga escala.

---

## :bookmark_tabs: Azure Policy

O Azure Policy é uma das principais ferramentas de governança da plataforma. Seu objetivo é aplicar padrões organizacionais e avaliar continuamente a conformidade dos recursos implantados.

### Principais Funcionalidades

- Controle de configurações dos recursos.
- Auditoria automática de conformidade.
- Aplicação de padrões corporativos.
- Correção automática de recursos não compatíveis.
- Criação de políticas personalizadas.
- Governança em múltiplas assinaturas e ambientes.

### Exemplos de Uso

- Permitir recursos apenas em regiões específicas.
- Exigir a utilização de tags obrigatórias.
- Garantir envio de logs para monitoramento.
- Restringir a criação de recursos fora dos padrões corporativos.

---

## :lock: Resource Locks (Bloqueios de Recursos)

Os bloqueios de recursos ajudam a proteger serviços críticos contra alterações ou exclusões acidentais.

### Tipos de Bloqueio

- **ReadOnly**: impede alterações nos recursos.
- **Delete**: impede a exclusão dos recursos.

Esses bloqueios são amplamente utilizados em ambientes de produção para aumentar a proteção operacional.

---

## :pencil2: Microsoft Purview

O Microsoft Purview é a solução de governança de dados da Microsoft, projetada para ajudar organizações a descobrir, classificar, proteger e gerenciar dados distribuídos em ambientes locais, multicloud e Azure.

### Principais Recursos do Microsoft Purview

- Descoberta de dados corporativos.
- Classificação automática de informações sensíveis.
- Mapeamento e catalogação de dados.
- Rastreabilidade (Data Lineage).
- Governança centralizada de dados.
- Suporte a requisitos de conformidade e auditoria.

### Benefícios

- Melhor visibilidade sobre os dados da organização.
- Apoio à conformidade regulatória.
- Proteção de informações sensíveis.
- Maior controle sobre o ciclo de vida dos dados.
- Gestão unificada de ambientes híbridos e multicloud.

---

## :paperclip: Outras Ferramentas de Governança

### Azure Management Groups

Permite organizar múltiplas assinaturas em uma estrutura hierárquica para simplificar a administração e a aplicação de políticas.

### Azure Resource Graph

Ferramenta utilizada para inventário e consulta dos recursos implantados no Azure, facilitando auditorias e análises operacionais.

### Azure Blueprints

Permite criar modelos padronizados contendo políticas, permissões e recursos para implantação rápida de ambientes corporativos.

---

## :dart: Benefícios da Governança no Azure

- Padronização de ambientes.
- Controle centralizado dos recursos.
- Maior segurança operacional.
- Conformidade com políticas corporativas e regulamentações.
- Redução de erros de configuração.
- Melhor gerenciamento de dados e informações sensíveis.
- Auditoria e monitoramento contínuos.

---

## :hearts: Conclusão

O Azure disponibiliza um conjunto robusto de ferramentas para governança e gerenciamento de recursos. Soluções como **Azure Policy**, **Resource Locks**, **Management Groups** e **Microsoft Purview** permitem controlar ambientes em nuvem de forma segura, organizada e compatível com requisitos corporativos. Entre elas, o **Microsoft Purview** se destaca por oferecer uma visão unificada dos dados da organização, auxiliando na governança, classificação e proteção das informações em escala corporativa.
