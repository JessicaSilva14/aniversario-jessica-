🚀 Projeto 27 Anos — Front-end Moderno & Performance
📄 Descrição
O projeto "27 Anos" é uma landing page moderna e responsiva construída para celebrar um evento especial, destacando-se pela implementação de um contador regressivo (countdown) em tempo real desenvolvido em JavaScript dinâmico.

O principal foco deste projeto foi a aplicação de boas práticas de desenvolvimento front-end, utilizando pré-processamento de estilos com SASS e uma esteira de automação e empacotamento de alto desempenho com o Parcel Bundler para garantir carregamento rápido e otimização de assets.

🛠️ Tecnologias e Ferramentas
O projeto foi construído utilizando o seguinte ecossistema de ferramentas:

HTML5 — Estrutura semântica e acessível.

SASS (SCSS) — Estilização avançada com arquitetura modular, variáveis e mixins.

JavaScript (ES6+) — Lógica de manipulação do DOM e cálculo matemático do countdown.

Parcel Bundler — Compilação de scripts, minificação de código, otimização de imagens e bundling ultra-rápido.

⚙️ Arquitetura e Diferenciais Técnicos
1. Performance & Bundling (Parcel)
Em vez de depender de configurações complexas, o Parcel foi adotado por sua velocidade e capacidade de entregar arquivos de produção altamente otimizados.

Minificação Automática: Redução drástica no tamanho dos arquivos CSS e JS finais.

Hot Module Replacement (HMR): Ambiente de desenvolvimento ágil com atualizações em tempo real no navegador (através do servidor local do Opera/VS Code).

2. Estilização Avançada com SASS
A estilização não utiliza CSS puro e estático. Foi aplicada uma estrutura escalável com SASS:

Modularização: Separação de arquivos de estilo para manter o código limpo e de fácil manutenção.

Mixins & Variáveis: Centralização da paleta de cores, tipografia e regras de responsividade (media queries), garantindo consistência visual em dispositivos mobile e desktop.

3. Lógica do Countdown (JavaScript)
A engrenagem principal da página é um script personalizado que calcula a diferença de tempo milissegundo por milissegundo, atualizando os campos de dias, horas, minutos e segundos no DOM sem causar gargalos de renderização (re-flows desnecessários).

🚀 Como Executar o Projeto
Pré-requisitos
Antes de começar, você vai precisar ter instalado em sua máquina o Node.js e um gerenciador de pacotes (npm).

Passo a Passo

git clone https://github.com/seu-usuario/projeto-27-anos.git
cd projeto-27-anos
npm install
npm run dev
# ou o comando específico configurado no seu package.json (ex: npx parcel index.html)
npm run build

Isso criará uma pasta dist/ com todo o código minificado, imagens otimizadas e pronto para deploy.

📂 Estrutura de Pastas Principais
├── src/
│   ├── assets/       # Imagens e mídias otimizadas
│   ├── styles/       # Arquivos SASS (.scss) organizados por módulos
│   └── js/           # Script do contador e manipulação do DOM
├── index.html        # Arquivo HTML principal (ponto de entrada do Parcel)
├── package.json      # Dependências e scripts de automação
└── README.md         # Documentação do projeto

👤 Autora
Jessica Silva — GitHub / LinkedIn
