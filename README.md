# virus-spread-simulator

Este projeto é um **Simulador Epidemiológico Estocástico** desenvolvido em Java. Ele utiliza o **Método de Monte Carlo** para modelar como um vírus se espalha em uma população dinâmica, permitindo a análise de variáveis como taxa de contágio, letalidade e tempo de recuperação.

## 🧪 O Conceito Científico
Diferente de modelos lineares, este simulador baseia-se em **probabilidades aleatórias**. Através da função `Math.random()`, o algoritmo decide em tempo real o destino de cada indivíduo na lista, simulando o caos e a imprevisibilidade de um surto real.

## 🚀 Funcionalidades
- **Paciente Zero:** Introdução aleatória de um agente infectado em uma população saudável.
- **Dinâmica de Contágio:** Probabilidade de infecção baseada na proximidade (vizinhos na lista).
- **Estados da População:**
  - `O`: Saudável
  - `X`: Infectado
  - `R`: Recuperado (Imune)
  - `.` : Mortalidade (Removido da lista)
- **Relatórios Diários:** Exibição de estatísticas e gráficos de barras em ASCII no console.

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** Java (JDK 17+)
- **Estruturas de Dados:** `ArrayList` para manipulação dinâmica da população.
- **Lógica:** Estruturas de repetição (`while`, `for`) e condicionais complexas.

## 📋 Como Executar
1. Clone o repositório:
   ```bash
   git clone [https://github.com/biancamgomes/virus-spread-simulator.git](https://github.com/biancamgomes/virus-spread-simulator.git)
