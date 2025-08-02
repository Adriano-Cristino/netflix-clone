# Netflix Clone 🎬

Um clone responsivo da interface do Netflix, desenvolvido com HTML, CSS e JavaScript.

![Netflix Clone](https://github.com/user-attachments/assets/c1de3b9d-bf36-400a-a9e0-e5385bceeb6b)

## 🚀 Funcionalidades

- Interface responsiva que replica o design do Netflix
- Carrossel interativo de filmes/séries usando Owl Carousel
- Design moderno e atrativo
- Navegação funcional
- Compatível com dispositivos móveis

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura da página
- **CSS3** - Estilização e responsividade
- **JavaScript** - Funcionalidades interativas
- **jQuery 3.7.1** - Manipulação do DOM
- **Owl Carousel 2.3.4** - Carrossel de imagens
- **Font Awesome** - Ícones

## 📦 Dependências

| Biblioteca | Versão | Descrição |
|-----------|--------|-----------|
| jQuery | 3.7.1 | Biblioteca JavaScript para manipulação do DOM |
| Owl Carousel | 2.3.4 | Plugin de carrossel responsivo |
| Font Awesome | Latest | Biblioteca de ícones vetoriais |

## 🚀 Como Executar

### Pré-requisitos
- Python 3.x (para servidor local)
- Navegador web moderno

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/Adriano-Cristino/netflix-clone.git
cd netflix-clone
```

2. Inicie o servidor local:
```bash
# Usando Python
npm start
# ou
python3 -m http.server 8000
```

3. Abra o navegador e acesse:
```
http://localhost:8000
```

## 📁 Estrutura do Projeto

```
netflix-clone/
├── index.html              # Página principal
├── package.json            # Configurações do projeto
├── DEPENDENCIES.md         # Documentação das dependências
├── README.md              # Este arquivo
├── img/                   # Imagens e assets
├── js/                    # Scripts JavaScript
│   └── owl/
│       ├── jquery.min.js
│       ├── owl.carousel.min.js
│       └── setup.js
└── style/                 # Arquivos CSS
    ├── main.css
    ├── responsive.css
    └── owl/
        ├── owl.carousel.min.css
        └── owl.theme.default.min.css
```

## 🔧 Scripts Disponíveis

- `npm start` - Inicia o servidor de desenvolvimento
- `npm run serve` - Alias para npm start

## 📱 Responsividade

O projeto foi desenvolvido com foco em responsividade, funcionando perfeitamente em:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (até 767px)

## 🤝 Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👨‍💻 Autor

**Adriano Cristino**
- GitHub: [@Adriano-Cristino](https://github.com/Adriano-Cristino)

## 🎯 Próximas Melhorias

- [ ] Adicionar mais filmes/séries ao carrossel
- [ ] Implementar reprodução de trailers
- [ ] Adicionar sistema de busca
- [ ] Integração com API de filmes
- [ ] Modo escuro/claro

---

⭐ Se este projeto te ajudou, deixe uma estrela no repositório!