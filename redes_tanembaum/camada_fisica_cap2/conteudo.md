# CAMADA FÍSICA

 A camada física começa mostrando coisas relacionadas ao meios de transmissão por cabo que existem.

## Par Trançado:
    O par trançado é um cabo que possui pares de fios de cobre entrelaçados dentro deles.
    Os fios de cobre são entrelassados pois eles de forma paralela atuam como antenas simples
    o que causaria um quantidade tremenda de interferência. Os cabos com par trançado hoje em 
    dia conseguem transmitir até 10Gbps de dados. Esses tipos de cabos vem evoluindo, hoje o mais 
    famoso deles é o RJ45 Cat 6, que possui uma capacidade de transmissão maior de sinais. Os Cat 7 
    e Cat 8 não muitos populares pois o 7 possui um blindagem especial para sofrer menos interferência
    e o 8 só funciona em uma distância de 30 metros mais ou menos, ele consegue transmitir um 
    volume massivo de dados, só é usado para transmitir dados entre servidores próximos.

## Cabo Coaxial:
    Támbem conhecido como cabo coax, o coaxial era muito famoso por fazer a transmissão do sinal de 
    televisão. O cabo coaxial sofre menos interfêrencia que o par trançado, mas isso é devido a sua
    construção. Os materiais usados são o fio de cobre que é colocado no núcleo do cabo, o material 
    de cobre é revestido por um material isolante, o material isolante é revestido por uma malha de 
    de metal que por sua vez é revestido pela capa plástica. Hoje em dia é um dos meios de transmissão
    de dados de internet e Tv a cabo mais utilizados.

## Rede pela Energia:
    A rede pela energia é o famoso PoE (Power on Ethernet). Embora seja um tecnologia muito promissora 
    e que já seja possível fazer a transmissão de alguns bits pela rede, ainda sofre muita interferência 
    da rede de energia. O que tornou essa tecnologia possível foi o fato de que ondes elétricas possuem 
    um baixa frequência e as ondas digitais não, fazendo com que seja possível a execução dessa técnica.

## Fibra Optíca:
    Talvez a tecnologia de transmissão de dados seja a fibra optíca, o seu preço é relativamente barato 
    pois o material principal é sílica, ou seja, areia. O funcionamento da fibra é feito a partir da incidência 
    de um raio de luz dentro da fibra que é refratada e refletita ao longo da própria fibra. Uma fibra pode 
    transmitir o sinal por cerca de 100km, outro benefício é de que a fibra é mais leve para ser implementada
    ainda que a sua instalação seja um pouco mais trabalhosa. Existem dois tipos de fibra, as multi-modo e as mono-modo.
    Fibras multi-modo são as fibras que utilizam LEDs pois a vários raios de luz passando pela mesmas fibra, as 
    caractrísticas da fibra multi-modo são que ela é a fibra mais barata, tem uma durabilidade maior, transmissão
    inferior a fibra mono-modo. A fibra mono-modo é transmitida por um laser, suas características são que é a 
    fibra mais cara, dura pouco, mas a transmissão de dados é muito alta e é mais rápida támbem.

## Outras coisas tratadas no capítulo:
    A transmissão de dados massivos de um local a outro é mais fácil de ser feita por um quantidade grande de HDs ou 
    SSDs sendo transportados de um lugar para o outro, fazendo assim com que a taxa de transmissão por segundo seja
    extremamente alta.  A amanzon por exemplo possui um serviço desse, ela tem um camissão que armazena os dados e 
    leva para outro lugar.

    A velocidade máxima de um sinal qualquer no vácuo é de 2/3 da velocidade da luz, mas no mundo real a frenquência do 
    sinal tem uma pequena alteração nessa velociadade. 

# Meios de transmissão pelo ar 

## Espectro eletrómagnetico:
    O espectro eletrómagnetico trata da base de como a transmissão funciona, um circuito elétrico 
    somando com uma antena adequada consegue transmitir o sinal por distâncias razoáveis. Explica sobre
    alguns dos aspectos fisícos como a velocidade do sinal nunca é maior que a da luz pois é a velocidade 
    máxima do nosso universo. A relação entre frequência e sinal.

## Espectro de dispersão por salto de frequência

    O espectro por dispersão por salto de frenquência é quando um sinal fica transitando por várias 
    frequências diferentes. Os benfícios que isso traz é que o sinal é quase impossível de ser obstruído, 
    tem resistência a interferência e ao enfraquecimento, possui multiplos caminhos e é utilizado pelos
    militares. O uso comercial é no bluetooth

## Espectro de dispersão por sequência direta

    O espectro de dispersão por sequência direta funciona a partir de um sequência de códigos que 
    transmite o sinal através da banda, que por sua vez é mais larga. Tem resistência ao enfraque-
    cimento e a interferência. É a base para a comunicação 3G e para o sistema de posicionamento 
    global (GPS). O acesso a parte da banda é feito pelo metódo de acesso multiplo por divisão de 
    código. 

## Comunicação de banda ultra larga
    Diferente das anteriores a UWB não interfere na frequência da portadora. O seu funcionamento
    é a partir do envio rápido de pequenos pulsos elétricos por diferentes frequências. Um banda é
    definida como ultra larga se ela tiver pelo menos 500MHz ou se ela tiver 20% da capacidade 
    total da frequência central da banda. Tem uma forte resistência contra o enfraquecimento, é 
    muito utilizada para mapear imagens através de objetos e é usado em sistemas de localização
    precisos.

