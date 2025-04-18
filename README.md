# Guia Rápido da Interface GLPI
![GUI](./src/img/main_gui.jpeg)
___

Este documento descreve as principais funcionalidades visíveis na tela de gerenciamento de chamados do GLPI.

## 1. Menu Lateral Esquerdo
![Aba Lateral](./src/img/aba_lateral.jpeg)
Esta barra vertical à esquerda contém as principais opções de navegação:

* **Home:** Leva para a página inicial do sistema.
* **+ Criar um chamado:** Inicia o processo para abrir um novo ticket de suporte ou solicitação.
* **Chamados:** Exibe a lista de chamados existentes (tela atual na imagem).
* **Reservas:** (Se habilitado) Permite gerenciar reservas de itens ou recursos.
* **FAQ:** Acesso à Base de Conhecimento ou Perguntas Frequentes.
* **Recolher menu:** Minimiza ou expande este menu lateral.

## 2. Barra Superior

Localizada no topo da página, contém:

* **Caminho de Navegação (Breadcrumb):** Mostra sua localização atual no sistema (Ex: `Home / Chamados`).
* **Botões de Ação Rápida:**
    * `+`: Provavelmente para criar um novo item rapidamente (como um chamado).
    * `Q` (Lupa): Atalho para uma função de busca.
    * `☆`: Atalho para visualizações salvas ou itens favoritados.
* **Informações do Usuário/Entidade:**
    * `Self-Service`: Indica o perfil de acesso (neste caso, autoatendimento).
    * `Entidade raiz`: Mostra a entidade (departamento, empresa) à qual o usuário pertence ou está visualizando.
    * `AS` (Iniciais): Acesso ao perfil do usuário, configurações ou opção de logout.

## 3. Área Principal: Visualização de Chamados

Esta é a área central onde os chamados são listados e gerenciados.

### 3.1. Filtros e Pesquisa

Permite refinar a lista de chamados exibida:

* **Dropdowns de Critérios:** Permitem selecionar campos (Ex: `Características - Status`) e valores (Ex: `é Novo`, `Todos`) para filtrar a lista. Pode-se adicionar múltiplos critérios.
* **Botões `regra`, `regra global`, `grupo`:** Opções avançadas para combinar ou gerenciar regras de filtro.
* **Botão `Pesquisar`:** Aplica os filtros selecionados à lista de chamados.
* **Ícones `☆` e `👁️` (ao lado de Pesquisar):**
    * `☆`: Provavelmente para salvar a configuração atual de filtros como uma visualização favorita.
    * `👁️`: Possivelmente para gerenciar quais colunas são exibidas na tabela ou outras opções de visualização.

### 3.2. Barra de Ações da Tabela

Acima da lista de chamados, contém ícones para realizar ações nos chamados selecionados:

* **(Checkbox):** Selecionar todos os chamados visíveis na página.
* **(Lápis):** Editar o(s) chamado(s) selecionado(s).
* **(Lixeira):** Excluir o(s) chamado(s) selecionado(s).
* **(Lupa):** Visualizar detalhes do(s) chamado(s) selecionado(s).
* **(Ícone com '...')** : Provavelmente oferece mais ações (atualizar, fundir, etc.). *Nota: O ícone exato pode variar.*

### 3.3. Tabela de Chamados

Exibe a lista de chamados com base nos filtros aplicados. As colunas comuns são:

* **ID:** Identificador único do chamado.
* **TÍTULO:** Assunto ou breve descrição do chamado.
* **STATUS:** Situação atual do chamado (Ex: Novo, Em atendimento, Pendente, Solucionado).
* **ÚLTIMA ATUALIZAÇÃO:** Data e hora da modificação mais recente.
* **DATA DE ABERTURA:** Quando o chamado foi criado.
* **PRIORIDADE:** Nível de urgência do chamado (Ex: Baixa, Média, Alta).
* **REQUERENTE:** Quem abriu o chamado.
* **ATRIBUÍDO - TÉCNICO:** O técnico ou grupo responsável pelo atendimento.
* **CATEGORIA:** Classificação do tipo de chamado.
* **TEMPO PARA SOLUÇÃO:** Prazo (SLA) para resolver o chamado.

### 3.4. Controles de Paginação

Abaixo da tabela:

* **Dropdown (Ex: `15`):** Permite escolher quantos chamados exibir por página.
* **Texto (Ex: `Exibindo 1 a 1 de 1 linhas`):** Informa quantos itens estão sendo mostrados na página atual e o total de itens encontrados. (Na imagem, há apenas 1 chamado correspondente ao filtro).

---

Este README fornece uma visão geral das funcionalidades presentes na interface da imagem. Funcionalidades específicas podem variar ligeiramente dependendo da versão do GLPI e das configurações personalizadas.
