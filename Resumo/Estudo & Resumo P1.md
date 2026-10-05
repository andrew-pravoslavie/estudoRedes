Camada mais baixa, tendo três tipos diferentes de transmissão de bits: Cabeada, sem fio e satélite. 
Quase sempre a transmissão que ocorre por um fio ou cabo físico é chamado de meio te transmissão guiado, os mais comuns são cabos coaxiais e de fibra óptica. 

O autor utiliza o exemplo de transporte de dados por meio de uma caixa cheia de fitas de Ultrim (cada fita capaz de carregar 30 Tb). Para transmissão de muitos dados, essa costuma ser a melhor saída, a amazon mesmo tem um veículo chamado "Snowmobile" que é um grande caminhão cheio de milhares de discos rígidos chegando a até 100PB de capacidade de armazenamento total no caminhão. É uma forma de transmissão de dados mais rápida e mais barata. 

O cabo par trançado se torna uma espécie de antena, e os dois polos cancelam um ao outro (blindagem), diminuindo fatores externos. Um sinal é transportado a partir da diferença de tensões terminais (ddp), os dados trafegam pelo cabo com a  mesma intensidade nos dois terminais, mantendo a ddp relativamente inalterada.

Os enlaces que podem ser utilizados nos dois sentidos (enviando e recebendo dados) são chamados de full-duplex, enquanto os que apenas podem ir em um sentido por vez, são chamados de half-duplex. E os que podem ir em apenas um sentido único (ou indo, ou vindo) são chamados de simplex. 

Até a Categoria 6, esses tipos de fios são conhecidos como par trançado não blindado, ou UTP (Unshielded Twisted Pair), pois consistem simplesmente em fios e isolamento. 

Um cabo coaxial consiste em um fio de cobre esticado na parte central, protegido por um material isolante. O isolante é envolvido por um condutor cilíndrico, geralmente como urna malha sólida entrelaçada. O condutor externo é coberto por uma camada plástica protetora.

![[Pasted image 20261003171457.png]]


O uso da fiação elétrica doméstica para transmissão de dados (tecnologia PLC) traz a conveniência de conectar dispositivos à rede diretamente pelas tomadas, sobrepondo sinais de alta frequência (em MHz) à corrente elétrica convencional (50–60 Hz). Embora essa infraestrutura enfrente grandes desafios técnicos — como forte atenuação de sinal, ruídos transitórios causados por eletrodomésticos e emissão de interferências eletromagnéticas por não usar pares trançados —, técnicas modernas de modulação e tratamento de erros tornam viável atingir taxas de transmissão acima de 500 Mbps.


Para cabos de fibra, são feitos de fibra de vidro internamente (por isso que não podem ser dobrados) e enviando sinais de luz que ricocheteiam nas extremidades do cabos. Podendo levar um bit 1 e um bit 0. 

Dizemos que cada raio tem um modo específico; assim, uma fibra que apresenta essa propriedade é chamada de fibra multimodo.

Se o diâmetro da fibra for reduzido a alguns comprimentos de onda de luz (menos de 10 micra, ao contrário de mais de 50 micra para a fibra multimodo), a fibra agirá como um guia de onda e a luz só poderá se propagar em linha reta, sem ricochetear, produzindo, assim, uma fibra de modo único ou fibra monomodo.


![[Pasted image 20261003180759.png]]


![[Pasted image 20261003181554.png]]


2.2

Tipos de transmissão sem fio:
- Espectro Eletromagnético
- Espectro de Dispersão por Salto de Frequência
- Espectro de Dispersão de Sequência Direta
- Comunicação de Banda Ultralarga 

O espectro de dispersão por salto de frequência, utilizado em tecnologias como Bluetooth e redes 802.11, foi criado por várias pessoas, em espacial por uma atriz austriaca que descobriu que seu marido, vendendo armas para Hitler, utilizava essa tecnologia para bloquear a comunicaçã ode torpedos.

UWB = Ultra Wide Band, 
Ela consegue por meio das ondas do espectro localizar e formar imagens (parede, solo e corpos), é utilizado tambpem para tecnologioas de rastreamento.

2.3 - Transmissões através do Espectro

- Transmissão de Rádio
- Transmissão de Micro-ondas
- Transmissão de Infravermelho
- Transmissão via Luz

2.3.microondas
	Multipath fading é o enfraquecimento de ondas de micro-ondas onde ondas 


### **2.6 Redes de Telefonia Móvel (Visão Geral) & 2.6.1 Conceitos Comuns**

- **Telefones móveis / Telefones celulares**: Dispositivos que utilizam comunicação sem fio para transmissão remota de voz e dados[1].
- **Células**: Divisões geográficas da área de cobertura[1]. Cada célula utiliza um conjunto de frequências que não é usado pelas células vizinhas imediatas, permitindo o reuso de frequências em células mais afastadas[1].
- **Microcélulas**: Células com áreas de cobertura reduzidas criadas em locais com alta densidade de usuários para aumentar a capacidade de tráfego e a reutilização de frequências[1].
- **Estação-base**: Antena e equipamento transmissor/receptor localizados no centro de cada célula, responsáveis pela comunicação direta com os aparelhos celulares[2].
- **Centro de comutação móvel (MSC -** **Mobile Switching Center** **)**: Central que gerencia um grupo de estações-base, coordenando a comutação de chamadas e a conexão com a rede telefônica fixa (PSTN)[2].
- **Handoff**: O processo de transferência de uma chamada em andamento de uma estação-base para outra conforme o usuário se desloca entre células[2].
- **Canais de rádio**: Divididos em **canais de controle** (gerenciamento do sistema), **canais de localização** (_paging_, alerta de chamadas recebidas), **canais de acesso** (estabelecimento de chamadas e alocação de canais) e **canais de dados** (transporte efetivo de voz, fax ou dados)[2].

