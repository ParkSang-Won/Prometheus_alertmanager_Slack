# Prometheus_alertmanager_Slack
프로메테우스 얼럿매니저와 슬랙 연동

prometheus-community/prometheus 의 values.yaml 과 prometheus-community/alertmanager 를 참고해 만들었습니다.

rule은 bitnami/nginx의 exporter(:9113)가 동작 중인것을 가정했습니다.
