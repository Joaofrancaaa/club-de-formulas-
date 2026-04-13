🧪 Acervo Digital de Fórmulas - Naturalis
Uma plataforma de Sales Enablement (Aceleração de Vendas) e Catálogo Digital desenvolvida sob medida para representantes da farmácia de manipulação Naturalis.

O sistema foi desenhado com foco em fricção zero: permite que médicos, nutricionistas e prescritores encontrem fórmulas clínicas validadas, copiem a prescrição para seus prontuários e solicitem orçamentos via WhatsApp com apenas um clique.

✨ Principais Funcionalidades
Lâminas Técnicas Digitais: Páginas editoriais focadas em conversão para ativos de alto valor (como PROGO®, DL-185™ e Colagenew), contendo estudos clínicos, mecanismos de ação e sugestões de fórmulas.

Integração Nativa com WhatsApp: Geração de links dinâmicos que abrem o WhatsApp do representante com a mensagem pré-preenchida (ex: "Gostaria de solicitar a fórmula X").

One-Click Copy: Botão inteligente que formata a fórmula (ativos, dosagem, posologia e veículo) no padrão exato para o médico colar em seu software de receituário.

Design Editorial & Brutalista: Interface premium focada no público médico, utilizando tipografia forte, blocos de cor e imagens panorâmicas de alta qualidade.

Painel Administrativo (CMS): Sistema completo (CRUD) para gestão de categorias segmentadas (Saúde Humana, Veterinária, etc.) e fórmulas.

Link na Bio Otimizado: Rota /bio dedicada para tráfego vindo do Instagram, substituindo ferramentas de terceiros (como Linktree) e retendo o usuário no domínio próprio.

🛠️ Tecnologias Utilizadas
Este projeto foi construído com as ferramentas mais modernas do ecossistema React:

Next.js (App Router): Framework React para renderização híbrida (Server e Client) e roteamento avançado.

TypeScript: Tipagem estática para maior segurança e previsibilidade do código.

Prisma ORM: Gerenciamento de banco de dados e migrações tipadas.

CSS Modules: Estilização componentizada, evitando vazamento de escopo e conflitos de CSS.

React Hook Form + Zod: Validação de dados robusta no Front-end e Back-end.

Lucide React: Biblioteca de ícones consistente e leve.

🛡️ Segurança e Infraestrutura
A plataforma foi desenvolvida adotando boas práticas de segurança corporativa:

Proteção de Rotas: Autenticação rigorosa e verificação de sessão para garantir que o Painel Administrativo seja restrito à equipe autorizada.

Limites de Logins: Implementação de mecanismos de rate limiting para bloquear múltiplas tentativas falhas, prevenindo ataques de força bruta.

Proteção contra Ataques: Sanitização estrita de dados utilizando Zod para evitar Injections e uso das proteções nativas do Next.js contra vulnerabilidades web comuns.

🚀 Como Executar o Projeto Localmente
Pré-requisitos
Node.js (v18 ou superior)

NPM ou Yarn

Um banco de dados PostgreSQL (ou SQLite para testes rápidos)

Instalação
Clone o repositório:

Bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
Instale as dependências:

Bash
npm install
# ou yarn install
Configure as variáveis de ambiente:
Crie um arquivo .env na raiz do projeto contendo as credenciais do seu banco de dados e as chaves de autenticação (caso use NextAuth/Supabase):

Snippet de código
DATABASE_URL="sua_url_de_conexao_aqui"
Execute as migrations do banco de dados:

Bash
npx prisma migrate dev
Inicie o servidor de desenvolvimento:

Bash
npm run dev
# ou yarn dev
A aplicação estará disponível em http://localhost:3000.

📸 Vitrine do Projeto
<table align="center">
<tr>
<td align="center" width="50%">
<img src="https://github.com/user-attachments/assets/92998e28-ba70-4693-9f97-6630707d249f" style="border-radius: 8px;" />


<sub><b>Catálogo de Fórmulas / Home</b></sub>
</td>
<td align="center" width="50%">
<img src="https://github.com/user-attachments/assets/0b5647bb-d1a1-4b6d-9159-f7aee37ccb32" style="border-radius: 8px;" />


<sub><b>Lâmina Técnica com One-Click Copy</b></sub>
</td>
</tr>
<tr>
<td align="center">
<img src="https://github.com/user-attachments/assets/fff5c22a-af9b-4d39-80fa-557f1bc12270" style="border-radius: 8px;" />


<sub><b>Acesso Administrativo Restrito</b></sub>
</td>
<td align="center">
<img src="https://github.com/user-attachments/assets/7df321e6-f86a-4b79-b2ad-56afb3576378" style="border-radius: 8px;" />


<sub><b>CMS para Gestão de Conteúdo</b></sub>
</td>
</tr>
</table>

👨‍💻 Autor
Desenvolvido por João França
