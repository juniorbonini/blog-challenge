📸 Fotoblog | Galeria Responsiva
Projeto de uma galeria de fotos moderna e fluida, desenvolvido durante o programa Explorer da Rocketseat. O foco principal foi o domínio de estruturas complexas de layout com CSS Grid e a implementação de animações de entrada para melhorar a experiência do usuário (UX).

🧪 Tecnologias e Conceitos Aplicados
Este projeto foi construído utilizando tecnologias fundamentais da web, com foco em boas práticas:

HTML5 Semântico: Uso de tags como <main>, <section>, <figure> e <figcaption> para melhor acessibilidade e SEO.

CSS Grid Layout: Implementação de um grid de 3 colunas (repeat(3, 1fr)) com controle total de espaçamento (gap).

Variáveis CSS: Centralização da paleta de cores e controle de estados de animação através de variáveis customizadas (:root).

Animações (Keyframes): * Efeito de entrada suave com translateY no Header e Footer.

Animação de "surge" (appear) nos itens da galeria com atraso progressivo (animation-delay) via variáveis inline.

Efeitos de Hover: Transformações visuais (scale, rotate, filter) para feedback interativo ao usuário.

🚀 Como visualizar
Clone este repositório:

Bash
git clone https://github.com/juniorbonini/Links-Generator.git
Abra o arquivo index.html em seu navegador ou utilize a extensão Live Server no VS Code.

🎨 Diferenciais Técnicos (O que aprendi)
Neste projeto, foquei em resolver desafios comuns de interface:

Aspect Ratio: Uso de aspect-ratio: 16/9 para manter a consistência visual das imagens independente do tamanho original do arquivo.

Transbordamento (Overflow): Controle de rolagem apenas na área de conteúdo principal (main), mantendo o Header e Footer fixos.

Delays Dinâmicos: Aplicação de lógica de animação onde cada card aparece em um tempo diferente, criando um efeito de cascata visualmente agradável.

👤 Autor
Desenvolvido por Junior Bonini — Web & Mobile Developer

"Transformando layouts estáticos em experiências dinâmicas."
