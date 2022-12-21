# PAC3_Manovich_Reloaded
# **Visionant el futur amb les ulleres de Manovich: redescobrint la hibridació**

Guillem Vidal

## Heightmapper

En el disseny 3D un height map, o mapa d'altura, és una imatge en la qual cada píxel compta amb informació sobre la posició vertical a l'espai que té aquest, és a dir a partir d'una imatge 2D podem generar un relleu en es. Aquestes imatges emmagatzemen informació en una escala de grisos, sent el negre el valor més baix i el blanc el valor més alt, com més clar sigui el píxel més altura tindrà al passeig a un software 3D, a la vegada, el dissenyador pot ampliar o disminuir la distancia total, es a dir la distancia que hi hauria entre un pixel blanc i un de negre depenent de l’altura que es vulgui epr al profucte final

Els mapes d'altures, al no ser més que una imatge amb diferents tons de grisos, es poden crear manualment o generar aleatòriament amb un algorisme, però també es poden importar del món real.

Heightmapper es basa en això, podem descarregar un mapa d'altura de qualsevol part del món per després poder importar-lo al nostre software 3D i recrear el terreny d'una zona en específic.

Això és molt útil si volem crear un videojoc o simplement una escena 3D amb un terreny realista, ja que si ho intentéssim fer a mà pot ser que el resultat quedés artificial. En el cas de voler un terreny muntanyós, podríem buscar a Google Maps alguna zona amb muntanyes, buscar les coordenades al heightmapper I importar-les a la nostra escena per poder recrear-les.

Aquesta vista també revela detalls de la superfície que no són fàcilment visibles fins i tot en un model 3D. En augmentar el contrast de les dades, proporciona una visió de la història profunda del paisatge, amagada en petites diferències en el terreny, el que és molt útil per projectes de recerca.

![Sin título-1](https://user-images.githubusercontent.com/121120193/208963584-8d50d4a1-247e-414f-9114-fb0610e8a1f1.png)


## Microsoft flight simulator 2020

Un altre cas d'hibridació pot ser el videojoc Microsoft flight simulator 2020, aquest és un simulador de vol, creat per Microsoft que va sortir a la venda l'any 2020 i la part interessant és que el mapa jugable és una recreació del món escala 1:1, no només això, sinó que l'il·luminació, l'hora, el clima i factors meteorològics canvien al joc en funció del que passa al món real, és a dir, si a Barcelona està plovent dintre del joc també estarà plovent a Barcelona.

Aquest joc no podria tenir un mapa tan gran si funcionés com la resta de videojocs, ja que només la grandària del mapa seria de 2PB.

Per solucionar això el que fa flight simulator és agafar data de Bing maps, l'alternativa a Google Maps de Microsoft, i via stream ho porta dins del joc juntament amb les situacions climatològiques de cada part del món. Aquest també compta amb una IA per recrear tràfic aeri per aconseguir una experiència encara més immersiva.

Per poder jugar en la seva màxima esplendor i poder agafar tots els detalls i textures del bing maps es necessita connexió a internet constant, però el joc també disposa d'una alternativa offline, aquesta el que fa és repetir textures, models i asets que ja venen dins del joc i les va situant al mapa a mesura que ens movem.

Aquest títol és l'últim i més perfeccionat simulador de vol creat per Microsoft, no és el primer ni molt menys, ja que és el darrer d'una llarga saga de 18 altres títols que van començar a sortir l'any 1982 amb el llançament de Microsoft flight simulator 1.0, però sí que és el primer que incorpora dades de satèl·lits i una recreació tan gran del planeta terra.

Gràcies a l'innovació que presentava aquest joc i l'èxit en vendes que va ser va guanyar el Word Guinness al simulador de vol més rendible de l'història, ja que no només persones aficionades als simuladors compraven aquest títol sinó que a l'utilitzar data importada de satèl·lits i a la fidelitat que tenia amb el món real persones més amateurs també van comprar-lo.

Microsoft flight simulator 2020 també compta amb suport per ulleres de realitat virtual.

![Microsoft-Flight-Simulator-2020](https://user-images.githubusercontent.com/121120193/208963682-7df11747-41e0-4576-9b18-60cc42bcddbd.jpg)

## Referències i bibliografia:

-   Manovich, Lev. (2013).”El software toma el mando”. Barcelona. Editorial UOC.
    
-   [https://www.sidefx.com/docs/houdini/shade/normalmaps.html](https://www.sidefx.com/docs/houdini/shade/normalmaps.html)
    
-   [https://mspoweruser.com/microsoft-flight-simulator-bing-maps/](https://mspoweruser.com/microsoft-flight-simulator-bing-maps/)
    
-   [https://www.youtube.com/watch?v=YrvdQWx5WL8](https://www.youtube.com/watch?v=YrvdQWx5WL8)
    
-   [https://en.wikipedia.org/wiki/Heightmap](https://en.wikipedia.org/wiki/Heightmap)
    
-   [https://tangrams.github.io/heightmapper/#14.70833/37.6156/-107.3727](https://tangrams.github.io/heightmapper/#14.70833/37.6156/-107.3727)
