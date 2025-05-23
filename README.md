
# 🎬 Imagem para Vídeo Cinematográfico com Estilo (Google Colab)

Gera vídeos curtos e cinematográficos a partir de imagens estáticas usando **Stable Video Diffusion** com uma interface interativa Gradio. Perfeito para criar animações com estilo "filme", "anime", "pintura artística", e muito mais — tudo grátis e sem instalar nada!

---

## 🚀 Funcionalidades

✨ Geração de vídeo automática a partir de imagens  
🎨 Escolha de estilos visuais (ex: anime, pintura, cinematográfico)  
🕹️ Movimento de câmara (zoom, pan) configurável  
🎬 Duração e FPS por clipe ajustáveis  
🎼 Música de fundo personalizável  
💬 Legendas por imagem (opcional)  
🎞️ Vídeo final em MP4 com download direto  

---

## ▶️ Abrir diretamente no Google Colab

> ⚠️ O repositório deve estar **público** para este botão funcionar

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ilhavo/imagem-para-video/blob/main/imagem_para_video_filme_PERFEITO.ipynb)

---

## 🧑‍💻 Como Usar

1. Torna este repositório **temporariamente público** (ver instruções abaixo)
2. Clica no botão “Abrir no Colab” acima
3. Sobe as tuas imagens e preenche os parâmetros:
   - Estilo (ex: `cinematic`, `anime watercolor`)
   - Duração por clipe
   - FPS
   - Legenda por imagem (opcional)
4. Gera os vídeos
5. Faz o download do MP4 final
6. Torna o repositório **privado novamente** (opcional)

---

## ⚙️ Verificar GPU no Google Colab

O modelo usa a GPU para gerar vídeos com qualidade. Certifica-te que tens uma **T4 ou superior** ativa.

### 🔍 Como confirmar:

1. No Colab, vai a **Ambiente de execução > Alterar tipo de ambiente de execução**
2. Em **Acelerador de hardware**, escolhe: `GPU`
3. Executa a célula abaixo para verificar a GPU:

```python
!nvidia-smi
```

Se vires `Tesla T4` ou superior — estás pronto para gerar vídeos com desempenho ideal 🚀

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

> 🔒 Isto é 100% seguro. Apenas tu tens acesso como dono do repositório.

---

## 📄 Licença

Este projeto é apenas para uso pessoal e educacional.  
Baseado em modelos da [Stability AI](https://stability.ai) e bibliotecas open source.

---

**Desenvolvido com ❤️ por [ilhavo]**
