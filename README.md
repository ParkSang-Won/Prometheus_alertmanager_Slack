# Prometheus_alertmanager_Slack

프로메테우스 얼럿매니저와 슬랙 연동

prometheus-community/prometheus 와 prometheus-community/alertmanager 의 values 파일을 참고해 만들었습니다.(helm show)

rule은 bitnami/nginx의 exporter(:9113)가 동작 중인것을 가정했습니다.

slack 채널에 web-hook 어플추가를 통해 slack_api_url을 확인할 수 있습니다.

helm install -f filename.yaml pro prometheus-community/prometheus
