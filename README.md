# Vaja3-ADC-trigger-timer-conversion-STM32F4
Odgovori na vprašanja.

1) Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to? ____PA1______.

2) Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina? ____ADC_IN1_____.

3) Aktiviramo samo zeleno LED diodo na ustreznem izhodu ___PD12_______.

4) V Clock Configuration spremenimo APB1 Timer clock (MHz) na 16 MHz (pritisnemo ENTER). Kaj opazite? ____________Ko spremenimo APB1 Timmer na 16 MHz se spremenijo tudi APB1 peripheral clocks, APB2 peripheral clocks__________.

l) V razdelku TIM1, pod Counter Settings, bi radi časovniku spremenili frekvenco na 1 kHz, zato moramo frekvenco ABP1 Timer Clock preskalirati v polju Prescaler (PSC – 16 bit value). Koliko znaša ta vrednost? _____16000_______.

![Slika vezave](https://raw.githubusercontent.com/bozoslapy/Vaja3-ADC-trigger-timer-conversion-STM32F4/main/slika%20vezave.jpg)
![Slika mikroprocesorja](https://raw.githubusercontent.com/bozoslapy/Vaja3-ADC-trigger-timer-conversion-STM32F4/main/vaja%203%20pinout.PNG)
