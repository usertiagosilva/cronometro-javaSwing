![cronometro](https://github.com/user-attachments/assets/e53f4f91-af44-4292-94d2-c9d178ecfb8d)



# Cronômetro e Temporizador

Este projeto é uma aplicação Java para um Cronômetro e Temporizador simples, desenvolvido como parte de um projeto acadêmico. A interface gráfica foi criada utilizando o Swing, com funcionalidades de cronômetro e controle de voltas.

## Funcionalidades

- **Cronômetro**: Conta milésimos, segundos e minutos.
- **Temporizador**: Pode ser iniciado e redefinido a qualquer momento.
- **Controle de Voltas**: Possibilidade de registrar voltas, com cálculo do tempo entre elas.

## Estrutura do Projeto

- `Milesimo.java`: Classe responsável por contar os milésimos de segundo.
- `Minuto.java`: Classe responsável por contar os minutos.
- `Segundo.java`: Classe responsável por contar os segundos.
- `Tela.java`: Classe principal que define a interface gráfica e controla o fluxo do programa.

## Pré-requisitos

- **Java JDK 8+**: Certifique-se de ter o Java Development Kit instalado.
- **IDE**: Recomenda-se o uso de uma IDE como IntelliJ IDEA, Eclipse ou netbeans para facilitar o desenvolvimento.

## Como Executar

1. **Clone o repositório**:

    ```bash
    git clone https://github.com/username/cronometro-temporizador.git
    ```

2. **Abra o projeto em sua IDE**.

3. **Compile e execute o projeto**.

4. **Use os botões na interface**:
    - `Iniciar`: Inicia o cronômetro.
    - `Redefinir`: Interrompe e zera o cronômetro.
    - `Volta`: Registra uma volta, calculando o tempo desde a última volta.

## Contribuição

Se quiser contribuir para o projeto, siga os passos abaixo:

1. Fork este repositório.
2. Crie um branch para sua feature (`git checkout -b feature/nome-da-feature`).
3. Faça um commit das suas alterações (`git commit -m 'Adiciona nova feature'`).
4. Faça o push para o branch (`git push origin feature/nome-da-feature`).
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

