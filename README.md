# TESTNETS POW

Written by: @hvrsh (TG)

Channel: https://t.me/hashvers

---
**Automation of POW faucets**

**Configuration upon launching `testnetsPow.xml`:**

1. Use Finger Switcher - Should fingerprints be used?
   1. Finger Print Key - If enabled with **1**, a key is required to obtain fingerprints, which can be purchased here - https://fingerprints.bablosoft.com/
2. 2captcha API-key
3. Chain - Holesky or Sepolia
4. Amount - amount for mining(from,to). 
5. Threads - Number of concurrently running threads.(Recomend to use one thread)
6. Sleep - Time between accounts in the thread.
7. Clear DoneList - After successful completion or insufficient balance, private keys are recorded in the file `done_list.txt` so the software understands which accounts it has processed and which ones it hasn't. In case you interrupt its operation or a thread terminates with an error, if you need to rerun all wallets, select Yes.
8. Wallet shuffle - Should wallet shuffling be performed?

 **Files for Operation**

 `addresses.txt` - Specify addresses.

 `proxy.txt` - Proxies, selected line by line.(if you work in one thread mode you can use it without proxy. Quality of the proxy can affect to farming speed)

---

**Автоматизация Фаусета**

**Настройка при запуске `testnetsPow.xml`:**

1. Use Finger Switcher - использовать ли отпечатки.
	1. Finger Print Key - в случае включения **1** нужно ввести ключ для получения отпечатков, покупается тут - https://fingerprints.bablosoft.com/
2. 2captcha  - ключ солвера
3. chain - выбор чейна.
3. Amount - диапазон сколько минтить(from,to). 
4. Threads - количество потоков запущенных одновременно.(Лучше работать в одном потоке).
5. Sleep - сон между аккаунтами в потоке.
6. Clear DoneList - После успешного выполнения или отсутствия достаточного баланса в файл `done_list.txt` записываются приватники, чтобы софт понимал какие аккаунты он прошел а какие нет, в случае если вы прервали его работу или поток завершится с ошибкой. Если нужно прогнать все кошельки заново - выбираем Yes.
7. Wallet shuffle - делать ли перемешивание кошельков.

 **Файлы для работы**

 `addresses.txt` - указывать приватники.

 `proxy.txt` - прокси, выбираются построчно(если работаете в один поток то можно и без прокси. На плохих поркси фарм идет дольше).

Check modules installing\Проверьте включены ли модули перед установкой.
![Example](https://github.com/HhvrshH/testnetsPOW/blob/main/example.jpg)
