---
tipo: preparacao-prova
disciplina: Redes de Computadores
prova: P1
data_prova: 
status_geral: 🟡 Em Preparação # 🔴 Iniciando, 🟡 Em Preparação, 🟢 Pronto
meta_nota: 
tags:
  - redes
  - fatec
  - prova
  - revisao
---

# 🎯 Guia de Revisão: {{title}}

> [!important] Informações da Avaliação
> - **Data da Prova:** 
> - **Formato:** [ ] Dissertativa  [ ] Múltipla Escolha  [ ] Mista  [ ] Prática em Lab
> - **Pode consulta?** [ ] Não  [ ] Formulário fornecido  [ ] Consulta livre

---

## 📋 Matriz de Conteúdo & Status de Domínio
Classifique cada assunto: 
- 🔴 *Crítico / Preciso estudar* 
- 🟡 *Médio / Entendo o conceito, falta praticar* 
- 🟢 *Dominado / Consigo explicar sem olhar*

| Capítulo / Tópico | Escopo / Seções | Teoria | Prática/Cálculo | Status |
| :--- | :--- | :---: | :---: | :---: |
| **Cap. 2 - Camada Física** | 2.1, 2.2, 2.3, 2.6, 2.7 | [ ] | [ ] | 🔴 |
| **Cap. 3 - Camada de Enlace** | Tudo (exceto código-fonte) | [ ] | [ ] | 🔴 |
| **Cap. 5 - Camada de Rede** | Roteamento, IP, Sub-redes | [ ] | [ ] | 🔴 |
| **Cap. 6 - Camada de Transporte**| TCP, UDP, Congestionamento | [ ] | [ ] | 🔴 |
| **Cap. 7 - Camada de Aplicação** | DNS, HTTP, E-mail | [ ] | [ ] | 🔴 |

---

## 🧮 Folha de Fórmulas e Cálculos Rápidos
*(Fórmulas cruciais que podem ser cobradas)*

### 1. Capacidade Máxima de Canal (Nyquist - Sem Ruído)
$$ C = 2B \log_2(V) \text{ bps} $$
- $B$ = Largura de banda (Hz)
- $V$ = Número de níveis discretos de sinal

### 2. Capacidade Máxima de Canal (Shannon - Com Ruído)
$$ C = B \log_2(1 + S/N) \text{ bps} $$
- Relação Sinal/Ruído em dB: $\text{dB} = 10 \log_{10}(S/N)$

### 3. Atraso Total de Pacote (Delay)
$$ D_{total} = D_{proc} + D_{fila} + D_{transmissao} + D_{propagacao} $$
- **Transmissão:** $D_{trans} = \frac{L \text{ (tamanho do pacote)}}{R \text{ (taxa de transmissão)}}$
- **Propagação:** $D_{prop} = \frac{d \text{ (distância)}}{v \text{ (velocidade do meio)}}$

---

## ⚡ Diferenças Conceituais & Pegadinhas Clássicas
| Comparação | Elemento A | Elemento B | Pegadinha Típica |
| :--- | :--- | :--- | :--- |
| **Camada Física vs Enlace** | Bits brutos no meio físico | Quadros, controle de acesso e detecção de erros | Achar que bit rate é tratado no enlace |
| **Hub vs Switch vs Roteador** | Camada 1 (Broadcast geral) | Camada 2 (MAC / Tabela CAM) | Camada 3 (IP / Roteamento) |
| **TCP vs UDP** | Orientado a conexão, confiável | Não-orientado, rápido, sem garantia | Achar que UDP tem checksum obrigatório em tudo |
| **Fluxo vs Congestionamento** | Receptor sobrecarregado (janela) | Rede/roteadores sobrecarregados | Confundir o culpado pelo gargalo |

---

## ✍️ Banco de Questões de Treino / Simulado

### Questão 1 (Teórica)
- **Enunciado:** 
- **Minha Resposta:** 
- **Gabarito Oficial / Correção:** 
- **Autoavaliação:** [ ] Acertei 100% | [ ] Acertei parcial | [ ] Errei

### Questão 2 (Cálculo / Resolução)
- **Enunciado:** 
- **Passo a passo da resolução:** 
- **Resposta final:** 

---

## 🛑 Caderno de Erros (O que errei e por quê?)
> [!caution] Não erre isso no dia da prova!
> 1. **Erro recorrente:** 
>    - *Por que errei:* 
>    - *Como lembrar corretamente:* 
