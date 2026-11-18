<div align="center">

# 🔔 IBN Avisos

**Chegue a tempo.**
Protótipo de um PWA que avisa quando a transmissão do culto começa e leva você até ela.

[![Site](https://img.shields.io/badge/🌐_Ver_o_site-ff0931?style=for-the-badge)](https://nobrew-cell.github.io/ibn-avisos-site/index.html)
[![Protótipo](https://img.shields.io/badge/📱_Testar_o_protótipo-141414?style=for-the-badge)](https://nobrew-cell.github.io/ibn-avisos-site/prototipo.html)
[![Vídeo](https://img.shields.io/badge/🎬_Vídeo_de_anúncio-e5ae45?style=for-the-badge&labelColor=141414)](https://nobrew-cell.github.io/ibn-avisos-site/anuncio.html)

![Projeto de extensão](https://img.shields.io/badge/projeto-de_extensão_UNIFACS-ff0931?style=flat-square)
![Protótipo](https://img.shields.io/badge/status-protótipo-e5ae45?style=flat-square)
![Custo](https://img.shields.io/badge/custo-R$_0,00-2ea44f?style=flat-square)
![Site estático](https://img.shields.io/badge/site-HTML_·_CSS_·_JS-141414?style=flat-square)

</div>

---

## 💡 A ideia

Quem acompanha o culto de casa muitas vezes perde o começo: o aviso do YouTube demora, achar o link dá trabalho e, quando a pessoa entra, a oração inicial já passou. O **IBN Avisos** é um protótipo de aplicativo que resolve só isso: avisar na hora certa e abrir a transmissão com um toque.

O mascote é o **Horivaldo**, um relógio de smoking sem rosto, porque o que importa nele são o visor e os ponteiros.

## 🧭 O que tem aqui

- 🏠 **Página inicial** (`index.html`): a história do projeto, as decisões de design, as telas do app em carrosséis e as ferramentas usadas.
- 📱 **Protótipo navegável** (`prototipo.html`): as telas do Figma ligadas umas às outras, para testar o caminho de um frequentador.
- 🎬 **Vídeo de anúncio** (`anuncio.html`): a apresentação do projeto em vídeo.

## ✅ O que o protótipo mostra

- 🔔 O aviso de live, com **Entrar na live** e **Compartilhar**
- ⏳ A espera de cinco minutos antes de avisar (na demonstração, 10 segundos)
- 🗓️ Escolha de cultos e o modo **estou presencialmente**
- 📼 Lives anteriores, com atalho para a playlist
- 🔑 Entrada com o Google (simulada) ou sem conta

> **Nada é enviado de verdade.** Não há servidor, login real nem coleta de dados: é só uma simulação das telas.

## 🗂️ Estrutura

```
├── index.html        # página inicial
├── prototipo.html    # protótipo navegável
├── anuncio.html      # vídeo de anúncio
├── paginas.css       # estilos compartilhados
├── img/              # telas, mascote, ícones e controles do protótipo
└── video/            # animações usadas no protótipo
```

## ▶️ Rodando localmente

É um site estático, sem etapa de build. Basta servir a pasta:

```bash
python3 -m http.server 8000
```

e abrir `http://localhost:8000`.

## 📄 Licença

[MIT](LICENSE)
