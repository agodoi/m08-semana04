Durante este encontro, os estudantes serão apresentados aos sistemas embarcados e a forma como eles devem ser integrados com os demais sistemas. Os elementos essenciais e suas funcionalidades do sistemas embarcados serão abordados neste encontro. O conceito de sistemas ciber físicos, CPS (Cyber-Physical Systems), integração entre os sistemas computacionais e o mundo físico, é apresentado aos alunos, bem como suas aplicações. Uma análise crítica será realizada durante o encontro para verificar a importância dos sistemas embarcados neste contexto. Espera-se que ao final do encontro, os alunos possam conhecer os sistemas embarcados, CPS e as integrações realizadas entre eles. Neste encontro serão abordados: Sistemas Embarcados; Características de sistemas embarcados; Diferenças de sistemas convencionais e embarcados; Programação de sistemas embarcados; Conceito de entrada e saída; Apresentação de periféricos e sua utilização no contexto embarcado.

Assuntos relacionados
CPU e processamento

Memórias

Programação de microcontroladores

Simulação de sistemas embarcados


# Sistemas Ciberfísicos

## O que é isso?

Sistemas Ciberfísicos, do inglês Cyber-Physical Systems (CPS), compõem uma área interdisciplinar que combina elementos da:

1) Ciência da Computação;

2) Engenharia Elétrica;

3) Engenharia Mecânica;

4) Engenharia de Controle e Automação

Serve para criar e controlar sistemas integrados que incorporam tanto componentes físicos quanto virtuais. Esses sistemas são projetados para interagir e coordenar de maneira estreita com o mundo físico, tornando-os muito relevantes para o campo da **Ciência da Computação**.

## Características dos Sistemas Ciberfísicos

1. Integração de componentes físicos e virtuais: CPS combinam hardware (sensores, atuadores, dispositivos mecânicos) com software (algoritmos, sistemas de controle) para criar sistemas completos. **Exemplo: projeto tapete sensorial + Greg Maker + compilador de vocês**.

2. Conexão com o mundo real: Eles interagem com o ambiente físico e geralmente usam sensores para coletar dados do mundo real e atuadores para realizar ações no mundo real. **Exemplo: tapete sensorial e o alto-falante ou display da gameficação do projeto**. 

3. Comunicação em tempo real: CPS muitas vezes requerem comunicação em tempo real para coordenar ações entre seus componentes. **Exemplo: o paciente interage em tempo real com o computador e terapeuta ocupacional**.

4. Controle e automação: São frequentemente usados para sistemas de controle e automação em uma variedade de setores, como **saúde**, manufatura, automação residencial e transporte. **Exemplo: Projeto AACD**.

5. Sistemas embarcados: CPS são frequentemente implementados em sistemas embarcados, que são sistemas de computação dedicados a tarefas específicas. **Exemplo: Greg Maker + compilador de vocês**.

6. Segurança e confiabilidade: Devido à sua integração com o mundo real, a segurança e a confiabilidade são preocupações fundamentais na concepção de sistemas ciberfísicos.

Esses sistemas têm aplicações em uma ampla gama de setores, incluindo manufatura inteligente, cidades inteligentes, assistência médica, veículos autônomos, automação de edifícios e muitos outros. 

Na **Ciência da Computação**, os estudantes e pesquisadores podem se envolver no desenvolvimento de algoritmos, sistemas de controle, comunicação em tempo real e segurança para sistemas ciberfísicos. Portanto, os sistemas ciberfísicos representam um campo empolgante e em crescimento na interseção da Ciência da Computação com outras disciplinas de engenharia.

Sistemas embarcados são sistemas de computação especializados projetados para realizar tarefas específicas ou funções dedicadas. Eles têm várias características distintivas em comparação com sistemas de computação convencionais (como computadores pessoais ou servidores). Aqui estão algumas características dos sistemas embarcados e diferenças em relação aos sistemas convencionais:

## Características dos Sistemas Embarcados

1. **Dedicados a tarefas específicas:** Os sistemas embarcados são projetados para executar uma tarefa ou um conjunto específico de tarefas. Eles não são computadores de propósito geral.

2. **Recursos limitados:** Geralmente, têm recursos de hardware limitados, como poder de processamento, memória e armazenamento, adequados para suas tarefas específicas.

3. **Tamanho compacto:** São frequentemente pequenos e compactos, projetados para caber em dispositivos ou sistemas maiores.

4. **Consumo de energia otimizado:** São projetados para serem eficientes em termos de consumo de energia, uma vez que muitos deles são alimentados por baterias ou fontes de energia limitadas.

5. **Sistemas operacionais dedicados:** Muitas vezes, executam sistemas operacionais dedicados, em vez de sistemas operacionais de propósito geral, para melhor atender às suas necessidades.

6. **Integração de hardware e software:** Hardware e software são altamente integrados para otimizar o desempenho e a eficiência.

7. **Tempo real:** Alguns sistemas embarcados são projetados para operar em tempo real, o que significa que precisam responder a eventos dentro de prazos especificados.

## Diferenças entre Sistemas Embarcados e Convencionais:

1. **Propósito:** Os sistemas embarcados têm um propósito específico, enquanto os sistemas convencionais são projetados para uma ampla variedade de tarefas.

2. **Tamanho e forma:** Os sistemas embarcados são geralmente menores e mais compactos, enquanto os sistemas convencionais, como PCs, podem ser grandes e ter diferentes formatos.

3. **Recursos de hardware:** Os sistemas convencionais têm recursos de hardware mais abundantes, incluindo processadores mais poderosos, mais memória e maior capacidade de armazenamento.

4. **Sistemas operacionais:** Os sistemas convencionais geralmente executam sistemas operacionais de propósito geral, como Windows, Linux ou macOS, enquanto os sistemas embarcados usam sistemas operacionais específicos para suas tarefas.

