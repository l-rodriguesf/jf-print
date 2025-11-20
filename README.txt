# 🧾 JF — Print Solutions

## 💡 Sobre o Projeto
O **JF Print Solutions** é um site institucional desenvolvido como parte do Projeto Integrador do curso de Análise e Desenvolvimento de Sistemas.  
O objetivo é oferecer uma presença online moderna e funcional para a empresa, destacando seus serviços de manutenção, formatação, venda de cartuchos e suporte técnico, facilitando o contato com clientes e fortalecendo sua imagem no mercado local.

---

## 🎯 Tema, Objetivo e Público-Alvo

**Tema:** Prestação de serviços em informática e manutenção de equipamentos.  
**Objetivo:** Promover os serviços oferecidos pela JF, permitir que clientes encontrem informações de forma rápida e incentivar o contato direto com a empresa.  
**Público-alvo:** Usuários domésticos, pequenas empresas e escritórios locais que buscam manutenção e suporte técnico confiáveis para computadores, impressoras e periféricos.

---

## 🎨 Justificativas de Design (Figma)

O design do site foi planejado com foco em **clareza, profissionalismo e usabilidade**, refletindo o caráter técnico da empresa e a confiança necessária em serviços de informática.

- **Cores:** tons de azul e cinza foram escolhidos para transmitir **tecnologia, confiança e seriedade**.  
- **Tipografia:** fontes simples e legíveis (como *Poppins* ou *Roboto*), escolhidas pela **boa leitura em telas** e **aparência moderna**.  
- **Layout:** estrutura limpa e direta, com menu reduzido e foco no conteúdo principal, facilitando a navegação.  
- **Ícones e botões:** adotados para reforçar as seções e chamadas de ação (CTA) de forma intuitiva.  
- **Usabilidade:** o design é responsivo e adaptado para diferentes tamanhos de tela, garantindo boa experiência tanto no desktop quanto no celular.

🔗 **Protótipo no Figma: https://www.figma.com/design/bDYLMX3PtHDRjDS60YsxHe/Sem-t%C3%ADtulo?node-id=0-1&t=jNK9o4iSILlJ6Yjq-1**

---

## 🖥️ Estrutura do Projeto
JF-print/
│
├── index.html → Página inicial  
├── sobre.html → Página “Sobre Nós”  
├── servicos.html → Página de serviços  
├── contato.html → Página de contato
│
├── componentes/
│ └── footer.html → footer modularizado
│ └── header.html → header modularizado    
│
├── css/  
│ └── style.css → Arquivo principal de estilos
│ └── responsive.css → Arquivo de responsividade  
│  
│
├── img/  
│ ├── logo.webp → Logotipo da empresa  
│ ├── aluguel.webp - Imagem para informação de Aluguel de Impressoras  
│ ├── cartucho-1.webp - Imagem do Cartucho para venda  
│ ├── cartucho-2.webp - Imagem do Cartucho 2 para venda  
│ ├── formatacao.webp - Imagem ilustrativa de formatação  
│ ├── toner-samsung.webp - Imagem do Toner para venda
│ ├── favicon.png - Imagem da logo para miniatura
│
├── docs/
│   ├── testes-navegadores/  
│   │   ├── teste-chrome.jpeg → Teste no Navegador Chrome  
│   │   └── teste-edge → Teste no Navegador Edge  
│   └── testes-responsividade/  
│       ├── Desktop-Full-HD.jpeg → Responsividade em Desktop Full HD  
│       ├── Desktop-HD.jpeg → Responsividade em Desktop HD
│       ├── Ipad.jpeg → Responsividade em Ipad
│       ├── Ipad-Pro.jpeg → Responsividade em Ipad Pro
│       ├── Iphone-12-Pro.jpeg → Responsividade em Iphone 12 Pro
│       └── Iphone-SE.jpeg → Responsividade em Iphone SE
│
│├── JF PRINT SOLUTIONS - Rubrica Atualizado.docx - documento Rubrica
│
│
└── README.md → Documentação do projeto

---

## ⚙️ Tecnologias Utilizadas
- **HTML5** — Estrutura semântica e acessível  
- **CSS3** — Estilização responsiva e consistente  
- **Figma** — Planejamento visual e prototipagem  
- **Git & GitHub** — Controle de versão e publicação (GitHub Pages)

---

## 🚀 Etapas Realizadas

| Data | Etapa | Responsável |
|------|-------|--------------|
| 10/10/2025 | Definição do tema e escopo do projeto | Leonardo e Pedro Lacerda |
| 11/10/2025 | Criação do protótipo no Figma | Pedro Lacerda |
| 13/10/2025 | Desenvolvimento das páginas HTML e CSS | Leonardo |
| 14/10/2025 | Ajustes visuais e responsividade | Leonardo e Pedro Lacerda |
| 15/10/2025 | Publicação no GitHub Pages e documentação parcial | Leonardo |
| 28/10/2025 | Início da modularização do header e footer para padronização entre páginas | Leonardo |
| 02/11/2025 | Criação e integração do arquivo responsive.css para centralizar regras de responsividade | Leonardo e Pedro Lacerda|
| 15/10/2025 | Revisão final da modularização e otimização dos estilos globais | Leonardo |
| 15/10/2025 | Publicação no GitHub Pages e atualização da documentação para a parte 2 | Leonardo |
| 13/11/2025 | Implementação do Formspree para envio de mensagens pelo formulário | Leonardo |
| 18/11/2025 | Otimização do SEO e de performance, adicionando meta tags e compressão das imagens | Leonardo |


