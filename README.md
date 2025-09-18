# Armazenamento_Azure
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

Contas de armazenamento
O que é: Recipiente para todos os serviços de armazenamento, fornecendo um namespace exclusivo.
Tipos de conta:
Standard: Baseada em HDD, ideal para armazenamento de baixo custo e uso geral.
Premium: Baseada em SSD, oferece alto desempenho e baixa latência para cargas de trabalho intensivas.
Como usar no Portal: Busque por "Contas de armazenamento", clique em Criar e siga os passos. O tipo de conta (Standard/Premium) e outras configurações são definidos durante a criação.
Armazenamento de Blobs do Azure
O que é: Armazenamento de objetos massivamente escalável para dados não estruturados, como imagens, vídeos, documentos e backups.
Como usar no Portal: Dentro da sua conta de armazenamento, navegue para Contêineres em Armazenamento de dados. Crie um contêiner para organizar seus blobs e depois faça o upload dos arquivos diretamente.
Arquivos do Azure
O que é: Compartilhamentos de arquivos gerenciados na nuvem, acessíveis via protocolos SMB e NFS, para uso em ambientes locais ou na nuvem.
Como usar no Portal: Na sua conta de armazenamento, vá para Compartilhamentos de arquivos em Armazenamento de dados. Crie um compartilhamento de arquivos e defina as configurações de segurança (SMB).
Armazenamento de Filas do Azure
O que é: Fila de mensagens para comunicação assíncrona entre componentes de aplicativos. Ideal para desacoplar tarefas e processar grandes volumes de mensagens.
Como usar no Portal: Dentro da sua conta de armazenamento, clique em Filas em Armazenamento de dados. Crie uma fila para onde as mensagens serão enviadas por seus aplicativos.
Armazenamento de Tabelas do Azure
O que é: Armazena dados NoSQL (não relacionais) estruturados, oferecendo um design sem esquema para conjuntos de dados flexíveis.
Como usar no Portal: Na sua conta de armazenamento, selecione Tabelas em Armazenamento de dados. Crie uma tabela para armazenar seus dados.
Gerenciando o armazenamento no Portal
Gerenciador de Armazenamento: Ferramenta visual no Portal para navegar e gerenciar seus blobs, arquivos, filas e tabelas.
Gerenciamento do ciclo de vida: Configure regras para gerenciar o ciclo de vida dos seus blobs, como mover dados mais antigos para níveis de acesso mais frios para otimizar custos. Acesse em Gerenciamento de dados.
Chaves de acesso: Gerencie as chaves que fornecem acesso à sua conta de armazenamento. Recomenda-se usar o Azure Key Vault para gerenciar chaves com segurança.
Monitoramento: Use o Monitor no Portal para ver métricas e a disponibilidade dos seus serviços de armazenamento.
