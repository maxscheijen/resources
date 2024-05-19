# Energy

- **[easyEnergy](https://www.easyenergy.com/)**: Get dynamic energy prices for The Netherlands.

Electricity Prices

```bash
curl "https://mijn.easyenergy.com/nl/api/tariff/getapxtariffs/?startTimestamp=2024-05-01T00:00:00.000Z&endTimestamp=2024-05-02T00:00:00.000Z&includeVat=true"
```

Gas Prices

```bash
curl "https://mijn.easyenergy.com/nl/api/tariff/getlebatariffs/?startTimestamp=2024-05-01T00:00:00.000Z&endTimestamp=2024-05-02T00:00:00.000Z&includeVat=true""
```

- **[EnergyZero](https://energyzero.com/)**: Get dynamic energy prices for The Netherlands.

Electricity Prices

```bash
curl "https://api.energyzero.nl/v1/energyprices?fromDate=2024-05-01T00:00:00.00Z&tillDate=2024-05-02T00:00:00.00Z&usageType=1&interval=4&inclBtw=true"
```

Gas prices

```bash
curl "https://api.energyzero.nl/v1/energyprices?fromDate=2024-05-01T00:00:00.00Z&tillDate=2024-05-02T00:00:00.00Z&usageType=3&interval=4&inclBtw=true"
```
