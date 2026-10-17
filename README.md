# forecast-ledger-heads

One line per day: the fingerprint (SHA-256 chain head) of the SignalTrace forecast ledger at the end of that day.

The ledger itself is private. Publishing the fingerprint here, in a public history we cannot quietly rewrite, lets anyone later check that a forecast shown as "made on date X" really existed on date X and was not edited or removed afterwards.

Format of `heads.txt`:

```
<date (KST)>  <ledger lines>  <sha256 chain head>
```

No forecasts, prices or personal data are stored here.
