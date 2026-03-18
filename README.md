# 🗓️ NETDA Staff Allocator

Um dashboard interativo e inteligente para alocação de membros de equipa a horários e funções de eventos, com suporte para arrastar-e-soltar e exportação para Excel.

---

## 🚀 Funcionalidades Principais

### 1. 📥 Importação e Gestão de Equipa
*   **Importação via Excel**: Suporte a ficheiros `.xlsx` / `.csv` (via SheetJS) arrastando para um _Dropzone_.
*   **Visualização Modular (Chips)**: Visualização compacta e moderna dos membros com friso de cor lateral associado ao departamento.
*   **Filtros Inteligentes**: Segmented Controls estilo iOS para alternar a ordenação por _Adição_, _Nome (A-Z)_ ou _Área/Prioridade_ (Direção > Marketing > etc).
*   **Adição Manual**: Formulários internos sem sobrecarga para introduzir novos elementos "on the fly".

### 2. ⚙️ Configuração do Evento
*   **Gestão de Cargos/Funções**: Adicione funções de uma lista de predefinições ou invente uma nova de raiz.
*   **Dimensionamento Rápido**: Botões `+` e `-` para alterar a quota de vagas de cada posto sem acionamentos acidentais de edição.
*   **Vínculo com Áreas**: Permite acoplar uma função a um Departamento/Área (_Nenhuma_ por defeito) para dar preferência a membros dessa área.
*   **Timeline Incremental**: Botão automático _+ Próxima Hora_ para criar blocos sequenciais sem introdução manual repetitiva.

### 3. 🧩 Alocação Dinâmica
*   **Alocação Inteligente**: Um algoritmo de 1 clique distribui a equipa avaliando compatibilidades de área e balanceando a carga de trabalho de forma justa.
*   **Mesa Giratória e Magnetismo**: Drag & Drop ultra-rápido (via SortableJS) com inclinação física de 4º e _shadow casting_ nos cartões para maior feedback tátil.
*   **Montagem e Desmontagem Fixas**: Espetros de alocação de fundo/topo dedicados imitam o Setup e Teardown de portas com travões lógicos de vagas.
*   **Correção "Midnight Crossing"**: Suporte nativo e ordenação contínua para eventos que atravessam a meia-noite (ex: 23:00 terminando às 04:00 da manhã).

### 4. 📊 Exportação
*   **Relatório Excel**: Gera um ficheiro rico com títulos estilizados, cores por departamento, e uma leitura horizontal das horas, pronto para imprimir e afixar.

---

## 🛠️ Tecnologias e Dependências

A aplicação foi construída sob uma arquitetura de **Ficheiro Único (HTML/CSS/JS)** sem necessidade de servidores ou compiladores. 

*   **Lucide Icons**: Fontes de ícones minimalistas.
*   **SheetJS (XLSX.js)**: Leitura de ficheiros de Excel.
*   **ExcelJS**: Criação do ficheiro de exportação estilizado.
*   **SortableJS**: Comportamento Drag and Drop.

---

## 🏃 Como Correr / Build

1. **Abrir `index.html`**: Basta dar duplo-clique no ficheiro `index.html` em qualquer navegador web moderno (Chrome, Edge, Safari, Brave, Firefox).
2. Não há dependências de pacotes `node_modules` nem comandos de terminal.

---

## 🎨 Modos de Cores

*   **Dark Mode Nativo**: Suporte para alternar esquema de cores escuro/claro no canto superior direito para melhor legibilidade em ambientes nocturnos.
