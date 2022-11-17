# pulsar-adsb-cockroachdb
Apache Pulsar -> CockroachDB



#### Create a table

````



CREATE TABLE public.aircraft (
  alt_baro INT,
  alt_geom INT,
  baro_rate INT,
  category STRING,
  emergency STRING,
  flight VARCHAR,
  gs FLOAT,
  gva INT,
  hex STRING,
  lat FLOAT,
  lon FLOAT,
  mach FLOAT,
  messages INT,
  nac_p INT,
  nac_v INT,
  nav_altitude_mcp INT,
  nav_heading FLOAT,
  nav_qnh FLOAT,
  nic INT,
  nic_baro INT,
  rc INT,
  rssi FLOAT,
  sda INT,
  seen FLOAT,
  seen_post FLOAT,
  sil INT,
  sil_type STRING,
  speed FLOAT,
  squawk INT,
  track FLOAT,
  version INT
  );
  

````


#### References

* https://github.com/tspannhw/FLiP-Py-ADS-B
* https://github.com/tspannhw/pulsar-adsb-function
