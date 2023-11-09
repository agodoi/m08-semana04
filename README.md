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

Greg Maker é um Arduino Uno, modelo do chip: [atmega32u4](https://www.microchip.com/en-us/product/atmega32u4)

### Qual a função do Arduino Uno R3 no projeto?

É transformar os toques manuais sobre objetos semicondutores e condutores em **movimentos do mouse e algumas teclas do teclado**. No mouse, funcina os movimentos da seta na tela, clique do botão esquerdo e menu do botão direito. No teclado, tem-se a barra de espaço, o ENTER e as 4 setas.

**Portanto, o responsável pela detecção dos toques manuais é o Arduino Uno R3**.

Exemplo: a figura abaixo apresenta alimentos e objetos condutores e semicondutores conectados ao Greg Maker, que ao serem tocados manualmente por uma pessoa com deficiência motora ou cerebral, moverá o mouse na tela do computador, ou pressionará a barra de espaço ou o ENTER ou alguma opção de setas. Vai depender de quais fios foram conectados em cada objeto.

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/ProjetoAACD/blob/main/imgs/gregMaker.png">
   <img alt="Família ESP32" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/ProjetoAACD/blob/main/imgs/gregMaker.png)">
</picture>

### Relembrando o Diagrama de Blocos da Solução

A figura a seguir demonstra o diagrama de blocos da solução mínima para a fundação AACD. Observe com calma!

**A missão desse projeto está na gamificação para o ambiente Windows e não no Arduino Uno R3**.

O Arduino é somente um sistema embarcado que captura dados de toques e os converte em movimentos do mouse e algumas teclas do teclado.

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/ProjetoAACD/blob/main/imgs/ArquiteturaAACD.png">
   <img alt="Arquitetura AACD" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/ProjetoAACD/blob/main/imgs/ArquiteturaAACD.png)">
</picture>

### Arduino Uno - Documentação

Nessa instrução, vamos explorar o hardware que converterá os toques manuais nos **trem da mesa :)** em movimentos do mouse e teclado.

[Fonte](https://docs.arduino.cc/resources/datasheets/A000066-datasheet.pdf)

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/ProjetoAACD/blob/main/imgs/arduinoUnoR3.png">
   <img alt="Arduino Uno R3" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/ProjetoAACD/blob/main/imgs/arduinoUnoR3.png)">
</picture>

### Pinout Arduino Uno R3

O pinout (significado de cada pino) é demonstrado na imagem a seguir:

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/ProjetoAACD/blob/main/imgs/ArduinoPinout.png">
   <img alt="Arduino Uno R3" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/ProjetoAACD/blob/main/imgs/ArduinoPinout.png)">
</picture>

### Como o Greg Maker funciona?

Usando essa simulação, temos uma base de como o Greg Maker detecta toques da pela humana.

No fundo, no fundo, ele deve ter um analogRead() que monitora um portal de dados e, que, ao se aproximar do nível baixo **LOW** em sua conversão, ele entende que é um toque e faz a conversão para o mouse ou teclado, a depender de qual entrada você está utilizando.

A seguir, tem-se uma simulação de como o Greg Maker deve funcionar. Não temos certeza, pois é um produto prioprietário.

1) Usando o [TinkerCad](https://www.tinkercad.com/dashboard), puxe um Arduno Uno R3 para a área de desenvolvimento da tela;
  
3) Clique no botão **código** e altere para **Texto** e confirma numa tela **Continuar**.
   
5) Clique no botão **Iniciar simulação** para rodar o pisca-pisca no LEDBUILT_IN da placa. Esse programa é o básico da plataforma TinkerCad.

6) Interrompa a simulação clicando em **Parar simulação** e altere o tempo do delay para o tempo que você quiser e execute o programa novamente.

7) Agora, no mesmo Arduino, vamos emular um sensor de tato usando o comando ```analogRead()```para simular um contato do paciente no tapete sensorial.
  
9) Monte o circuito conforme a imagem a seguir:

