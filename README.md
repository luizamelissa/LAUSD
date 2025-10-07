# LAUSD

🔒 CyberSec Analytics

Um site web moderno e interativo dedicado à análise de segurança cibernética, apresentando o estudo de caso do ataque ransomware ao Distrito Escolar Unificado de Los Angeles (LAUSD).


📋 Sobre o Projeto

Este projeto apresenta uma análise detalhada do ataque de ransomware que atingiu o segundo maior distrito escolar dos Estados Unidos em setembro de 2023. O site foi desenvolvido com foco em design moderno, interatividade avançada e experiência do usuário otimizada.

🎯 Objetivos

•
Educacional: Apresentar as fases de um ataque cibernético de forma didática

•
Informativo: Documentar o caso real do ataque ao LAUSD

•
Técnico: Demonstrar controles de segurança e medidas preventivas

•
Visual: Criar uma experiência web moderna e envolvente

✨ Características Principais

🎨 Design Moderno

•
Design System Profissional com variáveis CSS customizadas

•
Paleta de cores azul harmoniosa e acessível

•
Tipografia moderna usando Inter (Google Fonts)

•
Layout responsivo adaptável a todos os dispositivos

•
Glassmorphism e efeitos de profundidade

🚀 Interatividade Avançada

•
Cursor trail personalizado que segue o movimento do mouse

•
Loading screen animado com spinner customizado

•
Scroll reveal animations com timing perfeito

•
Parallax background sutil para profundidade

•
Ripple effects nos cliques dos elementos

•
Hover states sofisticados com transformações 3D

📱 Experiência do Usuário

•
Navegação flutuante com efeito glassmorphism

•
Smooth scrolling otimizado

•
Active navigation highlighting baseado na posição

•
Mobile-first approach com navegação adaptativa

•
Performance otimizada com throttled scroll events

🏗️ Estrutura do Projeto

Plain Text


cybersecurity-website/
├── index.html          # Arquivo principal com HTML, CSS e JavaScript
├── README.md           # Documentação do projeto
└── .git/              # Controle de versão Git


📖 Conteúdo

1. 🏫 Caso de Estudo: LAUSD

•
Contexto: Segundo maior distrito escolar dos EUA

•
Impacto: 500 GB de dados pessoais comprometidos

•
Atacante: Vice Society (gangue especializada em educação)

•
Consequências: Dados vazados na dark web após recusa de pagamento

2. ⚡ Fases do Ataque Cibernético

1.
Reconhecimento - Coleta de informações públicas

2.
Enumeração - Descoberta de serviços e vulnerabilidades

3.
Acesso Inicial - Primeiro ponto de entrada

4.
Escalonamento - Elevação de privilégios

5.
Movimento Lateral - Expansão na rede

6.
Ação no Objetivo - Execução do ataque principal

7.
Persistência - Manutenção de acesso e limpeza de rastros

3. 🛡️ Controles de Segurança

•
Técnicos: Firewalls, EDR, criptografia, backups

•
Administrativos: Políticas, procedimentos, treinamento

•
Físicos: Videomonitoramento, controle de acesso, alarmes

4. 📚 Referências

•
Arctic Wolf - Cyber Attacks Against Schools

•
BleepingComputer - LAUSD Data Leak Coverage

•
CBS News - Ransomware Attack Reporting

•
Material didático acadêmico

🛠️ Tecnologias Utilizadas

Frontend

•
HTML5 - Estrutura semântica moderna

•
CSS3 - Estilização avançada com:

•
CSS Custom Properties (variáveis)

•
Flexbox e CSS Grid

•
Animations e Transitions

•
Media Queries responsivas



•
JavaScript ES6+ - Interatividade com:

•
Intersection Observer API

•
RequestAnimationFrame

•
Event Listeners otimizados

•
Smooth scrolling nativo



Fontes

•
Inter - Tipografia principal (Google Fonts)

•
JetBrains Mono - Código e elementos técnicos

Recursos Visuais

•
Gradientes CSS personalizados

•
SVG patterns para backgrounds

