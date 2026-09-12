# 🛒 Lista de Mercado Fácil

Uma aplicação web simples, acessível e funcional desenvolvida em **HTML5, CSS3 e JavaScript puro (Vanilla JS)** focada na praticidade para gerenciamento de estoque doméstico e controle de compras de supermercado.

O projeto foi desenhado focando em **Experiência do Usuário (UX) e Acessibilidade**, com atenção especial a facilidades de leitura e uso por pessoas de idade mais avançada.

🔗 **Links do Projeto:**
* 🌐 **Testar Aplicação (GitHub Pages):** [https://renepadua.github.io/listadosupermercado/](https://renepadua.github.io/listadosupermercado/)
* 📦 **Repositório do Código (GitHub):** [https://github.com/RenePadua/listadosupermercado](https://github.com/RenePadua/listadosupermercado)

---

---

## 🌟 Principais Funcionalidades

1. **Gestão Inteligente de Estoque:**
   * Controle de quantidade mantida em casa vs. quantidade a comprar.
   * Ao finalizar as compras, os itens adquiridos somam automaticamente ao estoque de casa e a lista é zerada.

2. **Navegação Simples (Foco em Usabilidade/Acessibilidade):**
   * Fontes grandes, contraste elevado (Modo Escuro) e botões de toque generosos.
   * **Modos de Visualização:**
     * 🛒 *Falta Pegar:* Itens pendentes de compra.
     * ✅ *Já Peguei:* Itens marcados no carrinho durante o mercado.
     * 🏠 *Ver lista completa:* Visão geral do cadastro.
   * Seções colapsáveis (Cards recolhíveis) para economizar espaço e evitar poluição visual.

3. **Backup e Compartilhamento via WhatsApp (Zero Custo / 100% Client-Side):**
   * **Exportar:** Transforma toda a lista em um código codificado (Base64) e abre no WhatsApp para envio a si mesmo ou familiares/cuidadores.
   * **Importar/Restaurar:** Permite colar o texto recebido do WhatsApp para carregar e sincronizar a lista inteira instantaneamente.
   * Funciona sem necessidade de banco de dados externo ou servidor.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica.
* **CSS3:** Layout responsivo (Flexbox), CSS Variables para temas e Dark Mode nativo.
* **JavaScript (Vanilla):** Lógica da aplicação, manipulação do DOM e persistência de dados.
* **LocalStorage:** Armazenamento local no navegador do dispositivo.
* **WhatsApp Deep Links (Web Intent):** Integração com o WhatsApp para compartilhamento sem dependência de APIs pagas.
