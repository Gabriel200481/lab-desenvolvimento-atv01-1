# Ideias de Design - Portfólio Profissional

## Abordagem Escolhida: Modern Minimalist with Accent

### Design Movement
**Modern Minimalism com Acentos Funcionais** - Inspirado em portfolios contemporâneos de desenvolvedores e designers, com foco em clareza, hierarquia visual e interatividade sutil.

### Core Principles
1. **Hierarquia Clara**: Tipografia estratégica com contraste entre títulos em negrito e corpo em peso regular
2. **Espaço Respirável**: Uso generoso de whitespace para criar elegância e foco no conteúdo
3. **Acentos Funcionais**: Cores vibrantes (azul-índigo) apenas onde há interação ou destaque importante
4. **Responsividade Elegante**: Layout fluido que se adapta graciosamente em todos os dispositivos

### Color Philosophy
- **Fundo**: Branco limpo (quase branco) com leve toque de cinza para profundidade
- **Texto Principal**: Cinza escuro/charcoal para legibilidade confortável
- **Acentos**: Azul-índigo vibrante (#3B82F6) para CTAs, links e destaques
- **Secundário**: Cinza médio para elementos menos importantes
- **Intenção Emocional**: Profissionalismo, confiança e modernidade

### Layout Paradigm
- **Hero Section**: Assimétrico com apresentação pessoal à esquerda e elemento visual à direita
- **Seções Alternadas**: Conteúdo alterna entre lado esquerdo/direito para evitar monotonia
- **Grid Flexível**: Projetos em grid responsivo (1-3 colunas conforme viewport)
- **Navegação Fixa**: Header sticky com navegação clara e logo/nome

### Signature Elements
1. **Linha de Acentuação**: Barra vertical azul-índigo ao lado de seções principais
2. **Cards com Hover Elevado**: Efeito de profundidade ao passar o mouse (sombra suave)
3. **Ícones Funcionais**: Lucide React para redes sociais, tecnologias e ações

### Interaction Philosophy
- **Transições Suaves**: Todas as mudanças de estado com transição de 300ms
- **Feedback Visual**: Hover states claros em botões e links
- **Scroll Animations**: Elementos aparecem suavemente ao entrar no viewport
- **Formulário Responsivo**: Validação em tempo real com feedback visual

### Animation
- **Entrance**: Fade-in + slide-up leve (200ms) para elementos ao carregar
- **Hover**: Scale 1.05 em cards, mudança de cor em links
- **Scroll**: Parallax suave em hero section, fade-in em seções
- **Loading**: Spinner animado para formulário de contato

### Typography System
- **Display**: Geist Sans Bold (700) - Títulos principais, h1, h2
- **Heading**: Geist Sans SemiBold (600) - Subtítulos, h3
- **Body**: Geist Sans Regular (400) - Corpo de texto, descrições
- **Accent**: Geist Mono (400) - Tags de tecnologia, código
- **Hierarchy**: h1 (32px) → h2 (24px) → h3 (18px) → body (16px)

---

## Estrutura de Páginas

### Home (Landing)
- Hero com apresentação pessoal
- Destaque de skills principais
- CTA para seções principais

### About (Sobre Mim)
- Apresentação bilíngue (PT/EN)
- Timeline de formação
- Skills com ícones
- Interesses profissionais

### Projects (Projetos)
- Timeline visual dos projetos
- Cards com imagem, descrição, tecnologias
- Links para GitHub e demo

### Experience (Experiências)
- Lista de experiências profissionais
- Estágios, freelas, open source
- Período e descrição

### Contact (Contato)
- Ícones clicáveis para redes sociais
- Formulário de contato funcional
- Feedback visual de envio

---

## Implementação Técnica
- **Framework**: React 19 + TypeScript
- **Styling**: Tailwind CSS 4 + Custom CSS para animações
- **Componentes**: shadcn/ui para consistência
- **Ícones**: Lucide React
- **Animações**: Framer Motion para scroll/entrance
- **Formulário**: React Hook Form + Zod para validação
