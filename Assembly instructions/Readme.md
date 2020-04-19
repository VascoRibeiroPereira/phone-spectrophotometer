**Assembly instructions**

+ [Version Française](#instruction-pour-assemblage)

After sourcing the materials described in the BOM start assembling the parts as described in this document.

**3D printed parts**

There are two parts to be 3D printed - the PLA LED block and the Cuvette Holder.

You can use a 3D printer service online or in your local community, or even print it yourself.
If you are going to print it yourself the the recommended settings to 3D print are described in the table 1 (using Ultimaker Cura software).

<i>Table 1 - Main characteristics used to 3D print the Phone Spectrometer</i>

|  Characteristic |  Selection |
|:-:|:-:|
| Layer height  |  0.2mm |
|  Wall thickness |  2mm |
| Top/Bottom thickness  | 0.8mm  |
|  Infill density |  20% |
| Printing temperature  | 210ºC  |
|  Retraction | Enabled  |
| Print speed  | 50mm/s  |
| Generate support  |  No |
|  Build plate adhesion type | Brim  |

Since the 3D printed method is by Fused Deposition Manufacturing the layers are horizontal. This means that the cuvette holder may be fragile at some key parts, and may easily snap. We recommend you to 3D print the cuvette holder horizontally so you have a stronger and much durable part to work with (figure 1).

![alt text](https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/Assembly%20instructions/Assembly_assets/3Dprint_orientation.PNG?raw=true)
<i>Figure 1 - Recommended orientation to 3D print the Cuvette Holder</i>

The recommended material to 3D print is a Traffic Black PLA filament (RAL 9017), from Fillamentum Manufacturing Czech s.r.o. or equivalent. 

**Cuvette Holder**

This part only requires the addition of the rubber part (i.e. figure 2)

<img src="https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/Assembly%20instructions/Assembly_assets/rubber_part.PNG?raw=true" width="200">

<i>Figure 2 - Rubber part to be glued to the cuvette holder.</i>

Use a puncher to do a hole in the middle of the rubber
Glue it tightly aligned to the rear aperture of the cuvette holder so it will stay between the light exit and the phone sensor - as seen in the BOM designators doc.

This rubber will help you align the rear hole with the phone sensor to get the maximum light measurement possible and also limit the ambient light to interfere with the sensor.

**LED Block**

The LED you choose to use depends on the analyte; for instance, you can have several PLA LED Blocks with different LED mounted and so different emission wavelengths.

To mount the LED you have to identify the LED cathode (-) and anode (+) - figure 3.

<img src="https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/Assembly%20instructions/Assembly_assets/LED_scheme.PNG?raw=true" width="200">

<i>Figure 3 - A simple scheme of how to identify the cathode and the anode legs of an LED.</i>

Next, mount the LED as specified in figure 4.

![alt text](https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/Assembly%20instructions/Assembly_assets/LED_mount.PNG?raw=true)

<i>Figure 4 - LED mounted in the printed block, with a CR2032 battery. The anode passes trough the right hole to the outside, touching the battery when it is in the down position and the cathode passes in the first hole to the outside and them to the further left hole to the inside of the model, creating a loop.</i>


The two parts - LED Block and Cuvette Holder fit together and the LED goes inside the front aperture of the Cuvette Holder - it may be necessary to adjust the LED position the first time.

**Finish**

After the assembly of the parts, turn on the LED and mount it with the rear hole pointed near the front camera of your phone. Open the Shoebox Spectrophotometer APP (here on play store https://play.google.com/store/apps/details?id=appinventor.ai_billhosker.Shoeboxspec&hl=en_US and here the source Apk https://androidcrew.com/app/appinventor.ai_billhosker.Shoeboxspec), start moving the model checking the light measure to figure when the light gets to the sensor - you should get reading from 0, when the rear hole is completely misaligned, to a big value like 4000 for example (this depends on the sensor of your phone).

<ins>Note:</ins>

If the LED Block have a loose fit to the Cuvette Holder you may use something so it remains stable (such as a little piece of paper between the models, or an elastic rubber). You may even glue it if you don’t intend to change the LED Block.
The LED Block turns on when the coin battery in down and off when the battery is up.
You can use the LED Block turned on to help you glue the rubber part to the Cuvette Holder.
Do not use the APP when the light measurement seams to be at the highest value possible. Move a little the holder so it slightly misalign with the sensor and gets a more variable value so the sensor is not saturated with light.

## Instruction pour assemblage

Après avoir sélectionné les matériaux décrits dans la nomenclature, commencez à assembler les pièces comme décrit dans ce document.

**Pièces imprimées en 3D**

Il y a deux parties à imprimer en 3D : le bloc LED PLA et le porte-cuvette.

Vous pouvez utiliser un service d'impression 3D en ligne ou dans votre communauté locale, ou même l'imprimer vous-même. Si vous comptez l'imprimer vous-même, les paramètres recommandés pour l'impression 3D sont décrits dans le tableau 1 (à l'aide du logiciel Ultimaker Cura).

<i>Tableau 1 - Principales caractéristiques utilisées pour l'impression 3D du spectromètre téléphonique</i>

| Caractéristiques | Selection |
|:-:|:-:|
| Hauteur de la couche | 0,2 mm |
| Epaisseur de la paroi | 2mm |
| Épaisseur du dessus/du dessous | 0,8 mm |
| Densité de remplissage | 20 |
| Température d'impression | 210ºC |
| Rétraction | activée |
| Vitesse d'impression | 50mm/s |
| Générer un support | Non |
| Construire une plaque d'adhérence typée | Brim |

Comme la méthode d'impression en 3D est celle de la fabrication par dépôt fondu, les couches sont horizontales. Cela signifie que le porte-cuvette peut être fragile à certains endroits clés et peut facilement se casser. Nous vous recommandons d'imprimer en 3D le porte-cuvette à l'horizontale afin d'avoir une pièce plus solide et plus durable pour travailler (figure 1).

![alt text](https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/Assembly%20instructions/Assembly_assets/3Dprint_orientation.PNG?raw=true)

<i>Figure 1 - Orientation recommandée pour l'impression 3D du porte-cuvette</i>

Le matériau recommandé pour l'impression 3D est un filament PLA Traffic Black (RAL 9017), de Fillamentum Manufacturing Czech s.r.o. ou équivalent.

**Porte-cuvette**

Cette partie ne nécessite que l'ajout de la partie en caoutchouc (c'est-à-dire la figure 2)

<img src="https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/Assembly%20instructions/Assembly_assets/rubber_part.PNG?raw=true" width="200">

<i>Figure 2 - Pièce en caoutchouc à coller sur le porte-cuvette.</i>

Utilisez un poinçon pour faire un trou au milieu du caout. Cochouc. Collez la pièce fermement alignée sur l'ouverture arrière du porte-cuvette afin qu'elle reste entre la sortie de la lumière et le capteur du téléphone − comme indiqué dans le document des désignations de la nomenclature.

Ce caoutchouc vous aidera à aligner le trou arrière avec le capteur du téléphone pour obtenir la mesure de lumière maximale possible et aussi limiter la lumière ambiante pour interférer avec le capteur.

**Bloc de LED**

La LED que vous choisissez d'utiliser dépend de l'analyte ; par exemple, vous pouvez avoir plusieurs blocs de LED PLA avec différentes LED montées et donc différentes longueurs d'onde d'émission.

Pour monter la LED, vous devez identifier la cathode (-) et l'anode (+) de la LED - figure 3.

<img src="https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/Assembly%20instructions/Assembly_assets/LED_scheme.PNG?raw=true" width="200">

<i>Figure 3 - Un schéma simple pour identifier la cathode et les pattes d'anode d'une LED.</i>

Ensuite, montez la LED comme indiqué sur la figure 4.
![alt text](https://github.com/VascoRibeiroPereira/phone-spectrophotometer/blob/master/Assembly%20instructions/Assembly_assets/LED_mount.PNG?raw=true)


<i>Figure 4 - LED montée dans le bloc imprimé, avec une pile CR2032. L'anode passe à travers le trou de droite vers l'extérieur, touchant la pile lorsqu'elle est en position basse et la cathode passe dans le premier trou vers l'extérieur et eux dans le trou plus à gauche vers l'intérieur du modèle, créant ainsi une boucle.</i>

Les deux parties - le bloc de LED et le porte-cuvette s'emboîtent et la LED passe dans l'ouverture avant du porte-cuvette - il peut être nécessaire d'ajuster la position de la LED la première fois.

**Terminer**

Après l'assemblage des pièces, allumez la LED et placez la avec sur trou arrière pointé près de la caméra avant de votre téléphone. Ouvrez l 'application de spectrophotomètrie de Shoebox (ici sour le play store https://play.google.com/store/apps/details?id=appinventor.ai_billhosker.Shoeboxspec&hl=en_US et ici son Apk https://androidcrew.com/app/appinventor.ai_billhosker.Shoeboxspec), commencez à déplacer le modèle en vérifiant la mesure de la lumière pour savoir quand la lumière arrive au capteur − vous devriez obtenir une lecture de 0, lorsque le trou arrière est complètement désaligné, à une grande valeur comme 4000 par exemple (cela dépend du capteur de votre téléphone).

<ins>Note :</ins>

Si le bloc de LED est mal ajusté au porte-cuvette, vous pouvez utiliser quelque chose pour qu'il reste stable (comme un petit morceau de papier entre les pièces assemblées, ou un élastique). Vous pouvez même le coller si vous n'avez pas l'intention de changer le bloc de LED. Le bloc LED s'allume lorsque la pile est déchargée et s'éteint lorsque la pile est pleine. Vous pouvez utiliser le Bloc LED allumé pour vous aider à coller la partie en caoutchouc sur le Porte-cuvette. N'utilisez pas l'application lorsque la mesure de la lumière semble être à la valeur la plus élevée possible. Déplacez un peu le support pour qu'il s'aligne légèrement sur le capteur et obtienne une valeur plus variable afin que le capteur ne soit pas saturé de lumière.

