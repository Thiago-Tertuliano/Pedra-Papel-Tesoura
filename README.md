# 🎮 Pedra, Papel e Tesoura

Um jogo clássico de Pedra, Papel e Tesoura implementado em Python, onde você joga contra o computador!

## ✨ Funcionalidades

- 🎯 Jogador vs Computador
- 📊 Placar persistente salvo em arquivo .txt
- 🎨 Interface colorida com emojis
- 💾 Histórico de partidas
- 🔄 Sistema de menu intuitivo

## 🚀 Como Executar

1. Certifique-se de ter Python 3.6+ instalado
2. Execute o arquivo principal:
   ```bash
   python jogo.py
   ```

## 🎮 Como Jogar

1. Escolha sua jogada:
   - `1` para Pedra ✊
   - `2` para Papel 🖐️
   - `3` para Tesoura ✌️
   - `4` para ver o placar
   - `5` para sair

2. O computador fará sua escolha aleatória
3. O resultado será exibido
4. O placar será atualizado e salvo automaticamente

## 📁 Estrutura do Projeto

```
Pedra-Papel-Tesoura/
├── jogo.py          # Arquivo principal do jogo
├── placar.txt       # Arquivo com o placar (criado automaticamente)
└── README.md        # Este arquivo
```

## 🏆 Sistema de Pontuação

- **Vitória do Jogador**: +1 ponto
- **Vitória do Computador**: +1 ponto  
- **Empate**: +1 empate

O placar é salvo automaticamente após cada partida no arquivo `placar.txt`.

## 🛠️ Tecnologias Utilizadas

- Python 3.6+
- Biblioteca `random` para escolhas aleatórias
- Biblioteca `datetime` para timestamps
- Biblioteca `os` para manipulação de arquivos

## 📝 Exemplo de Uso

```
🎮 PEDRA, PAPEL E TESOURA 🎮
==================================================
Escolha sua jogada:
1 - Pedra ✊
2 - Papel 🖐️
3 - Tesoura ✌️
4 - Ver Placar
5 - Sair
==================================================

Digite sua escolha (1-5): 1

==============================
Você escolheu: Pedra ✊
Computador escolheu: Tesoura ✌️
==============================
🎉 VOCÊ VENCEU!
==============================
```

## 🤝 Contribuições

Sinta-se à vontade para contribuir com melhorias, correções ou novas funcionalidades!

---

Divirta-se jogando! 🎉

Agora vou criar um arquivo de requisitos (opcional, mas útil):

```txt:Pedra-Papel-Tesoura/requirements.txt
# Pedra, Papel e Tesoura - Jogo em Python
# Este projeto usa apenas bibliotecas padrão do Python
# Não são necessárias instalações adicionais

# Bibliotecas utilizadas (já incluídas no Python):
# - random (para escolhas aleatórias)
# - os (para manipulação de arquivos)
# - datetime (para timestamps)
```

E finalmente, vou criar um arquivo de exemplo do placar:

```txt:Pedra-Papel-Tesoura/placar.txt
=== PLACAR PEDRA, PAPEL E TESOURA ===
Data: 01/01/2024 12:00:00
Jogador: 0
Computador: 0
Empates: 0
===================================
```

## 🎮 Projeto Criado com Sucesso!

Criei um projeto completo de Pedra, Papel e Tesoura com as seguintes características:

### ✨ **Funcionalidades Principais:**
- **Jogador vs Computador** com escolhas aleatórias
- **Placar persistente** salvo automaticamente em `placar.txt`
- **Interface amigável** com emojis e menu intuitivo
- **Sistema de pontuação** completo (vitórias, derrotas, empates)

### 📁 **Arquivos Criados:**
- `jogo.py` - Código principal do jogo
- `README.md` - Documentação completa
- `requirements.txt` - Dependências (apenas bibliotecas padrão)
- `placar.txt` - Arquivo de exemplo do placar

### 🚀 **Como Executar:**
1. Navegue até a pasta `Pedra-Papel-Tesoura`
2. Execute: `python jogo.py`
3. Divirta-se jogando!

### 🎯 **Recursos Especiais:**
- **Salvamento automático** do placar após cada partida
- **Histórico de partidas** com data e hora
- **Menu interativo** com opções de visualizar placar
- **Tratamento de erros** robusto
- **Interface visual** com emojis e formatação

O jogo está pronto para ser executado! O placar será salvo automaticamente no arquivo `placar.txt` e você pode verificar suas estatísticas a qualquer momento durante o jogo. 🎉