<picture>
   <source media="(prefers-color-scheme: light)" srcset="https://github.com/agodoi/ProjetoAACD/blob/main/imgs/arduino_sensor_umidade.png">
   <img alt="Tipos de Arquitetura" src="[YOUR-DEFAULT-IMAGE](https://github.com/agodoi/ProjetoAACD/blob/main/imgs/arduino_sensor_umidade.png)">
</picture>

10) Use esse código como exemplo

```
void setup()
{
  pinMode(A0,INPUT);
  Serial.begin(9200);
}

void loop()
{
  int dadoTapete = analogRead(A0);
  Serial.println(dadoTapete);
  delay(1000); // Wait for 1000 millisecond(s)
}
```

11) Clique no sensor de umidade e simule o nível de umidade e observe o **monitor serial** para entender os dados chegando.


## Conversor AD e DA

O Arduino Uno plataforma de desenvolvimento de microcontroladores que incorpora conversores analógico-digitais (AD) e digitais-analógicos (DA) para facilitar a interação com o mundo real. 

### Características do Conversor Analógico-Digital (AD) do Arduino Uno:

1. Resolução: O Arduino Uno possui um conversor AD de 10 bits, o que significa que ele pode converter uma tensão analógica de entrada em um valor digital de 0 a 1023.

   - A matemática do **trem** é o seguinte: ```N_combinações = 2^n bits```. Então ```N_Combinações = 2^10 = 1024``` (de 0 a 1023).
   
2. Canais: O Arduino Uno possui 6 pinos de entrada analógica (A0 a A5), permitindo que você meça até 6 sinais analógicos diferentes simultaneamente.

3. Tensão de referência: A placa Arduino Uno permite selecionar a tensão de referência para a conversão analógica, o que é útil para adaptar a faixa de medição ao seu projeto. O limite máximo é de 5V.
   
4. Velocidade de conversão: O conversor AD do Arduino Uno é relativamente rápido e pode realizar conversões em microssegundos, dependendo da configuração.

**Pontos Positivos:**

1. Facilidade de uso: O conversor AD do Arduino Uno é simples de usar e é amplamente suportado pela comunidade;
2. Baixo custo: O Arduino Uno é acessível, tornando-o uma ótima opção para projetos com orçamento limitado;
3. Adequado para muitos aplicativos: A resolução de 10 bits é suficiente para muitas aplicações, como leitura de sensores, controle de motores e outros projetos de automação.

**Pontos Negativos:**

1. Baixa resolução: A resolução de 10 bits pode ser insuficiente para aplicações que exigem alta precisão. Exemplo: medir um sinal de balança, que trabalha na casa de 2 a 5 milivolts;
   
2. Sensibilidade a ruído: O conversor AD do Arduino Uno pode ser sensível a ruído elétrico, o que pode afetar a qualidade das leituras. Para reduzir, use capacitores de aterramento ou gaiola de Faraday;

3. Limitado a sinais analógicos: O Arduino Uno não é adequado para aplicações que requerem processamento de sinal analógico em tempo real, como áudio de alta fidelidade.

### Características do Conversor Digital-Analógico (DA) do Arduino Uno:

1. Resolução: O Arduino Uno utiliza um conversor DA de 8 bits para gerar sinais analógicos;

2. Saída PWM: O Arduino Uno utiliza a modulação por largura de pulso (PWM) para simular saídas analógicas em alguns de seus pinos digitais;

3. Fácil controle: A biblioteca do Arduino fornece funções simples para gerar saídas analógicas.

**Pontos Positivos:**

1. Simplicidade: O conversor DA do Arduino Uno é fácil de usar e é adequado para muitas aplicações básicas que requerem saídas analógicas.

2. Custo acessível: O Arduino Uno é uma opção econômica para projetos com requisitos de saída analógica limitados.

3. Suporte da comunidade: Como o Arduino é amplamente adotado, você encontrará muitos recursos e exemplos disponíveis.

**Pontos Negativos:**

1. Baixa resolução: A resolução de 8 bits limita a precisão das saídas analógicas.

