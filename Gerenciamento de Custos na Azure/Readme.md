# Gerenciamento de Custos na Azure

### Fatores que Afetam os Custos
	- Calculadora de custos e preços
	- Gerenciamento de custos e marcas
	
	Fatores que afetam o preço, calculadorea de preços e a calculadorea de custo total de propriedade (TCO)
	
	Desccreva a ferramenta de gerenciamento de custos do azure
	Descrever a finalidade das marcas (tags)
	
	1 - Tipo de recurso - custos especificos por recurso, 
	2 - Consumo - pay-as, pay-go, modelo pago conforme o uso, modelo de reserva (informa o tempo de uso)
	3 - Manutenção - Monitorar seu volme e manter seu ambiente pode ajudalo a idenficicar e reduzir os custos nao necessarios, como desligar maquinas virtuais
	4 - Área geografcica - mesmo recurso pode custar valor diferente dependendo da área
	5 - Tráfego de rede - Embora algumas transferencias de dados de entrada sejam gratuitas, o custo de saida ou dados entre os recursos é afetado por zonas de cobrança
	6 - Assinatura - Tipo e configuração da assinatura por afetar o custo, avaliação gratuita permite explorar alguns recursos gratuitamente
	
### Azure Marketplace

	Permite que os clientes encontrem, experimentem, comprem e provisionem aplicativos e serviços de centenas de provedores de serviços lideres, que são todos certificados para execução no azure
	
	- Plataformas de contaier de software livre
	- Imagens de VM e banco
	- Software de compilação e implantação de apps
	- Ferramentas para devs
	- Mais de 10.000 itens listados
	
	MS não é responsavel pelos aplicativos disponibilizados no marketplace
	
### Calculando o Custo Total no Azure (Calculadora de preços)

	Maquina, Região, SO, Tipo (somente SO), Instancia, x Horas
	
	- Região
	- Camada
	- Opções de cobrança
	- Opções de suporte
	- Programas e ofertas
	- Preço de dev/testes azure
	
### Calculadorea de custo total de propriedade (TCO) 
	- Uma ferramenta para estimar a economia de custos possivel ao migrar para azure
	- Um relatorio compara os custos das infras locais com os custos de uso de produtos e servicos na nuvem
	
	- Relatorio de cobrança
	- Enriquecimento de dados
	- Colocar alertas custos para não ter surpresas
	
	- Orçamentos: definir um orçamnento de gastos
	- Alertas: quando o custo excede os limites
	- Recomendação: recomendações de custo
	
### Marcas (TAGs)
	Não são obrigatorias e não são herdaveis
	- Fornececem metadados aos recursos 
	- Organizam os recursos em uma taxonomia de maneira logica
	- Consistem em em par nome-valor 
	- Identificar os recursos na descrição da cobrança
	- Opção de forçar a marca na criação do recurso
	
	
	Resource group (proprietarioo: joe, departamento: mkt, ambiente: prd)
	
	IBEP (centro de custos: mkt)
	
