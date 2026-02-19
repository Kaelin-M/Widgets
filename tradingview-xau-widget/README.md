# TradingView Gold Price Widget

An embeddable TradingView **Symbol Overview** widget displaying live gold prices in USD and AUD.

## Symbols

| Symbol               | Description              |
| -------------------- | ------------------------ |
| `PEPPERSTONE:XAUUSD` | Gold / US Dollar         |
| `PEPPERSTONE:XAUAUD` | Gold / Australian Dollar |

## Embed Usage

### Option 1 – GitHub Pages (standalone page)

1. Fork or clone this repo.
2. Enable **GitHub Pages** (`Settings → Pages → Branch: main / root`).
3. Your widget will be live at `https://<your-username>.github.io/<repo-name>/`.

### Option 2 – Embed in another page via `<iframe>`

```html
<iframe
  src="https://<your-username>.github.io/<repo-name>/"
  width="100%"
  height="400"
  frameborder="0"
  scrolling="no"
>
</iframe>
```

### Option 3 – Copy the snippet directly

Copy the widget `<div>` block from `index.html` and paste it into any HTML page.

## Customisation

Edit the JSON config inside the `<script>` tag in `index.html`:

| Key                   | Effect                               |
| --------------------- | ------------------------------------ |
| `colorTheme`          | `"light"` or `"dark"`                |
| `chartType`           | `"area"`, `"candlesticks"`, `"bars"` |
| `symbols`             | Add/remove trading pairs             |
| `dateRanges`          | Adjust available time ranges         |
| `showMA` / `maLength` | Toggle moving average and period     |

## License

Widget content is provided by [TradingView](https://www.tradingview.com) under their embed terms of service.
