# Mamoti - Website Corporativo

Website corporativo para a Mamoti, empresa especializada em governança e gestão de TI.

## Sobre o Projeto

Este projeto é um website responsivo desenvolvido para apresentar os serviços e a visão da Mamoti, uma empresa focada em:

- Desenvolvimento de software de monitoramento e gestão empresarial
- Soluções personalizadas para o mercado B2B
- Governança e gestão de TI
- Consultoria técnica especializada

## Estrutura do Projeto

```
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # JavaScript para interatividade
├── logo-mamoti.svg     # Logotipo oficial da Mamoti
├── README.md           # Documentação do projeto
└── .github/
    └── copilot-instructions.md
```

## Características

### Design
- Design moderno e responsivo
- Paleta de cores profissional (azul/roxo)
- Typography limpa usando a fonte Inter
- Animações suaves e efeitos de transição
- Layout otimizado para desktop e mobile

### Seções
1. **Header/Navegação** - Menu fixo com navegação suave
2. **Hero Section** - Apresentação principal da empresa
3. **Sobre** - Descrição da empresa e diferenciais
4. **Serviços** - Cards com os principais serviços oferecidos
5. **Nossa Visão** - Objetivos e estatísticas da empresa
6. **Reflexões** - Perguntas críticas sobre governança de TI
7. **Contato** - Formulário de contato e informações
8. **Footer** - Links e informações adicionais

### Funcionalidades
- Navegação suave entre seções
- Menu hambúrguer para dispositivos móveis
- Formulário de contato com validação
- Animações de entrada nos elementos
- Efeitos de hover e transições
- Contadores animados na seção de visão
- Design totalmente responsivo

## Como Executar

1. Abra o arquivo `index.html` em qualquer navegador web
2. Ou use um servidor local para desenvolvimento:
   ```bash
   # Com Python
   python -m http.server 8000
   
   # Com Node.js (usando npx)
   npx serve .
   ```

## Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos e responsividade
  - CSS Grid e Flexbox
  - Gradientes e animações
  - Media queries para responsividade
- **JavaScript** - Interatividade
  - Intersection Observer API
  - Event listeners
  - Validação de formulário
  - Animações dinâmicas

## Responsividade

O site é totalmente responsivo e foi testado em:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (até 767px)

## Customização

### Cores
As cores principais podem ser alteradas no arquivo `styles.css`:
- Primária: `#667eea` (azul)
- Secundária: `#764ba2` (roxo)
- Gradiente: `linear-gradient(135deg, #667eea 0%, #764ba2 100%)`

### Conteúdo
Todo o conteúdo pode ser editado diretamente no arquivo `index.html`.

### Imagens
As imagens estão usando placeholders. Substitua os elementos `.placeholder-image` por imagens reais.

## Melhorias Futuras

- Integração com backend para formulário de contato
- Sistema de blog/notícias
- Galeria de projetos/cases
- Integração com redes sociais
- Otimização SEO
- Implementação de analytics

## Licença

Este projeto foi desenvolvido para a Mamoti. Todos os direitos reservados.

---

**Desenvolvido para Mamoti - Transformando a Gestão de TI**
