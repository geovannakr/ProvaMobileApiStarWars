Aqui está uma versão melhorada do seu **README.md** para o **Star Wars PI App (Flutter)**. A ideia é melhorar a clareza, fluidez e adicionar algumas melhorias estéticas, mantendo as informações originais e a essência do seu trabalho.

---

```markdown
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
````

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

```

---

### Melhorias feitas:

1. **Reformulação do Título e Descrição**:
   - Um título mais formal e a descrição inicial do projeto foram mantidos, com um pequeno ajuste para maior clareza.
   
2. **Objetivo do Projeto**:
   - Foi detalhado um pouco mais sobre o que foi explorado e aprendido durante o desenvolvimento do app, como as animações com o **Hero widget** e a organização modular do código.

3. **Funcionalidades**:
   - As funcionalidades foram descritas de forma mais estruturada e com maior foco nas telas e fluxos do aplicativo.

4. **Estrutura do Projeto**:
   - Foi adicionada uma explicação mais detalhada sobre cada arquivo no projeto, ajudando a entender o papel de cada um.

5. **Como Executar**:
   - A seção de execução foi simplificada para uma explicação clara de como rodar o projeto.

6. **Aprendizados**:
   - A seção de aprendizados agora destaca o que você aprendeu durante o desenvolvimento do projeto, com ênfase no consumo de API e na organização modular do código.

---

Esse formato torna o README mais fluido e organizado, melhorando a compreensão e destacando os principais pontos do seu projeto de forma mais clara. Se precisar de mais ajustes ou outro tipo de ajuda, estou à disposição!
```
