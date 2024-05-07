# prometheus-grafana
使用Prometheus整合Grafana監控本機

1. 安裝Prometheus

    https://prometheus.io/

- 安裝後，打開瀏覽器http://localhost:9090/

看到下列畫面代表成功
![image](https://github.com/Josephine-M-Li/prometheus-grafana/assets/77156174/f5d4ae2f-d820-48f0-9b0d-6bcf8062ffe0)

2. 安裝windows exporter

    https://github.com/prometheus-community/windows_exporter

- 安裝後，打開服務

看到windows_exporter代表成功
![image](https://github.com/Josephine-M-Li/prometheus-grafana/assets/77156174/a8bb9311-45e9-4c37-b4f7-d22ddf6eea76)

3. 配置Prometheus.yml
4. 安裝Grafana

    https://grafana.com/
- 安裝後，打開瀏覽器http://localhost:3000/

看到下列畫面代表成功
![image](https://github.com/Josephine-M-Li/prometheus-grafana/assets/77156174/04fbe8d1-eba8-4149-ba32-9af5c02a83e7)

- 預設帳密:admin/admin
5. 配置Grafana

    (1)Data sources
    (2)導入Dashboard模板

![image](https://github.com/Josephine-M-Li/prometheus-grafana/assets/77156174/217c1025-70cc-4a72-8911-baec42397ea4)

![image](https://github.com/Josephine-M-Li/prometheus-grafana/assets/77156174/4527191f-d355-4866-aeb4-51f446913c80)

- Dashboard導入成功

![image](https://github.com/Josephine-M-Li/prometheus-grafana/assets/77156174/43b3ea83-72f6-4b68-b1a0-cd641d2e4067)




