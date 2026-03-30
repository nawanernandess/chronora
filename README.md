# Chronora

Relógio digital e cronômetro com interface minimalista.

## Preview

<p align="center">
  <img src="assets/images/preview-desktop.png" width="600"/>
  <img src="assets/images/preview-mobile.png" width="220"/>
</p>

## Funcionalidades

### 🕐 Relógio
- Exibe a hora atual em tempo real no formato **HH:MM:SS**
- Exibe a data completa por extenso em português (ex: _sábado, 28 de março de 2026_)
- Atualização automática a cada segundo

### ⏱ Cronômetro
- Contagem de **horas, minutos, segundos e centésimos**
- **Iniciar** a contagem
- **Pausar** e retomar a qualquer momento
- **Registrar voltas** (laps) durante a contagem
- **Resetar** o cronômetro e limpar as voltas registradas

## Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura da página |
| CSS3 | Estilização e layout |
| JavaScript (ES6+) | Lógica do relógio e cronômetro |
| [Bootstrap 5](https://getbootstrap.com/) | Navegação em abas e utilitários |
| [Font Awesome 6](https://fontawesome.com/) | Ícones do menu |

## Como Usar

### Relógio
A aba **Relógio** é exibida automaticamente ao abrir o projeto. A hora e a data são atualizadas em tempo real, sem nenhuma interação necessária.

### Cronômetro
1. Clique na aba **Cronômetro** no menu lateral
2. Pressione ▶ para **iniciar** a contagem
3. Pressione 🚩 para **registrar uma volta** (pode ser feito quantas vezes quiser)
4. Pressione ⏸ para **pausar**
5. Com o cronômetro pausado, pressione **Reset** para zerar e limpar as voltas

## Como Rodar o Projeto

Por ser uma aplicação front-end pura (sem dependências ou build), basta abrir o arquivo diretamente no navegador:

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/chronora.git
```

2. Acesse a pasta do projeto:
```bash
cd chronora
```

3. Abra o arquivo `index.html` no navegador

> Recomendado: use a extensão **Live Server** no VS Code para recarregamento automático.

## Estrutura do Projeto

```
chronora/
├── assets/
│   └── icons/
│       ├── clock.png       # Favicon e ícone do menu
│       ├── flag.png        # Botão de volta
│       ├── pause.png       # Botão de pausar
│       ├── play.png        # Botão de iniciar
│       └── square.png      # Ícone reserva
├── index.html              # Página principal (estrutura HTML)
├── index.js                # Lógica do relógio e cronômetro
├── style.css               # Estilização da interface
└── README.md
```