---

### **2.6.2 Primeira Geração (1G): Voz Analógica**

- **Sistemas "apertar para falar" (** **push-to-talk** **) e IMTS (** **Improved Mobile Telephone System** **)**: Tecnologias precursoras baseadas em transmissores de alta potência e poucos canais[2].
- **AMPS (** **Advanced Mobile Phone System** **)**: O principal sistema analógico de 1G[2]. Utilizava **FDD (** **Frequency Division Duplex** **)** para separar a transmissão e a recepção em pares de canais simplex[2].

---

### **2.6.3 Segunda Geração (2G): Voz Digital & 2.6.4 GSM**

- **Tecnologias 2G**: Transição para sinalização e transmissão digitais de voz[3]. Incluiu padrões como **D-AMPS**, **GSM (** **Global System for Mobile Communications** **)** e **CDMA / IS-95**[3]. Comercializados em algumas regiões sob o nome **PCS (** **Personal Communications Services** **)**[3].
- **Cartão SIM (** **Subscriber Identity Module** **)**: Cartão removível contendo as informações do assinante e chaves de criptografia[4].
- **BSC (** **Base Station Controller** **)**: Controlador encarregado de gerenciar os recursos de rádio das estações-base e cuidar do handoff[4].
- **Registradores de localização**:
    - **HLR (** **Home Location Register** **)**: Banco de dados principal da rede que armazena a localização e o perfil original do assinante[4].
    - **VLR (** **Visitor Location Register** **)**: Banco de dados temporário que registra os aparelhos atualmente presentes na área atendida pelo MSC[4].
- **MAHO (** **Mobile Assisted HandOff** **)**: Técnica em que o próprio dispositivo móvel mede o sinal das estações vizinhas e informa o BSC para determinar a necessidade de handoff[5].

---

### **2.6.5 Terceira Geração (3G): Voz e Dados Digitais**

- **3G e IMT-2000**: Padrão global definido pela ITU para unificar redes móveis de alta velocidade[5].
- **EDGE (** **Enhanced Data Rates for GSM Evolution** **)**: Etapa intermediária (2,5G) que aprimorou as taxas de dados das redes GSM[5].
- **Tecnologias dominantes de 3G**: **WCDMA / UMTS (** **Universal Mobile Telecommunications System** **)** e **CDMA2000**[6].
- **Propriedades do CDMA**: Baseia-se em **baixa correlação cruzada** e **autocorrelação** de sequências pseudoaleatórias para separar sinais de múltiplos usuários na mesma frequência[6].
- **Tipos de Handoff**:
    - **Hard handoff**: A conexão com a célula antiga é interrompida antes que a conexão com a nova célula seja estabelecida ("quebra antes de conectar")[7].
    - **Soft handoff**: O dispositivo conecta-se à nova estação-base antes de se desligar da antiga, mantendo a transmissão em duas frequências simultaneamente[7].

---

### **2.6.6 Quarta Geração (4G): Comutação de Pacotes**

- **4G / IMT Advanced / LTE (** **Long Term Evolution** **)**: Arquitetura inteiramente baseada em comutação de pacotes IP[7].
- **EPC (** **Evolved Packet Core** **)**: O núcleo de rede simplificado responsável por rotear apenas pacotes IP[8].
- **eNodeB**: As estações-base evoluídas da rede de acesso do LTE[8].
- **VoLTE (** **Voice over LTE** **)**: Tecnologia para transporte de chamadas de voz comutada por pacotes sobre a rede LTE[8].

---

### **2.6.7 Quinta Geração (5G)**

- **5G**: Focada em velocidades de gigabits e baixíssima latência[8].
- **Ultra-densificação e descarregamento**: Uso massivo de células menores como **picocélulas** e **femtocélulas** para reutilização de espectro em curtas distâncias[8].
- **Ondas milimétricas**: Uso de frequências muito altas (na faixa de 20 a 300 GHz) com grandes larguras de banda disponíveis[9].
- **Avanços em Antenas**:
    - **MIMO / MU-MIMO / Massive MIMO / FD-MIMO (** **Full-Dimension MIMO** **)**: Uso de múltiplas antenas no transmissor e receptor para aumentar a eficiência espectral e focar os feixes diretamente nos usuários[9].
- **Arquiteturas de Rede**:
    - **Fatiamento de rede (** **network slicing** **)**: Criação de redes virtuais independentes sobre a mesma infraestrutura física para atender diferentes requisitos de aplicação[9].
    - **SDN (** **Software-Defined Networking** **)** e **NFV (** **Network Functions Virtualization** **)**: Tecnologias de virtualização e controle por software que sustentam a flexibilidade da arquitetura 5G[9].