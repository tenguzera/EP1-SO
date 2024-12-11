# EP1-SO
O objetivo desse EP foi implementar uma nova chamada de sistema para o xv6, um sistema operacional criado para fins educativos pelo MIT, que informa a quantidade de vezes que a syscall read() foi chamada por qualquer processo.

Passos para compilar e rodar o sistema: (Comandos com base na versõ 24 do Ubuntu)

GCC11 (Não há garantia de funcionamento nas versão mais novas):
```$ sudo apt install gcc-11```

O emulador QEMU:
```$ sudo apt install qemu-system```

Clonar esse repositório com git:
```$ git clone https://github.com/tenguzera/EP1-SO/```

Complilar os arquivos e executar o xv6:
```$ cd xv6-modificado/```
```$ make```
```$ make qemu-gdb```

Programas para teste da nova chamada de sistema também foram incluídos, test_1 e test_2, que podem ser executados dentro do xv6. Suas implementaçãos e o resutado esperado se encontra junto com os arquivos do xv6.

```$ test_1```
```$ test_2```
