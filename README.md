# 🚿⚡ Acqua Energy

> Otimização e monitoramento inteligente de consumo de água e energia elétrica.

![Status do Projeto](https://img.shields.io/badge/Status-Concluído-green) 
![Node.js](https://img.shields.io/badge/Backend-Node.js-green) 
![ESP32](https://img.shields.io/badge/Hardware-ESP32-red)
[![Demo Online](https://img.shields.io/badge/Demo_Online-Acesse_Aqui-blue?style=for-the-badge&logo=github)](https://gabrieldsrod.github.io/acqua-energy/)

## 📖 Sobre o Projeto

O **Acqua Energy** é uma solução IoT (Internet das Coisas) desenvolvida para promover a sustentabilidade doméstica. O sistema utiliza um microcontrolador **ESP32** para monitorar, em tempo real, o consumo de água e energia elétrica durante o banho, enviando os dados para uma interface web onde são convertidos em valores monetários.

O projeto combina sensores físicos com uma interface amigável, permitindo que o usuário visualize gráficos de consumo e faça simulações de gastos baseadas na tarifa local.

🔗 **[Acesse o Site do Projeto](https://gabrieldsrod.github.io/acqua-energy/)**

---

## 🎬 Vídeo Demonstração

Veja o projeto funcionando na prática (Hardware + Dashboard):

[![Assista ao vídeo do Acqua Energy](https://img.youtube.com/vi/sXAoivzwp-M/0.jpg)](https://www.youtube.com/watch?v=sXAoivzwp-M)

> *Clique na imagem acima para assistir no YouTube.*

---

## 🚀 Funcionalidades

* **Monitoramento IoT:** Leitura de fluxo de água e tempo de banho processada pelo **ESP32**.
* **Cálculo de Custos:** Conversão automática do consumo (litros e kWh) para Reais (R$) com base na potência do chuveiro e tarifas configuradas.
* **Dashboard Web:**
    * Gráficos interativos de consumo por banho.
    * Calculadora de estimativa de gastos (input de Tensão, Potência e Estação).
    * Relatórios detalhados de Água, Energia e Esgoto.
* **Sustentabilidade:** Ferramenta de apoio para redução de desperdício.

---

## 🛠 Tecnologias Utilizadas

O projeto foi desenvolvido utilizando uma arquitetura que integra Hardware e Software:

### Hardware & Embarcados
* **ESP32:** Microcontrolador principal responsável pela leitura dos sensores e comunicação.
* **C++:** Linguagem utilizada para programação do firmware do ESP32.
* **Sensores:** Sensores de fluxo de água e eletrônica para medição.

### Software (Web & Backend)
* **Node.js:** Backend para processamento das regras de negócio.
* **JavaScript (Vanilla):** Lógica de interação no frontend e gráficos.
* **HTML5 & CSS3:** Estruturação e estilização do Dashboard responsivo.

---

## 📦 Como executar

### Pré-requisitos
* [Node.js](https://nodejs.org/) instalado.
* Hardware (ESP32 + Sensores) configurado.

### Passo a passo

1. **Clone o repositório**
   ```bash
   git clone [https://github.com/Gabrieldsrod/acqua-energy.git](https://github.com/Gabrieldsrod/acqua-energy.git)
