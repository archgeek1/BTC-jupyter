To download the latest data and remove the watermark in the first line:
```bash
curl -L -o ./Bitstamp_BTCUSD_d.csv https://www.cryptodatadownload.com/cdd/Bitstamp_BTCUSD_d.csv
sed -i '1d' ./Bitstamp_BTCUSD_d.csv
```