2. Limitações de frequência: O sinal de saída PWM tem limitações em termos de frequência e pode não ser adequado para todas as aplicações.

3. Não é um conversor verdadeiro: O Arduino Uno não possui um conversor DA real, o que limita sua capacidade de gerar sinais analógicos com alta precisão.

Em resumo, o conversor AD e DA do Arduino Uno são recursos úteis para muitos projetos, mas eles têm limitações em termos de resolução e precisão. Para aplicações que requerem maior qualidade de conversão analógica, é necessário considerar outras placas ou módulos com conversores AD e DA mais avançados.


## Memória empregada

O uso de memória e o endereçamento de memória desempenham um papel importante ao trabalhar com o conversor analógico-digital (AD) e o conversor digital-analógico (DA) do Arduino Uno. Vamos entender como a memória é alocada e endereçada ao usar esses conversores, bem como destacar os pontos positivos e negativos associados a esse aspecto.

**Uso de Memória com o Conversor AD:**

Quando você utiliza o conversor AD do Arduino Uno, a memória é alocada principalmente para armazenar as leituras analógicas e os dados relacionados à configuração. Aqui estão os principais componentes de memória relacionados ao conversor AD:

1. **Buffer de Leitura:** O Arduino Uno tem um buffer de leitura de 2 bytes (16 bits) para cada um dos 6 pinos analógicos (A0 a A5). Isso permite armazenar temporariamente os valores convertidos antes que você os acesse em seu código.

2. **Configurações de Referência e Resolução:** As configurações de referência, resolução e outros parâmetros do conversor AD são armazenados em memória, mas ocupam uma quantidade mínima de espaço.

**Pontos Positivos do Uso de Memória com o Conversor AD:**

1. **Economia de espaço:** O Arduino Uno alocou uma quantidade razoável de memória para os buffers de leitura, tornando mais fácil armazenar e processar leituras analógicas.
   
2. **Facilidade de acesso:** Os valores lidos nos pinos analógicos podem ser acessados facilmente em seu código, tornando a programação mais simples.

**Pontos Negativos do Uso de Memória com o Conversor AD:**

1. **Limitação de buffer:** O buffer de leitura é limitado a 2 bytes por pino, o que pode ser insuficiente se você estiver amostrando sinais analógicos rapidamente ou se precisar armazenar muitos dados.
   
2. **Potencial de desperdício:** Se você não usar todos os pinos analógicos, parte da memória alocada para buffers de leitura pode ser desperdiçada.

**Endereçamento de Memória com o Conversor DA:**

Ao usar o conversor DA do Arduino Uno, a memória é usada principalmente para armazenar tabelas de valores que representam a forma da onda analógica que você deseja gerar. Aqui estão os principais componentes de memória relacionados ao conversor DA:

1. **Tabelas de Valores (Look-up Tables):** Para gerar sinais analógicos com o conversor DA, você precisa armazenar uma tabela de valores digitais que representam a forma da onda desejada. Esses valores são armazenados na memória do programa, geralmente na forma de arrays.

2. **Temporizadores e Interrupções:** Em alguns casos, temporizadores e interrupções podem ser usados para controlar a taxa de atualização do sinal analógico gerado, o que também envolve o uso de memória.

**Pontos Positivos do Endereçamento de Memória com o Conversor DA:**

1. **Flexibilidade na Geração de Sinais:** Usando tabelas de valores, você pode criar uma ampla variedade de formas de onda personalizadas, o que oferece grande flexibilidade para aplicações que requerem saídas analógicas complexas.

2. **Controle de Tempo:** Ao usar temporizadores e interrupções, você pode controlar precisamente a taxa de atualização do sinal analógico, permitindo ajustes finos na frequência e amplitude.

**Pontos Negativos do Endereçamento de Memória com o Conversor DA:**

1. **Consumo de Memória:** Tabelas de valores podem ocupar uma quantidade significativa de memória, especialmente se você estiver gerando formas de onda complexas ou de alta resolução.
   
