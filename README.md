
# 🎮 Jogo da Forca em Python

Este é um simples jogo da forca implementado em Python. O objetivo é adivinhar a palavra secreta, letra por letra, antes que todas as chances se esgotem.

## 🧠 Como funciona

- O programa escolhe aleatoriamente uma palavra de uma lista.
- O jogador tem **7 chances** para errar.
- A cada rodada, o jogador digita uma letra.
- Se a letra estiver correta, ela aparece nas posições correspondentes da palavra.
- Se a letra estiver errada, o número de chances restantes diminui.
- O jogo termina quando:
  - O jogador adivinha toda a palavra corretamente (vitória).
  - O jogador erra 7 vezes (derrota).

## 📦 Pré-requisitos

- Python 3 instalado.

## ▶️ Como jogar

1. Salve o código em um arquivo, por exemplo, `forca.py`.
2. No terminal, execute o arquivo com:

```bash
python forca.py
```

3. Siga as instruções no terminal para digitar as letras.

## 📝 Exemplo de execução

```
_ _ _ _ _ _
Você tem 7 chances
Escolha uma letra para advinhar: a
_ _ _ a _ _
Você tem 7 chances
Escolha uma letra para advinhar: b
_ _ _ a _ _
Você tem 6 chances
...
Parabéns. você ganhou. A palavra era: aula
```

## 🛠️ Melhorias possíveis

- Mostrar as letras já tentadas.
- Tratar entradas inválidas (como números ou mais de uma letra).
- Adicionar um sistema de pontuação.
- Permitir reiniciar o jogo após o término.
