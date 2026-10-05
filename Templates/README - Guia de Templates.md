# 📚 Guia de Uso dos Templates de Estudo (Redes - Fatec)

Esta pasta reúne modelos estruturados para otimizar seus estudos na disciplina de **Redes de Computadores** e na leitura do livro texto (**Tanenbaum - Redes de Computadores, 6ª Ed.**).

O Obsidian já foi configurado para reconhecer esta pasta automaticamente (`Templates`).

---

## 📂 Modelos Disponíveis

### 1. `Template - Leitura de Livro.md`
- **Quando usar:** Ao ler os capítulos do Tanenbaum (especialmente os listados para a sua prova: Cap. 2, 3, 5, 6 e 7).
- **Destaques:** Seções divididas por tópicos do livro, tabelas de vocabulário, espaço para equações (Shannon, Nyquist, etc.) e resolução de exercícios propostos no final de cada capítulo.

### 2. `Template - Protocolo de Rede.md`
- **Quando usar:** Ao estudar protocolos específicos (ex: `TCP`, `UDP`, `IPv4`, `IPv6`, `ARP`, `ICMP`, `DNS`, `HTTP`, `BGP`).
- **Destaques:** Mapeamento de camadas (OSI vs TCP/IP), layout de cabeçalho, diagrama de fluxo de mensagens (Mermaid), filtros de Wireshark e pegadinhas clássicas de prova.

### 3. `Template - Aula Teórica.md`
- **Quando usar:** Durante ou logo após as aulas na Fatec.
- **Destaques:** Registro das ênfases do professor ("isso cai na prova"), dúvidas para a próxima aula e checklist de tarefas pós-aula.

### 4. `Template - Preparação para Prova.md`
- **Quando usar:** Ao organizar a revisão final para a **P1** ou **P2**.
- **Destaques:** Matriz com semáforo de domínio (🔴 Crítico / 🟡 Médio / 🟢 Dominado), folha rápida de fórmulas, pegadinhas frequentes e caderno de erros.

### 5. `Template - Laboratório e Prática (Lab).md`
- **Quando usar:** Em aulas práticas de laboratório, simuladores (Cisco Packet Tracer, GNS3) ou análises reais de tráfego com Wireshark/Linux.
- **Destaques:** Diagrama de topologia em Mermaid, tabela de endereçamento IP e máscaras, comandos executados e troubleshooting de problemas de conexão.

### 6. `Template - Conceito e Glossário.md`
- **Quando usar:** Para notas atômicas de conceitos-chave (ex: *Throughput*, *Jitter*, *MTU*, *Janela Deslizante*, *CSMA/CD*).
- **Destaques:** Definição simples (técnica de Feynman), analogias do cotidiano e links bidirecionais `[[...]]` para fortalecer o grafo do Obsidian.

---

## ⚡ Como Inserir um Template no Obsidian

1. Crie uma nova nota vazia (ex: `Cap 2.1 - Meios Guiados` ou `Protocolo TCP`).
2. Pressione o atalho:
   - **`Ctrl + P`** (ou `Cmd + P` no Mac) e digite: `Templates: Insert template` (ou `Modelos: Inserir modelo`).
   - Ou clique no ícone de template na barra lateral esquerda.
3. Selecione o template desejado na lista.
4. As variáveis `{{title}}`, `{{date}}` e `{{time}}` serão substituídas automaticamente pelo título da sua nota e pela data/hora atuais!
