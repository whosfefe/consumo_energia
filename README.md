# ⚡ Primeiro Projeto – Calculadora de Consumo Elétrico

Este projeto em **Python** foi desenvolvido para praticar o ciclo:

**Entrada → Processamento → Saída**

O programa solicita ao usuário algumas informações sobre um aparelho elétrico:

1. 🔌 **Nome do equipamento**
2. ⚡ **Potência do aparelho em Watts (W)**
3. ⏱️ **Tempo médio de uso por dia, em horas**

## 📊 Funcionamento

Após inserir os dados, o programa calcula o **consumo estimado de energia elétrica em kWh/mês** do equipamento informado pelo usuário.

A fórmula utilizada é:

```text
Consumo mensal = (Potência × Horas por dia × 30) / 1000
```

Além disso, o programa calcula uma estimativa do custo mensal considerando o valor de **R$ 0,79 por kWh**.

## 💻 Exemplo de saída

```text
Informe o nome do aparelho: Geladeira
Informe a potência em Watts do aparelho: 100
Informe o tempo em horas de uso do aparelho por dia: 10

O consumo estimado de Geladeira é de 30.00 kWh/mês.

O valor estimado do consumo, considerando o custo de R$ 0,79/kWh,
é de R$ 23,70 por mês.
```

## 💰 Cálculo do custo

O custo estimado é calculado utilizando a seguinte fórmula:

```text
Custo mensal = Consumo mensal × Valor do kWh
```

Neste projeto, foi utilizado o valor de referência de **R$ 0,79/kWh**.

> ⚠️ Esse valor é apenas uma referência.

## 🛠️ Tecnologias utilizadas

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge\&logo=python\&logoColor=white)

![GitHub](https://img.shields.io/badge/GitHub-Reposit%C3%B3rio-black?style=for-the-badge\&logo=github\&logoColor=white)

![Energia](https://img.shields.io/badge/Energia-El%C3%A9trica-yellow?style=for-the-badge\&logo=lightning\&logoColor=black)
