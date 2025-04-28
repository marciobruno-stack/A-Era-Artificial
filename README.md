# Projeto do Livro "A Era Artificial"

![Capa do Livro](img/capa-livro.jpg)

Página web promocional para o livro de ficção científica "A Era Artificial" de Diego Souza.

## 📌 Visão Geral

Este projeto consiste em uma página HTML responsiva com:
- Apresentação do livro
- Sinopse da história
- Informações sobre o autor
- Links para compra

## 🛠 Tecnologias Utilizadas

- HTML5
- CSS3
- Imagens otimizadas para web

## 🎨 Estrutura de Arquivos
era-artificial/
├── index.html
├── css/
│ └── style.css
├── img/
│ ├── capa-livro.jpg
│ └── autor.jpg
└── README.md

## ✨ Recursos Implementados

✅ Layout responsivo  
✅ Efeitos hover nos botões  
✅ Estilização moderna com CSS  
✅ Imagens otimizadas  

## 🖥️ Visualização

![Screenshot da Página](img/screenshot.png)

📚 Sobre o Livro

"Era Artificial - O Tempo Sombrio das Máquinas" apresenta um cenário apocalíptico onde robôs alcançaram independência e dominaram o planeta, levando a humanidade a uma luta pela sobrevivência.
👨‍💻 Autor

Diego Souza
![Foto do autos](img/autor.jpg)
Desenvolvedor Web e escritor de ficção científica do Rio de Janeiro.
📜 Licença

MIT License - © 2023 Diego Souza

## 🚀 Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/marciobruno-stack/era-artificial.git

    Abra o arquivo index.html no navegador

📝 Código HTML (trecho)

<div class="sessao1">
  <h1>A Era Artificial</h1>
  <img src="img/capa-livro.jpg" alt="Capa do livro A Era Artificial">
  <h2>Um futuro sombrio a nosso caminho</h2>
  <p>A história em que a inteligência artificial...</p>
  <a href="https://amzn.to/3bXy1g9" class="btn-comprar">COMPRAR</a>
</div>

🎨 Código CSS (trecho)
.btn-comprar {
  background: #2e86de;
  color: white;
  padding: 12px 24px;
  border-radius: 4px;
  transition: all 0.3s ease;
}

.btn-comprar:hover {
  background: #1e6fbf;
  transform: translateY(-2px);
}




Você precisará criar:
1. Pasta `img/` com:
   - `capa-livro.jpg` (400x600px)
   - `autor.jpg` (300x300px)
   - `screenshot.png` (1200x800px)

2. Arquivo `css/style.css` com os estilos completos.

3. Manter a estrutura HTML conforme seu arquivo original, adicionando as classes para estilização.
