# Guia Rápido da Interface GLPI
![GUI](./src/img/main_gui.jpeg)
___

Este documento descreve as principais funcionalidades visíveis na tela de gerenciamento de chamados do GLPI.

## 1. Menu Lateral Esquerdo
![Aba Lateral](./src/img/aba_lateral.jpeg)
___

Esta barra vertical à esquerda contém as principais opções de navegação:

* **Home:** Leva para a página inicial do sistema.
* **Criar um chamado:** Inicia o processo para abrir um novo ticket de suporte ou solicitação.
* **Chamados:** Exibe a lista de chamados existentes (tela atual na imagem).
* **Reservas:** (Se habilitado) Permite gerenciar reservas de itens ou recursos.
* **FAQ:** Acesso à Base de Conhecimento ou Perguntas Frequentes.
* **Recolher menu:** Minimiza ou expande este menu lateral.

## 2. Dentro da Aba de Chamados
![Tela de Chamados](./src/img/chamados_screen.jpeg)
___

### 2.1 Barra de Filtros e Pesquisa
Permite refinar a lista de chamados exibida.
* **Filtros Predefinidos:** Botões/Dropdowns para filtrar por `Características`, `Status` e outros critérios (`Todos`).
* **Campo de Pesquisa:** Caixa para busca textual, com opções para `Limpar` a busca, aplicar `regra global` ou filtrar por `grupo` antes de clicar em `Pesquisar`.
* **Ações de Visualização:** Ícones para salvar a pesquisa atual ou configurar a visualização.

### 2.2 Tabela de Chamados
* *Ações em Massa:** Ícones acima da tabela permitem realizar ações em um ou mais chamados selecionados (ex: editar, excluir, vincular - *dependendo da funcionalidade exata dos ícones*).
* **Listagem:** Exibe os chamados em formato de tabela com as seguintes colunas principais:
* `Título`: Assunto do chamado.
* `Status`: Situação atual do chamado (Ex: Novo, Em atendimento, Pendente, Solucionado, Fechado).
* `Última Atualização`: Data e hora da última modificação.
* `Data de Abertura`: Quando o chamado foi criado.
* `Prioridade`: Nível de urgência (Ex: Baixa, Média, Alta, Urgente).
* `Requerente`: Usuário que abriu o chamado.
* `Atribuído - Técnico`: Técnico ou grupo responsável pelo atendimento.
* `Categoria`: Classificação do chamado.
* `Tempo para Solução`: Prazo estimado ou meta para resolução (SLA).
* **Seleção:** Permite selecionar chamados individualmente ou todos de uma vez para ações em massa.

### 2.3 Controles de Paginação
**Controles de Paginação:**
* Localizados abaixo da tabela.
* **Linhas por Página:** Dropdown para selecionar quantos chamados serão exibidos por página (Ex: 15, 30, 50).
* **Navegação:** Informa o total de chamados encontrados e permite navegar entre as páginas de resultados.


## 3. 

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
