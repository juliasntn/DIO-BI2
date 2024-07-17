# Conectar o Azure MySQL ao Power BI

Este guia descreve os passos para conectar sua instância do Azure MySQL ao Power BI, permitindo que você importe dados diretamente do seu banco de dados para análise.

## Configurar a Conexão no Azure MySQL

1. **Crie uma Instância do Azure MySQL:**

   - Acesse o [Portal do Azure](https://portal.azure.com/).
   - Crie ou selecione uma instância existente do MySQL no Azure.

2. **Configurações de Segurança:**

   - Certifique-se de que a instância do MySQL no Azure permite conexões externas, se necessário.
   - Anote o nome do servidor MySQL, o nome do banco de dados e as credenciais de usuário necessárias para acessar o banco de dados.

3. **Configuração do Firewall:**
   - No portal do Azure, vá para a configuração de Firewall da sua instância do MySQL.
   - Adicione as regras de firewall necessárias para permitir o acesso ao banco de dados de onde você estará executando o Power BI ou qualquer outra aplicação que precise acessar o MySQL.

## Conectar o Power BI ao Azure MySQL

1. **Abrir o Power BI:**

   - Baixe e instale o [Power BI Desktop](https://powerbi.microsoft.com/desktop/), se ainda não tiver feito isso.

2. **Conectar ao Banco de Dados MySQL:**

   - No Power BI Desktop, vá para a guia "Obter Dados" (Get Data).
   - Selecione "MySQL" na lista de fontes de dados disponíveis e clique em "Conectar".

3. **Configurar Detalhes de Conexão:**

   - Preencha os detalhes de conexão necessários:
     - **Servidor**: Nome do servidor MySQL (exemplo: `mysqlserver.mysql.database.azure.com`).
     - **Base de Dados**: Nome do banco de dados que deseja acessar.
     - **Nome de Usuário e Senha**: Credenciais de usuário configuradas no MySQL.
   - Clique em "OK" para estabelecer a conexão.

4. **Importar Dados:**

   - Após conectar com sucesso, selecione as tabelas ou consultas que deseja importar para o Power BI.
   - Escolha opções de transformação e carregamento conforme necessário.

5. **Gerenciar Atualizações Automáticas:**

   - No Power BI Desktop, vá para "Modelo" (Model) e selecione "Atualizações de Dados" (Data Refresh).
   - Configure as opções para atualizar automaticamente os dados conforme necessário.

6. **Salvar e Publicar:**
   - Salve seu arquivo do Power BI Desktop com todas as conexões e transformações.
   - Para compartilhar e colaborar, publique o relatório e o conjunto de dados no [Power BI Service](https://powerbi.microsoft.com/service/).

## Exemplo de Uso

- **Análise de Dados:**
  - Utilize o Power BI para criar dashboards interativos, relatórios e análises baseadas nos dados do seu Azure MySQL.
  - Explore e visualize dados diretamente do seu banco de dados em tempo real.

## Recursos Adicionais

- [Documentação do Power BI](https://docs.microsoft.com/power-bi/)
- [Documentação do Azure MySQL](https://docs.microsoft.com/azure/mysql/)
- [Tutorial do Power BI](https://docs.microsoft.com/power-bi/guided-learning/)

#### FIZ ESSE PEQUENO TUTORIAL PARA DEMOSTRAR QUE VI OS VIDEOS E REALIZEI O PROCESSO POIS NÃO E POSSIVEL COMPARTILHAR O PROJETO NO GITHUB DEVIDO AS POLITICAS DA COMPANHIA NO QUAL TRABALHO E ESTOU UTILIZANDO A CONTA!
