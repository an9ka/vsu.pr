Чтобы запустить приёмник:
```
gcc receiver.c -o r && ./r
```

Чтобы отправить сигнал: 
```
gcc emitter.c -o e && ./e <PID> <SIGNAL>
```

Где <br>
PID - число, которое отобразилось в консоли после запуска приёмника <br>
SIGNAL - значение: ( SIGUSR1 | SIGUSR2 )