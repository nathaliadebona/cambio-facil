# 💱 CâmbioFácil

Conversor de moedas fictício desenvolvido do zero em **HTML, CSS e JavaScript puro**, sem frameworks ou bibliotecas de front-end.

> Projeto pessoal de estudo, construído como prática progressiva de JavaScript: captura de eventos, leitura de valores do DOM, lógica de cálculo com objetos, validação de entrada e manipulação dinâmica de conteúdo na tela.

<img width="901" height="597" alt="image" src="https://github.com/user-attachments/assets/a82c3453-b068-47a6-9064-ac5985517120" />
<img width="636" height="396" alt="image" src="https://github.com/user-attachments/assets/e8d10591-8bf3-48c7-8e82-537c36ff7bbc" />

---

## 🔗 Demo

https://nathaliadebona.github.io/cambio-facil/
`[link do site publicado]`

---

## 📋 Sobre o projeto

O CâmbioFácil é um conversor de moedas fictício voltado para quem precisa converter valores de forma rápida e sem complicação — seja para viagens, compras internacionais ou curiosidade. A proposta é uma ferramenta direta, sem jargão financeiro e sem excesso de informação.

O site é uma single page com header (logo + tagline), ferramenta de conversão em destaque, seção "Como funciona" e rodapé. A identidade visual usa azul petróleo e verde-água, transmitindo confiança e modernidade, com tipografia geométrica (Poppins) nos títulos e sans-serif neutra (Inter) no corpo.

---

## ✨ Funcionalidades

- 💱 **Converter moedas** — calcula a conversão entre BRL, USD, EUR e GBP com taxas fixas
- 🔁 **Trocar moedas** — botão ⇄ inverte as moedas de origem e destino instantaneamente
- ⌨️ **Atalho de teclado** — pressionar Enter no campo de valor dispara a conversão sem clicar no botão
- ✅ **Validação de entrada** — exibe mensagem de erro se o campo estiver vazio ou com valor inválido

---

## 🛠️ Tecnologias

- **HTML5** — marcação semântica
- **CSS3** — variáveis CSS, Flexbox, media queries, transições
- **JavaScript (Vanilla)** — manipulação do DOM, eventos, objetos, template strings
- **Google Fonts** — tipografia (Poppins, Inter)

---

## 📁 Estrutura do projeto

```
cambiofacil/
├── index.html    # Página única com toda a estrutura
├── style.css     # Estilos de todo o app
└── script.js     # Toda a lógica JavaScript
```

---

## 🎨 Paleta de cores e tipografia

| Uso | Cor |
|---|---|
| Fundo principal | `#F4F6F6` |
| Texto principal | `#2C2E2E` |
| Cor principal (header, títulos) | `#0B3D45` |
| Destaque (botões, foco) | `#3FAE9A` |

**Tipografia:** [Poppins](https://fonts.google.com/specimen/Poppins) (títulos e botões), [Inter](https://fonts.google.com/specimen/Inter) (corpo e campos)

---

## 🧠 Aprendizados

Este projeto foi construído em etapas, como prática progressiva de JavaScript:

- **`getElementById`** — seleção de elementos do DOM por id
- **`addEventListener`** — escuta de eventos (`click`, `keydown`) em elementos da página
- **`evento.key`** — leitura da tecla pressionada dentro de um evento de teclado
- **`.value`** — leitura e escrita de propriedades de inputs e selects
- **`.textContent`** — inserção de conteúdo textual dinâmico em elementos da página
- **Objetos como tabela de dados** — uso de um objeto literal (`taxas`) para mapear chaves a valores numéricos
- **Notação de colchetes `obj[variavel]`** — acesso dinâmico a propriedades de um objeto usando uma variável como chave
- **Lógica de conversão em duas etapas** — transformar o valor em "moeda ponte" (Real) antes de converter para o destino
- **`.toFixed(2)`** — formatação de números com casas decimais fixas
- **Template strings** — interpolação de variáveis em strings com crases e `${}`
- **Validação com `return` antecipado** — interrupção da função antes do cálculo quando a entrada é inválida
- **Variável temporária para swap** — troca de dois valores usando uma terceira variável auxiliar (`temp`)
- **Funções anônimas (callbacks)** — uso de funções sem nome passadas como argumento para `addEventListener`
- **Organização de variáveis no topo** — declaração única dos elementos do DOM, reutilizados em múltiplos listeners
- **Listeners independentes** — cada `addEventListener` declarado no mesmo nível, sem aninhamento
- **Media queries** — responsividade com breakpoint em 480px, ajustando layout dos selects e passos para mobile
- **Variáveis CSS** — sistema de design consistente com cores centralizadas no `:root`

---

## 🚀 Como rodar o projeto

Não há dependências ou build — é só HTML, CSS e JS puro.

```bash
# Clone o repositório
git clone https://github.com/nathaliadebona/cambio-facil.git

# Entre na pasta
cd cambiofacil

# Abra o index.html no navegador
```

Ou, se preferir, use a extensão **Live Server** do VS Code para rodar com recarregamento automático.

---

## 👩‍💻 Autoria

Desenvolvido por **Nathália** como projeto de estudo em front-end.

Github https://github.com/nathaliadebona
Portfólio https://nathaliadebona.github.io/portfolio/

---

## 📄 Licença

Este é um projeto de estudo, livre para consulta e aprendizado.
