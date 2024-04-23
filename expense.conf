proxy_http_version 1.1;

location /api/ { proxy_pass http://backend.daws78s.online:8080/; }

location /health {
  stub_status on;
  access_log off;
}