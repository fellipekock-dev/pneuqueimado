# Pneu Queimado | Centro Automotivo

Site institucional de um centro automotivo, desenvolvido como projeto acadêmico na disciplina de **Fundamentos de Desenvolvimento Web** do **CEET Vasco Coutinho**, sob proposta da professora **Rafaela Correia**.

[Acessar o site no GitHub Pages](https://fellipekock-dev.github.io/pneuqueimado/) · [Ver o repositório](https://github.com/fellipekock-dev/pneuqueimado)

## Sobre o projeto

A página reúne a apresentação da oficina, os serviços oferecidos, um catálogo de peças automotivas, depoimentos e canais de contato. O projeto aplica conceitos de HTML semântico, layout responsivo e manipulação do DOM em uma página única.

## Funcionalidades

- **Navegação responsiva** com menu para dispositivos móveis e links para as seções da página.
- **Serviços da oficina** com informações sobre manutenção preventiva, reparos mecânicos, freios e elétrica automotiva.
- **Catálogo de produtos** com imagens, preços e detalhes em uma janela modal.
- **Carrossel de depoimentos** com avanço automático e controles manuais.
- **Solicitação de agendamento pelo WhatsApp**. O formulário valida os campos e abre uma conversa com a mensagem preenchida. O visitante envia a solicitação pelo WhatsApp.

## Tecnologias

| Tecnologia | Uso no projeto |
| --- | --- |
| HTML5 | Estrutura da página, seções e formulário de agendamento |
| CSS3 | Estilos, layout responsivo e transições |
| JavaScript | Menu móvel, carrossel, modais e validação do formulário |
| Google Fonts e Font Awesome | Fontes Inter e Montserrat e ícones da interface |
| GitHub Pages | Hospedagem da versão online |

## Estrutura do repositório

```text
pneuqueimado/
├── index.html       # Página principal
├── css/
│   └── style.css    # Estilos do site
├── img/             # Imagens da oficina e dos produtos
├── script.js        # Interações da página
└── README.md        # Documentação do projeto
```

## Como executar localmente

1. Clone o repositório ou baixe o ZIP pelo menu **Code** no GitHub.

   ```bash
   git clone https://github.com/fellipekock-dev/pneuqueimado.git
   cd pneuqueimado
   ```

2. Abra o arquivo `index.html` no navegador. O site é estático e pode ser aberto diretamente.

### Caminho do JavaScript

Se o menu móvel, o carrossel e os modais ficarem inativos, confira a tag `<script>` no final de `index.html`. Com o arquivo `script.js` na raiz do repositório, use este caminho relativo.

```html
<script src="script.js"></script>
```

Depois de salvar, recarregue a página e teste o menu em uma janela estreita, o carrossel e o botão **Agendar Serviço**.
