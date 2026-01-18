# Jogo de Adivinhacao - Adivinhe o Numero

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Swing-GUI-blue?style=for-the-badge" alt="Swing">
  <img src="https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge" alt="Status">
</p>

## Sobre o Projeto

Aplicacao desktop desenvolvida em **Java** com interface grafica **Swing JFrame**, inspirada no estilo do Akinator. O programa sorteia um numero aleatorio entre **1 e 5** e o jogador deve tentar adivinhar qual e o numero secreto.

O jogo fornece dicas a cada tentativa, informando se o numero secreto e **maior** ou **menor** que o palpite do jogador, ate que ele acerte!

---

## Origem do Projeto

> Este projeto foi desenvolvido durante o **Curso de Java - 40 Horas** ministrado pelo professor **Gustavo Guanabara** no [Curso em Video](https://www.cursoemvideo.com/).

O curso oferece uma base solida em programacao Java, abordando desde conceitos fundamentais ate a criacao de interfaces graficas com Swing.

---

## Como Funciona

```
1. O programa sorteia um numero aleatorio entre 1 e 5
2. O jogador insere seu palpite
3. O programa responde:
   - "O numero e MAIOR!" - se o numero secreto for maior que o palpite
   - "O numero e MENOR!" - se o numero secreto for menor que o palpite
   - "PARABENS! Voce acertou!" - se o palpite estiver correto
4. O jogo conta quantas tentativas foram necessarias
```

---

## Funcionalidades

- [x] Geracao de numero aleatorio entre 1 e 5
- [x] Interface grafica amigavel com Swing JFrame
- [x] Sistema de dicas (maior/menor)
- [x] Contador de tentativas
- [x] Mensagem de vitoria ao acertar
- [x] Botao para iniciar novo jogo
- [x] Validacao de entrada (apenas numeros de 1 a 5)

---

## Screenshot

```
<img width="520" height="570" alt="image" src="https://github.com/user-attachments/assets/cd89c80d-f742-45d3-bdc2-86e7c263b45f" />

```

---

## Pre-requisitos

Antes de executar o projeto, certifique-se de ter instalado:

- **Java JDK 8** ou superior
- Uma IDE de sua preferencia (NetBeans, Eclipse, IntelliJ IDEA, VS Code)

---

## Como Executar

1. **Clone o repositorio**
   ```bash
   git clone https://github.com/seu-usuario/jogo-adivinhacao-java.git
   ```

2. **Acesse a pasta do projeto**
   ```bash
   cd jogo-adivinhacao-java
   ```

3. **Compile o projeto**
   ```bash
   javac Main.java
   ```

4. **Execute a aplicacao**
   ```bash
   java Main
   ```

> **Dica:** Se estiver usando uma IDE como NetBeans ou Eclipse, basta abrir o projeto e clicar em "Run".

---

## Estrutura do Projeto

```
jogo-adivinhacao-java/
|
+-- src/
|   +-- Main.java           # Classe principal
|   +-- JogoAdivinhacao.java # Logica do jogo
|   +-- TelaJogo.java       # Interface Swing
|
+-- README.md
```

---

## Tecnologias Utilizadas

- **Java SE** - Linguagem de programacao
- **Swing** - Biblioteca para interface grafica
- **JFrame** - Container principal da aplicacao
- **JTextField** - Campo de entrada do palpite
- **JButton** - Botoes de acao
- **JLabel** - Exibicao de mensagens e dicas
- **Random** - Classe para geracao de numeros aleatorios

---

## Logica do Jogo

```java
// Exemplo da logica principal
Random random = new Random();
int numeroSecreto = random.nextInt(5) + 1; // Gera numero de 1 a 5

if (palpite == numeroSecreto) {
    // Jogador acertou!
} else if (palpite < numeroSecreto) {
    // Dica: O numero e maior
} else {
    // Dica: O numero e menor
}
```

---

## Aprendizados

Durante o desenvolvimento deste projeto, foram aplicados os seguintes conceitos:

- Programacao Orientada a Objetos (POO)
- Criacao de interfaces graficas com Swing
- Manipulacao de eventos (ActionListener)
- Geracao de numeros aleatorios (classe Random)
- Estruturas condicionais (if/else)
- Tratamento de excecoes
- Variaveis de contagem

---

## Possiveis Melhorias

- [ ] Aumentar o intervalo de numeros (1-10, 1-100)
- [ ] Adicionar niveis de dificuldade
- [ ] Implementar sistema de ranking/pontuacao
- [ ] Adicionar efeitos sonoros
- [ ] Salvar recorde de menor numero de tentativas

---

## Contribuicoes

Contribuicoes sao sempre bem-vindas! Se voce tem alguma sugestao para melhorar este projeto:

1. Faca um Fork do projeto
2. Crie uma Branch para sua feature (`git checkout -b feature/NovaFeature`)
3. Commit suas mudancas (`git commit -m 'Adiciona NovaFeature'`)
4. Push para a Branch (`git push origin feature/NovaFeature`)
5. Abra um Pull Request

---



## Autor

Desenvolvido durante o **Curso de Java 40 Horas** do [Curso em Video](https://www.cursoemvideo.com/)

**Professor:** Gustavo Guanabara

---

## Links Uteis

- [Curso em Video - Java](https://www.cursoemvideo.com/curso/java-basico/)
- [Documentacao Java](https://docs.oracle.com/en/java/)
- [Tutorial Swing](https://docs.oracle.com/javase/tutorial/uiswing/)
- [Classe Random - Java](https://docs.oracle.com/javase/8/docs/api/java/util/Random.html)

---

<p align="center">
  Se este projeto te ajudou, considere dar uma estrela!
</p>
