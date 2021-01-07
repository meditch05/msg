# msg
curl -g 'http://127.0.0.1:20001/api/v1/query?query=max_over_time(container_memory_usage_bytes{pod_name=~"somepod-.*"}[1d])' | jq
