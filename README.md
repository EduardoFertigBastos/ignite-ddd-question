
### Entidades de domínio:

* Product: com atributos como número de identificação único, tamanho, cor e quantidade em estoque.
* SalesHistory: com informações sobre quantidades vendidas, lucro gerado e período de venda.
* PurchaseOrder: com detalhes sobre os produtos a serem comprados e quantidades.

### Ações (casos de uso):

* IndividualProductTrackingUseCase: Rastrear produtos individualmente.
* MinimumStockQuantitiesDefinitionUseCase: Definir limites mínimos de estoque para receber alertas.
* SendNotificationUseCase: Enviar alertas por e-mail e notificação no sistema quando o estoque estiver baixo.
* SalesAndStockHistoryViewingUseCase: Visualizar informações sobre vendas e estoque ao longo do tempo.
* FetchPurchaseOrderUseCase: Gerenciar ordens de compra automaticamente com base em critérios definidos.
* CreatePurchaseOrderUseCase: Criar ordens de compra automaticamente com base em critérios definidos.
* SupplierIntegrationUseCase: Integrar o sistema com fornecedores para receber atualizações automáticas sobre prazos de entrega.
