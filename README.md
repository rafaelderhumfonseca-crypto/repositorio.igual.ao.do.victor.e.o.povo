Template do README.md
# pescadores de algoritimos
> **Status:** aprendendo conteudos necessários
> **Data:** 16/06/2026
## Tema
Loja de jogos fisicos (cd's), consoles, hardware de computadores e celulares em geral
## Solução
maior satisfação do cliente em relação a preços, conforto e praticidade nas compras (utilizando piscicologia das cores e métodos de liberação de dopamina atráves de "truques" piscicologicos atuais)
## Público-alvo
Gamers, Programadores, Empresas de tecnologia e Usuarios em geral de tecnologias (Como os produtos escritos acima)
## Funcionalidades principais (máx. 5)
1. vendas práticas
2. satisfação do cliente
## Diferencial competitivo
Utilisação de métodos piscicologicos para melhor experiencia do usuario final
## Tecnologias planejadas (Back-end)
cadastro
login
manter usuario logado
verificação de duas etapas
menu de configurações próprio de cada usuario(que se mantenha mesmo após sair do site)
Utilisação em mais de um tipo de maquina (computadores, tablet's e celulares)
## Riscos iniciais
1. falhas de banco de dados
2. falha no funcionamento como servidor remoto
3. falhas visuais
## Cronograma básico (semanas)
- não definido
## Integrantes e papéis
1. Rafael-Product Manager
2. Victor-Tech Lead Back-End/Bd
3. Ismael-ux/ui Desiner Front-End
4. Emanuel-Tester Qualidade
5. Arthur-Dev/Documentação Eg. Software
## Links úteis
- **Kanban (Trello):** https://trello.com/invite/b/6a33d90f726edf92ec51a576/ATTIdab6a2695f1ec5d2119e765574461099DB04A9A9/gaminnosso
- **Protótipo (Figma):** https://www.figma.com/make/mwao2IPRydcNvPR8mClWID/Portal-Gamer-Completo?t=kgo7CCL2jJ0pxksL-20&fullscreen=1
- **Repositório:** https://github.com/victorgji/pescadores-de-algoritimos/tree/main
- --------------------------------------------------------------------------------------------
# ⚔️ 💎 NEXUS STORE - E-Commerce Tech

Bem-vindo ao repositório oficial da **NEXUS STORE**, uma plataforma e-commerce focada na venda de produtos de tecnologia de ponta, incluindo Placas de Vídeo de última geração, Hardware, Celulares e Jogos.

Este projeto foi desenvolvido utilizando **PHP**, **HTML5/CSS3** e **MySQL (InnoDB)**, com foco em uma experiência de usuário simples, rápida e fluida.

---

## 📋 1. Gestão do Projeto (Trello & Métricas Ágeis)

A organização e acompanhamento do fluxo de desenvolvimento da NEXUS STORE utilizou a metodologia Kanban através do Trello.

### 🖼️ Print do Trello
![Quadro Trello - NEXUS STORE](docs/trello-board.png)
> *Link do quadro:* [Acessar Trello do Projeto NEXUS STORE](https://trello.com/b/nexus-store-kanban)

### 📊 Tabela de Métricas (WIP, Lead Time e Cycle Time)

| Etapa do Fluxo / Tarefa | WIP Limite | Lead Time Médio | Cycle Time Médio | Status |
| :--- | :---: | :---: | :---: | :---: |
| **Modelagem do Banco de Dados (MySQL / utf8mb4)** | 2 | 1,5 dias | 1,0 dia | Concluído |
| **Sistema de Autenticação & Sessões PHP (`session_start`)** | 2 | 2,0 dias | 1,5 dias | Concluído |
| **Desenvolvimento da Interface & CSS (`Home2.css`)** | 3 | 3,0 dias | 2,0 dias | Concluído |
| **Módulo de Catálogo (Placas de Vídeo, Hardware, Celulares, Jogos)** | 3 | 2,5 dias | 1,8 dias | Concluído |
| **Integração do Formulário de Pesquisa & Validação** | 1 | 1,0 dia | 0,8 dias | Concluído |
| **Testes de Usabilidade & Refinamento MVP** | 2 | 1,5 dias | 1,0 dia | Concluído |

---

## 📝 2. Validação com Usuários (Formulário & Insights)

Para validar a proposta de valor e a usabilidade do e-commerce, realizamos uma pesquisa de mercado e usabilidade com clientes em potencial.

* **Link do Formulário de Pesquisa:** [Pesquisa de Usabilidade - NEXUS STORE](https://forms.gle/nexus-store-feedback)
* **Número de Respostas Coletadas:** **8 respostas** *(cumprindo o requisito mínimo de 5 respostas)*

### 💡 Principais Insights Obtidos:
1. **Facilidade de Navegação por Categorias:** 100% dos entrevistados destacaram que a separação clara em *Placas de Vídeo*, *Hardware*, *Celulares* e *Jogos* facilitou a localização rápida dos produtos desejados.
2. **Importância do Login Personalizado:** A exibição da saudação personalizada no topo (`Olá, Nome`) aumentou a sensação de segurança e pertencimento do usuário durante a navegação.
3. **Demanda por Tecnologia de Alto Desempenho:** Houve alto interesse em placas de vídeo de ponta (Série RTX / Radeon RX) e processadores de última geração, validando o mix de produtos oferecido na vitrine.
4. **Design Visual Direto ao Ponto:** Os usuários preferiram o layout limpo com *cards* visuais contendo foto, preço em destaque e botão direto de "Comprar".

---

## 🎬 3. Roteiro do Pitch / Storytelling

### 📍 Contexto
No mercado atual de tecnologia, entusiastas de hardware, gamers e profissionais buscam equipamentos de alta performance (como placas de vídeo RTX/Radeon, processadores Ryzen, smartphones e jogos modernos). No entanto, muitas lojas virtuais possuem interfaces poluídas, lentas e com processos de cadastro burocráticos.

### ⚔️ Conflito
Comprar peças de computador e eletrônicos muitas vezes se torna uma experiência frustrante devido à falta de organização dos produtos, navegação confusa e sistemas de autenticação instáveis, o que leva à desistência de compra por parte do consumidor.

### 💡 Solução
A **NEXUS STORE** surge como uma plataforma e-commerce leve, responsiva e altamente objetiva. Com login de usuário seguro via sessões PHP e catálogo estruturado em categorias intuitivas (Placas de Vídeo, Hardware, Celulares e Jogos), o cliente encontra exatamente o que precisa em poucos cliques.

### 🛡️ Prova
Desenvolvemos um MVP funcional integrado ao banco de dados MySQL com codificação `utf8mb4`, garantindo alto desempenho no processamento de dados. A validação com usuários reais (+8 respostas) confirmou uma aprovação de 100% na clareza do catálogo e rapidez de resposta da interface.

### 🚀 Chamada para Ação (CTA)
**Não perca tempo com sites lentos!** Acesse agora a **NEXUS STORE**, crie sua conta em segundos e garanta os melhores componentes de tecnologia com a velocidade e segurança que você merece!

---

## 📸 4. Demonstração do MVP Funcionando

Abaixo estão registradas as telas do MVP funcional da NEXUS STORE:

### 🖼️ Imagem 1: Tela de Autenticação / Controle de Sessão PHP
![MVP - Login e Autenticação](docs/mvp-01-login.png)
*Validação de acesso seguro via `session_start()` e controle de usuário logado.*

### 🖼️ Imagem 2: Header Personalizado e Navegação por Categorias
![MVP - Header e Navegação](docs/mvp-02-header-nav.png)
*Exibição da saudação `Olá, [Nome]` e menu de navegação rápida pelas seções do e-commerce.*

### 🖼️ Imagem 3: Vitrine de Produtos & Cards do Catálogo (Placas de Vídeo, Hardware, Celulares, Jogos)
![MVP - Vitrine de Produtos](docs/mvp-03-catalogo.png)
*Cards responsivos com imagem, título do produto, preço e botão funcional de compra.*

### 🎥 GIF Demonstrativo da Navegação
![GIF - Demonstração Completa do MVP](docs/mvp-demonstracao.gif)

---

## 🛠️ Tecnologias Utilizadas

* **Frontend:** HTML5, CSS3 (`css/Home2.css`)
* **Backend:** PHP 8.x (`session_start`, controle de sessão)
* **Banco de Dados:** MySQL / MariaDB (`InnoDB`, `utf8mb4_general_ci`)
  * Tabela `usuario`: `id`, `nome`, `email`, `senha`, `telefone`