5. **Consumo de energia:** Os sistemas embarcados são otimizados para baixo consumo de energia, enquanto os sistemas convencionais geralmente têm requisitos de energia mais elevados.

6. **Ampla conectividade:** Os sistemas convencionais frequentemente têm uma ampla gama de opções de conectividade, como Wi-Fi, Ethernet, USB, etc., enquanto os sistemas embarcados podem ter opções limitadas.

7. **Custo:** Os sistemas embarcados podem ser mais econômicos devido ao seu foco em recursos específicos, enquanto os sistemas convencionais podem ser mais caros devido à sua flexibilidade e capacidade de propósito geral.

8. **Complexidade de software:** Os sistemas embarcados tendem a ter software mais especializado e simplificado, enquanto os sistemas convencionais podem executar uma ampla variedade de aplicativos complexos.

## Sensor Greg Maker

### O modelo que vamos adotar nesse projeto é o Arduino Uno

### Modelo do chip: [atmega32u4](https://www.microchip.com/en-us/product/atmega32u4)


## Qual a função do Arduino Uno R3 no projeto?

O projeto AACD é o **desenvolvimento de um compilador para PC "de alto nível"** que será transformado para linguagem Python. Esse Python chamaremos de "baixo nível" que rodará no ambiente Windows.

Esse compilador de alto nível, desenvolvido pelos alunos, deverá **resolver uma gamificação do TO** (Terapeuta Ocupacional) da AACD.

A gamificação contará com a entrada de dados provenientes do [Greg Maker](https://www.gregmaker.com.br/), **que transforma os toques manuais** sobre objetos semicondutores e condutores em **movimentos do mouse e algumas teclas do teclado**, como barra de espaço, ENTER e setas.

**O responsável pela detecção dos toques manuais é o Arduino Uno R3**.

Exemplo: a figura abaixo apresenta alimentos e objetos condutores e semicondutores conectados ao Greg Maker, que ao serem tocados manualmente por uma pessoa com deficiência motora ou cerebral, moverá o mouse na tela do computador, ou pressionará a barra de espaço ou o ENTER ou alguma opção de setas. Vai depender de quais fios foram conectados em cada objeto.

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/ProjetoAACD/blob/main/imgs/gregMaker.png">
   <img alt="Família ESP32" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/ProjetoAACD/blob/main/imgs/gregMaker.png)">
</picture>

## Diagrama de Blocos da Solução

A figura a seguir demonstra o diagrama de blocos da solução mínima para a fundação AACD. Observe com calma!

**A missão desse projeto está na gamificação para o ambiente Windows e não no Arduino Uno R3**.

O Arduino é somente um sistema embarcado que captura dados de toques e os converte em movimentos do mouse e algumas teclas do teclado.

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/ProjetoAACD/blob/main/imgs/ArquiteturaAACD.png">
   <img alt="Arquitetura AACD" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/ProjetoAACD/blob/main/imgs/ArquiteturaAACD.png)">
</picture>

## Arduino Uno - Documentação

Nessa instrução, vamos explorar o hardware que converterá os toques manuais nos **trem da mesa :)** em movimentos do mouse e teclado.

[Fonte](https://docs.arduino.cc/resources/datasheets/A000066-datasheet.pdf)

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/ProjetoAACD/blob/main/imgs/arduinoUnoR3.png">
   <img alt="Arduino Uno R3" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/ProjetoAACD/blob/main/imgs/arduinoUnoR3.png)">
</picture>

### Esquemático Eletrônico

Na figura a seguir você pode entender com mais profundidade, do que é feita uma placa Arduino Uno R3. 

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/ProjetoAACD/blob/main/imgs/Arduino-UNO-Description.png">
   <img alt="Arduino Uno R3" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/ProjetoAACD/blob/main/imgs/Arduino-UNO-Description.png)">
</picture>

Perceba que a placa possui dois conectores ICSP (In-Circuit Serial Programming). Ambos servem para programar um chip mesmo já inserido na placa e com todos os componentes eletrônicos em sua volta. [Documentação](https://ww1.microchip.com/downloads/en/DeviceDoc/30277d.pdf). Como há dois chips programáveis no Arduino IDE, um ICSP é do chip USB e o outro ICSP é do Arduino.

O Greg Maker usou o ICSP do chip USB, **chip U3** da figura a seguir para alterar seu firmware e converter a comunicação USB em comandos padronizados de mouse e teclado. É como se o Arduino se comportasse como um adaptador de mouse e teclaso sem fio. Mas o Arduino não sai assim de fábrica. Precisa reprogramar o conversor USB U3 da imagem a seguir. Esse chip conversor USB tem que ser o "quadradinho" e não um retângulo. O retângulo não aceita reprogramação de firmware.

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/ProjetoAACD/blob/main/imgs/arduinoUnoR3Esquematico.png">
   <img alt="Esquemático do Arduino Uno R3" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/ProjetoAACD/blob/main/imgs/arduinoUnoR3Esquematico.png)">
</picture>

O que tem na placa dessa arquitetura embarcada?

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/ProjetoAACD/blob/main/imgs/ArduinoChips.png">
   <img alt="Esquemático do Arduino Uno R3" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/ProjetoAACD/blob/main/imgs/ArduinoChips.png)">
</picture>

### Pinout Arduino Uno R3

O pinout (significado de cada pino) é demonstrado na imagem a seguir:

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/ProjetoAACD/blob/main/imgs/ArduinoPinout.png">
   <img alt="Arduino Uno R3" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/ProjetoAACD/blob/main/imgs/ArduinoPinout.png)">
</picture>
## Conversor AD e DA

## Memória empregada

## Interrupções

## Prática com Interrupção
