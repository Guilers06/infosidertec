# INFOSIDERTEC - Landing Page

Landing page institucional da Infosidertec, desenvolvida com Bootstrap 5 e tema claro/escuro.

## Tecnologias

- **HTML5** - Estrutura semântica
- **CSS3** - Variáveis CSS, animações, transições
- **Bootstrap 5.3.2** - Grid system e componentes
- **Bootstrap Icons 1.11.1** - Ícones
- **Google Fonts** - Inter + JetBrains Mono
- **JavaScript** - Tema dinâmico, scroll reveal, counters

## Estrutura do Projeto

```
.
├── index.html          # Landing page principal
├── assets/
│   └── img/            # Imagens (logos, ícones)
│       ├── logo.png
│       ├── 2logo.png
│       ├── 4logo.png
│       ├── 5logo.png
│       └── 6logo.png
└── README.md           # Este arquivo
```

## Seções da Página

1. **Hero** - Apresentação principal com estatísticas animadas
2. **Serviços** - Grid de 8 cards com ícones
3. **Detalhes dos Serviços** - Infraestrutura, Segurança e Help Desk
4. **CTA** - Chamada para contato
5. **Por que escolher a Infosidertec?** - 4 diferenciais
6. **Contato** - Formulário + informações de contato
7. **Footer** - Links, redes sociais e WhatsApp

## Funcionalidades

| Feature | Descrição |
|---------|-----------|
| Dark/Light Mode | Toggle no navbar, salvo em `localStorage` |
| Scroll Reveal | Animações de entrada ao rolar a página |
| Stagger Cards | Cards aparecem em sequência com delay |
| Counter Animation | Números incrementais no Hero |
| Smooth Scroll | Navegação suave entre seções |
| WhatsApp Float | Botão flutuante → `wa.me/5511957458422` |
| Form Submit Simulado | Feedback visual de envio no formulário |

## Cores

### Dark Theme
- Background: `#050505`
- Primary: `#1a9cb8` (azul tech)
- Primary Light: `#2bc5e0`

### Light Theme
- Background: `#f4f6f9`
- Cards: `rgba(255, 255, 255, 0.85)`
- Texto: `#1a1a2e`

## Como Usar

1. Abra o `index.html` diretamente no navegador
2. Para desenvolvimento local, use um servidor estático:
   ```bash
   # Python
   python3 -m http.server 8080

   # Node.js
   npx serve .
   ```
3. Acesse `http://localhost:8080`

## Personalização

- **WhatsApp:** Altere o número no link `wa.me/` no final do HTML
- **Cores:** Edite as variáveis CSS nos blocos `[data-theme="dark"]` e `[data-theme="light"]`
- **Logo:** Substitua `assets/img/logo.png` pela imagem desejada
- **Imagens Unsplash:** Troque as URLs do Unsplash nas seções de detalhes por imagens próprias
