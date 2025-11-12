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
│ ├── logo.png → Logotipo da empresa  
│ ├── aluguel.png - Imagem para informação de Aluguel de Impressoras  
│ ├── cartucho-1.png - Imagem do Cartucho para venda  
│ ├── cartucho-2.webp - Imagem do Cartucho 2 para venda  
│ ├── formatacao.jpeg - Imagem ilustrativa de formatação  
│ ├── toner-samsung.png - Imagem do Toner para venda  
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

## 🧭 Próximos Passos
- Implementar o **Formspree** para envio de mensagens pelo formulário.  
- Adicionar **botão de WhatsApp flutuante** para contato rápido.  
- Inserir **JavaScript** em seções específicas para dinamismo e interatividade.  
- Otimizar **SEO e performance** (meta tags, compressão de imagens e melhorias no carregamento).  

---

## 👨‍💻 Autores
**Leonardo Rodrigues e Pedro Henrique Lacerda Frota**  
Graduandos em Análise e Desenvolvimento de Sistemas  
Projeto Integrador — 2025/2

🔗 **Repositório GitHub:** https://github.com/l-rodriguesf/jf-print.git  
🌐 **Site publicado (GitHub Pages):** https://l-rodriguesf.github.io/jf-print/servicos.html
