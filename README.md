#Automação de Cadastro de Produtos com PyAutoGUI#

Este projeto automatiza o cadastro de produtos em um site utilizando PyAutoGUI e Pandas.

O script:
* Abre o navegador automaticamente
*Acessa a página de login
*Realiza o login
*Lê um arquivo produtos.csv (≈300 linhas)
*Preenche e envia o formulário de cadastro para cada produto
*Tudo de forma 100% automática, simulando teclado e mouse.

🛠 Tecnologias utilizadas
- Python
- PyAutoGUI
- Pandas
- 📄 Arquivo CSV
* O arquivo produtos.csv deve conter colunas como:
codigo
marca
tipo
categoria
preco_unitario
custo
obs (opcional)

⚠️ Observações
* As coordenadas do mouse (moveTo) dependem da resolução da tela
* O navegador deve estar configurado em tela cheia
* O script usa sleep para garantir o carregamento correto das páginas
 
🎯 Objetivo
- Praticar automação, manipulação de dados com Pandas e integração entre scripts Python e interfaces gráficas.
