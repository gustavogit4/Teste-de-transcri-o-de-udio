# Projeto de Transcrição de Áudio com Whisper

Este projeto utiliza o modelo Whisper, desenvolvido pela OpenAI, para transcrever áudios em texto. A transcrição pode ser salva em formato de legenda (`.srt`) e ser utilizada para diferentes finalidades, como geração de legendas para vídeos ou documentação.

## 🔧 Funcionalidades

- Transcrição de áudios em diferentes idiomas.
- Salvamento da transcrição no formato `.srt` para fácil utilização em vídeos.
- Suporte para diferentes modelos de Whisper: `base`, `medium`, `large`.

## 📋 Requisitos

Antes de rodar o código, você precisará instalar algumas dependências. Aqui estão as bibliotecas necessárias:

1. **OpenAI Whisper** para transcrição de áudio.
2. **FFmpeg** para processamento de arquivos de áudio.

### Instalação

Para instalar as dependências necessárias, execute o seguinte:

```bash
# Instalar o Whisper
pip install openai-whisper

# Instalar o FFmpeg
apt-get update && apt-get install -y ffmpeg
