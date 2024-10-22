Identidade, Acesso e Segurança
	- Servicos de diretorio
	- Metodos de autenticacao
	- Modelos de segurança


	- Microsoft Entra ID (antigo AD) e Domain Services
		- Autenticação (funcionarios entram para acessar os recursos)
			- Autenticação
				- Identifica a pessoa ou serviço
				- Solicita credencias para acesso legitimo
				- Base para criar principios de identidade e controle de acesso seguros
			- Autorização
				- Determina o nivel de acesso de uma pessoa ou serviço
				- Define quais dados eles podem acessar e o q podem fazer
			- Autenticação Multifator (MFA)
				- fornece uma segurança adicional para as identidades exigindo dois ou mais elementos para uma autenticacao completa
		- Logon unico (SSO)
		- Gerenciamento de aplicativos
		- Negocios para Negocios (B2B)
			- ID externo do Microsoft Entra
		- Gerenciamento de dispositivos
	
		- Acesso condicional
			- Associacao de usuario ou grupo
			- Local do IP
			- Dispositivo
			- Aplicativo
			- Detecção de risco
			
		- Controle de acesso baseado em função (RBAC)
			- Gerenciamento de acesso de granilaridade fina
			- Divida as tarefas dentro da equipe e conceda somente a quantidade de acesso de que os usuarios precisam para trabalhar
			- Habilite o acesso ao portal do Azure e controle de acesso aos recursos
		
		- Confiança Zero
			- Protege ativos em qualquer lugar com uma politica central
		- Abordagem classica
			- Restringe tudo a uma rede segura
			
		- Proteção completa (em camadas)
			1 Segurança fisica
			2 Identidade e acesso
			3 Perimetro
			4 Rede
			5 Computação
			6 Aplicativo
			7 Dados
			
			- Uma abordagem em camadas para proteger sistemas de computador
			- Fornece varios niveis de proteção
			- Ataques contra uma camada sao isolados das camadas subsequentes
			
		- Microsoft Defender for cloud
			- É uma aplicação cloud native, que fornece monitoramento de proteção contra ameaças nos datacenter do Azure e locais
		
			Recursos do Azure
				- Fornece recomendações de segurança 
				- Detecta e bloqueia malware
				- Analisa e identifica ataques potenciais
				- Controle de acesso just-in-time para portas
				
			
			
Microsoft Entra ID
- Criar usuário local para replicar na cloud
- Permissões / Rabc
- Listagem de membros, coluna de sincronização
- Usuario removido pode ser restaurado em até 30 dias
- Health Preview (SLA)
- Windows Defender for cloud (Integra com aws, gcp)
