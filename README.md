### 🚀 Hızlı Otomatik Yükleyici (Loadstring)

Kodların tamamını kopyalamak yerine, aşağıdaki tek satırlık yükleyiciyi tarayıcı konsoluna (`F12 -> Console`) yapıştırıp `Enter`'a basarak her zaman **en güncel sürümü** doğrudan çalıştırabilirsiniz:

```javascript
fetch('https://raw.githubusercontent.com/klurla/infinite-craft2/refs/heads/main/inf').then(r=>r.text()).then(eval);
