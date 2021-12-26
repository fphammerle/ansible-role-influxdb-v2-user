# Ansible Role: InfluxDB v2 User

Ansible's `influxdb_*` modules do not support InfluxDB v2 as they are based on https://github.com/influxdata/influxdb-python:

> Note: This library is for use with InfluxDB 1.x. For connecting to InfluxDB 2.x instances, please use the the influxdb-client-python client.

## Required Variables

```yaml
influxdb_v2_user_url: http://localhost:8086
influxdb_v2_user_url_username: admin
influxdb_v2_user_url_password: admin-password
influxdb_v2_user_name: new-user
```

## Returned Variables

```
influxdb_v2_user_id
influxdb_v2_user_url_cookies_string
```
