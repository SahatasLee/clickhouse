# Access

```sh
./clickhouse client --host 10.111.0.175 --port 9000 --user default --password 123456789
ClickHouse client version 24.11.1.695 (official build).
Connecting to 10.111.0.171:9000 as user default.
Code: 210. DB::NetException: Connection refused (10.111.0.171:9000). (NETWORK_ERROR)


./clickhouse client -h 10.111.0.171 \
                  --port 8123 \
                  -u default \
                  --password 123456789
ClickHouse client version 24.11.1.695 (official build).
Connecting to 10.111.0.171:8123 as user default.
Code: 210. DB::NetException: Connection refused (10.111.0.171:8123). (NETWORK_ERROR)

```