
slikovni izrezek Pinout mikroporcesorja iz CubeMX:
![image](https://user-images.githubusercontent.com/97598727/197708423-54024416-d6e6-4a9d-b2b5-643894c0ce70.png)

okno od TIM1 configuration-parameter settings [5%] ter ADC configuration-parameter settings:
![image](https://user-images.githubusercontent.com/97598727/197708755-ecc529df-9a99-47c2-9fbb-0c8cb33f40f4.png)

Odgovori na vprašanja:
- Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to? _____PA5_____.
- Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina? ___ADC_IN5______.
- Aktiviramo samo zeleno LED diodo na ustreznem izhodu ___PC15_______.
- V Clock Configuration spremenimo APB1 Timer clock (MHz) na 16 MHz
(pritisnemo ENTER). Kaj opazite? ________________spremeni se cela veja________________________.
- V razdelku TIM1, pod Counter Settings, bi radi časovniku spremenili frekvenco na 1 kHz, zato moramo frekvenco ABP1 Timer Clock preskalirati v polju Prescaler (PSC – 16 bit value). Koliko znaša ta vrednost? ________16000 Hz________. Vpišite to vrednost v zahtevano polje.

Slika potenciometra: 

![image_67201025 (1)](https://user-images.githubusercontent.com/97598727/200509814-f41bec29-beb6-4767-83db-6fc05e3bf1a4.JPG)

Komentar:
- Imela sva težave pri programiranju, prvič ko sva naredila program je kazalo brez napak, potem pa je v programu javljalo napake.



