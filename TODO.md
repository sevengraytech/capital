# TODO

- [ ] Update `frontend/dashboard.html` live market chart section to match `frontend/index.html` (BTC/ETH/XRP, OHLC from CoinGecko, 3s ticks, 30s live price refresh, same UI labels/badges).
- [ ] Add FAQ chatbot panel to `frontend/dashboard.html`.
  - [x] Create chat UI (messages container, input, send button)
  - [x] Add JS to call `POST /chatbot/message` and render bot replies
  - [x] Wire Enter key to send
- [ ] Smoke test: open `/dashboard`, verify charts render + tick; verify FAQ bot works.


