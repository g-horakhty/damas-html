# Jogo de Damas

Um jogo de damas completo, desenvolvido em um único arquivo HTML para funcionar offline em qualquer navegador.

## 📋 Sobre o Projeto

Este projeto nasceu da necessidade de ter um jogo de damas completo que funcione em um Chromebook simples, sem necessidade de instalação ou conexão com a internet. O jogo é totalmente contido em um único arquivo HTML, utilizando apenas HTML, CSS e JavaScript puro.

## ✨ Funcionalidades

- **Múltiplas variantes de damas**: Americana/Inglesa, Brasileira e Internacional
- **Inteligência Artificial**: Implementação do algoritmo Minimax com poda Alpha-Beta
- **Personalização**: Escolha sua cor e quem começa o jogo
- **Três níveis de dificuldade**: Fácil, Médio e Difícil
- **Interface responsiva**: Funciona em desktop e dispositivos móveis
- **Modo offline**: Totalmente funcional sem conexão com a internet
- **Sistema de tempo**: Contador de tempo de jogo e movimentos
- **Finalizações automáticas**: Detecta fim de jogo por falta de movimentos ou excesso de jogadas sem capturas

## 🎮 Como Jogar

1. Abra o arquivo `damas.html` em qualquer navegador moderno
2. Selecione a variante de damas desejada
3. Escolha sua cor (Brancas ou Pretas)
4. Defina quem começa jogando
5. Selecione o nível de dificuldade da IA
6. Clique em "Novo Jogo" para começar

### Movimentação:
- Clique em uma peça para selecioná-la
- Clique em uma casa destacada para mover
- As damas são representadas com o símbolo ♔

## 🏗️ Estrutura Técnica

O projeto utiliza uma arquitetura simples mas eficiente:

### Algoritmo de IA
- **Minimax com poda Alpha-Beta**: Para tomada de decisão da IA
- **Função de avaliação**: Considera material, posição e mobilidade
- **Profundidade ajustável**: Diferentes níveis de dificuldade

### Variantes Implementadas

| Variante | Tamanho | Dama Longa | Captura para Trás |
|----------|---------|------------|-------------------|
| Americana/Inglesa | 8x8 | Não | Não |
| Brasileira | 8x8 | Sim | Sim |
| Internacional | 10x10 | Sim | Sim |

### Estrutura de Código
- **Estado do jogo**: Matriz representando o tabuleiro
- **Sistema de coordenadas**: Notação algébrica adaptada
- **Geração de movimentos**: Baseada nas regras específicas de cada variante

## 🚀 Como Executar

1. Faça o download do arquivo `damas-v0.1.html`
2. Abra o arquivo em qualquer navegador moderno (Chrome, Firefox, Edge)
3. O jogo carregará instantaneamente, sem necessidade de instalação

## 📁 Estrutura do Projeto

```
damas.html          # Arquivo único contendo todo o projeto
```

## 🛠️ Tecnologias Utilizadas

- HTML
- CSS3 (Grid, Flexbox, Variáveis CSS)
- JavaScript ES6+
- Algoritmo Minimax com Alpha-Beta Pruning

## 🌟 Recursos Avançados

1. **Design Responsivo**: Interface adaptável a diferentes tamanhos de tela
2. **Feedback Visual**: Destaque de movimentos possíveis e peças selecionadas
3. **Modais Interativos**: Para fim de jogo e informações
4. **Timer Integrado**: Contagem de tempo de jogo
5. **Estatísticas em Tempo Real**: Contagem de peças e damas

## 🔧 Personalização

É possível personalizar o jogo modificando as variáveis CSS no início do arquivo:

```css
:root {
  --bg: #0f172a;           /* Cor de fundo */
  --accent: #22c55e;       /* Cor de destaque */
  --cell-light: #e5d4b7;   /* Cor das casas claras */
  --cell-dark: #8b5a33;    /* Cor das casas escuras */
  /* ... outras variáveis */
}
```

## 📝 Regras Implementadas

- Movimento de peças comuns e damas
- Captura simples e múltipla
- Promoção a dama
- obrigatoriedade de captura (configurável)
- Finalização por falta de movimentos
- Finalização por excesso de jogadas sem captura (30 movimentos)

## 🤝 Contribuindo

Como este é um projeto de arquivo único, contribuições são bem-vindas através de:
1. Fork do projeto
2. Criação de um branch para sua feature
3. Commit das mudanças
4. Push para o branch
5. Abertura de um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

## 🐛 Reportar Problemas

Encontrou um bug ou tem uma sugestão? Sinta-se à vontade para abrir uma issue no repositório.

---

**Nota**: Desenvolvido em Chromebook simples com ChromeOS, mas compatível com qualquer navegador moderno.
