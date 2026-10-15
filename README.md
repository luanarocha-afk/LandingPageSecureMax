# Secure Max — Documentação do Projeto

**Curso:** Análise e Desenvolvimento de Sistemas  
**Disciplina:** Programação Web — 1ª fase  
**Projeto:** Landing page da Secure Max — Segurança Eletrônica  
**Tecnologias utilizadas:** HTML5 e CSS3

---

# PÁGINA 1 — Documentação técnica da landing page

## 1. Apresentação do projeto

Este projeto consiste em uma landing page desenvolvida para apresentar os serviços da **Secure Max — Segurança Eletrônica**, empresa do irmão da autora. O trabalho foi realizado como atividade acadêmica da disciplina de Programação Web, na primeira fase do curso de Análise e Desenvolvimento de Sistemas.

A página foi pensada para apresentar a empresa de forma moderna, organizada e profissional, destacando seus serviços e oferecendo ao visitante um caminho simples para solicitar um orçamento pelo WhatsApp.

## 2. Objetivos da página

- Apresentar a Secure Max e sua proposta de segurança eletrônica.
- Divulgar os principais serviços de instalação e proteção.
- Reforçar a importância de um trabalho cuidadoso e preciso nas instalações.
- Facilitar o contato entre possíveis clientes e a empresa.
- Aplicar conhecimentos iniciais de HTML e CSS em um projeto prático.

## 3. Estrutura do HTML

O documento utiliza `<!DOCTYPE html>` para indicar HTML5 e `<html lang="pt-BR">` para informar que o conteúdo está em português do Brasil. No `<head>`, foram definidos a codificação UTF-8, a configuração de visualização para dispositivos móveis, o título da página e a importação da fonte Montserrat. As regras CSS estão inseridas no próprio arquivo, dentro de duas tags `<style>`.

### Principais tags utilizadas

| Tag | Função no projeto |
|---|---|
| `<!DOCTYPE html>` | Declara o tipo de documento como HTML5. |
| `<html>` | Elemento raiz da página; define o idioma com `lang="pt-BR"`. |
| `<head>` | Reúne metadados, título, fonte externa e estilos. |
| `<meta>` | Define a codificação de caracteres e a configuração responsiva da tela. |
| `<title>` | Define o título exibido na aba do navegador. |
| `<link>` | Conecta a página aos recursos externos da fonte Montserrat. |
| `<style>` | Contém as regras CSS de aparência e adaptação da página. |
| `<body>` | Abriga o conteúdo visível da página. |
| `<header>` | Contém o cabeçalho e o menu de navegação. |
| `<nav>` | Agrupa os links de navegação “Início” e “Soluções”. |
| `<a>` | Cria links, incluindo navegação entre páginas e acesso ao WhatsApp. |
| `<section>` | Organiza o conteúdo em áreas temáticas, como apresentação, objetivo, serviços e chamada para ação. |
| `<div>` | Agrupa elementos para organização e aplicação de estilos CSS. |
| `<h1>` e `<h2>` | Apresentam títulos principais e títulos de seções/serviços. |
| `<p>` | Exibe parágrafos e descrições. |
| `<span>` | Destaca partes de textos, como “MAX” e palavras coloridas dos títulos. |
| `<img>` | Exibe a imagem da logo da Secure Max. O atributo `alt` fornece uma descrição alternativa. |
| `<svg>` e `<path>` | Desenham o ícone do WhatsApp diretamente no código, por meio de formas vetoriais. |
| `<footer>` | Exibe o rodapé com o nome da empresa e o ano. |

## 4. Quantidade e uso das tags `<div>`

O código analisado contém **24 tags de abertura `<div>` e 24 tags de fechamento `</div>`**, formando 24 elementos `div`. Elas são usadas como contêineres para organizar o conteúdo e aplicar estilos sem atribuir, por si só, um significado semântico específico.

Distribuição das `div` por classe:

