# tipos-serviços-nuvem-DIO

A configuração de uma instância de banco de dados na Azure é um processo intuitivo que proporciona alta disponibilidade, escalabilidade e segurança para suas aplicações. O primeiro passo é acessar o Portal do Azure e navegar até o serviço "Azure Database" ou escolher o tipo específico de banco de dados desejado, como Azure SQL Database, MySQL ou PostgreSQL.
Em seguida, deve-se clicar em "Criar" e preencher os detalhes básicos, como o nome do servidor, nome do banco de dados, usuário administrador e senha. É importante selecionar a região mais próxima dos usuários para reduzir a latência.
Depois, na aba de configuração, o usuário pode escolher o tamanho da instância (SKU), que determina recursos como vCores, memória e armazenamento.
As opções de alta disponibilidade, backups automáticos e configurações de segurança, como firewalls e autenticação, também devem ser definidas.
Após revisar as configurações, o banco é criado e provisionado em poucos minutos.
Finalizada a implantação, é possível acessar o banco utilizando ferramentas como Azure Data Studio, SQL Server Management Studio ou qualquer cliente de banco de dados compatível.
Além disso, o Azure oferece monitoramento integrado e recomendações de otimização de desempenho.
Esse processo facilita muito o gerenciamento e a escalabilidade de bancos de dados para aplicações modernas na nuvem.

# Configuração de Instância de Banco de Dados no Azure

## 🛠️ Etapas:

1. **Acessar o Portal do Azure**  
   - Link: [Portal Azure](https://portal.azure.com)

2. **Procurar pelo Serviço de Banco de Dados**  
   - No menu de pesquisa, digite o tipo de banco desejado (ex: "Azure SQL Database", "Azure Database for MySQL" ou "Azure Database for PostgreSQL").

3. **Criar um Novo Banco de Dados**  
   - Clique em **Criar** > **Banco de Dados Único** ou o tipo de serviço selecionado.

4. **Preencher Informações Básicas**  
   - Nome do servidor e nome do banco de dados.
   - Usuário administrador e senha.
   - Região onde o banco será hospedado.

5. **Escolher Configurações de Hardware**  
   - Selecione o plano (SKU), número de vCores, memória e tamanho do armazenamento.

6. **Configurar Backup e Alta Disponibilidade**  
   - Defina as políticas de backup automáticas e (opcionalmente) habilite a alta disponibilidade.

7. **Configurar Regras de Firewall**  
   - Adicione regras para permitir o acesso ao banco apenas de IPs confiáveis.

8. **Revisar e Criar**  
   - Clique em **Revisar + Criar** para validar as configurações e depois em **Criar** para iniciar a implantação.

9. **Conectar-se ao Banco de Dados**  
   - Após a criação, use ferramentas como Azure Data Studio ou SSMS para gerenciar o banco.

10. **Monitorar e Gerenciar**  
    - Utilize os recursos de monitoramento do Azure para acompanhar o desempenho, otimizar consultas e configurar alertas.

---

> **Nota**: Para economizar custos, lembre-se de pausar ou excluir a instância quando não estiver em uso.
