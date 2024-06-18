O desenvolvimento do projeto foi realizado utilizando o software CADeSimu 4.0, disponibilizado durante as aulas. Para atender aos requisitos de implementação, foram utilizados os seguintes componentes:
•	Um Controlador Lógico Programável (CLP) SIEMENS LOGO 24RCE;
•	Uma soft-starter modelo SFT1;
•	Uma furadeira (MF) e um motor (ME) para levantar e abaixar a furadeira;
•	Duas lâmpadas, onde L1 indica estado "ligado" e L2 indica estado "desligado";
•	Relés M1 (para a descida) e M2 (para a subida) do motor ME;
•	Relé M3 que aciona o motor da furadeira através da soft-starter;
•	Botoeiras de clique (B1, B2 e EM) e sensores representados por botoeiras (S1, S2, S3, S4, S7).
Para representar o movimento de descida, os contatores M1 e M2 fazem uma inversão entre os terminais S e T da rede trifásica, o que alimenta o motor trifásico ME adequadamente.
Em relação às saídas do módulo lógico do CLP, as configurações são as seguintes:
•	Q1 ativa o relé M1;
•	Q2 ativa o relé M2;
•	Q3 aciona a lâmpada de estado "ligado";
•	Q4 aciona a lâmpada de estado "desligado".
A programação das saídas foi realizada utilizando a linguagem ladder, que permite configurar as saídas com base nos valores de entrada. Este processo assegura que o comportamento desejado do sistema seja alcançado de forma precisa e eficiente.
Uma imagem ilustrativa do sistema pode ser observada na figura abaixo, que demonstra a disposição e interconexão dos componentes mencionados.
