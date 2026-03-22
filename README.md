# MARKET TERMINAL v13 : Just a Hobbby: A work in Progress.. Any Suggestions would be great

A Bloomberg-style macroeconomic dashboard with 12 live data tabs, TV player, and real-time news feeds.

**Live Data:** FRED (St. Louis Fed) + Yahoo Finance  
**TV Channels:** Schwab Network, Bloomberg TV, BBC News, CNBC, Fox Weather, Top Gear UK  
**News:** Reuters, MarketWatch, Yahoo Finance, CNBC, Investing.com, AP Business  

---

## 🚀 Deploy to GitHub Pages (FREE — 5 minutes)

### Step 1: Create a GitHub Account
If you don't have one, go to [github.com](https://github.com) and sign up (free).

### Step 2: Create a New Repository
1. Click the **+** button (top right) → **New repository**
2. Name it: `market-terminal`
3. Set it to **Public**
4. Check **"Add a README file"**
5. Click **Create repository**

### Step 3: Upload the Files
1. In your new repo, click **"Add file"** → **"Upload files"**
2. Drag and drop the `index.html` file from this folder
3. Click **"Commit changes"**

### Step 4: Enable GitHub Pages
1. Go to your repo **Settings** (gear icon tab)
2. In the left sidebar, click **Pages**
3. Under "Source", select **Deploy from a branch**
4. Branch: **main**, Folder: **/ (root)**
5. Click **Save**

### Step 5: Access Your Terminal
After 1-2 minutes, your terminal will be live at:

```
https://YOUR-USERNAME.github.io/market-terminal/
```

Open this URL on your Android phone, desktop, tablet — any device with a browser!

---

## 📱 Add to Android Home Screen (Optional)

For an app-like experience on your phone:

1. Open the URL in **Chrome** on your Android phone
2. Tap the **three dots menu** (⋮) in the top right
3. Tap **"Add to Home screen"**
4. Name it "Market Terminal" and tap **Add**
5. It now appears on your home screen like a native app!

---

## 📊 Features

| Tab | Key | Data |
|-----|-----|------|
| Macro Overview | F1 | GDP, ISM, CPI, VIX, regime assessment |
| Rates / Inflation | F2 | Yield curve, Fed funds, PCE, PPI, mortgage |
| Labor / Growth | F3 | NFP, unemployment, claims, retail sales |
| FX / Currencies | F4 | DXY, EUR/USD, USD/JPY, GBP/USD, AUD, CAD, CHF |
| Equity Markets | F5 | S&P 500, Dow, Nasdaq, sectors, mega-caps |
| Commodities | F6 | WTI, Brent, gold, silver, copper, natgas, wheat |
| Credit & Liquidity | F7 | HY/IG spreads, M2, Fed balance sheet, NFCI |
| Housing & Leading | F8 | Permits, starts, Case-Shiller, auto sales, sentiment |
| Sentiment | F9 | VIX, VIX 3M term structure, UMich sentiment |
| Global Central Banks | F10 | 9 major CB rates, next meetings, policy bias |
| Crypto | F11 | BTC, ETH, SOL, ADA, DOT, LINK |
| Fed Watch | F12 | FOMC calendar, dot plot, probabilities, speakers |

## 📺 TV Channels
- Schwab Network (via DistroTV)
- Bloomberg TV (HLS m3u8 stream)
- BBC News (HLS m3u8 stream)
- CNBC (HLS m3u8 stream)
- Fox Weather (via Pluto TV)
- Top Gear UK (via Pluto TV)

## Data Refresh
- Market data: every 3 minutes (Yahoo Finance + FRED)
- News headlines: every 3 minutes (6 RSS feeds)
- All state saved to localStorage (tabs, TV channel, panel size)

---

*Built with Claude (Anthropic) — single-file HTML, no backend required.*
