# pizzaria-js
Sistema web desenvolvido para gestão de pizzarias de pequeno porte, com foco em controle de pedidos, estoque e finanças, utilizando exclusivamente tecnologias front-end.

# Descrição do Projeto

O **Pizzaria JS** é uma aplicação modular feita com HTML, CSS e JavaScript puro (sem back-end), que permite:

- Criação e personalização de pedidos (sabores, bebidas, tamanho, cidade);
- Acompanhamento do status do pedido em tempo real (Recebido → Preparando → Enviado → Entregue);
- Controle automático de estoque conforme pedidos realizados;
- Geração de relatórios financeiros com receitas, despesas e lucros mensais (gráficos via Chart.js);
- Persistência de dados no navegador com `localStorage`;
- Sincronização de dados entre abas com `BroadcastChannel`.

Ideal para pizzarias que precisam de um sistema leve, funcional e que funcione diretamente no navegador.

#  Instruções de Execução

1. Baixe ou clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/pizzaria-js.git

2.Navegue até a pasta do projeto:

cd pizzaria-js

3. Abra o arquivo index.html no navegador de sua preferência.

# Tecnologias Utilizadas
HTML5 – Estrutura das páginas

CSS3 – Estilização e responsividade

JavaScript (ES6+) – Lógica de funcionamento

localStorage API – Armazenamento de dados

BroadcastChannel API – Sincronização entre abas

Chart.js – Geração de gráficos financeiros

# Estrutura dos Arquivos

pizzaria-js
index.html           # Página inicial

pedido.html          # Tela de criação de pedido

pedidos.html         # Painel administrativo de pedidos

estoque.html         # Controle e visualização de estoque

financeiro.html      # Relatórios financeiros (gráficos)

resumo.html          # Tela de status de pedido (cliente)

recuperar.html       # Recuperação de pedidos

script.js            # Toda a lógica e funcionamento do sistema

styles.css           # Estilização visual centralizada

fundo.png            # Imagem de fundo

icon.png             # Ícone da aplicação


# Integrantes do Grupo
Gustavo Alexandre Silva

David Gomes Batista Neto

Renan Costa Souza

Laura Beatriz de Sena Rocha

Gustavo Henrique Barros Ribeiro

Pedro Kalebe Roque

Gustavo Oliveira

Júlia Ramiro
