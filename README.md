# 🎬 Imagem para Vídeo Cinematográfico com Estilo (CogVideoX-5B-I2V via Google Colab)

Gera vídeos curtos e cinematográficos a partir de **uma imagem estática + um prompt descritivo**, usando o modelo de última geração **CogVideoX-5B-I2V** diretamente no Google Colab com GPU. Ideal para criar cenas realistas com controle total do conteúdo textual e visual.

---

## 🚀 Funcionalidades

🎞️ Geração de vídeo realista a partir de imagem + texto  
🎨 Controle por prompt descritivo (ex: “a sunset over the ocean”)  
⚙️ Otimizado para rodar em Colab com GPU T4  
💾 Download direto do vídeo final em `.mp4`  
🎛️ Interface gráfica interativa com Gradio  

---

## ▶️ Abrir diretamente no Google Colab

> ⚠️ O repositório deve estar **público** para este botão funcionar

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ilhavo/imagem-para-video/blob/main/imagem_para_video_filme.ipynb)

---

## 🧑‍💻 Como Usar

1. Torna este repositório **temporariamente público** (ver instruções abaixo)
2. Clica no botão “Abrir no Colab” acima
3. Faz login com token Hugging Face
4. Sobe uma imagem e insere o prompt textual (ex: “waves crashing under the moonlight”)
5. Gera o vídeo
6. Faz o download do `.mp4` final
7. Torna o repositório **privado novamente** (opcional)

---

## ⚙️ Verificar GPU no Google Colab

Este modelo exige uma GPU com pelo menos **12 GB de VRAM (T4 ou superior)**.

### 🔍 Como confirmar:

1. Vai em **Ambiente de execução > Alterar tipo de ambiente de execução**
2. Escolhe **GPU** como acelerador
3. Executa:

```python
!nvidia-smi
```

Se vires `Tesla T4` ou superior, estás pronto para gerar vídeos realistas 🎬

---

## 🔐 Alternar entre Público e Privado no GitHub

### ➤ Tornar Público:

1. Vai à aba **Settings** do repositório
2. Rola até **Danger Zone**
3. Clica em **“Change repository visibility”**
4. Seleciona **Public** e confirma

### ➤ Voltar a Privado:

1. Vai novamente a **Settings > Danger Zone**
2. Clica em **“Change repository visibility”**
3. Seleciona **Private** e confirma

---

## 📄 Licença

Este projeto é apenas para uso pessoal e educacional.  
Baseado no modelo CogVideoX da [THUDM](https://huggingface.co/THUDM/CogVideoX-5b-I2V) e bibliotecas open source.

---

**Desenvolvido com ❤️ por [ilhavo]**
