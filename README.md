Esse documento tem como o intuito explicar como o processador feito funciona, falando sobre cada módulo e tudo mais.

**Esses 3 componentes explicam como a instrução é passada ao processador e como novas instruções são carregadas a cada ciclo de clock, além de mostrar como instruções posteriores são carregadas**

### REGISTRADOR PC
![Registrador de PC](RegistradorPC.png)

### ROM
![ROM](ROM.png)

### SOMA 4
![Soma 4](Soma4.png)



**Esses componentes mostram boa parte da estrutura do processador, mostrando como ele pode realizar cálculos e salvar dados nos registradores e RAM, além de conseguir resgatar esses valores para colocar no registradores**


### CONTROL
![Control](Control.png)

### SEPARADOR DE BITS DE INSTRUÇÕES
![Separador de Bits de Instruções](SeparadorBitsDeInstrucao.png)

### EXTENSOR DE SINAL
![Extensor de Sinal](ExtensorDeSinal.png)

### MUX DE REGISTRADOR QUE VAI TER DADOS ESCRITOS
![Mux de Registrador que vai ter dados escritos](MuxDeRegistradorASerEscrito.png)

### BANCO DE REGISTRADORES
![Banco de Registradores](BancoDeRegistradores.png)

### ALU CONTROL (ULA CONTROL)
![ULA Control](ALU_Control.png)

### ULA
![ULA](ULA.png)

### MUX DE SEGUNDO OPERANDO
![Mux de segundo operando](MuxDeSegundoOperando.png)

### RAM
![RAM](RAM.png)

### MUX DE DADO QUE DEVE SER ESCRITO
![Mux de dado que deve ser escrito](MuxDeDadoASerEscrito.png)


**Esses componentes mostram como funciona a estrutura de Desvio, permitindo que o programa possa ir para determinados espaços de memória onde estão as instruções requisitadas, como BNE, BEQ e Jump**


### PORTAS LÓGICAS DE BNE E BEQ
![Portas Lógicas de BNE e BEQ](BNE_e_BEQ_Portas.png)

### SOMA PC DESVIO
![Soma PC Desvio](SomaPcDesvio.png)

### MUX DE DESVIO DE ENDEREÇO
![Mux de desvio de endereço](MuxDeDesvioEndereco.png)

### SEPARADOR DE BITS DE ENDEREÇO
![Separador de bits de endereço](SeparadorDeBitsDeEndereco.png)

### SHIFT LEFT DE 2 BITS
![Shift Left de 2 bits](ShiftLeft2.png)

### ESTRUTURA PARA CRIAR NOVO ENDEREÇO
![Estrutura para criar novo endereço](EstruturaDeCriacaoDeNovoEndereco.png)

### MUX DE JUMP
![Mux de Jump](MuxDeJump.png)


**Esses dois componentes servem para ajudar o aluno a debugar melhor o processador e entender como os dados estão sendo usados e quais registradores possuem quais valor**


### DISPLAY DE DEBUG
![Display de Debug](DisplayDebug.png)

### CONTROLE DO PROCESSADOR
![Controle do Processador](ControleProcessador.png)





















