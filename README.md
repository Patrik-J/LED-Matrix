<a name="readme-top"></a>

# LED Matrix 
This is part of a bigger project where I aim to built of a LED-strip and a LED-Matrix with several cool functions.

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#general">General</a>
    <li><a href="#built-with">Built with</a>
    <li><a href="#led-matrix">Needed Hardware</a>
  <!--  -->
  <!--  -->
    <!-- <li> -->
      <!-- <a href="#about-the-project">General</a> -->
      <!-- <ul> -->
        <!-- <li><a href="#built-with">Built With</a></li> -->
      <!-- </ul> -->
    <!-- </li> -->
    <!-- <li> -->
      <!-- <a href="#getting-started">Getting Started</a> -->
      <!-- <ul> -->
        <!-- <li><a href="#prerequisites">Prerequisites</a></li> -->
        <!-- <li><a href="#installation">Installation</a></li> -->
      <!-- </ul> -->
    <!-- </li> -->
    <!-- <li><a href="#usage">Usage</a></li> -->
    <!-- <li><a href="#roadmap">Roadmap</a></li> -->
    <!-- <li><a href="#contributing">Contributing</a></li> -->
    <!-- <li><a href="#license">License</a></li> -->
    <!-- <li><a href="#contact">Contact</a></li> -->
    <!-- <li><a href="#acknowledgments">Acknowledgments</a></li> -->
  </ol>
</details>

## General
For the LED-Matrix my goal is to have it have at least three different functionalities:
1. Reacting to music 
2. Clock
3. Maybe somehow displaying the played music by connecting to spotify? 

## Built with
* (Mainly) C

## Needed Hardware
Probably at least one Arduino, as a RP Pico probably wont be enough. Maybe even a small RP Pi (i.e. 3A etc.).
Just for the LED-Matrix, I will need at least 260 LEDs, as to have the construct a total width of 80cm and height 
of approx. 50cm. I plan for the LEDs to have a spacing of 4cm in between them. 
Now that I am mentioning it, I'll need to 3D-print some kind of holder for all these LEDs. 

