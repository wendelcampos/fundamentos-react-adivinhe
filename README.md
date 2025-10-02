# 🎯 Adivinhe - Jogo de Palavras

Um jogo interativo de adivinhação de palavras desenvolvido com React.js para praticar os fundamentos da biblioteca.

## 📋 Sobre o Projeto

Este é um projeto educativo que implementa um jogo de adivinhação de palavras, onde o jogador deve descobrir uma palavra oculta através de dicas e tentativas limitadas. O projeto foi desenvolvido para demonstrar e praticar os conceitos fundamentais do React.js.

## 🎮 Como Jogar

1. **Objetivo**: Descubra a palavra oculta usando as dicas fornecidas
2. **Tentativas**: Você tem um número limitado de tentativas (palavra + 5 tentativas extras)
3. **Dicas**: Cada palavra possui uma dica para ajudar na descoberta
4. **Letras**: Digite uma letra por vez e confirme sua escolha
5. **Feedback**: Letras corretas aparecem na posição certa, letras incorretas são marcadas como usadas

## 🚀 Tecnologias Utilizadas

- **React 19.1.1** - Biblioteca principal para construção da interface
- **TypeScript** - Para tipagem estática
- **Vite** - Build tool e servidor de desenvolvimento
- **CSS Modules** - Para estilização modular
- **ESLint** - Para análise de código

## 🏗️ Estrutura do Projeto

```
src/
├── components/          # Componentes reutilizáveis
│   ├── Button/         # Botão customizado
│   ├── Header/         # Cabeçalho do jogo
│   ├── Input/          # Campo de entrada
│   ├── Letter/         # Componente de letra
│   ├── LettersUsed/    # Lista de letras utilizadas
│   └── Tip/            # Componente de dica
├── utils/              # Utilitários e dados
│   └── words.ts        # Banco de palavras e dicas
├── assets/             # Recursos estáticos
├── App.tsx             # Componente principal
├── main.tsx            # Ponto de entrada
└── global.css          # Estilos globais
```

## 🎯 Conceitos do React Demonstrados

### 1. **Componentes Funcionais**
- Estrutura de componentes usando funções
- Props e tipagem com TypeScript
- Composição de componentes

### 2. **Hooks Essenciais**
- `useState`: Gerenciamento de estado local
- `useEffect`: Efeitos colaterais e ciclo de vida
- Estado para: pontuação, letras usadas, desafio atual

### 3. **Gerenciamento de Estado**
- Estado local no componente principal
- Atualização de estado baseada em ações do usuário
- Estado derivado para lógica do jogo

### 4. **Event Handling**
- Manipulação de eventos de clique
- Eventos de input e formulários
- Confirmações do usuário

### 5. **Renderização Condicional**
- Renderização baseada no estado do jogo
- Componentes condicionais para diferentes fases

### 6. **Listas e Keys**
- Renderização de listas com `map()`
- Uso correto de keys para otimização

### 7. **CSS Modules**
- Estilização modular e escopada
- Classes CSS específicas por componente

## 🛠️ Como Executar

### Pré-requisitos
- Node.js (versão 18 ou superior)
- npm ou yarn

### Instalação
```bash
# Clone o repositório
git clone <url-do-repositorio>

# Entre no diretório
cd adivinhe

# Instale as dependências
npm install
```

### Executar o Projeto
```bash
# Modo desenvolvimento
npm run dev

# Build para produção
npm run build

# Preview da build
npm run preview

# Linting
npm run lint
```

## 📚 Aprendizados Práticos

### Estado e Interatividade
- Como gerenciar múltiplos estados em um componente
- Sincronização entre diferentes estados
- Validação de entrada do usuário

### Lógica de Jogo
- Implementação de regras de negócio
- Controle de fluxo do jogo
- Feedback visual para o usuário

### Componentização
- Separação de responsabilidades
- Reutilização de componentes
- Props e comunicação entre componentes

### TypeScript
- Tipagem de props e estado
- Interfaces para estruturas de dados
- Type safety em todo o projeto

## 🎨 Personalização

### Adicionando Novas Palavras
Edite o arquivo `src/utils/words.ts` para adicionar novas palavras e dicas:

```typescript
export const WORDS: Challenge[] = [
  // ... palavras existentes
  { id: 6, word: "NOVA_PALAVRA", tip: "Sua dica aqui" },
]
```

### Modificando Estilos
Cada componente possui seu próprio arquivo CSS Module em `styles.module.css` para personalização independente.

## 🤝 Contribuição

Este é um projeto educativo. Sinta-se livre para:
- Adicionar novas funcionalidades
- Melhorar a interface
- Adicionar mais palavras ao banco de dados
- Implementar novos conceitos do React

## 📝 Licença

Este projeto é para fins educacionais e pode ser usado livremente para aprendizado.

---

**Desenvolvido para praticar os fundamentos do React.js** ⚛️