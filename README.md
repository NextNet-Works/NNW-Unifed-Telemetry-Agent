# NNW-Unifed-Telemetry-Agent
Grafana agent with our tweaks ready to use
# Install local exporters


```
  wget -O install_exporters.sh [https://raw.githubusercontent.com/NextNet-Works/NNW-Unifed-Telemetry-Agent/main/nnw-install_exporters.sh](https://raw.githubusercontent.com/NextNet-Works/NNW-Unifed-Telemetry-Agent/main/nnw-install_exporters.sh) && chmod +x install_exporters.sh && ./install_exporters.sh 
  
  ```
  
     confirm 9100 & 9300 ports are open
     confirm systemd services (cosmos-exporter & node-exporter) 
     
     install grafana-agent
  
     to start service you need to provide proper config and run 
     
     grafana-agent -config.file /etc/grafana-agent.yaml
     
     
    wget https://raw.githubusercontent.com/NextNet-Works/NNW-Unifed-Telemetry-Agent/main/nnw-grafana-agent.yml
     
