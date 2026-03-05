# 🎮 Pokédex

Uma aplicação web interativa e responsiva que permite buscar e visualizar informações detalhadas sobre Pokémons. Desenvolvida com HTML, CSS e JavaScript puro, utilizando a [PokéAPI](https://pokeapi.co/) como fonte de dados.

## ✨ Funcionalidades

- 🔍 **Busca por Nome ou Número**: Procure qualquer Pokémon digitando seu nome ou número de Pokédex
- ⏪ **Navegação**: Botões "Anterior" e "Próximo" para navegar entre Pokémons sequencialmente
- 🖼️ **Imagens Animadas**: Exibição de sprites animados dos Pokémons (quando disponíveis)
- 📱 **Design Responsivo**: Interface otimizada para desktop, tablet e celular
- ⚡ **Carregamento Dinâmico**: Busca em tempo real usando a PokéAPI
- 🎨 **Interface Intuitiva**: Design inspirado no visual clássico da Pokédex

## 🚀 Como Usar

1. Abra o arquivo `index.html` em seu navegador web
2. Você verá o primeiro Pokémon (Bulbassauro) carregado por padrão
3. Use a caixa de busca para:
   - Digitar o **nome** do Pokémon (ex: "pikachu")
   - Digitar o **número** do Pokémon (ex: "25")
4. Clique nos botões **Prev** e **Next** para navegar entre Pokémons
5. Pressione Enter ou clique em "Buscar" para executar a busca

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica da página
- **CSS3**: Estilização responsiva e efeitos visuais
- **JavaScript (ES6+)**: Lógica da aplicação e integração com API
- **PokéAPI**: API gratuita com dados de Pokémons
- **Fetch API**: Requisições HTTP assíncronas

## 📁 Estrutura do Projeto

```
Pokedex/
├── index.html          # Arquivo principal com HTML
├── style.css           # Estilos e layout responsivo
├── script.js           # Lógica e interatividade
├── README.md           # Este arquivo
├── favicons/          # Ícones do projeto
│   └── favicons/
│       └── favicon-16x16.png
├── images/            # Imagens estáticas
│   └── pokedex.png    # Imagem de fundo da Pokédex
└── .gitignore         # Arquivos ignorados pelo Git
```

## 💻 Instalação Local

1. Clone o repositório:
   ```bash
   git clone https://github.com/EdcarlosJunior/Pokedex.git
   cd Pokedex
   ```

2. Abra o arquivo `index.html` diretamente no navegador, ou use um servidor local:
   ```bash
   # Com Python 3
   python -m http.server 8000
   
   # Com Python 2
   python -m SimpleHTTPServer 8000
   ```

3. Acesse `http://localhost:8000` no seu navegador

## 🔧 Melhorias Futuras

- [ ] Adicionar informações de tipos de Pokémon
- [ ] Exibir habilidades e estatísticas
- [ ] Filtro por tipo de Pokémon
- [ ] Modo favoritos (localStorage)
- [ ] Paginação automática
- [ ] Tema escuro/claro

## 🌐 API Utilizada

Dados fornecidos pela [PokéAPI](https://pokeapi.co/) - uma API RESTful completa e gratuita para dados de Pokémon.

## 📝 Licença

Este projeto é de código aberto e está disponível sob a licença MIT.

## 👤 Autor

**Edcarlos Junior**  
GitHub: [@EdcarlosJunior](https://github.com/EdcarlosJunior)

---

Desenvolvido com ❤️ para fãs de Pokémon
