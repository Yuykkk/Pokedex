<div align="center">

  <img src="./recursos/images/Pokemon-Logo.png" width="420" alt="Logo Pokémon" />

  <br>

  <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/25.png" width="72" alt="Pikachu" />
  <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/1.png" width="72" alt="Bulbasaur" />
  <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/4.png" width="72" alt="Charmander" />
  <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/7.png" width="72" alt="Squirtle" />
  <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/133.png" width="72" alt="Eevee" />

  <h1>Pokédex</h1>

  <p>
    Uma Pokédex feita para pesquisar Pokémon, ver informações, evoluções, versão shiny e cartas TCG.
  </p>

  <p>
    <img src="https://img.shields.io/badge/HTML-ffcb05?style=for-the-badge&logo=html5&logoColor=2a3f9d" alt="HTML" />
    <img src="https://img.shields.io/badge/CSS-2a3f9d?style=for-the-badge&logo=css3&logoColor=ffcb05" alt="CSS" />
    <img src="https://img.shields.io/badge/JAVASCRIPT-d62828?style=for-the-badge&logo=javascript&logoColor=ffcb05" alt="JavaScript" />
    <img src="https://img.shields.io/badge/PokeAPI-ffffff?style=for-the-badge&logo=pokemon&logoColor=d62828" alt="PokeAPI" />
    <img src="https://img.shields.io/badge/TCGdex-111111?style=for-the-badge&logo=cardano&logoColor=ffcb05" alt="TCGdex" />
  </p>

  <p>
    <a href="https://yuykkk.github.io/Pokedex/">
      <img src="https://img.shields.io/badge/TESTAR%20PROJETO-ffcb05?style=for-the-badge&logo=githubpages&logoColor=2a3f9d" alt="Testar projeto online" />
    </a>
  </p>

</div>

---

<h2 align="center">Sobre o Projeto</h2>

<p align="center">
  Esse projeto é uma Pokédex web com busca por Pokémon e uma área separada para pacotes de cartas TCG.
  A ideia é juntar informações principais dos Pokémon com um visual leve, colorido e com cara de Pokédex.
</p>

<div align="center">
  <img src="./recursos/images/pokedex.png" width="96" alt="Ícone da Pokédex" />
</div>

---

<h2 align="center">Funcionalidades</h2>

<table>
  <tr>
    <td width="50%">
      <strong>Busca de Pokémon</strong><br>
      Pesquise pelo nome e veja sugestões enquanto digita.
    </td>
    <td width="50%">
      <strong>Informações completas</strong><br>
      Mostra tipo, habilidades, peso, altura, status base e descrição.
    </td>
  </tr>
  <tr>
    <td width="50%">
      <strong>Evoluções</strong><br>
      Navegação entre a cadeia de evolução do Pokémon pesquisado.
    </td>
    <td width="50%">
      <strong>Modo shiny</strong><br>
      Alterna o sprite normal e shiny quando disponível.
    </td>
  </tr>
  <tr>
    <td width="50%">
      <strong>Fraquezas e resistências</strong><br>
      Calcula relações de dano pelos tipos do Pokémon.
    </td>
    <td width="50%">
      <strong>Histórico de pesquisa</strong><br>
      Guarda os últimos Pokémon pesquisados no navegador.
    </td>
  </tr>
  <tr>
    <td width="50%">
      <strong>Cartas TCG</strong><br>
      Busca cartas relacionadas ao Pokémon usando a TCGdex.
    </td>
    <td width="50%">
      <strong>Pacotes TCG</strong><br>
      Pesquisa pacotes, lista cartas, filtra por tipo, raridade e especiais.
    </td>
  </tr>
</table>

---

<h2 align="center">Preview</h2>

<p align="center">
  <img src="./referencias/Captura%20de%20tela%202026-04-08%20112137.png" width="420" alt="Preview da Pokédex" />
  <img src="./referencias/Captura%20de%20tela%202026-04-08%20112205.png" width="420" alt="Preview das informações do Pokémon" />
</p>

<p align="center">
  <img src="./referencias/Captura%20de%20tela%202026-04-08%20112720.png" width="420" alt="Preview das cartas TCG" />
</p>

---

<h2 align="center">Como Rodar</h2>

<p align="center">
  <a href="https://yuykkk.github.io/Pokedex/">
    <img src="https://img.shields.io/badge/ABRIR%20SITE%20ONLINE-2a3f9d?style=for-the-badge&logo=githubpages&logoColor=ffcb05" alt="Abrir site online" />
  </a>
</p>

```bash
git clone https://github.com/Yuykkk/Pokedex.git
cd Pokedex
```

Depois é só abrir o arquivo `index.html` no navegador.

Se quiser rodar com um servidor local:

```bash
python -m http.server 8000
```

Abra no navegador:

```text
http://localhost:8000
```

---

<h2 align="center">APIs Usadas</h2>

<table>
  <tr>
    <td><strong>PokeAPI</strong></td>
    <td>Busca dados dos Pokémon, sprites, tipos, espécies e evolução.</td>
  </tr>
  <tr>
    <td><strong>TCGdex API</strong></td>
    <td>Busca cartas, pacotes, imagens, raridades e dados do TCG.</td>
  </tr>
  <tr>
    <td><strong>Tradutores externos</strong></td>
    <td>Usados como apoio para traduzir descrições quando necessário.</td>
  </tr>
</table>

---

<h2 align="center">Estrutura</h2>

```text
Pokedex/
├─ index.html
├─ styles.css
├─ tcg_set_base1.json
├─ recursos/
│  └─ images/
│     ├─ Pokemon-Logo.png
│     └─ pokedex.png
└─ referencias/
   └─ capturas de tela do projeto
```

---

<h2 align="center">Tecnologias</h2>

<p align="center">
  <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/6.png" width="64" alt="Charizard" />
  <img src="https://img.shields.io/badge/HTML-ffcb05?style=for-the-badge&logo=html5&logoColor=2a3f9d" alt="HTML" />
  <img src="https://img.shields.io/badge/CSS-2a3f9d?style=for-the-badge&logo=css3&logoColor=ffcb05" alt="CSS" />
  <img src="https://img.shields.io/badge/JavaScript-d62828?style=for-the-badge&logo=javascript&logoColor=ffcb05" alt="JavaScript" />
  <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/9.png" width="64" alt="Blastoise" />
</p>

---

<div align="center">
  <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/150.png" width="80" alt="Mewtwo" />
  <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/151.png" width="80" alt="Mew" />

  <p>
    Feito para estudar API, manipulação de DOM, busca, filtros e interface web.
  </p>
</div>
