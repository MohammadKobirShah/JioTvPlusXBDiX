# SOCKS5 Reverse Proxy for Live Streams

Proxy a stream through SOCKS5 using Node.js and deploy to Railway.

## 🧦 SOCKS5 Proxy Config
```
type: socks5
server: 103.159.218.218
port: 1920
username: test
password: test
```

## 🛠 Setup
1. Upload project to GitHub
2. Deploy to [Railway](https://railway.app)
3. Done! Access stream via:

```
https://your-app.up.railway.app/sonicbangla/master.m3u8
```

> Proxies requests to: `https://live.dinesh29.com.np/stream/jiotvplus/sonicbangla/master.m3u8`