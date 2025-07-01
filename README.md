# Calculadora de Consumo de Combustível

## 📋 Descrição

Este é um programa JavaScript simples que calcula o custo total de uma viagem baseado no consumo de combustível. O programa foi desenvolvido como parte de um desafio de JavaScript para praticar conceitos básicos de programação.

## 🚀 Funcionalidades

- Calcula o consumo total de combustível em litros
- Determina o custo total da viagem em reais
- Utiliza variáveis para facilitar a personalização dos valores

## 📊 Como Funciona

O programa utiliza as seguintes variáveis:
- **Preço do combustível**: R$ 5,79 por litro
- **Consumo médio**: 12 km por litro
- **Distância da viagem**: 1.100 km

### Fórmulas Utilizadas

1. **Consumo de combustível**:
   ```
   Litros necessários = Distância ÷ Consumo médio (km/l)
   ```

2. **Custo total**:
   ```
   Custo total = Litros necessários × Preço por litro
   ```

## 💻 Como Executar

1. Certifique-se de ter o Node.js instalado em seu computador
2. Abra o terminal na pasta do projeto
3. Execute o comando:
   ```bash
   node "DESAFIO 1 - CALCULO KM-L.js"
   ```

## 📁 Estrutura do Projeto

```
JS/
├── DESAFIO 1 - CALCULO KM-L.js    # Arquivo principal do programa
└── README.md                      # Este arquivo de documentação
```

## 🔧 Personalização

Para adaptar o programa às suas necessidades, você pode modificar as seguintes variáveis no início do arquivo:

```javascript
const preco = 5.79;        // Preço do combustível por litro
const kmPorLitro = 12;     // Consumo médio do veículo (km/l)
const distancia = 1100;    // Distância da viagem em km
```

## 📝 Exemplo de Saída

Com os valores padrão configurados, o programa calculará:
- **Distância**: 1.100 km
- **Consumo**: 91,67 litros (1.100 ÷ 12)
- **Custo total**: R$ 530,77 (91,67 × 5,79)

## 🛠️ Tecnologias Utilizadas

- **JavaScript** - Linguagem de programação principal
- **Node.js** - Ambiente de execução

## 👨‍💻 Desenvolvimento

Este projeto foi criado como parte de um desafio de JavaScript para praticar:
- Declaração de variáveis
- Operações matemáticas
- Console.log para exibição de resultados

## 📄 Licença

Este projeto é de uso livre para fins educacionais e de aprendizado.

---

**Desenvolvido como parte de um desafio de JavaScript** 🚗⛽ 