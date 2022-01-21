<p align="center"><img src="docs/images/pcbfront.png" width="300px" /></p>

### [EN Version](README-EN.md)


# Rudolph a rena de nariz vermelho - Cartão de Natal IOT

Olá, eu sou o Rudolph e sei que você me conhece das histórias do Papai Noel, e eu estou aqui para ajudar ele a levar mensagens vindas do mundo todo diretamente para sua árvore de Natal.

Nos dias de hoje, com restrições de viagens (2021/2022), o Papai Noel me pediu alguma idéia genial para fazer as pessoas mais felizes, e olhando para a minha mesa, eu encontrei vários materiais de "Faça Você Mesmo" e com algum esforço, serei capaz de criar meu primeiro dispositivo IOT (Sou chique :D). Deixa eu mostrar o "my precious":

Eu tenho um modulo da espressif chamado ESP32-S2 e um display Oled (SD1309) 128x64 pixels, alguns headers e fiozinhos, além de uma PCB "da hora"(você concorda?) que vai funcionar com um software (firmware) que conectará a internet e recebera mensagens vindas do Twitter e mostrará diretamente na árvore.

Todo esse trabalho duro me deixou cansado e como você sabe, em aguns meses eu precisarei ajudar o velhinho novamente. O Software é um código aberto e você está intimado a ajudar o Velho do Saco também, chega junto e espalhe alegria pelo mundo :)


## Concurso JULIALABS PCB CHALLENGE 2021

No ano de 2020, participei do  JULIALABS PCB CHALLENGE 2020 com o projeto do [Anjinho](https://www.pcbway.com/project/shareproject/Christmas_PCB_Contest___JuliaLabs.html) e esse ano estou participando novamente com nosso Rudolph, me desejem sorte!

Obrigado [Julia](https://www.twitch.tv/julialabs) por fazer esse cuncurso que é tão legal, Valeu também [Mouser](https://br.mouser.com/) e [PCBWay](https://www.pcbway.com/) por estar junto com a Julia nessa jornada! e também a [Altium Designer](https://www.altium.com/altium-designer/)

### Links importantes!

Antes de ver os detalhes do Hardware, deixo aqui os links do projeto caso você queira produzir uma cópia dessa placa lá na PCBWay, só [clicar aqui](https://www.pcbway.com/project/shareproject/Rudolph_the_Red_Christmas_IOT_Card_fdf2904b.html).

E aqui estão os componentes utilizados nesse projeto, com exceção do display [(clique aqui p/ ver)](https://s.click.aliexpress.com/e/_Aa7ykQ), você também pode ver [clicar aqui](https://www.mouser.com/ProjectManager/ProjectDetail.aspx?AccessID=f3c79484f0) para ver direto no site da Mouser


## Hardware

Eu decidi usar o ESP32-S2 "sozinho", sem um módulo já pronto como o Node32s para esse projeto, Isso significa que o Kadu (o cara que me ajuda a trazer essas coisas para o mundo real) pegou um projeto base, chamado [Franzininho Wifi](https://github.com/Franzininho/Franzininho-WIFI), que utiliza o mesmo modulo (Valeu Fabio Souza - Criador do franzinho), Então subi no ombro de gigantes e trouxe várias das coisas do projeto para esse aqui. Você pode ver  lista de compras dos componentes abaixo ou diretamente no link do projeto da Mouser

## Software

Esse é um trabalho em desenvolvimento, será feito usando o Framework Arduino, e se for possivel programarei no Platform.IO (Extensão do VS Code). A idéia é ter uma configuração de Wifi que irá guiar o usuário pela configuração e mostrará o caminho para a configuração da conta no Twitter também. E depois disso, é só correr para o abraço, ou melhor, ver as mensagens chegaram na tela, diretamente do mundo inteiro!

Veja a lista de componentes, images e links no final desse arquivo.


## Imagens

<img src="docs/images/pcbfront.png" width="400px" />
<img src="docs/images/pcbback.png" width="400px" />


## Esquemático

![Schematics](docs/images/schematics_v2.svg "Schematics")

## Lista de Compras

| Qtde| Item              | Descrição       |
| --- | ---               | ---             |
| 01  | [ESP32-S2-WROOM](https://br.mouser.com/ProductDetail/356-ESP32S2WRM3200PH)    | MCU ESP32-S2    |
| 02  | [667-EVQ-P0N02B](https://br.mouser.com/ProductDetail/667-EVQ-P0N02B)    | Push Button     |
| 02  | [WSL080500000ZEA9](https://br.mouser.com/ProductDetail/71-WSL080500000ZEA9)  | Resistor 0Ohms  |
| 04  | [TMCP1A106MTRF](https://br.mouser.com/ProductDetail/74-TMCP1A106MTRF)     | Capacitor 10uF  |
| 03  | [885382207007](https://br.mouser.com/ProductDetail/710-885382207007)      | Capacitor 100nF |
| 02  | [C0805C200J3GACTU](https://br.mouser.com/ProductDetail/80-C0805C200J3G)  | Capacitor 20pF  |
| 01  | [C0805C105K4RAC7210](https://br.mouser.com/ProductDetail/80-C0805C105K4R7210)| Capacitor 1uF   |
| 01  | [1N5819W-T](https://br.mouser.com/ProductDetail/583-1N5819W-T)         | Diode           |
| 03  | [CPDUC5V0R-HF](https://br.mouser.com/ProductDetail/750-CPDUC5V0R-HF)      | Diode           |
| 01  | [APT2012CGCK](https://br.mouser.com/ProductDetail/604-APT2012CGCK)       | LED             |
| 01  | [4684](https://br.mouser.com/ProductDetail/485-4684)              | Neopixel RGB LED|
| 01  | [NCP1117LPST33T3G](https://br.mouser.com/ProductDetail/863-NCP1117LPST33T3G)  | LDO             |
| 01  | [20021121-00010C8LF](https://br.mouser.com/ProductDetail/649-200211210010C8LF)| Headers         |
| 01  | [UJ2-MIBH-G-SMT-TR](https://br.mouser.com/ProductDetail/490-UJ2-MIBH-G-SMTTR) | USB Socket      |
| 01  | [OLED Display](https://s.click.aliexpress.com/e/_Aa7ykQ)      | OLED Display    |
