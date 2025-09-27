# Weather-Alert-Automation
# 🌦️ Alerta do Clima com Automação (n8n)

Este fluxo envia alertas de clima para o Telegram com base na sua localização (iOS ou default configurada).

---

## 🚀 Instalação

1. Clone ou importe este fluxo no **n8n**.
2. Configure as variáveis de ambiente no servidor onde o n8n roda:

```bash
# .env ou config do n8n
OPENWEATHER_API_KEY=xxxxxx
TELEGRAM_BOT_TOKEN=xxxxxx
TELEGRAM_CHAT_ID=xxxxxx
DEFAULT_CITY="Miguel Pereira"
DEFAULT_STATE="RJ"
DEFAULT_LAT=-22.45
DEFAULT_LON=-43.46
