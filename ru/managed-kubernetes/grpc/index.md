# Yandex Managed Service for Kubernetes
Чтобы выполнить операцию над ресурсом выполните RPC-вызов. Используйте домен `mks.api.cloud.yandex.net` для выполнения запросов к API. Подробнее об архитектуре API Яндекс.Облака, см. [Концепции API Яндекс.Облака](/docs/api-design-guide/).

Спецификации API Яндекс.Облака смотрите на [GitHub](https://github.com/yandex-cloud/cloudapi).

Сервис | Описание
--- | ---
[ClusterService](./cluster_service.md) | Набор методов для управления кластером Kubernetes.
[NodeGroupService](./node_group_service.md) | Набор методов для управления группами узлов.
[OperationService](./operation_service.md) | Набор методов для управления операциями в асинхронных запросах API. Ссылки указаны относительно домена `operation.api.cloud.yandex.net`.
