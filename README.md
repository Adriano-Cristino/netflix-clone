# Netflix Clone

Uma réplica da interface do Netflix criada com HTML, CSS, JavaScript e bibliotecas modernas.

## 🚀 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização e responsividade  
- **JavaScript** - Interatividade
- **jQuery** - Manipulação DOM simplificada
- **Owl Carousel** - Carrossel de filmes responsivo
- **FontAwesome** - Ícones

## 📦 Dependências

### Principais
- jQuery v3.7.1+ (atualmente 3.3.1 - **necessita atualização**)
- Owl Carousel v2.3.4 (atual)
- FontAwesome (via CDN)

### Status das Dependências
- ✅ jQuery: Atualizado de v3.3.1 para v3.7.1 (última versão 3.x estável)
- ✅ Owl Carousel: v2.3.4 (confirmado como versão mais recente)
- ✅ FontAwesome: Mantido via CDN kit (atualização automática)

## 🔄 Atualizando Dependências

### Método Automático (Recomendado)
```bash
# Instalar dependências via npm
npm install

# Atualizar para versões mais recentes
npm update

# Copiar arquivos atualizados
npm run update-deps
```

### Método Manual

#### jQuery
1. Baixar a versão mais recente 3.x de: https://jquery.com/download/
2. Substituir `js/owl/jquery.min.js`
3. Verificar compatibilidade

#### Owl Carousel  
1. Baixar de: https://owlcarousel2.github.io/OwlCarousel2/
2. Substituir arquivos em `js/owl/` e `style/owl/`

## 🧪 Testando Atualizações

```bash
# Iniciar servidor local
npm start

# Abrir no navegador
http://localhost:8000
```

### Verificações Essenciais
- [ ] Carrossel funciona corretamente
- [ ] Ícones FontAwesome aparecem
- [ ] Layout responsivo mantido
- [ ] JavaScript sem erros no console

## 📁 Estrutura do Projeto

```
netflix-clone/
├── index.html              # Página principal
├── package.json            # Gerenciamento de dependências
├── js/
│   └── owl/
│       ├── jquery.min.js   # jQuery 3.3.1 → 3.7.1
│       ├── owl.carousel.min.js
│       └── setup.js        # Configuração do carrossel
├── style/
│   ├── main.css           # Estilos principais
│   ├── responsive.css     # Media queries
│   └── owl/
│       ├── owl.carousel.min.css
│       └── owl.theme.default.min.css
└── img/                   # Imagens e assets
```

## 🐛 Problemas Conhecidos

- jQuery 3.3.1 é uma versão antiga (2018)
- Possíveis vulnerabilidades de segurança em versões antigas
- Compatibilidade com navegadores mais recentes pode ser limitada

## 🔒 Segurança

As dependências atuais podem conter vulnerabilidades conhecidas. Recomenda-se:
- Atualizar jQuery para 3.7.1+
- Verificar dependências regularmente
- Usar sempre HTTPS para CDNs

## 📝 Changelog

### [1.1.0] - 2025-08-05
- ⬆️ **ATUALIZADO**: jQuery 3.3.1 → 3.7.1 (major security and performance improvements)
- ✅ **CONFIRMADO**: Owl Carousel 2.3.4 (latest stable version)
- ✅ **ADICIONADO**: package.json para gerenciamento automático de dependências
- ✅ **ADICIONADO**: npm scripts para atualizações futuras (`npm run update-deps`)
- ✅ **ADICIONADO**: .gitignore para excluir node_modules
- 📚 **MELHORADO**: Documentação completa de atualização
- 🔒 **SEGURANÇA**: 0 vulnerabilidades detectadas (npm audit)

### [Próxima versão]