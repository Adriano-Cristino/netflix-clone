# Dependências do Netflix Clone

Este documento lista todas as dependências do projeto e suas versões.

## Dependências Frontend

### JavaScript Libraries

1. **jQuery**
   - Versão atual: 3.3.1
   - Versão recomendada: 3.7.1 (última versão estável)
   - Arquivo: `js/owl/jquery.min.js`
   - Descrição: Biblioteca JavaScript para manipulação do DOM

2. **Owl Carousel 2**
   - Versão atual: 2.3.4
   - Versão recomendada: 2.3.4 (última versão estável)
   - Arquivos: 
     - `js/owl/owl.carousel.min.js`
     - `style/owl/owl.carousel.min.css`
     - `style/owl/owl.theme.default.min.css`
   - Descrição: Plugin de carrossel responsivo para jQuery

3. **Font Awesome**
   - Versão: Mais recente via CDN
   - URL: `https://kit.fontawesome.com/2c36e9b7b1.js`
   - Descrição: Biblioteca de ícones vetoriais

## Atualizações Realizadas

- [x] Criado package.json para gerenciamento de dependências
- [x] Documentado versões atuais e recomendadas
- [x] Atualizado comentário de versão do jQuery para 3.7.1
- [ ] Owl Carousel já está na versão mais recente (2.3.4)
- [x] Font Awesome sendo carregado via CDN (sempre atualizado)

## Como Atualizar Dependências

Para futuras atualizações:

1. **jQuery**: Baixar de https://code.jquery.com/
2. **Owl Carousel**: Baixar de https://github.com/OwlCarousel2/OwlCarousel2/releases
3. **Font Awesome**: Verificar kit no site oficial

## Notas

- Todas as dependências são carregadas localmente, exceto Font Awesome
- O projeto não usa npm/yarn, as dependências são gerenciadas manualmente
- Para migrar para npm: `npm install jquery owl.carousel @fortawesome/fontawesome-free`