# NEAR Price Alert Skill

## Purpose
Monitors $NEAR price and sends Telegram notifications when price crosses user-defined thresholds.

## Commands
- near-price-alert add 3.00 above — Alert when NEAR > $3.00
- near-price-alert add 2.00 below — Alert when NEAR < $2.00
- near-price-alert check — Run immediate price check
- near-price-alert list — View all active alerts

## Details
- Check Interval: 3600 seconds
- Notification: Telegram
- Sources: CoinGecko, CoinMarketCap
