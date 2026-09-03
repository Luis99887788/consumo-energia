# ⚡ Calculadora de Consumo Elétrico

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![GitHub](https://img.shields.io/badge/GitHub-Projeto-black?logo=github)
![Energia](https://img.shields.io/badge/Energia-Elétrica-yellow)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)

## 📌 Sobre o projeto

A **Calculadora de Consumo Elétrico** é um programa desenvolvido em Python para estimar o consumo mensal de energia elétrica de um aparelho.

O usuário informa o nome do aparelho, sua potência em watts e o tempo médio de utilização por dia. Com essas informações, o programa calcula o consumo estimado em **kWh por mês**.

Além disso, o sistema apresenta uma estimativa do custo mensal utilizando o valor fixo de **R$ 0,75 por kWh**.

## 🎯 Objetivo

O objetivo do projeto é ajudar o usuário a entender quanto um aparelho elétrico pode consumir de energia durante um mês e ter uma estimativa de seu custo.

## 🐍 Linguagem utilizada

* Python

## 🧮 Fórmula utilizada

O consumo mensal é calculado utilizando a seguinte fórmula:

**Consumo mensal = (Potência × Horas por dia × 30) ÷ 1000**

Para calcular o custo estimado:

**Custo mensal = Consumo mensal × R$ 0,75**

## 💻 Como executar

### 1. Baixe ou clone o projeto

Abra o projeto no Visual Studio Code.

### 2. Verifique se o Python está instalado

No terminal do VS Code, execute:

```bash
python --version
```

### 3. Execute o programa

No terminal, digite:

```bash
python app.py
```

### 4. Informe os dados solicitados

O programa irá pedir:

* Nome do aparelho;
* Potência em watts (W);
* Tempo médio de uso diário em horas.

Depois, o sistema apresentará o consumo mensal e o custo estimado.

## 📝 Exemplo

```text
===================================
   CALCULADORA DE CONSUMO ELÉTRICO
===================================

Digite o nome do aparelho: Geladeira
Digite a potência do aparelho em watts (W): 200
Digite o tempo de uso diário em horas: 8

----------- RESULTADO -----------
Aparelho: Geladeira
Consumo estimado: 48.00 kWh/mês
Custo estimado: R$ 36.00 por mês
---------------------------------
```

## 🛠️ Tecnologias utilizadas

* 🐍 Python
* 💻 Visual Studio Code
* 🌐 GitHub
* 🔧 Git

## 📂 Estrutura do projeto

```text
consumo-energia/
├── app.py
└── README.md
```

## ⚡ Funcionalidades

* ✅ Cadastro do nome do aparelho;
* ✅ Entrada da potência em watts;
* ✅ Entrada do tempo de uso diário;
* ✅ Cálculo do consumo mensal;
* ✅ Estimativa do custo de energia;
* ✅ Exibição dos resultados no terminal.

## 👨‍💻 Autor

Projeto desenvolvido como atividade de iniciação em tecnologia e programação.

---

⚡ **Calculadora de Consumo Elétrico — Python**

📚 Projeto desenvolvido para fins educacionais.