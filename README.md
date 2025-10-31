# Template Nuxt 4.1.3 + Supabase + Tailwind CSS

Um template completo para iniciar projetos com **Nuxt 4.1.3**, **@nuxtjs/supabase** e **@nuxtjs/tailwindcss**.

## 🚀 Tecnologias

- **Nuxt 4.1.3** - Framework Vue.js full-stack
- **@nuxtjs/supabase** - Integração com Supabase (autenticação e banco de dados)
- **@nuxtjs/tailwindcss** - Framework CSS utilitário
- **TypeScript** - Tipagem estática
- **Vue 3.5.22** - Framework reativo

## 📋 Pré-requisitos

- Node.js (versão 18+)
- Conta no [Supabase](https://supabase.com)

## 🛠️ Configuração

1. **Clone o repositório:**
```bash
git clone https://github.com/IsraelHenriquee/template-nuxt-supabase-tailwind.git
cd template-nuxt-supabase-tailwind
```

2. **Instale as dependências:**
```bash
npm install
```

3. **Configure as variáveis de ambiente:**
```bash
cp .env.example .env
```

Edite o arquivo `.env` com suas credenciais do Supabase:
```env
SUPABASE_URL="https://seu-projeto.supabase.co"
SUPABASE_KEY="sua-chave-aqui"
```

## 🚀 Desenvolvimento

Inicie o servidor de desenvolvimento:

```bash
npm run dev
```

A aplicação estará disponível em `http://localhost:3000`.

## 📜 Scripts Disponíveis

- `npm run dev` - Servidor de desenvolvimento
- `npm run build` - Build para produção
- `npm run preview` - Preview do build
- `npm run generate` - Geração de site estático

## 🔧 Configurações

### Supabase
- Redirecionamento automático desabilitado (`redirect: false`)
- Suporte a cookies SSR habilitado
- Pronto para autenticação PKCE

### Tailwind CSS
- Configurado com classes utilitárias
- Pronto para customização

## 📚 Documentação

- [Nuxt 4 Documentation](https://nuxt.com/docs)
- [@nuxtjs/supabase](https://supabase.nuxtjs.org)
- [@nuxtjs/tailwindcss](https://tailwindcss.nuxtjs.org)
- [Supabase Docs](https://supabase.com/docs)

## 📄 Licença

Este projeto é um template open-source. Sinta-se livre para usar e modificar.