2. **Complexidade de Programação:** O uso de temporizadores e interrupções para controlar a saída analógica pode tornar o código mais complexo, requerendo um conhecimento mais avançado de programação.

É essencial equilibrar as necessidades de armazenamento de dados com a eficiência do programa e a complexidade do código, a fim de desenvolver com sucesso projetos que envolvem esses conversores.

## Interrupções

As interrupções no Arduino Uno são uma característica essencial para lidar com eventos externos que requerem uma resposta imediata, enquanto o microcontrolador executa tarefas regulares. 

Elas permitem que o Arduino interrompa sua rotina principal de execução para lidar com eventos específicos, como pulsos de sensores, sinais de botões ou outros eventos de entrada.

**Como Funcionam as Interrupções no Arduino Uno:**

1. **Fontes de Interrupção:** O Arduino Uno possui várias fontes de interrupção, como pinos digitais específicos que podem ser configurados para acionar uma interrupção quando uma mudança de estado é detectada, como borda de subida (rising), borda de descida (falling), ou mudança (change) no nível lógico. Além disso, as interrupções podem ser geradas por temporizadores e contadores do Arduino Uno.

2. **Prioridade e Tratamento:** As interrupções têm uma prioridade associada a elas, e o Arduino Uno executa a rotina de tratamento da interrupção imediatamente quando a fonte de interrupção específica é acionada. Essa rotina de tratamento é definida pelo programador e é executada rapidamente antes de retornar à tarefa principal.

3. **Biblioteca e Funções:** O Arduino IDE fornece funções e bibliotecas que facilitam a configuração e uso de interrupções. Isso torna a programação de interrupções mais acessível para desenvolvedores, mesmo aqueles sem um profundo conhecimento de microcontroladores.

**Pontos Positivos das Interrupções:**

1. **Responsividade:** As interrupções permitem que o Arduino Uno responda rapidamente a eventos externos sem precisar monitorar constantemente as entradas. Isso é particularmente útil em aplicações que envolvem sensores e eventos imprevisíveis.

2. **Eficiência de Energia:** O uso de interrupções permite que o microcontrolador entre em um modo de economia de energia quando não há eventos a serem tratados, economizando energia em aplicações alimentadas por bateria.

3. **Temporização Precisa:** Interrupções são ideais para criar temporizações precisas e para executar ações em momentos específicos, como gerar pulsos PWM ou ler sensores em intervalos regulares.

**Pontos Negativos das Interrupções:**

1. **Complexidade do Código:** A programação com interrupções pode ser mais complexa do que a programação sequencial, uma vez que você precisa gerenciar o fluxo de controle entre a rotina principal e as rotinas de interrupção.

2. **Condições de Corrida:** Ao usar interrupções, é possível que ocorram condições de corrida, onde a rotina principal e a rotina de interrupção podem tentar acessar os mesmos recursos simultaneamente, levando a resultados inesperados. Isso requer cuidado na programação para evitar conflitos.

3. **Consumo de Memória:** A implementação de rotinas de tratamento de interrupção pode aumentar o consumo de memória, especialmente em projetos com várias fontes de interrupção. É importante equilibrar o uso de interrupções com as restrições de memória do Arduino Uno.

## Prática com Interrupção

Para explorar a função de interrupção do ESP32 em um projeto no WokWi, você pode criar um circuito que utilize um sensor de movimento PIR (Passive Infrared Sensor) para detectar movimento e disparar uma interrupção quando o sensor for acionado. Vou guiá-lo através de um projeto que faz exatamente isso:

**Componentes Necessários:**

1. ESP32 no WokWi (simulação online).
2. Sensor de movimento PIR (disponível no WokWi).

**Passos do Projeto:**

