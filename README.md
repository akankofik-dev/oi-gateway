# oi-gateway

Gateway IM untuk Oi — mengubah platform chat menjadi pintu masuk agent dengan penanganan
slash-command, percakapan berulir, dan relay media.

Bagian dari [Oi](https://github.com/akankofik-dev/Oi); dipakai via git pin, tidak dipublikasikan di PyPI.

## Install

```bash
pip install "git+https://github.com/akankofik-dev/oi-gateway.git@v1.0.0"
```

Dari checkout Oi, paket ini dideklarasikan di `[tool.uv.sources]`, jadi `uv sync` menyelesaikannya.

## Isi

| Modul | Fungsi |
|---|---|
| `oi_gateway.channels` | Ingress DingTalk, QQ, WeCom, Feishu, MQTT, webhook |
| `oi_gateway.processor` | Routing pesan ke runtime agent |
| `oi_gateway.threads` | Threading percakapan per platform |
| `oi_gateway.slash` | Slash command yang dipakai bersama dashboard |

## Lisensi

MIT — lihat [LICENSE](LICENSE).
