# Arbo
Projeto Integrador da faculdade focado em inovação e sustentabilidade

map-project/                 → pasta raiz do projeto

├── web/                     → aplicação frontend (interface do usuário) feita com Angular
│
│   ├── src/                 → código-fonte principal do frontend
│   │
│   │   ├── app/             → lógica principal da aplicação Angular
│   │   │
│   │   │   ├── components/  → componentes reutilizáveis da interface (botões, cards, menus, etc)
│   │   │   ├── pages/       → páginas completas do sistema (home, mapa, login, etc)
│   │   │   └── services/    → serviços que fazem comunicação com a API e lógica compartilhada
│   │   │
│   │   ├── assets/          → arquivos estáticos usados no site
│   │   │
│   │   │   ├── images/      → imagens do projeto (logos, backgrounds, etc)
│   │   │   ├── icons/       → ícones da interface ou do mapa
│   │   │   └── styles/      → arquivos de estilo globais (CSS/SCSS)
│   │   │
│   │   └── index.html       → página base onde o Angular carrega toda a aplicação
│
├── api/                     → backend da aplicação (Java / Spring Boot)
│   │
│   └── src/                 → código-fonte do servidor (controllers, services, models, etc)
│
└── database/                → scripts e estrutura do banco de dados
                              (criação de tabelas, migrations, dados iniciais)