| Classe ou identificação | Quantidade | Utilização |
|---|---:|---|
| `.card` | 6 | Um cartão para cada serviço divulgado. |
| `.icon` | 6 | Um contêiner para o emoji de cada serviço. |
| `.label` | 3 | Pequenos rótulos de destaque em diferentes seções. |
| `.container nav` | 1 | Organiza a área de navegação do cabeçalho. |
| `.container hero-content` | 1 | Organiza o conteúdo principal de apresentação. |
| `div` sem classe | 1 | Agrupa o texto principal dentro da área de apresentação. |
| `.security-icon` | 1 | Exibe o símbolo de confirmação na apresentação. |
| `.small-title` | 1 | Exibe o texto “SEGURANÇA ELETRÔNICA”. |
| `.logo-area` | 1 | Reserva a área de exibição da logo. |
| `.container objective-content` | 1 | Organiza o conteúdo da seção de objetivo. |
| `.container services-grid` | 1 | Organiza a grade de cartões de serviços. |
| `.container` | 1 | Centraliza o conteúdo da chamada para orçamento. |
| **Total** | **24** | **Soma dos elementos `div` encontrados no código.** |

## 5. Organização visual das seções

- **Cabeçalho (`header`):** mostra o nome da marca e os links de navegação.
- **Apresentação (`hero`):** apresenta a mensagem principal, uma descrição curta e a logo.
- **Objetivo (`objective`):** comunica o compromisso da empresa com tecnologia, planejamento e instalação profissional.
- **Apresentação dos serviços (`services-header` e `services`):** introduz e lista os serviços em cartões.
- **Chamada para ação (`cta`):** convida o visitante a solicitar um orçamento.
- **Atalho do WhatsApp (`whatsapp`):** fica fixo no canto inferior da tela para facilitar o contato.
- **Rodapé (`footer`):** apresenta a identificação da empresa e o ano.

---

# PÁGINA 2 — Identidade visual e apresentação da empresa

## 6. A empresa Secure Max — Segurança Eletrônica

A Secure Max é apresentada neste projeto como uma empresa voltada à segurança eletrônica. A landing page tem como finalidade explicar visualmente os serviços oferecidos e facilitar o contato de pessoas interessadas em proteger suas residências, empresas e patrimônios.

Os serviços destacados na página são:

1. **Câmeras de segurança:** sistemas de monitoramento para acompanhar e proteger o ambiente.
2. **Alarmes:** soluções para ampliar a segurança e alertar sobre situações suspeitas.
3. **Cercas elétricas:** proteção perimetral para diferentes tipos de propriedades.
4. **Controle de acesso:** recursos para controlar a entrada e a saída de pessoas.
5. **Interfones:** equipamentos que facilitam a comunicação e o controle de acesso.
6. **Fechaduras eletrônicas:** soluções modernas para controlar o acesso com praticidade.

A proposta do conteúdo é destacar a precisão e o cuidado necessários na instalação dos equipamentos. A página também reforça a ideia de que tecnologia, planejamento e instalação profissional contribuem para ambientes mais seguros.

## 7. Identidade visual e cores

O visual utiliza uma combinação de verde-escuro, verde vibrante, branco e tons de cinza. A intenção é transmitir tecnologia, confiança, modernidade e segurança, mantendo os textos legíveis sobre o fundo escuro.

| Cor | Código utilizado | Aplicação observada |
|---|---|---|
| Verde-escuro | `#061b16` | Fundo principal da página. |
| Verde vibrante | `#29e38b` | Destaques da marca, títulos, ícones e elementos interativos. |
| Verde do botão WhatsApp | `#25d366` | Fundo do atalho flutuante do WhatsApp. |
| Verde mais claro | `#54efa5` | Efeito visual do botão ao passar o cursor. |
| Branco | `#ffffff` | Textos principais e preenchimento branco do ícone do WhatsApp. |
| Cinza-esverdeado claro | `#b9c9c4` | Links do menu. |
| Cinza-esverdeado | `#aebfba`, `#9eb0aa` e `#91a59e` | Textos descritivos e parágrafos secundários. |
| Verde quase preto | `#041711` | Texto do botão principal. |

