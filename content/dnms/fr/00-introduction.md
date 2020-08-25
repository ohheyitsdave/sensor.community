---
title: Introduction
---
> 🚧 Fabriquez votre détecteur et prenez part à notre réseau mondial de données ouvertes et de technologies civiques. <br> Avec DNMS (Digital Noise Measuring Sensor), vous pouvez mesurer vous-même la pollution sonore.


 <img src="../docs/dnms/dnms-noise-measuring-sensor-kit.jpg" style="display: block; margin: 1em 0"/>


Consultez les instructions originales et les anciennes versions sur le [GitHub de Helmut Bitter](https://github.com/hbitter/DNMS/tree/master/Manual).
<br>
 Le compte GitHub présente différents montages avec différentes platines et différents microcontrôleurs.

 <br>
 
 Il existe deux grands types de montage :
 
* un montage où le microcontrôleur NodeMCU (portant le détecteur de particules fines, le thermomètre...) et le sonomètre DNMS sont séparés. Les platines sont appelées AIRROHR V1.4 and DNMS - T4 V1.4
* un montage avec le microcontrôleur NodeMCU et le sonomètre DNMS sur une même platine : DNMS - T4+NodeMCU V1.4

<br>

Seule la variante où le NodeMCU et le DNMS sont séparés est présentée ici. Pour les autres solutions, consultez le GitHub de Helmut Bitter !
 
La variante présentée sur cette page permet de séparer le détecteurs de particules fines et le sonomètre avec un câble mesurant jusqu'à 10 mètres. 
  
Ceci est particulièrement utile pour pouvoir placer le sonomètre au mieux et obtenir les mesures acoustiques les plus précises.

### Liste des composants

#####  Composants individuels
* [NodeMCU ESP8266 CPU/WLAN](https://www.aliexpress.com/wholesale?groupsort=1&SortType=price_asc&SearchText=nodemcu+v3+esp8266+ch340)
* [Teensy 4.0 development board](https://www.pjrc.com/store/teensy40.html). Autres vendeurs : [EXPTECH](https://www.exp-tech.de/plattformen/teensy/9596/teensy-4.0-development-board), [Antratek](https://www.antratek.de/teensy-4-0?gclid=EAIaIQobChMIydqP3t2Y6wIVhtKyCh1IagurEAQYASABEgJAKPD_BwE), [PIMORONI](https://shop.pimoroni.com/products/teensy-4-0-development-board)
* [Digitales Mikrofon ICS-43434](https://www.tindie.com/products/onehorse/ics43434-i2s-digital-microphone/)
* câbles silicone ultra-flexibles avec un diamètre de 0,15mm² (AWG 26) en 6 couleurs différentes
<br>
Le DNMS (Digital Noise Measuring Sensor) peut être associé avec le capteur de particules fines airRohr :

* [Capteur de particules fines SPS30](https://www.sparkfun.com/products/15103). Autres vendeurs: [TME](https://www.tme.eu/de/details/sps30/gassensoren/sensirion/1-101638-10/?brutto=1&gclid=EAIaIQobChMI-63cmP6Y6wIVDM53Ch1hNwmGEAYYASABEgLp5PD_BwE), [SOS electronic](https://www.soselectronic.de/products/sensirion/sps30-2-304234?gclid=EAIaIQobChMIsYW85oOZ6wIVAtGyCh0f8wU_EAYYASABEgK8PfD_BwE). Le capteur clasique [SDS011](https://de.aliexpress.com/wholesale?catId=0&initiative_id=AS_20200813122806&SearchText=sds011) peut aussi ête utilisé.
* [BME280 6-PIN Version, temperature & humidity](https://www.aliexpress.com/wholesale?catId=0&initiative_id=SB_20200308040440&SearchText=bme280+-5V+%2B3.3V). Autres vendeurs: [Nettigo](https://nettigo.eu/products/module-pressure-humidity-and-temperature-sensor-bosch-bme280), [Berrybase](https://www.berrybase.de/bauelemente/sensoren-module/feuchtigkeit/bme680-breakout-board-4in1-sensor-f-252-r-temperatur-luftfeuchtigkeit-luftdruck-und-luftg-252-t)
* [Câbles](http://www.aliexpress.com/wholesale?groupsort=1&SortType=price_asc&SearchText=Dupont+cable+20cm+female-female)
* [Câble Micro-USB plat](https://www.aliexpress.com/wholesale?catId=0&initiative_id=SB_20200308040708&SearchText=micro+usb+flat+cable+2m)
* [Alimentation USB](https://www.aliexpress.com/wholesale?catId=0&initiative_id=SB_20200308040834&SearchText=single+micro+usb+eu+power+supply)
* [Serre-câbles](https://www.aliexpress.com/wholesale?catId=0&initiative_id=SB_20200308040852&SearchText=cable+straps)

Les platines et le boitier sont décrits ci-dessous.

<br>

🙌 Vous avez décidé d'acheter les pièces en ligne, très bien ! 
La livraison va cependant prendre quelques semaines. 
En attendant, profitez de la vie.