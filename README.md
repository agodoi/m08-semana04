Durante este encontro, os estudantes serão apresentados aos sistemas embarcados e a forma como eles devem ser integrados com os demais sistemas. Os elementos essenciais e suas funcionalidades do sistemas embarcados serão abordados neste encontro. O conceito de sistemas ciber físicos, CPS (Cyber-Physical Systems), integração entre os sistemas computacionais e o mundo físico, é apresentado aos alunos, bem como suas aplicações. Uma análise crítica será realizada durante o encontro para verificar a importância dos sistemas embarcados neste contexto. Espera-se que ao final do encontro, os alunos possam conhecer os sistemas embarcados, CPS e as integrações realizadas entre eles. Neste encontro serão abordados: Sistemas Embarcados; Características de sistemas embarcados; Diferenças de sistemas convencionais e embarcados; Programação de sistemas embarcados; Conceito de entrada e saída; Apresentação de periféricos e sua utilização no contexto embarcado.

**Assuntos relacionados**

- CPU e processamento

- Memórias

- Programação de microcontroladores

- Simulação de sistemas embarcados


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

4. Tensão de referência: A placa Arduino Uno permite selecionar a tensão de referência para a conversão analógica, o que é útil para adaptar a faixa de medição ao seu projeto.
5. Velocidade de conversão: O conversor AD do Arduino Uno é relativamente rápido e pode realizar conversões em microssegundos, dependendo da configuração.

Pontos Positivos:
1. Facilidade de uso: O conversor AD do Arduino Uno é simples de usar e é amplamente suportado pela comunidade.
2. Baixo custo: O Arduino Uno é acessível, tornando-o uma ótima opção para projetos com orçamento limitado.
3. Adequado para muitos aplicativos: A resolução de 10 bits é suficiente para muitas aplicações, como leitura de sensores, controle de motores e outros projetos de automação.

Pontos Negativos:
1. Baixa resolução: A resolução de 10 bits pode ser insuficiente para aplicações que exigem alta precisão.
2. Sensibilidade a ruído: O conversor AD do Arduino Uno pode ser sensível a ruído elétrico, o que pode afetar a qualidade das leituras.
3. Limitado a sinais analógicos: O Arduino Uno não é adequado para aplicações que requerem processamento de sinal analógico em tempo real, como áudio de alta fidelidade.

Conversor Digital-Analógico (DA) do Arduino Uno:

Características:
1. Resolução: O Arduino Uno utiliza um conversor DA de 8 bits para gerar sinais analógicos.
2. Saída PWM: O Arduino Uno utiliza a modulação por largura de pulso (PWM) para simular saídas analógicas em alguns de seus pinos digitais.
3. Fácil controle: A biblioteca do Arduino fornece funções simples para gerar saídas analógicas.

Pontos Positivos:
1. Simplicidade: O conversor DA do Arduino Uno é fácil de usar e é adequado para muitas aplicações básicas que requerem saídas analógicas.
2. Custo acessível: O Arduino Uno é uma opção econômica para projetos com requisitos de saída analógica limitados.
3. Suporte da comunidade: Como o Arduino é amplamente adotado, você encontrará muitos recursos e exemplos disponíveis.

Pontos Negativos:
1. Baixa resolução: A resolução de 8 bits limita a precisão das saídas analógicas.
2. Limitações de frequência: O sinal de saída PWM tem limitações em termos de frequência e pode não ser adequado para todas as aplicações.
3. Não é um conversor verdadeiro: O Arduino Uno não possui um conversor DA real, o que limita sua capacidade de gerar sinais analógicos com alta precisão.

Em resumo, o conversor AD e DA do Arduino Uno são recursos úteis para muitos projetos, mas eles têm limitações em termos de resolução e precisão. Para aplicações que requerem maior qualidade de conversão analógica, é necessário considerar outras placas ou módulos com conversores AD e DA mais avançados.


## Memória empregada

## Interrupções

## Prática com Interrupção
