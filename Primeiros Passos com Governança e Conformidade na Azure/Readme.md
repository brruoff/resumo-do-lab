# Primeiros Passos com Governança e Conformidade na Azure

### Blueprints, Políticas e Bloqueios de Recurso

	Governança e conformidade

	- Azure policy
	
		- Ajuda a impor padrões organizacionais e avaliar a conformidade em escala
		- Ele fornece governança e consistencia de recursos conforme regulatoria, segurança, custo e gerenciamento independente do nivel de permissao do usuario
		- Tipos de status (non-compliant/remediation/compliant)
		- Avalia e identifica recursos que não atendem as suas politicas
		- Fornece definições de politicas e iniciativas integradas em cat como armazenamento, rede, computação, central de segurança
	
	- Bloqueios de recurso
		- Proteja os recusrtos do Azure de exclusão ou modificação acidental
		- Gerenciar bloqueios na assinatura, grupo de recurso ou niveis de recursos individuais dentro do portal do azure
		- Se adicionar um bloqueio no resource group, todos os resource herdam esta configuração
		- Tipos de bloqueio - excluir (ler/atualizar) / readonly (ler), permisões (ler/atualizar/excluir)
		
	- Portal de confiança do serviço
		- Link aberto ao publico, tipos de protocolos, leis
	
	- Microsoft Pureview
		- familia de soluções de governança, riscos e conformidade
		- reune insights sobre seus dados locais, multinumvem e de software
	
