# 🐳 Monitoring Stack (Prometheus + Grafana + Node Exporter)

Este projeto configura uma **stack simples de monitoramento** utilizando **Docker Compose**.

---

## 🧱 Componentes da Stack
- **Prometheus** – coleta e armazena métricas  
- **Node Exporter** – expõe métricas do sistema  
- **Grafana** – visualiza métricas em painéis interativos  

---

## ⚙️ Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/<seu-usuario>/monitoring-stack.git
   cd monitoring-stack

2. Inicie os containers:
   ```
   docker-compose -f compose.yml up -d
   ```

3. Acesse os serviços:

   Grafana: http://localhost:3000
   
   Prometheus: http://localhost:9090


## Grafana Dashboard
![Grafana Dashboard](./assets/screenshot.png)


