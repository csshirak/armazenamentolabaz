# armazenamentolabaz
lab armazenamento azure
Para utilizar os serviços de armazenamento do Azure, é necessário criar uma conta de armazenamento, que permite gerenciar diferentes tipos de dados. Cada conta deve possuir um nome globalmente único e oferece acesso via internet para diversos serviços de armazenamento.Tipos de Armazenamento Disponíveis:
✅ Blob Storage: Ideal para armazenar grandes volumes de dados não estruturados, como imagens e vídeos.
✅ Azure Files: Compartilhamento de arquivos em rede altamente disponível via protocolo SMB.
✅ Queue Storage: Armazenamento de mensagens para aplicações distribuídas.
✅ Table Storage: Banco de dados NoSQL para armazenamento de dados estruturados sem esquema fixo.
✅ Disk Storage: Discos gerenciados para máquinas virtuais e aplicativos.

O Azure oferece opções para garantir redundância e disponibilidade dos dados:
🔹 Locally Redundant Storage (LRS) – Protege os dados replicando-os dentro de um único data center.
🔹 Zone-Redundant Storage (ZRS) – Distribui os dados entre diferentes zonas da mesma região.
🔹 Geo-Redundant Storage (GRS) – Replica os dados em uma segunda região geográfica.
🔹 Read-Access Geo-Redundant Storage (RA-GRS) – Oferece leitura dos dados na segunda região replicada.

Para facilitar a migração e gerenciamento de arquivos no Azure, a plataforma disponibiliza diversas ferramentas:
Azure Data Box: Armazena até 80 TB de dados e permite transferências físicas seguras para o Azure.
AzCopy: Utilitário de linha de comando para copiar arquivos e blobs rapidamente.
Gerenciador de Armazenamento do Azure: Interface gráfica semelhante ao Windows Explorer para administrar arquivos.
Sincronização de Arquivos do Azure: Mantém arquivos locais e na nuvem sempre atualizados de forma bidirecional.

A segurança no armazenamento do Azure é gerenciada por meio do Azure Role-Based Access Control (RBAC), que define permissões de acesso para diferentes usuários e aplicações. Além disso, há suporte para criptografia de dados em repouso e em trânsito.