---

## 🧩 Melhorias Implementadas na Parte 2

### 🔹 Componentes Modularizados
Foram modularizados os componentes **header** e **footer**, pois se repetiam em todas as páginas.  
Essa mudança garantiu **maior consistência visual**, **redução de código repetido** e **facilidade de manutenção**.  
Além disso, permitiu que qualquer atualização no menu de navegação ou nas informações de rodapé seja refletida automaticamente em todo o site.  

O processo de modularização também envolveu a **organização das regras de responsividade** dentro desses componentes, o que tornou o código mais limpo e centralizado.  
Essas modificações tornaram o projeto **mais escalável**, favorecendo futuras implementações como menus dinâmicos ou interações com JavaScript.

---

### 🔹 Ajustes de Acessibilidade
- Uso de **tags semânticas** (header, nav, main, footer) para melhorar a leitura por tecnologias assistivas.  
- Inclusão de **textos alternativos (alt)** em todas as imagens.  
- Verificação do **contraste de cores** e ajuste conforme boas práticas WCAG.  
- Hierarquia de títulos revisada para garantir estrutura coerente.  

Essas melhorias reforçam a preocupação com **usabilidade e inclusão digital**.

---

### 🔹 Ajustes de Responsividade
A responsividade já estava presente desde a primeira versão, mas agora foi **modularizada** junto aos componentes principais (header e footer).  
As regras de estilo foram otimizadas com **media queries específicas** para diferentes tamanhos de tela, garantindo melhor desempenho e organização.  

O resultado é um site com **layout fluido e adaptável**, preservando a boa experiência em dispositivos móveis e desktops.

---

### 🔹 Integrações Externas
- **Google Maps:** já adicionado na página de contato, exibindo a localização da loja de forma interativa.  
- **Botão de WhatsApp:** ainda não implementado, mas previsto para versões futuras.  
- **Formulário de Contato:** planejado para integração futura via **Formspree**.  

Essas integrações aumentam a interação entre cliente e empresa e ampliam o alcance do site.

---

## ⚙️ Justificativas Técnicas
As decisões técnicas buscaram equilibrar **simplicidade, eficiência e boa manutenção do código**:

- **HTML5 + CSS3:** base sólida e compatível com todos os navegadores modernos.  
- **Modularização:** melhora a produtividade e reduz erros futuros.  
- **Figma:** facilitou a definição da identidade visual e o alinhamento entre design e código.  
- **Integrações leves (iframe e links):** otimizam o site sem comprometer a performance.  

---

## 🧩 Desafios Encontrados e Soluções

| Desafio | Solução Aplicada |
|----------|------------------|
| Ajuste do iframe do Google Maps, que ultrapassava a área de exibição | O problema foi resolvido no **CSS**, aumentando os valores em pixels e ajustando o comportamento responsivo para evitar cortes em diferentes tamanhos de tela. |
| Repetição de conteúdo entre páginas | Modularização do **header** e **footer**, aplicando o mesmo código de base em todo o site. |
| Organização da responsividade | Centralização das regras dentro dos módulos, facilitando ajustes futuros. |

---

## Testes Realizados

**Navegadores testados:**
- Google Chrome  
- Brave (Chromium-based)  
- Microsoft Edge  
- Safari Mobile  

**Dispositivos e resoluções testadas:**
- iPhone 16 Pro Max  
- iPhone 12  
- iPhone 14 Pro Max  
- Samsung S24+  
- Desktop Full HD (1920x1080)

**Problemas encontrados e soluções adotadas:**
- Não foram identificados problemas de exibição ou funcionamento nos dispositivos e navegadores testados.

**Limitações conhecidas:**
- Até o momento, nenhuma limitação relevante foi identificada.


      ## 🧩 Reflexão Individual - Leonardo ##
**-Aprendizados Técnicos:
Durante o projeto, desenvolvi melhor minhas habilidades em HTML e CSS, especialmente na organização do código e na estruturação semântica das páginas. O conceito mais desafiador foi compreender boas práticas de responsividade e modularização, mas ao longo do desenvolvimento consegui evoluir bastante nisso. Hoje tenho um domínio muito maior sobre estrutura de pastas, versionamento com Git e organização geral do front-end em comparação ao início do trabalho.

