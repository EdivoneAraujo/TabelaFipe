# 🚗 TABELA FIPE

Este é um aplicativo Java que permite consultar marcas, modelos e valores de veículos na **Tabela FIPE**. Ele utiliza uma API para obter dados de **carros**, **motos** e **caminhões**. 💸

## ⚙️ Funcionalidades

- Consultar **marcas**, **modelos** e **anos** de veículos.
- Filtrar veículos por nome.
- Exibir valor de mercado por ano de fabricação.

## 🛠️ Tecnologias

- **Java**
- **API FIPE**
- **Gson** para manipulação de JSON.

## 🚀 Como Usar

1. Clone o projeto:
   ```bash
   git clone https://github.com/EdivoneAraujo/TabelaFipe.git
   ```
2. Compile e execute:
   ```bash
   javac Main.java
   java Main
   ```

3. Siga o menu para consultar veículos e ver seus valores!

## 📦 Estrutura

- `Main.java`: Menu principal e lógica do programa.
- `ConsumoAPI.java`: Faz as chamadas à API FIPE.
- `ConversorJSON.java`: Converte os dados JSON.

