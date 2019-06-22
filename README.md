# grafana-prometheus

Para generar hits accedemos a estas urls y refrescamos varias veces:<br />
http://localhost:9453/api/efectivo<br />
http://localhost:9453/api/tarjeta<br />
Para obtener las métricas de nuestra aplicación en GO:<br /><br />
http://localhost:9453/metrics<br />
Para ver las métricas generales de Prometheus:<br /><br />
http://localhost:9090/metrics<br />
Para revisar que los targets que se definieron estén funcionando:<br /><br />
http://localhost:9090/targets<br />
Para visualizar el gráfico de Grafana:<br /><br />
http://localhost:3000/d/-ByIgbUik/api?orgId=1&refresh=5s&from=now-5m&to=now
