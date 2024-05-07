# Sistema de Gerenciamento de Hotel

Este é um sistema de gerenciamento de hotel desenvolvido em Java. Ele simula as operações básicas de um hotel, incluindo check-in, check-out, limpeza de quartos e acomodação de grupos de hóspedes.

## Funcionalidades

- **Recepcionistas:** Responsáveis por realizar o check-in dos hóspedes e alocar quartos.
- **Camareiras:** Encarregadas da limpeza dos quartos.
- **Hóspedes:** Representam os visitantes do hotel.
- **Main:** Classe responsável por executar o projeto.
- **Hotel:** Recebe os Hospedes, tem seus quartos para abrigar esses hospedes, tem seus funcionarios que são as camareiras e recepcionistas.

## Classes

- `Recepcionista.java`: Esta classe modela o serviço de recepcionista no hotel. Ele realiza o check-in dos hóspedes, alocando quartos conforme disponibilidade.
- `Camareira.java`: Representa o serviço de camareira no hotel. Esta classe é responsável pela limpeza dos quartos.
- `Hospede.java`: Classe que representa um hóspede no hotel. Os hóspedes podem realizar check-in, passear pela cidade e retornar ao hotel.
- `Hotel.java`: Esta classe define a estrutura principal do hotel, incluindo a lista de quartos, fila de espera para grupos de hóspedes e métodos para alocar e liberar quartos.
- `Quarto.java`: Representa um quarto do hotel. Ele mantém uma lista de hóspedes, indica se está pronto para limpeza e fornece métodos para gerenciar os hóspedes.
- `Recepcionista.java`: Classe que representa um recepcionista em um hotel. Ele é responsável por realizar o check-in dos hóspedes, alocando quartos conforme disponibilidade.

## Instruções de Uso

Para utilizar este sistema, basta executar a classe `Main.java`, que inicializa e executa a simulação do hotel.

## Contribuidores

- Talys Alexandre Nobre
- Christian Noronha Picoli
- Joel Alves dos Santos
- Rafael Cutrim de Almeida
- Renan da Costa e Silva Sousa

## Licença

Este projeto está licenciado sob a Licença MIT.