Além dessas cores, o CSS utiliza valores `rgba(...)` para criar transparências, sombras e sobreposições. Uma camada verde-escura semitransparente sobre a imagem de fundo reduz seu destaque e ajuda a manter a leitura do conteúdo.

## 8. Fonte, layout e responsividade

A fonte **Montserrat** é carregada por meio do Google Fonts. Seus diferentes pesos ajudam a estabelecer hierarquia entre títulos, textos de apoio, menu e botões.

O CSS utiliza recursos como:

- **Flexbox (`display: flex`):** alinha e distribui elementos, como os itens do cabeçalho e o conteúdo dos ícones.
- **CSS Grid (`display: grid`):** organiza o conteúdo principal em colunas e os serviços em uma grade.
- **`max-width` e `width`:** controlam a largura dos elementos e ajudam a manter o conteúdo organizado.
- **`border-radius`:** arredonda os cartões, botões e elementos visuais.
- **`transition` e `transform`:** criam transições e efeitos ao passar o cursor sobre botões e cartões.
- **`@keyframes`:** define animações, como a pulsação do símbolo de segurança e do WhatsApp, além do movimento suave dos ícones dos serviços.
- **`@media`:** adapta o layout a telas menores. A grade de serviços passa de três colunas para duas e, em telas ainda menores, para uma coluna. O conteúdo principal também passa a ser organizado em uma coluna.

A regra `scroll-behavior: smooth` deixa a rolagem da página mais suave. A imagem de fundo é aplicada com `background-size: cover` e `background-position: center`, para preencher a área e manter o enquadramento central.

## 9. Ícone e contato pelo WhatsApp

A página possui um botão flutuante do WhatsApp fixado próximo ao canto inferior direito. Ele é construído com a tag `<a>` e contém um desenho vetorial feito com `<svg>` e `<path>`, em vez de depender de uma imagem externa ou de uma biblioteca de ícones.

O botão utiliza a cor verde `#25d366`, o símbolo branco, bordas arredondadas e uma animação de pulsação para chamar a atenção. O efeito `:hover` aumenta levemente o tamanho do botão.

O link utiliza o formato `https://wa.me/` com o número de contato e uma mensagem previamente preenchida. A página também possui um botão “Solicitar orçamento” que abre uma conversa pelo WhatsApp. Assim, o visitante pode entrar em contato sem precisar procurar manualmente o número da empresa.

## 10. Tecnologias e aprendizado

O projeto foi desenvolvido com **HTML5 e CSS3**, sem utilizar JavaScript no código apresentado. O HTML define a estrutura e o conteúdo, enquanto o CSS controla cores, tipografia, posicionamento, espaçamentos, animações e adaptação a diferentes tamanhos de tela.

A atividade permitiu aplicar conceitos introdutórios de desenvolvimento web, como:

- estruturação semântica de uma página;
- criação de links e inclusão de imagens;
- organização de conteúdo com contêineres;
- aplicação de classes e seletores CSS;
- uso de cores e tipografia para construir uma identidade visual;
- criação de layouts com Flexbox e Grid;
- adaptação responsiva com consultas de mídia;
- inclusão de um atalho de contato com SVG e link externo.

## 11. Considerações finais

A landing page da Secure Max foi criada para apresentar os serviços de segurança eletrônica de maneira clara, visual e acessível. O projeto combina uma identidade visual escura com destaques em verde, cartões de serviços, animações sutis e acesso rápido ao WhatsApp.

Como trabalho da primeira fase de Análise e Desenvolvimento de Sistemas, ele demonstra a aplicação prática dos fundamentos de HTML e CSS em uma necessidade real: divulgar os serviços de uma empresa e facilitar a comunicação com possíveis clientes.

---

**Observação:** esta documentação descreve o código HTML/CSS fornecido para análise. O código da landing page não foi alterado. Para entregar o projeto, mantenha o arquivo HTML original e este `README.md` juntos na pasta do projeto.
