ARYA TRADING JOURNAL V7.5 — PROP FIRM ANALYTICS EDITION

V7.5 updates:
- Fixed oversized monetary values in the four compact dashboard statistic cards so long values stay inside each card on iPhone.
- Expanded Analytics with core performance metrics: Net P/L, Win Rate, Profit Factor, Average R/R, Total Trades, Expectancy, Average Win, Average Loss.
- Added Prop Firm Risk Monitor: Max Drawdown, Current Drawdown, Worst Day, Best Day share of net P/L, Profitable Days, Recovery Factor, Average Risk, Largest Risk, Current Streak, Best Win Streak, Best Loss Streak, Daily Loss %.
- Added editable Reference Account Size for drawdown and daily-loss percentages. Default is $5,000 and the chosen value is saved locally with settings.
- Added Daily Performance, Pair Performance, and Monthly Performance breakdowns.
- Updated Service Worker cache to V7.5.

Important:
Analytics are estimates calculated from trades entered in this journal. They do not verify any prop firm's official rules, commissions, equity calculations, or pass/fail status. Each firm has different drawdown and consistency rules.

Deployment:
1. Extract this ZIP.
2. Upload the contents of the arya_v6 folder to the root of your GitHub Pages branch.
3. Replace the previous files and wait for deployment to finish.
4. Reopen the PWA/Safari page. If the old version remains, close the PWA and refresh the site once so the V7.5 service worker can install.

Data:
Trade data remains in the same localStorage key as earlier versions. Your existing journal entries should remain available on the same device/browser. Download a backup from Tools before major updates as a precaution.
