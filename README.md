# Sistema-de-Escalonamento-de-Processos-C  
Universidade de Vassouras  
Disciplina: Estrutura de Dados  
Professor: Gioliano Bertoni  

Simule um sistema operacional simplificado  

Use:  
Fila  
Processos aguardando CPU.  
Dados:  
• PID  
• nome do processo  
Pilha  
Histórico de processos encerrados.  
Dados:  
• PID  
• motivo do encerramento  

Lista Encadeada  
Processos ativos.  
Dados:  
• PID  
• nome  
• estado  

Implemente fila de prioridade onde processos críticos têm prioridade maior.  
Exemplo:  
• antivírus → prioridade 10  
• navegador → prioridade 3  
• editor → prioridade 2
O sistema deve executar primeiro o processo mais prioritário.

**Estrutura do Projeto:**  
Escalonamento/  
main.c  
fila.c  
fila.h  
pilha.c  
pilha.h   
lista.h   
lista.c   

**Comando para compilar no terminal:**  
gcc main.c fila.c pilha.c lista.c -o sistema.exe  

**Comando para executar:**  
./sistema.exe
