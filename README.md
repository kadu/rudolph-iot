### [EN Version bellow](#en)


# Rudolph a rena de nariz vermleho - Cartão de Natal IOT

Olá, eu sou o Rudolph e sei que você me conhece das histórias do Papai Noel, e eu estou aqui para ajudar ele a levar mensagens vindas do mundo todo diretamente para sua árvore de Natal.

Nos dias de hoje, com restrições de viagens (2021/2022), o Papai Noel me pediu alguma idéia genial para fazer as pessoas mais felizes, e olhando para a minha mesa, eu encontrei vários materiais de "Faça Você Mesmo" e com algum esforço, serei capaz de criar meu primeiro dispositivo IOT (Sou chique :D). Deixa eu mostrar o "my precious":

Eu tenho um modulo da espressif chamado ESP32-S2 e um display Oled (SD1309) 128x64 pixels, alguns headers e fiozinhos, além de uma PCB "da hora"(você concorda?) que vai funcionar com um software (firmware) que conectará a internet e recebera mensagens vindas do Twitter e mostrará diretamente na árvore.

Todo esse trabalho duro me deixou cansado e como você sabe, em aguns meses eu precisarei ajudar o velhinho novamente. O Software é um código aberto e você está intimado a ajudar o Velho do Saco também, chega junto e espalhe alegria pelo mundo :)

## Hardware

Eu decidi usar o ESP32-S2 "sozinho", sem um módulo já pronto como o Node32s para esse projeto, Isso significa que o Kadu (o cara que me ajuda a trazer essas coisas para o mundo real) pegou um projeto base, chamado Franzininho Wifi, que utiliza o mesmo modulo (Valeu Fabio Souza - Criador do franzinho), Então subi no ombro de gigantes e trouxe várias das coisas do projeto para esse aqui. Você pode ver  lista de compras dos componentes abaixo ou diretamente no link do projeto da Mouser

## Software

Esse é um trabalho em desenvolvimento, será feito usando o Framework Arduino, e se for possivel programarei no Platform.IO (Extensão do VS Code). A idéia é ter uma configuração de Wifi que irá guiar o usuário pela configuração e mostrará o caminho para a configuração da conta no Twitter também. E depois disso, é só correr para o abraço, ou melhor, ver as mensagens chegaram na tela, diretamente do mundo inteiro!

Veja a lista de componentes, images e links no final desse arquivo.


# Rudolph the red noused IOT Christmas Card

<a href="en"></a>
## Welcome aboard


Hi, I'm a Rudolph and you know me from Santa's Stories, and I'm here to help him to bring messages from all around the world directly to your Christmas tree.

Nowadays with some travel restrictions, Santa's asked me some genial Ideas to make happier people, and looking at my desk I found some DIY materials and with some effort, I've created my first IoT device (I'm fancy). Let me show "my precious":

I've got an Espressif MCU module called ESP32-S2 and an Oled display (SSD1309) with 2.4" and 128x64 pixels, some headers, and a cool PCB (did you like?)  that works with a Firmware that can connect to the Internet and receive messages from a Twitter account and show on the screen.

First, you will need to configure Internet Connection, and after you will be guided to get your Twitter API credentials and spread two the world how all the universe can send a graceful message directly to your Christmas tree.


All this hard work make me tired, and you know, in a few months I need to help Santa again, the Firmware code is an Open Source art of code, and you are invited to help Santa too, come with us spread happiness around the world

## Hardware


I've decided to use an ESP32-S2 standalone configuration for this project, It means that Kadu (the guy that help me to turn this thru the real world) found a project called Franzininho Wifi that use the same ESP32-S2 MCU and got a lot of Fabio's (Franzininho creator) idea and uses in mine. You could check the list of components that I've used in this CSV or directly on the Mouser Project Page.


## Software


This is a work in progress and will be made using Arduino Framework (if possible in the Platform.io environment). The Idea is to have a Wifi configuration that users can put their credentials and guided steps to configure Twitter, and after that, messages could be shown in the Screen

## Images

![Front](docs/images/pcbfront.png "Front")

![Back](docs/images/pcbback.png "Back")


## Schematics

![Schematics](docs/images/schematics_v2.svg "Schematics")

## Boom List

| Qtde| Item              | Descrição       | Link (wip)
| --- | ---               | ---             | ---
| 01  | ESP32-S2-WROOM    | MCU ESP32-S2    | Link
| 02  | 667-EVQ-P0N02B    | Push Button     | Link
| 02  | WSL080500000ZEA9  | Resistor 0Ohms  | Link
| 04  | TMCP1A106MTRF     | Capacitor 10uF  | Link
| 03  | 885382207007      | Capacitor 100nF | Link
| 02  | C0805C200J3GACTU  | Capacitor 20pF  | Link
| 01  | C0805C105K4RAC7210| Capacitor 1uF   | Link
| 01  | 1N5819W-T         | Diode           | Link
| 03  | CPDUC5V0R-HF      | Diode           | Link
| 01  | APT2012CGCK       | LED             | Link
| 02  | 4684              | Neopixel RGB LED| Link
| 01  | NCP1117LPST33T3G  | LDO             | Link
| 01  | 20021121-00010C8LF| Headers         | Link
| 01  | UJ2-MIBH-G-SMT-TR | USB Socket      | Link

Mouser link to project [here](https://www.mouser.com/ProjectManager/ProjectDetail.aspx?AccessID=f3c79484f0)

PCBWay Project [here](https://www.pcbway.com/project/shareproject/Rudolph_the_Red_Christmas_IOT_Card_fdf2904b.html)
