# 🚀 MISSION ORION — SISTEMA INTELIGENTE DE TELEMETRIA E EFICIÊNCIA ENERGÉTICA

## 🌌 1. VISÃO GERAL DO PROJETO

O **Mission Orion** é um ecossistema de software de missão crítica projetado para o **monitoramento inteligente de sitemas energéticos e telemetria aeroespacial**. O desafio central desta aplicação é interpretar fluxos de dados complexos e fornecer tanto análises em tempo real quanto relatórios preditivos avançados voltados à sustentabilidade, eficiência de hardware e conservação de recursos espaciais renováveis.

A aplicação destaca-se por implementar uma **camada cognitiva superior** utilizando o modelo de linguagem de larga escala **`gpt-oss:120b`** via Ollama Cloud, integrando IA de forma criteriosa e estruturada para tomadas de decisão autônomas no controle de missão.

---

## 🏗️ 2. ARQUITETURA DO SOFTWARE & FLUXO COGNITIVO

O ecossistema foi desenhado sob o princípio de **Sistemas de Defesa em Camadas**, priorizando a resiliência operacional e a sustentabilidade computacional através de um fluxo inteligente dividido em 4 etapas:

1. **📥 Captura de Telemetria:** O sistema centraliza e interpreta os dados brutos simulados (temperatura, comunicação, energia, suporte de vida e status dos módulos).
2. **🛡️ Triagem de Risco (Eficiência Energética):** Antes de acionar qualquer recurso externo, o código calcula o risco localmente. Se o estado for nominal (risco zero), a IA não é chamada, economizando processamento e tráfego de dados.
3. **🧠 Consulta Cognitiva (Ollama Cloud):** Caso uma anomalia seja detectada (risco > 0), as métricas são estruturadas e enviadas ao modelo `gpt-oss:120b` para gerar comandos de engenharia em tempo real.
4. **🔄 Contingência Automática (Redundância):** Se ocorrer uma falha de rede ou timeout com a API, o mecanismo de segurança `try/except` assume o controle instantaneamente, exibindo o protocolo básico pré-programado sem interromper a execução do console.

### 🛰️ Mecanismos de Usabilidade e Estabilidade:
* **Sustentabilidade Computacional:** Se a telemetria local indicar que todos os sistemas operam em faixa nominal (0 pontos de risco), o software inibe o acionamento da IA. Isso reduz custos de transmissão, tráfego de dados e processamento em nuvem.
* **Redundância e Tolerância a Falhas:** Através de blocos estruturados `try/except`, qualquer falha na chamada do Ollama Cloud (erros de conexão, timeouts ou credenciais expiradas) ativa imediatamente a **Inteligência de Contingência Local**, mantendo as diretrizes de segurança básicas na tela do operador sem travar a execução.

---

## 📊 3. MATRIZ DE CONFIGURAÇÃO DE TELEMETRIA

O sistema avalia dinamicamente 5 áreas críticas. Abaixo estão os limites operacionais estritos e as médias simuladas consolidadas no fechamento da missão:

| 📍 Área Monitorada | 🟢 Faixa Nominal | 🟡 Limiar de Atenção | 🔴 Limiar Crítico | 📈 Média da Missão |
| :--- | :---: | :---: | :---: | :---: |
| **Temperatura Interna** | $18.1ºC \dots 32.9ºC$ | $\ge 33.0ºC$ | $\ge 35.0ºC$ ou $\le 18.0ºC$ | **31.87 ºC** |
| **Comunicação com a Base**| $> 65.0\%$ | $\le 65.0\%$ | $\le 30.0\%$ | **55.00%** |
| **Sistemas de Energia** | $> 50.0\%$ | $\le 50.0\%$ | $\le 20.0\%$ | **58.00%** |
| **Suporte de Vida** | $> 90.0\%$ | $\le 90.0\%$ | $\le 80.0\%$ | **91.75%** |
| **Status dos Módulos** | $> 65.0\%$ | $\le 65.0\%$ | $\le 40.0\%$ | **69.67%** |

---

## 🛠️ 4. DESTAQUES DA IMPLEMENTAÇÃO TÉCNICA

### ⚡ Critérios Técnicos Atendidos
* **Mapeamento de Tendências:** Funções puras que comparam dinamicamente os riscos entre o ciclo atual e o anterior, reportando estados de `Melhora`, `Piora` ou `Estabilidade`.
* **Rastreamento de Crise:** Isolamento algorítmico das áreas de maior impacto por ciclo, tratando cenários de empate técnico de forma limpa no console.

### 💡 Inovação e Camada de IA
* **Baixa Temperatura de Inferência:** Configuração estrita de `temperature: 0.3` no Ollama Client, garantindo respostas lógicas, pragmáticas e puramente técnicas de engenharia de software aeroespacial.
* **Módulo de Análise Cognitiva de Sustentabilidade:** Ao gerar o relatório final, a IA analisa a performance energética agregada e gera um parecer técnico focado em otimização de hardware renovável para futuras missões experimentais.

---

## 🚀 5. INSTRUÇÕES DE EXECUÇÃO

### 📋 Pré-requisitos
O projeto necessita do Python 3.10+ e da biblioteca oficial de conexões do Ollama instalada:

```bash
pip install ollama
💻 Rodando o Monitoramento
Garanta que as suas configurações de chaves estejam mapeadas corretamente no cabeçalho do script:

Python
API_KEY = "3a7a5e76c2914495834ec14ab91a4730.ECpPqDEws6dXZ5ZKi9942xUA"
MODEL_NAME = "gpt-oss:120b"
Execute a central de controle via terminal:

Bash
python monitoramento_orion.py

🎬 6. LINKS DE ENTREGA (DOCUMENTAÇÃO OFICIAL)
Conforme os critérios estabelecidos nas diretrizes da Global Solution, segue o link do vídeo pitch:

🎥 Vídeo Demonstrativo no YouTube: [Insira o link aqui] (Duração máxima de 3 minutos, modo Não Listado)

👥 7. CORPO DOCENTE E INTEGRANTES DO PROJETO
Instituição: FIAP — Faculdade de Informática e Administração Paulista

Curso: Bacharelado em Ciência da Computação

Turma: 1CCPG

Matéria: Soluções em Energias Renováveis e Sustentabilidade, Professor: André Tritiack

João Marcelo de Melo e Silva — RM: 572569
Pablo Renato dos Santos Sobral de Carvalho — RM: 569894
Pedro Vianna — RM: 570747
