# Star Wars PI App (Flutter)

Este aplicativo Flutter foi desenvolvido como parte de um trabalho avaliativo na unidade curricular de **Programação Mobile**. O objetivo do projeto é consumir a API de Star Wars e criar uma experiência de navegação entre personagens, com foco na simplicidade e funcionalidade da interface.

## Por que Star Wars?
Originalmente, a ideia era utilizar a **API do Breaking Bad**, mas devido a problemas técnicos de funcionamento, optei pela **API de Star Wars**, que se mostrou mais estável e adequada para o escopo do projeto. A escolha também permitiu uma exploração mais rica de personagens e informações.

---

## Funcionalidades

* **Listagem de personagens**: Tela inicial exibe a lista de personagens com seus dados básicos. (arquivo: `home_screen.dart`).
* **Tela de detalhes**: Ao selecionar um personagem, uma tela detalhada é exibida com mais informações. (arquivo: `character_details_screen.dart`).
* **Organização modular**: O projeto é organizado em arquivos separados para facilitar a manutenção e legibilidade:
  - `main.dart`: Ponto de entrada da aplicação.
  - `api_service.dart`: Serviço responsável pelas requisições HTTP para a API.
  - `person.dart`: Modelo que representa os dados dos personagens.

**Observação**: Optou-se por não utilizar imagens neste projeto devido a dificuldades técnicas encontradas. No entanto, o visual foi priorizado para compensar essa limitação, com um layout limpo e bem estruturado.

---

## Estrutura do Projeto

Abaixo está a estrutura de pastas e arquivos do projeto:

```

lib/
├── main.dart                # Ponto de entrada da aplicação.
├── models/
│   └── person.dart          # Modelo de dados dos personagens.
├── services/
│   └── api_service.dart     # Serviço para consumir a API.
├── screens/
│   ├── home_screen.dart     # Tela inicial com a lista de personagens.
│   └── character_details_screen.dart # Tela de detalhes do personagem.

````

---

## Objetivo do Projeto

O principal objetivo deste projeto foi criar um **app Flutter** que fosse capaz de:

* Consumir uma **API externa** (Star Wars API) para apresentar uma lista de personagens.
* Implementar uma **navegação fluida** entre telas.
* Manter o código bem **organizado** e modularizado.
* Trabalhar com **tratamento de erros** e **carregamento de dados**.
* (Opcional) Explorar animações e transições utilizando o **Hero widget**.

---

## Como Executar

1. **Abra o projeto** no seu editor Flutter preferido (VS Code, Android Studio, etc.).
2. Execute o comando ou atalho:

   ```bash
   flutter run


ou, se preferir, use o atalho `F5` para rodar o app.

3. Aguarde o **carregamento** e comece a navegar pelas telas do app.

---

## Aprendizados

Durante o desenvolvimento deste projeto, pude aprender e aplicar vários conceitos importantes no **Flutter**:

* **Consumo de API** e transformação dos dados da resposta em modelos **Dart**.
* **Navegação entre telas** no Flutter, utilizando `Navigator` e parâmetros.
* Como **organizar o código** de forma modular, dividindo a aplicação em serviços, modelos e telas.
* Como lidar com **problemas técnicos** (como a falta de imagens) e contornar essas limitações sem afetar a experiência do usuário.

---

**Geovanna de Sousa Krüger**
**MIDS 76**
