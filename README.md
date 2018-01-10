# Coin
Python script that calls on the CoinMarketCap API.

## Download
Open a terminal shell and use **git clone** to download.
```bash
git clone https://github.com/syyntax/coin
```

## Move coin
Move the **coin** script to _/usr/local/bin_.
```bash
sudo mv coin /usr/local/bin
```

## Modify Permissions
Change the permissions of **coin** to allow it to execute.
```bash
sudo chmod +x /usr/local/bin/coin
```

## Usage
**Coin** takes one parameter: the coin name.  At this time, the script does not allow the use of tickers as valid parameters.  Tokens or coins with spaces in their names (e.g. _Basic Attention Token_) are usually replaced with dashes (i.e. _basic-attention-token_).

```python
coin bitcoin
```

![Snapshot](https://image.prntscr.com/image/TVfvDYC3RU2uD6fthdh-UQ.png "Snapshot")