Here will be a list of the stuff I will have to buy:
* [LEDs](https://www.amazon.de/Multicolor-LED-Dioden-Gemeinsame-Elektronikkomponenten-Leuchtdioden/dp/B01C3ZZT8W/ref=sr_1_17?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=3ATWNDFRV2ND&dib=eyJ2IjoiMSJ9.AbcKLuVLo8doK35MCzs8WJ3ObUxa_8BD_G60m2PbzkMTddyJnNBTcVt12bfbgbJuQqI2LZ9IjFJjsVpjMsfuluDJOnYMpj_CGrjLU9BZkWo1VEQf8R_DhuKLcKm7opE61eM1CwaFEDuZttvEkFvh7NvkYqf0XGhEa_lx6nPetWQaPde30EjgGs9tt30GfHcdJEBee7EA8Fh9hx_dlnWrp7OdybX77auVoVBSGczoLYoajpd4KQQQSAp-gKo7Z9Y1UlG26ejHioNteSbAwqLh4vV6yxRymwCDUXryKG5Wt1g.TTW-16pBtw7LlAOaftLfAbNlYI8PL4T52cSlQ8zEe6I&dib_tag=se&keywords=multicolor%2Bled&qid=1728067654&sprefix=multicolor%2Bed%2Caps%2C229&sr=8-17&th=1)
* [100Ω resistors](https://www.reichelt.de/widerstand-metallschicht-100-ohm-0207-0-6-w-1--metall-100-p11457.html?PROVID=2788&gad_source=1&gclid=Cj0KCQjwpP63BhDYARIsAOQkATZU4LP6TpeW5J_PMQelQ5OepPcES7iuFR4JH4RMYuypHPm_Sxj27ZEaAjliEALw_wcB)
* [Microphone](https://www.reichelt.de/arduino-mikrofon-modul-ard-mic-modul4-p282655.html?&trstct=pol_3&nbc=1)
* [IR emitters and receivers](https://www.amazon.de/LAOMAO-Infrarotdiode-Infrared-Leuchtdioden-Empf%C3%A4nger/dp/B00EFOTJZE/ref=sr_1_7?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=17KFJAFB0P6KB&dib=eyJ2IjoiMSJ9.WfuUFgHb98gNK7b9R3wvYSj-PseslOXY5BaiCCIXflnKdtYwDH_Kn35_QDINxlBWgyhLW0oFPXLgG3IGHzI_hK6kRrGjvRpOmCw_rOdn_QJljwKTRXa3koZleTWkTnbBye4zDa-yBRRpj92Re-iwt9baY_Iwq5TlhBJQ7YztFI58kTykQ2WPxEDzROpuZT-CBu0xWRxMgZgmHzOHib9oZ47-jhGlc1a7MZBFtyr8ScVJ3DI43d7CI_vLxdXN2DBS0KUclx3Liza_QeGRVkMdc7qR5hPLVs87gVqsc7fzoqY.aJg_Ty48PcAItSwxAbiwTZgBedx-t4gMRKmSYQeON0s&dib_tag=se&keywords=ir+sensor&qid=1728071184&sprefix=ir+sensor%2Caps%2C211&sr=8-7)
* [Only IR receivers](https://www.amazon.de/AZDelivery-Empf%C3%A4nger-Infrarot-Receiver-inklusive/dp/B089QKGRTL/ref=sr_1_8?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=17KFJAFB0P6KB&dib=eyJ2IjoiMSJ9.WfuUFgHb98gNK7b9R3wvYSj-PseslOXY5BaiCCIXflnKdtYwDH_Kn35_QDINxlBWgyhLW0oFPXLgG3IGHzI_hK6kRrGjvRpOmCw_rOdn_QJljwKTRXa3koZleTWkTnbBye4zDa-yBRRpj92Re-iwt9baY_Iwq5TlhBJQ7YztFI58kTykQ2WPxEDzROpuZT-CBu0xWRxMgZgmHzOHib9oZ47-jhGlc1a7MZBFtyr8ScVJ3DI43d7CI_vLxdXN2DBS0KUclx3Liza_QeGRVkMdc7qR5hPLVs87gVqsc7fzoqY.aJg_Ty48PcAItSwxAbiwTZgBedx-t4gMRKmSYQeON0s&dib_tag=se&keywords=ir+sensor&qid=1728071184&sprefix=ir+sensor%2Caps%2C211&sr=8-8)
* [IR remote and receiver](https://www.reichelt.de/arduino-infrarot-remote-kit-ard-ir-remote-p282671.html?&trstct=pos_5&nbc=1)
* [Cable](https://www.amazon.de/dp/B082WZC56B/ref=sspa_dk_detail_0?psc=1&pd_rd_i=B082WZC56B&pd_rd_w=YUEkK&content-id=amzn1.sym.6ffc9ff7-fa31-49da-8594-196e74bcf61e&pf_rd_p=6ffc9ff7-fa31-49da-8594-196e74bcf61e&pf_rd_r=02JVWE64Z0BXPFNN77RB&pd_rd_wg=goX6m&pd_rd_r=6ea90a62-c4eb-4059-bfb6-c83d24e42ccb&s=industrial&sp_csd=d2lkZ2V0TmFtZT1zcF9kZXRhaWw)
* [How the holder should look like](https://www.printables.com/model/144049-led-spacer)
* [RTC module](https://www.reichelt.de/serielle-echtzeituhr-56-byte-uhr-kalender-8-pin-soic-ds-1307z-p58150.html?&trstct=pos_13&nbc=1)
* [GPIO Expander and LED driver](https://www.berrybase.de/adafruit-aw9523-gpio-expander-und-led-treiber-breakout?c=2434)


## Approximated total cost
* 300 LEDs
* 100 resistors
* 2 microphones
* 1 IR remote and receiver
* 6m of cable
* RTC module 
* 2 GPIO Expander and LED driver

==> approx. 50€ (without 3D printing material, stuff for soldering, etc.)


