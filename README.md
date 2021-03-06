# Garagem Inteligente com Arduino e Esp-12E

## Objetivo

Trazer segurança para os habitantes de uma residência que possui garagem. 

Uma garagem que além de detectar a disponibilidade de vaga, ela detecta a presença de Gás GLD e fumaça. Ao detectar o gás ou fumaça, o portão abre automaticamente para entrar ar limpo, após sair o gás e/ou fumaça, o portão fecha automaticamente.
É possivel acionar a abertura do portão automaticamente pelo Adafruit.IO
Este projeto é um protótipo de uma garagem inteligente.


## Arquitetura:
	
- Dispositivos: Esp-12E & Arduino UNO.

## Software:

- Adafruit.IO.

## Dispositivos Utilizados:

- ESP-12E;
- Arduino Uno Atmega 328 Smd;
- 1 Sensor MQ2 (detecta gás de cozinha e fumaça);
- 1 Protoboard de 400 pontos;
- 1 Motor servo de 9g (abertura do portão); 
- 1 Sensor ultrassônico (detecta a existência de algum veículo na garagem);
- Cabos jumper de 20 cm macho X fêmea;
- Cabos jumper de 20 cm macho X macho;

## Observação:

Os diretórios são independentes, a diferença entre eles são algumas bibliotecas de conexão com Adafruit que diferem. O funcionamento é o mesmo. 
