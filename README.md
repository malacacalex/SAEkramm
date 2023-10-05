# SAEkramm
https://www.elastic.co/guide/en/logstash/current/docker-config.html
https://www.elastic.co/guide/en/logstash/current/docker.html
https://docs.datadoghq.com/fr/logs/guide/docker-logs-collection-troubleshooting-guide/
sudodocker run --name test -d busybox sh -c "while true; do $(echo date); sleep 1; done"
docker logs -f test > test.txt
