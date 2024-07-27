# KakinoTane
simple LLM misskey BOT?

## REQUIREMENTS
- Go 1.21
- OpenAI API Token
- Misskey API Token

## Run Locally
```bash
go mod tidy
export MISSKEY_TOKEN=xxxx
export OPENAI_API_KEY=xxxx
export BASE_URL=misskey.example.com
go run ./cmd/main.go
```

