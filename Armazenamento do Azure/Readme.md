Armazenamento do Azure
- Plataforma de migração unificada
- Intervalo de ferramentas integradas e autonomas
- Avaliação e migração


	- Serviços de armazenamento
		- Contas de armazenamento (Storage accounts)
			- Nome exclusivo globalmente
		- 4 Tipos de dados
			- Blob do Azure - utilizado para armazenamento massivo de dados não estruturados como texto ou binário
			- Disco do Azure - fornece discos para VM, apps e outros serviços acessarem
			- Fila do Azure - Armazenamento de mensagens, armazenamento e recuperação para grandes qts até 64KB
			- Arquivos do Azure - configura compartilhamento de arquivos de rede altamente disponivel, pode ser utilizado usando o protocolo do bloco de mensagens do servidor
			- Tabelas do Azure - fornece opção chave/atributo para armazenamento de dados estruturados não relacionais com design sem esquema
				- Exemplo de nomes publicos (https://<storage-acc-name>.blob.core.windows.net) dfs/file/queue/table
		- Camadas de acesso de armazenamento do Azure
			- Frequente - otimizada para armazenamento com dados acessados com frequencia
			- Esporadico - otimizada para armazenamento com dados acessados com baixa frequencia 30 dias
			- Frio - otimizada para armazenamento com dados acessados com baixa frequencia 90 dias
			- Arquivo morto - otimizada para armazenamento com dados acessados com baixa frequencia 180 dias
	- Opções de redundancia
		- LRS - armazenamento com redundancia local (ambas tem 3 copias, não indicada para produção)
		- ZRS - armazenamento com redundancia de zona (ambas tem 3 copias)
		- GRS - armazenamento com redundancia geografica (1 copia fora da regiao)
		- GZRS - armazenamento com redundancia zona geografica ()
		quanto mais "NOVES" maior a disponibilidade dos dados 
	- Gerenciamento e migração de arquivos
		- Azure Data Box 
			- Armazena até 80TB
			- Mova os backups de rec de desastre para o Azure
			- Proteja seus dados em uma caixa robusta durante o transito
			- Migre dados do Azure para conformidade ou necessidades regulatorias
			- Migre dados para o Azure de locais remotos ou conectividade limitada ou sem conectividade
		-AzCopy
			- Utilitario de linha de comando
			- copiar blobs ou arquivos ou conta de armazenamento
			- sincronização em uma direção
		- Gerenciador de armazenamento do Azure
			- Interface grafica do usuário
			- Compativel com windows, mac e linux
		- Sincronização de arquivos do Azure
			- Sincroniza os arquivos do Azure e locais de forma bilateral
			- Camada de nuvem mantem os arquivos acessados com frequencia no local, enquanto libera espaço
		



		
