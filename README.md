# 📹 WebCam Filter Studio

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Mobile%20%26%20Desktop-green)

> **Manipulador de Webcam com Filtros em Tempo Real** - Aplicação web progressiva para processamento de imagem client-side usando Canvas API e getUserMedia.

## 🎯 Sobre o Projeto

WebCam Filter Studio é uma aplicação web moderna e responsiva que permite aplicar filtros avançados em tempo real à câmera do dispositivo. Desenvolvida com JavaScript puro e processamento pixel-a-pixel no `<canvas>`, a aplicação demonstra conceitos fundamentais de visão computacional e processamento de imagem diretamente no navegador.

### ✨ Características Principais

- 🎨 **8 Filtros Profissionais** com processamento em tempo real
- 📱 **Totalmente Responsivo** - Desktop, Tablet e Mobile (Android/iOS)
- 🔄 **Alternância de Câmera** - Frontal e traseira em dispositivos móveis
- 📊 **Análise em Tempo Real** - FPS counter e informações de resolução
- 📸 **Captura de Imagem** - Download direto das fotos processadas
- ⚙️ **Controles Ajustáveis** - Intensidade e limiar configuráveis
- 🚀 **Zero Dependências** - Apenas HTML5, CSS3 e JavaScript vanilla

## 🎨 Filtros Disponíveis

### Filtros Básicos
- **Preto e Branco (Grayscale)** - Conversão para tons de cinza
- **Inverter Cores** - Negativo da imagem
- **Sépia** - Efeito vintage clássico

### Filtros Avançados
- **Detecção de Bordas** - Algoritmo Sobel para edge detection
- **Desfoque (Blur)** - Suavização da imagem com kernel configurável
- **Pontos Luminosos** - Detecção e destaque de áreas brilhantes
- **Pixelizar** - Efeito pixelado ajustável

## 🚀 Demonstração

### Desktop
![Desktop Demo](https://via.placeholder.com/800x400/1e1b4b/ffffff?text=Desktop+Demo)

### Mobile
![Mobile Demo](https://via.placeholder.com/375x667/1e1b4b/ffffff?text=Mobile+Demo)

## 🛠️ Tecnologias Utilizadas

- **HTML5 Canvas API** - Renderização e manipulação de imagem
- **getUserMedia API** - Acesso à webcam/câmera
- **JavaScript ES6+** - Programação orientada a objetos
- **Bootstrap 5** - Framework CSS responsivo
- **Bootstrap Icons** - Biblioteca de ícones

## 📋 Pré-requisitos

- Navegador moderno com suporte a:
  - `getUserMedia` API
  - `Canvas` API
  - JavaScript ES6+
- Conexão HTTPS (requerido para acesso à câmera)
- Permissão de acesso à câmera do dispositivo

## 🔧 Instalação

1. Clone o repositório
```bash
git clone https://github.com/brunnodev50/webcam-filter-studio.git
```

2. Navegue até o diretório
```bash
cd webcam-filter-studio
```

3. Abra o arquivo HTML em um servidor local
```bash
# Usando Python 3
python -m http.server 8000

# Usando Node.js (http-server)
npx http-server

# Usando PHP
php -S localhost:8000
```

4. Acesse no navegador
```
https://localhost:8000/index.html
```

> ⚠️ **Importante:** A API getUserMedia requer HTTPS. Use um servidor local com SSL ou deploy em plataforma com HTTPS.

## 💻 Como Usar

### Desktop
1. Clique em **"Iniciar Câmera"**
2. Permita o acesso à webcam quando solicitado
3. Selecione um filtro clicando nos botões
4. Ajuste a intensidade usando os sliders
5. Clique em **"Capturar Foto"** para salvar a imagem

### Mobile (Android/iOS)
1. Toque em **"Iniciar Câmera"**
2. Conceda permissão de acesso à câmera
3. Use o botão **"Alternar"** para trocar entre câmera frontal e traseira
4. Aplique filtros tocando nos botões
5. Ajuste controles deslizando os sliders
6. Toque em **"Capturar"** para fazer download da foto

### Atalhos de Teclado
- **Espaço** - Capturar foto
- **Números 1-8** - Selecionar filtros rapidamente

## 🎓 Conceitos Implementados

### Processamento de Imagem
- Manipulação pixel-a-pixel do `ImageData`
- Convolução de matrizes (Kernel operations)
- Algoritmo Sobel para detecção de bordas
- Filtros de média ponderada para blur

### Visão Computacional
- Detecção de brilho e limiarização
- Transformações de espaço de cor (RGB → Grayscale)
- Operações morfológicas básicas

### Performance
- `requestAnimationFrame` para renderização suave
- Context2D com `willReadFrequently` para otimização
- Cálculo de FPS em tempo real
- Throttling de eventos para mobile

## 📱 Compatibilidade

| Navegador | Desktop | Mobile |
|-----------|---------|--------|
| Chrome    | ✅      | ✅     |
| Firefox   | ✅      | ✅     |
| Safari    | ✅      | ✅     |
| Edge      | ✅      | ✅     |
| Opera     | ✅      | ✅     |

## 🌟 Funcionalidades Futuras

- [ ] Filtros adicionais (Oil Painting, Cartoon)
- [ ] Gravação de vídeo com filtros
- [ ] Detecção facial (Face Detection API)
- [ ] Efeitos de realidade aumentada (AR)
- [ ] Compartilhamento direto em redes sociais
- [ ] Histórico de capturas
- [ ] Presets de filtros personalizados
- [ ] Ajuste de curvas RGB

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um Fork do projeto
2. Criar uma Branch para sua feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a Branch (`git push origin feature/NovaFuncionalidade`)
5. Abrir um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

**Brunno**
- GitHub: [@brunnodev50](https://github.com/brunnodev50)
- LinkedIn: [Brunno Henrique]([https://linkedin.com/in/seu-perfi](https://www.linkedin.com/in/brunno-henrique-vilas-boas-4a514b14a/)l)

## 🙏 Agradecimentos

- [Bootstrap](https://getbootstrap.com/) - Framework CSS
- [Bootstrap Icons](https://icons.getbootstrap.com/) - Biblioteca de ícones
- [MDN Web Docs](https://developer.mozilla.org/) - Documentação e referências

## 📚 Recursos de Aprendizado

### APIs Utilizadas
- [getUserMedia API](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia)
- [Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
- [ImageData](https://developer.mozilla.org/en-US/docs/Web/API/ImageData)

### Conceitos
- [Processamento Digital de Imagens](https://en.wikipedia.org/wiki/Digital_image_processing)
- [Sobel Operator](https://en.wikipedia.org/wiki/Sobel_operator)
- [Gaussian Blur](https://en.wikipedia.org/wiki/Gaussian_blur)

---

⭐ Se este projeto foi útil para você, considere dar uma estrela no GitHub!

**Made with ❤️ and JavaScript**
