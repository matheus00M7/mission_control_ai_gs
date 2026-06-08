# 🚀 Mission Control AI

Sistema inteligente de monitoramento e análise operacional para missões espaciais simuladas.

## 👥 Integrantes

* Matheus Martins Lacerda — RM: 570843
* Roberson Reguero Luiz Junior — RM: 573031

## 📖 Sobre o Projeto

O **Mission Control AI** é um projeto desenvolvido em Python no Google Colab com o objetivo de simular o monitoramento de uma missão espacial experimental.

O sistema analisa dados operacionais simulados, como temperatura, energia, comunicação, oxigênio, radiação e status do módulo. A partir desses dados, ele gera alertas automáticos, classifica o nível de risco da missão e recomenda ações para auxiliar a equipe de controle.

Além das regras lógicas, o projeto utiliza Inteligência Artificial com o modelo **Llama 3.2 1B**, executado via **Ollama**, para gerar diagnósticos e recomendações em cenários críticos.

## 🎯 Funcionalidades

* Monitoramento da temperatura dos módulos
* Monitoramento do nível de energia
* Monitoramento da comunicação com a base
* Monitoramento do nível de oxigênio
* Monitoramento da radiação externa
* Monitoramento do status operacional do módulo
* Geração automática de alertas
* Classificação do risco da missão
* Recomendação de ações com base em regras lógicas
* Análise de cenário crítico com Inteligência Artificial
* Organização dos resultados em tabela
* Geração de gráfico comparativo
* Exportação de relatório em arquivo `.txt`

## 🧠 Inteligência Artificial

O projeto utiliza o modelo **Llama 3.2 1B** por meio do **Ollama** no Google Colab.

A IA recebe os dados simulados da missão e analisa a situação operacional, retornando uma resposta com:

* diagnóstico da missão;
* principais riscos identificados;
* consequências possíveis;
* recomendações de ação para a equipe de controle.

O prompt utilizado orienta a IA a agir como um sistema de controle de missão espacial, avaliando os dados de forma objetiva e focada em segurança operacional.

## 🛰️ Parâmetros Monitorados

| Parâmetro        | Descrição                            |
| ---------------- | ------------------------------------ |
| Temperatura      | Temperatura atual do módulo espacial |
| Energia          | Porcentagem de energia disponível    |
| Comunicação      | Qualidade do sinal com a base        |
| Oxigênio         | Nível interno de oxigênio            |
| Radiação         | Nível de radiação externa            |
| Status do módulo | Condição operacional geral do módulo |

## ⚠️ Regras de Alerta

O sistema identifica situações de risco com base nos valores simulados da missão.

Exemplos de alertas:

* Temperatura elevada indica risco térmico no módulo.
* Energia baixa indica necessidade de ativar modo de economia.
* Comunicação instável indica risco de perda de contato com a base.
* Oxigênio baixo indica risco no suporte de vida.
* Radiação elevada indica necessidade de proteção do módulo.

Com base na quantidade de alertas, o sistema classifica a missão como:

* **Normal**
* **Atenção**
* **Crítico**

## 🛠 Tecnologias Utilizadas

* Python
* Google Colab
* Ollama
* Llama 3.2 1B
* Pandas
* Matplotlib
* GitHub

## 📸 Demonstração

### Cenário Normal

![Cenário Normal](assets/cenario_normal.png)

### Cenário de Atenção

![Cenário de Atenção](assets/cenario_atencao.png)

### Cenário Crítico

![Cenário Crítico](assets/cenario_critico.png)

### Teste com Inteligência Artificial

![Teste com IA](assets/teste_ia.png)

### Gráfico Comparativo

![Gráfico Comparativo](assets/grafico_cenarios.png)

## ▶️ Como Executar

1. Abra o notebook `mission_control_ai_gs.ipynb` no Google Colab.

2. Execute as células em ordem.

3. As primeiras células instalam o Ollama, iniciam o servidor e baixam o modelo `llama3.2:1b`.

4. Depois, o notebook carrega os cenários simulados e as funções principais do sistema.

5. Execute as células de análise para visualizar:

   * dados da missão;
   * alertas automáticos;
   * classificação de risco;
   * ações recomendadas;
   * tabela resumo;
   * gráfico comparativo;
   * análise com Inteligência Artificial.

6. Ao final, o sistema pode gerar um relatório em arquivo `.txt`.

## 📂 Estrutura do Projeto

```text
mission-control-ai/
│
├── mission_control_ai_gs.ipynb
├── README.md
│
└── assets/
    ├── cenario_normal.png
    ├── cenario_atencao.png
    ├── cenario_critico.png
    ├── teste_ia.png
    └── grafico_cenarios.png
```

## 🎥 Vídeo de Demonstração

[Assistir ao vídeo]((https://youtu.be/V9fCGEY8wKk))

## ✅ Objetivo Acadêmico

Projeto desenvolvido para a disciplina **Prompt and Artificial Intelligence** da FIAP — Global Solution 2026.1.

O projeto aplica conceitos de programação, inteligência artificial, pensamento computacional, monitoramento operacional e tomada de decisão em um cenário inspirado nos desafios da indústria espacial moderna.
