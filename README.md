# 🧪 Acervo Digital de Fórmulas — Naturalis

[![Deploy Status](https://img.shields.io/badge/status-live-success?style=flat-square)](https://club-de-formulas.vercel.app/)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![Next.js](https://img.shields.io/badge/Next.js-14-black?style=flat-square&logo=next.js)](https://nextjs.org/)

> **Sales Enablement Platform** para acelerar prescrições médicas e aumentar a conversão comercial de fórmulas manipuladas.

🔗 **[Acessar Projeto](https://club-de-formulas.vercel.app/)**

---

## 📋 Sumário

- [O Problema](#o-problema)
- [A Solução](#a-solução)
- [Funcionalidades](#funcionalidades)
- [Tech Stack](#tech-stack)
- [Como Usar](#como-usar)
- [Roadmap](#roadmap)
- [Autor](#autor)

---

## 🎯 O Problema

Profissionais da saúde enfrentam fricções significativas no processo de prescrição:

- ❌ **Médicos** gastam tempo montando prescrições manualmente
- ❌ **Representantes** têm dificuldade em converter interesse em pedidos
- ❌ **Ferramentas descentralizadas** (WhatsApp, Instagram) não se integram ao fluxo de trabalho

---

## 💡 A Solução

Uma plataforma com **fricção zero**, onde o profissional:

1. ✅ **Encontra** fórmulas validadas com lâminas técnicas
2. ✅ **Copia** a prescrição com **1 clique** (já formatada)
3. ✅ **Solicita orçamento** direto no WhatsApp

---

## ✨ Funcionalidades

### Core Features

| Feature | Descrição |
|---------|-----------|
| 📄 **Lâminas Técnicas Digitais** | Conteúdo focado em conversão com estudos clínicos e mecanismos de ação |
| ⚡ **One-Click Copy** | Copia a fórmula já formatada para prontuário médico |
| 💬 **Integração WhatsApp** | Geração automática de mensagem para o representante |
| 🧠 **Organização Inteligente** | Categorias segmentadas (Humana, Veterinária, etc.) |
| 🔐 **CMS Administrativo** | CRUD completo para gestão de fórmulas |
| 🔗 **Link na Bio** | Substitui Linktree mantendo o tráfego no domínio |

### Diferenciais

- 🎯 **Produto orientado à conversão**, não apenas CRUD
- 🔄 **Integração real** com fluxo comercial (WhatsApp)
- 🎨 **UX otimizada** para reduzir atrito do usuário final
- 📊 **Contexto de negócio real** mapeado na solução

---

## 🛠️ Tech Stack

### Frontend

- **Next.js 14** — App Router com renderização híbrida
- **React 18** — Componentes modernos com Server Components
- **TypeScript** — Tipagem estática e segurança
- **CSS Modules** — Estilização isolada e performática
- **Lucide React** — Ícones de alta qualidade

### Backend & Database

- **Prisma ORM** — Camada tipada de acesso ao banco
- **PostgreSQL / SQLite** — Banco de dados robusto
- **Next.js API Routes** — Endpoints serverless

### Form & Validation

- **React Hook Form** — Gestão eficiente de formulários
- **Zod** — Validação compartilhada (client + server)

---

## 🏗️ Arquitetura

```
src/
├── app/                    # Next.js App Router
│   ├── admin/             # Dashboard administrativo
│   ├── formulas/          # Catálogo de fórmulas
│   └── api/               # Endpoints serverless
├── components/            # Componentes reutilizáveis
├── lib/                   # Utilitários e helpers
├── types/                 # Definições TypeScript
└── styles/                # CSS Modules globais
```

### Decisões Arquiteturais

- ⚡ **Server Components** para performance e SEO
- 🔁 **Separação clara** entre Client e Server
- 📦 **Prisma** como camada única de acesso ao banco
- 🧩 **Componentização** focada em reuso
- ✅ **Validação compartilhada** (front + back com Zod)

---

## 🚀 Como Usar

### Pré-requisitos

- **Node.js** ≥ 18.0
- **npm** ou **yarn**
- **Banco de dados** (PostgreSQL recomendado)

### Instalação

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/acervo-digital-formulas.git
cd acervo-digital-formulas

# Instale as dependências
npm install

# Configure as variáveis de ambiente
cp .env.example .env.local

# Configure o banco de dados
npx prisma migrate dev

# Rode o servidor de desenvolvimento
npm run dev
```

### Variáveis de Ambiente

```env
DATABASE_URL="postgresql://user:password@localhost:5432/formulas"
NEXTAUTH_URL="http://localhost:3000"
NEXTAUTH_SECRET="seu-secret-aqui"
WHATSAPP_API_KEY="seu-key"
```

### Build para Produção

```bash
npm run build
npm start
```

---

## 📸 Galeria do Projeto

<table align="center">
  <tr>
    <td align="center" width="50%">
      <strong>Home / Catálogo de Fórmulas</strong>
      <br/>
      <em>Interface principal com busca e filtros</em>
    </td>
    <td align="center" width="50%">
      <strong>Lâmina Técnica com Prescrição</strong>
      <br/>
      <em>Detalhe com estudos clínicos e botão one-click</em>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <strong>Login / Acesso Profissional</strong>
      <br/>
      <em>Autenticação segura de usuários</em>
    </td>
    <td align="center" width="50%">
      <strong>Dashboard Administrativo (CMS)</strong>
      <br/>
      <em>CRUD para gestão de fórmulas</em>
    </td>
  </tr>
</table>

---

## 📈 Roadmap

### ✅ Implementado

- [x] Catálogo de fórmulas com filtros
- [x] Integração WhatsApp
- [x] CMS administrativo
- [x] One-click copy
- [x] Link na bio (/bio)

### 🔄 Em Progresso

- [ ] Autenticação com níveis de acesso (RBAC)
- [ ] Analytics de uso e conversão
- [ ] Dashboard de performance

### 🎯 Futuro

- [ ] 🤖 Sugestão inteligente de fórmulas (IA)
- [ ] 📱 PWA / versão mobile otimizada
- [ ] 📊 Relatórios avançados por representante
- [ ] 🔔 Notificações push
- [ ] 🌐 Suporte multilíngue

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Por favor:

1. Faça um **Fork** do projeto
2. Crie uma **branch** para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um **Pull Request**

---

## 📝 Licença

Este projeto está licenciado sob a **MIT License** — veja o arquivo [LICENSE](LICENSE) para detalhes.

---

## 👨‍💻 Autor

**João França**

---

## 📞 Suporte

Para dúvidas ou sugestões, abra uma **[Issue](https://github.com/seu-usuario/acervo-digital-formulas/issues)** ou entre em contato através do email.

---

<div align="center">

**[⬆ Voltar ao topo](#-acervo-digital-de-fórmulas--naturalis)**

Desenvolvido com ❤️ para acelerar a prescrição médica

</div>