**-Aprendizados de Processo:
Trabalhar em dupla foi uma experiência positiva, mas desafiadora. Tivemos que alinhar horários, dividir responsabilidades e manter a comunicação clara para evitar retrabalho. A organização das tarefas funcionou bem através de checkpoints e alinhamentos rápidos, o que deixou o fluxo de produção mais eficiente. A metodologia colaborativa ajudou bastante a manter o foco e distribuir melhor as atividades.

**-Desafios Enfrentados:
O maior desafio do projeto foi lidar com partes do código que exigiam mais atenção técnica, além de sincronizar a evolução do trabalho entre os integrantes. Superamos isso através de comunicação constante e revisão conjunta. Se eu pudesse voltar no tempo, teria investido mais tempo inicial no planejamento e na definição da estrutura do projeto, o que teria evitado alguns ajustes posteriores.

      ## 🧩 Reflexão Individual — Pedro Henrique L. Frota ##
**-Aprendizados Técnicos
Desenvolvi e fortaleci habilidades em HTML semântico, CSS para estilização e responsividade, organização de código e modularização de componentes. Também aprimorei minha capacidade de criar layouts consistentes, navegáveis e com boa usabilidade, além do uso correto de formulários e links externos (WhatsApp e Instagram).
O conceito mais desafiador foi a responsividade completa, garantindo que grids, flexboxes e espaçamentos funcionassem bem em diferentes tamanhos de tela sem comprometer a estética ou a experiência do usuário.
Comparado ao início do projeto, hoje tenho maior domínio na criação de estruturas limpas, componentes reutilizáveis, layouts responsivos e um design visual mais coerente, facilitando a manutenção e melhorando a experiência do usuário.

**-Aprendizados de Processo
Trabalhar em dupla permitiu dividir tarefas e combinar ideias, mas exigiu coordenação constante para evitar conflitos de código e inconsistências de design.
As tarefas foram organizadas com responsabilidades claras — como HTML, CSS ou testes de responsividade — e a comunicação foi mantida por mensagens e revisões frequentes, garantindo alinhamento entre os integrantes.
O que mais funcionou na metodologia da dupla foi a colaboração ativa, a troca contínua de feedback e a revisão mútua do código, o que elevou a qualidade final do projeto e reduziu erros.

**-Desafios Enfrentados
O maior desafio foi manter todas as páginas visualmente coerentes, especialmente ao trabalhar com componentes reutilizáveis e diferentes seções que precisavam seguir o mesmo padrão estrutural e estético.
Superamos isso ao padronizar o uso de classes, manter um arquivo de estilos centralizado e revisar cada página comparando elementos como cabeçalho, espaçamentos, tipografia e componentes, garantindo uniformidade.
Se pudesse voltar no tempo, investiria em um planejamento inicial mais detalhado, incluindo um guia de estilos e um mapa de componentes, o que tornaria a construção das páginas mais rápida e evitaria retrabalhos na fase final. Isso também facilitaria uma divisão de tarefas ainda mais eficiente.

            --## ⚙️ Reflexão da dupla
**-Evolução do Projeto
O projeto evoluiu significativamente desde a Parte 1. Começamos com uma estrutura mais simples e, ao longo das etapas, aprimoramos a organização do código, a semântica do HTML, o design, além de implementar melhorias em acessibilidade e responsividade. As maiores mudanças foram justamente a reestruturação do layout, a padronização dos componentes e a melhoria da navegação. No geral, o resultado final atende bem à proposta inicial, entregando um site funcional, organizado e alinhado às necessidades do pequeno negócio escolhido.

**-Feedbacks Recebidos
Os feedbacks dos colegas foram importantes para identificar pontos que não tínhamos percebido. Entre eles, os mais úteis foram as sugestões sobre acessibilidade, estruturação de pastas e alguns ajustes de responsividade. Esses pontos ajudaram a melhorar a experiência do usuário e a tornar o código mais claro. Pretendemos aplicar essas sugestões em futuras versões, mantendo o foco em uma arquitetura mais modular e acessível.

**-Relevância para o Negócio
Acreditamos que o site realmente agregaria valor ao pequeno negócio escolhido, oferecendo uma presença digital clara, simples e direta, com informações acessíveis ao cliente. Se apresentássemos o projeto ao dono do negócio, destacaríamos a facilidade de navegação, a organização e a possibilidade de expansão futura. Usaríamos o projeto como parte do portfólio, pois ele demonstra domínio de conceitos fundamentais, boa estruturação e evolução ao longo das etapas.


## 🧭 Próximos Passos

- Adicionar **botão de WhatsApp flutuante** para contato rápido.  
- Inserir **JavaScript** em seções específicas para dinamismo e interatividade.  

---

## 👨‍💻 Autores
**Leonardo Rodrigues e Pedro Henrique Lacerda Frota**  
Graduandos em Análise e Desenvolvimento de Sistemas  
Projeto Integrador — 2025/2

🔗 **Repositório GitHub:** https://github.com/l-rodriguesf/jf-print.git  
🌐 **Site publicado (GitHub Pages):** https://l-rodriguesf.github.io/jf-print/servicos.html
