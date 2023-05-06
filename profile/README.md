# Модель машинного обучения, которая определяет биржевой сленг в комментариях соцсети Пульс.
## Развертывание
```yaml
version: "3"
services:
    tinkoff-bot:
        container_name: tinkoff-bot
        build: ./bot
        environment:
            TOKEN: $TOKEN
            API_URL: "http://tinkoff-backend:8000"

    tinkoff-backend:
        container_name: tinkoff-backend
        build: ./backend
        ports:
            - "3000:8000"
```

## Демо
<a href="https://tinkoff.dan.tatar/static/integrations" target="_blank">
	<img src="https://0x0.st/HZMm.jpg">
</a>

<a href="https://tinkoff.dan.tatar/static/" target="_blank">
	<img src="https://0x0.st/HZMa.jpg">
</a>

<a href="https://github.com/Tinkoff-Pulse-Research/cli" target="_blank">
	<img src="https://0x0.st/HZMB.jpg">
</a>

<a href="https://t.me/slang_robot" target="_blank">
	<img src="https://0x0.st/HZMM.jpg">
</a>

