# 🏠 KitNet OS — Dashboard de Gestão

Dashboard premium para gestão de kitnets com dark mode, avatares pixel art e gráficos interativos.

## 🚀 Setup Rápido

### 1. Instalar dependências
```bash
npm install
```

### 2. Configurar Supabase (opcional)
```bash
cp .env.example .env.local
# Edite .env.local com suas credenciais do Supabase
```

Execute o SQL em `src/lib/supabase.js` no Supabase SQL Editor para criar as tabelas.

### 3. Rodar localmente
```bash
npm start
```

### 4. Deploy na Vercel
```bash
# Via CLI:
npx vercel --prod

# Ou conecte o repositório no dashboard da Vercel
# Adicione as variáveis de ambiente no painel da Vercel:
# REACT_APP_SUPABASE_URL
# REACT_APP_SUPABASE_ANON_KEY
```

## 🔐 Modo Editor
- PIN padrão: **1234**
- Altere `EDITOR_PIN` em `src/lib/data.js`
- Somente o editor pode adicionar/remover transações

## 🎨 Funcionalidades
- 📊 Dashboard com 4 gráficos (Recharts)
- 💰 Cards animados com contador
- 🏢 Gestão de kitnets com status em tempo real
- 👥 Avatares pixel art 8-bit dos sócios
- 📈 Gráfico de payback com break-even automático
- 🔒 Sistema de PIN para controle de edição
- 🗄️ Integração Supabase pronta

## 🛠 Stack
- React 18 + Tailwind CSS
- Recharts para gráficos
- Supabase para backend
- Fontes: Rajdhani + DM Sans + JetBrains Mono