1. Abra o [WokWi](https://wokwi.com/), faça seu login usando uma conta Google e inicie um novo projeto com o ESP32 buscando por **Starter Templates**

2. Clique no botão **+** do WokWi e edicione o sensor de movimento PIR digitando o seu nome. O sensor PIR geralmente possui três pinos: VCC (alimentação), GND (terra) e OUT (saída).
   
3. Conecte VCC ao pino 3.3V do ESP32, GND ao GND do ESP32 e OUT a um pino de entrada digital que você deseja usar como fonte de interrupção, por exemplo, o pino D2.

5. Configure o pino D2 como pino de entrada digital no código.

```
const int pirPin = 2;  // Pino de entrada do sensor PIR
```

4. Configure a função de interrupção para o pino 19. Isso permitirá que o ESP32 seja interrompido sempre que o sensor PIR detectar movimento. Quando a interrupção for executada, um LED acenderá e uma mensagem no monitor serial será impressa. Note que a qualquer momento que você mexer no sensor, a interrupção será atendida, mesmo com a presença do **delay** (que trava o processador).

```
const int led =5;
const int pir =19;

void IRAM_ATTR handleInterrupt() {
  Serial.println("Interrupção executada");
}


void setup(){
  pinMode(led,OUTPUT);
  pinMode(pir,INPUT);
  Serial.begin(9600);
  attachInterrupt(digitalPinToInterrupt(pir), handleInterrupt, RISING);
}
void loop(){
  const int IP=digitalRead(pir);
  Serial.println(IP);
  delay(100);
  if(IP==1){
    digitalWrite(led,HIGH);
    delay(1000);  
  }
  else{
    digitalWrite(led,LOW);
    delay(1000);  
  
  }
}
```

Agora, quando o sensor PIR detectar movimento, ele acionará a interrupção associada ao pino D2, e a função `handleInterrupt` será chamada, exibindo uma mensagem no console serial.

Este projeto demonstra como usar uma interrupção com o sensor PIR no ESP32 no WokWi. Quando o sensor detectar movimento, ele irá interromper o loop principal para lidar com o evento de detecção. Isso é útil para economizar energia e recursos quando você deseja responder imediatamente a eventos externos, como o movimento detectado pelo sensor PIR. Certifique-se de adaptar o código e o circuito para suas necessidades específicas, e aproveite a funcionalidade de interrupção do ESP32 em seus projetos.

Seu projeto precisa ficar igual a esse [WokWi](https://wokwi.com/projects/380848293751158785) 


# Conclusões

1) Você viu a importância que uma interrupção tem em um sistema embarcado. Agora pare e pense! Onde mais você colocaria uma interrupção no seu projeto?

2) Você também viu a importância de um AD e DA para que o microcontrolador possa interagir com sensores e atuadores. Lembre-se! Nós humanos, somos analógicos, mas as máquinas são digitais e o AD e DA sãop as pontes para nos conectar com elas.
   
3) O seu projeto usa uma plataforma chamada Greg Maker, que é na verdade, um microcontrolador Arduino Uno, e a interface dele, é um sensor tipo umidade, que pega a umidade (ou a condutividade) da pele humana e transforma em movimentos do mouse ou teclas do teclado.

# Dicas da Ponderada da Semana

1) Usanso o Rapberry Pi Pico, instale a IDE de programação em Python chanmada [Thonny](https://thonny.org/) no seu computador;
 
2) Nesse caso, você estará usando a interface serial UART (pinos TX e RX da Rasp conectadas na porta USB do PC);

3) Agora pense numa ideia para dar sentindo nessa comunicação, como por exemplo, a leitura de um sensor ou botão pela Rasp e uma impressão de dados ou mensagem no monitor serial da IDE Thonny.

4) Ponderada em dupla, mas cada aluno da dupla precisa mover o seu card e cada aluno deve informar no seu campo de descrição da Adalove quem é o responsável pela postagem, mas um integrante de grupo posta o link do PDF na Adalove. Os dois da dupla não precisam postar o mesmo PDF, mas precisam informar o nome do outro integrante no campo de descrição da Adalove.

5) A dupla deve desenvolver a documentação necessária que comprove sua experiência e postar o link do PDF na Adalove.
 
6) Pegue um microcontrolador no lab com o laboratorista e devolva no final dessa ponderada.

7) Prazo de entrega: até 23h59 da quarta-feira, dia 15/nov.