## Transmissão do sinal pelo cabo 
    A a transmissão do sinal pelo cabo é feita através da diferença de tensão que é passada pelo 
    cabo. O princípio do envio de sinais é feito através da série de Fourrier que criou uma equação que 
    calcula o somátorio de sinais senoidais possívelmente infinitos. A série de fourrier faz a corversão de 
    diferentes ondas em senoides e as soma e gera um sequência de harmônicos (termos). Graças a fourrier Nyquist 
    conseguiu criar umas equações mais importantes da comunicação. Ele definiu que a largura de banda em um 
    canal sem ruído é de 2B log2 V bits/s (duas vezes a banda vezes o log de quantidade de tensão na base dois 
    em bits por segundo). Essa equação permitiu calcular a taxa maxíma de bits que podem ser emviadas por um 
    canal 10 log10 S/R (dez vezes o log de sinal e signal to ratio na base dez) as taxas de log são calculadas em deci e 
    em homenagem a Alexander Graham Bell o sufixo bell foi adicionado. Assim a medida da capacidade do fluxo é em 
    decibeis. Outro grande cientista foi Shannon que deduziu a equação considerando a quantidade de ruído de presente,
    B log2(1+S/N) bits/s (banda vezes o log de um mais a o valor de signal to ratio na base dois medidos em bits por segundo).

## Modulação Digital 
    Modulação digital trata da forma como o sinal é modulado de ondas senoidais para ondas digitais. Os bits são encarados 
    como a presença ou não de eletricidade. Foram criadas várias maneiras de se fazer modulções para aproveitar ao máximo o 
    espaço de cada largura de banda. Uma das forma foi de enviar mais de um sinal por vez utilizando símbolos, assim ao invés de 
    duas tensões 4 são passadas para simbolizar mais de um sinal. Existem alguns tipos de codificação do sinal para que seja melhor 
    aproveitado o banda e fique mais fácil de representar os sinais. O fluxo de bits padrão que é o reconhecimentos dos bits feitos 
    de acordo com a tensão se tem ou não tem. NRZ que é a onde difital que a acompanha os níveis de tensão, NRZ invertida. Existe a 
    codificação manchester onde uma sequência de 4 bits é mapeada para uma sequência de 5 bits, assim impedindo longas sequências de 0s 
    ou 1s. Os sinais balanceados são outro tópico da codificação, eles são ideais pois não utilizam cc, somente ca e utilizam um outro 
    mapeamento para evitar sequências longas de 0s ou 1s. É usado o mapeamento de 8 para 10 bits, onde os 8 são divididos em dois grupos 
    um grupo com 5 que é adicionado um sexto bit e um grupo com 3 que é adicionado um quarto bit, ambos são concatenados novamente.
    A transmissão do sinal ocorre através da transmissão de banda passante onde o sinal é passado por variação de amplitude, frequência ou
    fase. A fase pode variar na quantidade de fazes que vai ser utilizada, podendo ser dois ou quatro angulos de alteração. Assim com quatro 
    ângulos temos a passagem do sinal em quadratura e conforme quantidade de pontos na quadratura aumenta diferentes sinais podem ser passados 
    pela banda.

## Multiplexação
    A tentativa e o desejo de passar mais fluxo em um lugar menor. As únicas maneiras de fazer multiplexação são por tempo, frquência e código
    
    - FDM (Multiplexação por divisão de frequência) 
    
        A FDM nada mais é do a passagem de frequências diferentes por um meiot, para evitar ruído e sobreposição entre as frequências foi
        criado um espaçamento de proteção, mas na prática ele não funciona tão bem pelo fato dos condutores não serem ideais. A OFDM 
        (Multiplexação ortogonal por divisão de frequência) se tornou possível graças a transformada de fourier. A OFDM funciona dividindo a
        portadora em diversas subportadoras fazendo com que um grande fluxo de bytes seja dividido em vários fluxos menores.

    - TDM (Multiplexação por divisão de tempo)

        Essa é mais fácil de entender. TDM cada par que está se comunicando tem que esperar um período para poder utilizar o canal.
        Foi muito utilizado pelo sistema de telefônia. O grande ponto de dificuldade foi configurar os slots de tempo para sempre 
        garantir a sincronização dos pares.

    - CDM ou CDAM (Multiplexação por divisão de código) 

        A CDM funciona de modo que toda a banda larga de frequência é utilizada simultâneamente mas só as mensagens com o mesmo código 
        conseguem se comunicar e tratam o resto como ruído. O cógido é baseado na quantidade de chips, que são as subdivisões no tempo 
        de duração dos bits, que são enviados por bits. São geralmente usados 64 ou 128 bits, mas por questões didáticas o exemplo do 
        livro é com oito chips por bit. Os chips são um vetor, nesse caso um vetor de oito posições, que representam níveis de tensão 
        de +1V ou -1V para enviar um bit. Quando um bit é enviado ele é entendido como bit 1 e quando mandam sua negativa é entendido
        como bit 0. Cada vetor corresponde a estação da qual foi emitido, quando são emitidos simultâneamente são adicionados linearmente
        um ao outro ocasionam somatórios e operações de normalização. O CDMA ideal sem ruído permite a passagem de frequências maiores
        devido ao número maior de estações, esse número maior é representado com 2^n.

    - WDM 
        
        FDM só que com raios de lux, longa duração e mais confiável.
