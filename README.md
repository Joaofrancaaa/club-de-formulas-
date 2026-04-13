# 🧪 Acervo Digital de Fórmulas - Naturalis

Uma plataforma de *Sales Enablement* (Aceleração de Vendas) e Catálogo Digital desenvolvida sob medida para representantes da farmácia de manipulação Naturalis. 

O sistema foi desenhado com foco em **fricção zero**: permite que médicos, nutricionistas e prescritores encontrem fórmulas clínicas validadas, copiem a prescrição para seus prontuários e solicitem orçamentos via WhatsApp com apenas um clique.

## ✨ Principais Funcionalidades

* **Lâminas Técnicas Digitais:** Páginas editoriais focadas em conversão para ativos de alto valor (como PROGO®, DL-185™ e Colagenew), contendo estudos clínicos, mecanismos de ação e sugestões de fórmulas.
* **Integração Nativa com WhatsApp:** Geração de links dinâmicos que abrem o WhatsApp do representante com a mensagem pré-preenchida (ex: *"Gostaria de solicitar a fórmula X"*).
* **One-Click Copy:** Botão inteligente que formata a fórmula (ativos, dosagem, posologia e veículo) no padrão exato para o médico colar em seu software de receituário.
* **Design Editorial & Brutalista:** Interface premium focada no público médico, utilizando tipografia forte, blocos de cor e imagens panorâmicas de alta qualidade.
* **Painel Administrativo (CMS):** Sistema completo (CRUD) para gestão de categorias segmentadas (Saúde Humana, Veterinária, etc.) e fórmulas.
* **Link na Bio Otimizado:** Rota `/bio` dedicada para tráfego vindo do Instagram, substituindo ferramentas de terceiros (como Linktree) e retendo o usuário no domínio próprio.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído com as ferramentas mais modernas do ecossistema React:

* **[Next.js (App Router)](https://nextjs.org/):** Framework React para renderização híbrida (Server e Client) e roteamento avançado.
* **[TypeScript](https://www.typescriptlang.org/):** Tipagem estática para maior segurança e previsibilidade do código.
* **[Prisma ORM](https://www.prisma.io/):** Gerenciamento de banco de dados e migrações tipadas.
* **[CSS Modules](https://github.com/css-modules/css-modules):** Estilização componentizada, evitando vazamento de escopo e conflitos de CSS.
* **[React Hook Form](https://react-hook-form.com/) + [Zod](https://zod.dev/):** Validação de dados robusta no Front-end e Back-end.
* **[Lucide React](https://lucide.dev/):** Biblioteca de ícones consistente e leve.

## 🚀 Como Executar o Projeto Localmente

### Pré-requisitos
* Node.js (v18 ou superior)
* NPM ou Yarn
* Um banco de dados PostgreSQL (ou SQLite para testes rápidos)

### Instalação

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
   cd nome-do-repositorio
