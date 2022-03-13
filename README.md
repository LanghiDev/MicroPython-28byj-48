# Motor de passo 28BYJ-48 com MicroPython
- Há nesse repositório a biblioteca Stepper, muito utilizada no Arduino, porém na linguagem MicroPython. Quem usa essa linguagem em microcontroladores não precisa se preocupar em entender toda a lógica do motor de passo. Mas pode simplesmente usar os mesmos códigos que usaria no Arduino, importando a biblioteca Stepper.py.
- O arquivo Stepper.py pode ser baixado gratuitamente e inserida no seu microcontrolador que usa MicroPython. Então, no arquivo principal (main.py), você pode importá-lo.
- Nesse projeto há o arquivo main.py como exemplo, testado de forma bem-sucedida no ESP32S. Foi testado nas GPIO'S 19, 18, 5 e 17, ligadas ao driver ULN2003.

# Apenas para motores de 4 fases
- Apesar de ter sido copiada da biblioteca original do Arduino, a classe Stepper em MicroPython foi feita apenas para motores de 4 fases - pensando nos motores 28BYJ-48. Se você souber python e quiser extender para motores de 2 ou 5 fases, poderá baixar o arquivo e adicionar os códigos que possibilitarão seu funcionamento. Ou, talvez o autor dessa biblioteca decida adicionar essas opções no futuro.

# Aproveite!
- Aproveite para desfrutar dos códigos e aprender a controlar de forma simples e fácil um motor de passo com MicroPython! ;)