•
Box shadows em múltiplas camadas

•
Backdrop filters para glassmorphism

🚀 Como Executar

Método 1: Servidor Local

Bash


# Clone o repositório
git clone <repository-url>
cd cybersecurity-website

# Inicie um servidor HTTP local
python -m http.server 8000
# ou
npx serve .
# ou
php -S localhost:8000


Método 2: Abrir Diretamente

Bash


# Abra o arquivo diretamente no navegador
open index.html
# ou no Windows
start index.html


Método 3: Live Server (VS Code)

1.
Instale a extensão "Live Server"

2.
Clique com botão direito em index.html

3.
Selecione "Open with Live Server"

📱 Compatibilidade

Navegadores Suportados

•
✅ Chrome 90+

•
✅ Firefox 88+

•
✅ Safari 14+

•
✅ Edge 90+

Dispositivos

•
📱 Mobile: iPhone, Android (320px+)

•
📱 Tablet: iPad, Android tablets (768px+)

•
💻 Desktop: Todas as resoluções (1024px+)

•
🖥️ Large screens: 4K e ultrawide (1440px+)

🎯 Funcionalidades Técnicas

Performance

•
Lazy loading de animações

•
Throttled scroll events para otimização

•
RequestAnimationFrame para animações suaves

•
CSS transforms em vez de propriedades que causam reflow

Acessibilidade

•
Contraste adequado (WCAG 2.1 AA)

•
Navegação por teclado funcional

•
Semântica HTML apropriada

•
Alt texts em elementos visuais

SEO

•
Meta tags otimizadas

•
Estrutura HTML semântica

•
Heading hierarchy apropriada

•
Schema markup para conteúdo educacional

🔧 Personalização

Cores

As cores podem ser facilmente modificadas através das variáveis CSS no :root:

CSS


:root {
    --primary-blue: #0066ff;
    --secondary-blue: #004dd9;
    --accent-blue: #3388ff;
    /* ... outras variáveis */
}


Animações

Ajuste a velocidade das animações modificando as propriedades transition e animation:

CSS


.scroll-reveal {
    transition: all 0.8s cubic-bezier(0.4, 0, 0.2, 1);
}


Layout

O layout responsivo pode ser ajustado através dos breakpoints:

CSS


@media (max-width: 768px) {
    /* Estilos mobile */
}


📊 Métricas de Performance

•
First Contentful Paint: < 1.5s

•
Largest Contentful Paint: < 2.5s

•
Cumulative Layout Shift: < 0.1

•
First Input Delay: < 100ms

🤝 Contribuição

Como Contribuir

1.
Fork o projeto

2.
Crie uma branch para sua feature (git checkout -b feature/AmazingFeature)

3.
Commit suas mudanças (git commit -m 'Add some AmazingFeature')

4.
Push para a branch (git push origin feature/AmazingFeature)

5.
Abra um Pull Request

Padrões de Código

•
HTML: Semântico e acessível

•
CSS: BEM methodology para classes

•
JavaScript: ES6+ com comentários descritivos

•
Commits: Conventional Commits format

📝 Licença

Este projeto foi desenvolvido para fins educacionais sobre segurança cibernética. O conteúdo é baseado em fontes públicas e materiais acadêmicos.

👥 Autor

Desenvolvido como projeto educacional para demonstrar:

•
Técnicas modernas de desenvolvimento web

•
Princípios de UX/UI design

•
Conhecimentos em segurança cibernética

•
Boas práticas de desenvolvimento frontend

📞 Suporte

Para dúvidas ou sugestões sobre o projeto:

•
📧 Abra uma issue no repositório

•
💬 Entre em contato através dos canais apropriados

•
📖 Consulte a documentação técnica




⚠️ Aviso Legal: Este site é destinado exclusivamente para fins educacionais. As informações sobre ataques cibernéticos são apresentadas para conscientização sobre segurança digital e não devem ser utilizadas para atividades maliciosas.




<div align="center">

🔒 CyberSec Analytics - Educação em Segurança Cibernética




















</div>

