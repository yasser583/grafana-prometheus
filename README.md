# grafana-prometheus

Para generar hits accedemos a estas urls y refrescamos varias veces:
http://localhost:9453/api/efectivo
http://localhost:9453/api/tarjeta
Para obtener las métricas de nuestra aplicación en GO:
http://localhost:9453/metrics
Para ver las métricas generales de Prometheus:
http://localhost:9090/metrics
Para revisar que los targets que se definieron estén funcionando:
http://localhost:9090/targets
Para visualizar el gráfico de Grafana:
http://localhost:3000/d/-ByIgbUik/api?orgId=1&refresh=5s&from=now-5m&to=now
