# Cordel Moderno

**Cordel Moderno** é uma página web que apresenta um cordel moderno inspirado na obra de Milton Duarte. O projeto foi desenvolvido durante o curso do **Curso em Vídeo** e combina a tradição da literatura de cordel com um design moderno e responsivo.

---

## 📜 Sobre o projeto

O projeto é uma interpretação visual de um cordel, usando HTML e CSS. A página é organizada em seções que destacam estrofes do poema e utiliza imagens de fundo e efeitos visuais para enriquecer a experiência do usuário.  

O objetivo é unir **literatura popular brasileira** e **design web**, de forma simples e elegante.

---

## 🎨 Funcionalidades e estilos

- Estrutura semântica usando `header`, `section` e `footer`.  
- Diferenciação visual entre seções:  
  - `section.normal` → fundo branco e texto preto.  
  - `section.imagem` → fundo escuro, imagens de fundo, efeito de sombra interna e texto em caixa com leve transparência.  
- Uso de **fontes personalizadas do Google Fonts**:  
  - `'Passion One'` para o título.  
  - `'Sriracha'` para os versos.  
  - `'Verdana'` como fonte base do site.  
- Responsivo, com ajuste de tamanho e espaçamento para telas menores.  
- Links externos para o autor do poema e para o Curso em Vídeo.  
- Efeitos visuais:  
  - `background-size: cover` para imagens de fundo responsivas.  
  - `text-shadow` para destaque do texto sobre fundos escuros.  
  - `box-shadow` interno para efeito de profundidade nas seções de imagem.

---

## 🛠 Tecnologias utilizadas

- **HTML5** para a estrutura do conteúdo.  
- **CSS3** para estilização avançada, incluindo:  
  - Fontes personalizadas  
  - Gradientes e sombras  
  - Efeitos de fundo com `background-size: cover` e `background-attachment: fixed`  

---

## 🚀 Como usar

1. Clone ou baixe este repositório.  
2. Abra o arquivo `index.html` no navegador de sua preferência.  
3. Navegue pelas seções para ler o poema e visualizar os efeitos de estilo.  

> **Observação:** As imagens de fundo (`background001.jpg` e `background002.jpg`) devem estar na pasta `imagens/` para que as seções `.imagem` funcionem corretamente.

---

## 📁 Estrutura de arquivos
/ (pasta raiz)
│
├── index.html # Arquivo principal da página
├── estilo/
│ └── style.css # Estilos do site
└── imagens/
├── background001.jpg
└── background002.jpg
