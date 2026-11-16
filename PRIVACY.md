# Privacy Policy — Nifty Options Desk

_Last updated: 2026-11-16_

Nifty Options Desk ("the app") is a free desktop app published by Jude Finney (buildsbeyondAI). This policy covers
the Microsoft Store app.

## What the app collects

**Nothing.** The app has no account, no sign-in, no ads, no analytics, no telemetry and no crash reporting.
The developer receives no data about you or how you use the app.

## What stays on your PC

- Your settings, the paper trades you save, the app's own paper picks, your capital figure and the rules the app
  has tuned from closed trades.
- If you choose to use Zerodha Kite Connect: your Kite API key, API secret and the day's access token.
- A local log file used only for troubleshooting.

These live in `%LOCALAPPDATA%\NiftyOptionsDesk`. They never leave your PC, except that your Kite credentials are sent
to Zerodha's own servers when you use Kite as the data source. Uninstalling the app or deleting that folder removes
them.

## Network use

The app downloads published market data only. It identifies itself honestly as "NiftyOptionsDesk" in its user agent
and sends no personal information. It contacts:

- **National Stock Exchange of India Ltd.** (nseindia.in and nsearchives.nseindia.com), to read the public Nifty and
  Bank Nifty option chains and lot sizes: when you open or refresh a page, and every 30 seconds while the market
  trades (09:15–15:30 IST) and the app is open. NSE's own privacy policy applies to its website.
- **Zerodha Broking Ltd.** (api.kite.trade, kite.zerodha.com), only if you choose Zerodha Kite as the data source and
  enter your own Kite Connect keys. Zerodha's privacy policy applies. The app only reads market data; it never places,
  changes or cancels orders.

The app window uses Microsoft Edge WebView2, which is part of Windows and is governed by Microsoft's privacy statement.

## Children

The app is not directed at children and collects no data from anyone.

## Changes

Any change to this policy will be published in this file, with a new date above.

## Contact

Questions: open an issue at <https://github.com/buildsbeyondai-code/nifty-options-desk/issues>.
