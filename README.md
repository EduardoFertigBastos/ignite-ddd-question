
### Entidades de domínio:

* Product:
  * ID do produto (identificador único)
  * Nome
  * Descrição
  * Tamanho
  * Cor
  * Quantidade em estoque
  * Quantidade mínima em estoque
  * ID do fornecedor (chave estrangeira)
 
* SalesHistory:
  * ID da venda (identificador único)
  * ID do produto (chave estrangeira)
  * Data da venda
  * Quantidade vendida
  * Preço de venda
  * Lucro total
  
* PurchaseOrder: com detalhes sobre os produtos a serem comprados e quantidades.
  * ID da ordem (identificador único)
  * ID do produto (chave estrangeira)
  * ID do fornecedor (chave estrangeira)
  * Data da ordem
  * Data de entrega prevista
  * Quantidade solicitada
  * Status da ordem (por exemplo, pendente, entregue)
    
### Ações (casos de uso):

* IndividualProductTrackingUseCase: Rastrear produtos individualmente.
* MinimumStockQuantitiesDefinitionUseCase: Definir limites mínimos de estoque para receber alertas.
* SendNotificationUseCase: Enviar alertas por e-mail e notificação no sistema quando o estoque estiver baixo.
* SalesAndStockHistoryViewingUseCase: Visualizar informações sobre vendas e estoque ao longo do tempo.
* FetchPurchaseOrderUseCase: Gerenciar ordens de compra automaticamente com base em critérios definidos.
* CreatePurchaseOrderUseCase: Criar ordens de compra automaticamente com base em critérios definidos.
* SupplierIntegrationUseCase: Integrar o sistema com fornecedores para receber atualizações automáticas sobre prazos de entrega.
