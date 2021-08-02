# ccloudexporter-telegraf-example


1. Update docker-compose.yml with:
  * `CCLOUD_API_KEY`
  * `CCLOUD_API_SECRET`
  * `CCLOUD_CLUSTER`
2. Update `settings/telegraf.conf` with your Azure resource id 
3. Update `settings/telegraf.conf` with your Dynatrace `API token` and `url`
4. Then, run `docker-compose up -d`
