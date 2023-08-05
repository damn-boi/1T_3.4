# 1T_3.3

currency_load_variables:
{
  "table_name": "rates",
  "rate_base": "BTC",
  "rate_target": "RUB",
  "connection_name": "my_db_conn",
  "url_base": "https://api.exchangerate.host/"
}

Connections:
(
	Conn id: my_db_conn
	Conn type: postgres
	Host: host.docker.internal
	Schema: test
	Login/pass: postgres/password
	Port: 5430
)