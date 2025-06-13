# Conceito de Design do Site de Viagem - Florianópolis para Atacama

## 1. Estrutura do Site

### Páginas Principais:
- **Home/Landing Page**: Apresentação da viagem com hero visual impactante
- **Itinerário**: Timeline interativa dos 7 dias de viagem
- **Orçamento**: Breakdown detalhado dos custos
- **Destinos**: Seções dedicadas a Santiago e Atacama
- **Dicas de Viagem**: Informações práticas e recomendações

### Navegação:
- Menu horizontal fixo no topo
- Navegação suave entre seções (single-page application)
- Menu mobile responsivo (hamburger)

## 2. Conceito Visual

### Paleta de Cores:
- **Primária**: Azul profundo (#1e3a8a) - representando o céu do Atacama
- **Secundária**: Laranja quente (#f97316) - representando o pôr do sol no deserto
- **Terciária**: Verde esmeralda (#059669) - representando as paisagens chilenas
- **Neutros**: Branco (#ffffff), Cinza claro (#f8fafc), Cinza escuro (#334155)

### Tipografia:
- **Headings**: Fonte moderna sans-serif (Inter ou similar) - peso 700-800
- **Body**: Fonte legível sans-serif (Inter ou similar) - peso 400-500
- **Accent**: Fonte script elegante para elementos especiais

### Estilo Visual:
- Design moderno e minimalista
- Uso extensivo de imagens de alta qualidade
- Cards com sombras suaves e bordas arredondadas
- Gradientes sutis para backgrounds
- Ícones line-art personalizados

## 3. Elementos Interativos

### Animações e Transições:
- Parallax scrolling no hero section
- Fade-in animations para elementos ao scroll
- Hover effects em cards e botões
- Transições suaves entre seções (0.3s ease)

### Componentes Interativos:
- Timeline interativa do itinerário
- Calculadora de orçamento dinâmica
- Galeria de imagens com lightbox
- Mapa interativo dos destinos
- Formulário de contato com validação

### Micro-interações:
- Botões com efeito ripple
- Loading states animados
- Progress indicators
- Tooltips informativos

## 4. Layout e Responsividade

### Desktop (1200px+):
- Layout em grid de 12 colunas
- Sidebar fixa para navegação rápida
- Conteúdo principal centralizado (max-width: 1200px)

### Tablet (768px - 1199px):
- Layout adaptado para 2 colunas
- Menu colapsável
- Cards reorganizados em grid 2x2

### Mobile (320px - 767px):
- Layout single-column
- Menu hamburger
- Cards empilhados verticalmente
- Botões touch-friendly (min 44px)

## 5. Seções Detalhadas

### Hero Section:
- Background: Imagem panorâmica do Atacama com overlay
- Título principal: "Aventura Épica: Florianópolis ao Atacama"
- Subtítulo: "7 dias, 2 pessoas, R$ 10.000"
- CTA button: "Explore o Itinerário"
- Elementos flutuantes: Ícones de avião, montanha, sol

### Itinerário Timeline:
- Timeline vertical interativa
- Cada dia como um card expansível
- Ícones representativos para cada atividade
- Imagens de preview para cada destino
- Estimativa de custos por dia

### Seção Orçamento:
- Gráfico de pizza interativo
- Breakdown por categoria (voos, hospedagem, alimentação, atividades)
- Comparação com orçamento original
- Dicas de economia

### Galeria de Destinos:
- Grid masonry de imagens
- Hover effects com informações
- Lightbox para visualização ampliada
- Filtros por destino (Santiago/Atacama)

## 6. Tecnologias e Implementação

### Frontend:
- HTML5 semântico
- CSS3 com Flexbox e Grid
- JavaScript vanilla (ES6+)
- Animações CSS e JavaScript
- Responsive design (mobile-first)

### Recursos Especiais:
- Intersection Observer para animações
- CSS Custom Properties para temas
- Local Storage para preferências
- Service Worker para cache (opcional)

## 7. Acessibilidade

- Contraste adequado (WCAG AA)
- Navegação por teclado
- Alt text para imagens
- ARIA labels para elementos interativos
- Foco visível em elementos interativos

## 8. Performance

- Otimização de imagens (WebP quando possível)
- CSS e JS minificados
- Lazy loading para imagens
- Preload de recursos críticos
- Compressão gzip

Este conceito visa criar uma experiência imersiva e informativa que inspire os usuários a realizar esta viagem, apresentando todas as informações de forma visualmente atrativa e funcionalmente eficiente.

