Changement de paradigme dans les moniteurs en 2024, où l'OLED domine la plupart des segments haut de gamme, les dalles VA deviennent enfin performantes et l'IPS est relégué à l'entrée de gamme pour le plus grand plaisir des joueurs et créatifs à petit budget. Ce guide remplace l'ancien guide moniteur, que vous pouvez retrouver [ici](https://www.reddit.com/r/france/comments/raut39/guide_dachat_moniteurs/).

[Les autres guides d'achat](https://www.reddit.com/r/france/search?q=guide+author%3Achuckmauricefacts+flair%3Ascience&restrict_sr=on&sort=relevance&t=all)

[Les guides sur Github](https://github.com/chuckdisk/mercredi_tech)

## Taille et définition

Déjà on va commencer par une petite erreur de français : 

* La [définition](https://fr.wikipedia.org/wiki/D%C3%A9finition_d%27%C3%A9cran), c'est le nombre de pixels affichés à l'écran (appelée couremment à tort résolution). Ex : *1920x1080 pixels*.

* La [résolution](https://fr.wikipedia.org/wiki/R%C3%A9solution_spatiale_des_images_matricielles), c'est la définition divisée par la taille de l'écran. Ex : *1920x1080 à 24" (92 pixels par inch ou ppi)*

Parlons d'abord de définitions. Tout ça est [standardisé](https://en.wikipedia.org/wiki/Graphics_display_resolution), voici les plus communes :

| 16:9                 | Ultrawide (21:9)      |
| -------------------- | --------------------- |
| 1920 x 1080 (FHD)    | 2560 x 1080 (UW-FHD)  |
| 2560 x 1440 (QHD)    | 3440 x 1440 (UW-QHD)  |
| 3840 x 2160 (4K UHD) | 3840 x 1600 (UW-QHD+) |

Évidemment pour les joueurs, **plus la définition est élevée, plus la carte graphique est sollicitée.** L'incrément n'est pas linéaire grâce à différentes optimisations, mais faire tourner un jeu en QHD ou en 4K sera nettement plus lourd qu'en FHD (mais sans solliciter plus le CPU).

Au passage, on ne dit pas "2K" quand on parle de définition d'écran, c'est [une définition pour le mastering cinéma](https://videocide.com/glossary/dci-2k/) proche du FHD. Même les revendeurs s'y mettent maintenant, donc je me sens obligé de dire que ça signifie souvent **QHD** (2560x1440p), mais c'est une erreur.

## Résolution (=définition/taille)

Ce qui est important donc, c'est **la résolution**, le rapport entre la **taille de l'écran** et sa **définition** (en ppi, pixel par inch). De mon expérience, on ne distingue plus les pixels à partir d'un taux d'environ 100 ppi. A l'inverse, un taux de ppi trop élevé va rendre les éléments illisibles.

Ça varie selon les gens et des dalles, ça dépends de facteurs différent comme votre acuité visuelle, le type de dalle, la distance oeil-écran, l'habitude ou tout simplement l'utilisation que vous faites de votre écran (un graphiste sera plus exigeant qu'un gamer sur ce point).

En partant de ce postulat, on peut définir **les résolutions idéales pour un écran confortable :**

* 24" : 1920x1080 -> 91 ppi

* 27" : 2560x1440 -> 108 ppi

* 32" : 3840x2160 -> 138 ppi

Un site pratique pour calculer la densité de pixels : **[sven.de/dpi](https://www.sven.de/dpi/)**

L'augmentation de la définition permet également de profiter de plus de superficie sur son bureau pour afficher des fenêtes. Comparaison du nombre de fenêtres qu'on peut afficher sur ces 3 définitions : [FHD](https://imgur.com/3lxAmGi), [QHD](https://imgur.com/cBNLWFJ), [4K](https://i.imgur.com/ey9etWR.png). 

Pour la productivité, c'est génial car vous pourrez afficher plus d'éléments sur l'écran, ou utiliser le scaling (HiDPI, Retina) pour éviter d'avoir des éléments [trop petits](https://www.memesmonkey.com/images/memesmonkey/08/084f157e54694987ecb05a49eee33e86.jpeg). Pour le gaming, l'image affichée aura toujours la même taille, c'est surtout une augmentation des détails (même si certains jeux permettent d'ajuster la taille de l'interface).


## Technologies de dalle

Je vous fais grâce de la science, retenez que c'est des **grilles de cellules à cristaux liquides** (LCD) à [matrices actives](https://en.wikipedia.org/wiki/Liquid-crystal_display#Active-matrix_technologies) avec différentes façon d'activer chaque cellule (envoyer une tension) et de les rétro-éclairer. Sauf pour l'OLED, cf plus bas.

* **TN :** (Twisted Nematic) : très populaire du temps où on n'arrivait pas à faire des dalles haute fréquence avec les autres technos, c'est maintenant une technologie obsolète qui a de gros défauts (faibles angles de visions, couleurs exécrables). A oublier pour tout nouvel achat.

* **IPS :** (In-Plane Switching) : très bon sur la fidélité colorimétrique, les temps de réponse et les angles de vision. Elles ont cependant un contraste inférieur aux dalles VA. 

* **VA :** (Vertical Alignment) : longtemps resté inférieur à l'IPS sur les temps de réponse, mais supérieur sur le contraste, on trouve enfin des dalles VA performantes. Adieu le ghosting, bonjour les dalles VA modernes, une gamme qui se place maintenant entre l'IPS et l'OLED. Les angles de vision restent inférieurs mais ce n'est que rarement un problème

* **OLED :** (Organic Light-Emitting Diode) : contrairement aux dalles à cristaux liquides, une dalle OLED est une grille de diodes microscopiques qui émettent leur propre lumière. La technologie OLED est encore onéreuse mais offre de nombreux avantages : noirs parfaits, basse conso, temps de réponse imperceptibles... Elle s'impose comme le nouveau standard sur le haut de gamme, malgré un risque de  burn-in à long terme.

**Tableau récapitulatif :**

| **Dalle** | **Taux de contraste** | **Fidélité des couleurs** | **Rapidité** | **Angles de vision** | **Prix**  |
|-----------|------------|-------------|----------------|------------|------------
| IPS       | Moyen      | Bon         | Bon            | Excellent  | Abordable  |
| VA        | Bon        | Bon         | Bon            | Moyen      | Abordable  |
| OLED      | Excellent  | Excellent   | Excellent      | Excellent  | Elevé      |

[Explication des différentes technologies avec vues au microscope](https://tftcentral.co.uk/articles/panel_technologies).

> Note sur les dalles incurvées : en ultrawide (21:9 et plus), la courbe est là pour mieux épouser la vision en arc de l'oeil humain. **En 16:9 par contre, la courbe ne procure aucun avantage, elle existe pour réduire un défaut des dalles VA : les couleurs deviennent ternes sur les côtés.**


## Performance

Les paramètres à prendre en compte pour du jeu :

* **Fréquence de rafraichissement (en Hertz) :** le nombre de fois que l'image peut être actualisée en une seconde. 60-75Hz pour de la bureautique, 120-180Hz pour du jeu, 240Hz+ pour le jeu compétitif. 

* **Temps de réponse (en ms) :** le temps qu'il faut pour qu'[un pixel change complètement de couleur](https://www.rtings.com/monitor/tests/motion/motion-blur-and-response-time). C'est le principal critère différenciateur pour les écrans gaming. Le marketing est parfois un peu menteur en utilisant des temps de réponse idéaux (transition parfaite blanc à noir...) là où le vrai temps de réponse moyen est plus élevé. Les dalles OLED excellent dans les temps de réponses imperceptibles.

* **Input lag (en ms) :** le délai entre l'action que vous effectuez et son affichage à l'écran. [Plus d'infos ici](https://www.rtings.com/monitor/tests/inputs/input-lag).

* **AdaptiveSync :** permet d'adapter la fréquence de rafraichissement aux fps que peut générer la carte graphique. Auparavant il fallait choisir entre Freesync (AMD, Intel) et G-Sync (Nvidia), maintenant l'écrasante majorité des écrans récents sont Freesync + compatibles G-Sync.

Pour des performances optimales en jeu, on recherche évidemment l'écran avec la plus haute fréquence de rafraichissement et le plus bas input lag & temps de réponse possible. 

En pratique, la différence entre 60 et 144Hz est assez impressionnante (surtout si on revient à 60Hz après). La différence entre 144Hz et 240Hz, en comparaison, l'est beaucoup moins, et même certains joueurs compétitifs se trompent en blind-test.

[Comparaison de fréquence filmée en slow motion](https://www.youtube.com/watch?v=Q1cmhZs1P54).



## Couleurs

Le contraste, la consistance et la fidélité colorimétrique, critères essentiels pour les professionnels de l'image et de la vidéo.

* **Contraste et profondeur des noirs :** de nouvelles méthodes de rétroéclairage LCD (local dimming) permettent un contraste plus élevé. Les dalles OLED quand à elles sont dotées d'un contraste exceptionnel grâce au vrai noir atteint quand les pixels OLED sont éteints.

* **Espaces colorimétriques :** on mesure en "pourcentage de couverture" la capacité d'un écran à afficher correctement une plage de couleur. Il en existe plusieurs : **sRGB** ou **Adobe RGB** pour la photo, **REC 709** ou **DCI-P3** pour la vidéo. La grande majorité des écrans IPS récents ont une excellente couverture du sRGB, mais pas forcément des autres espaces. [Explications](https://www.rtings.com/monitor/tests/picture-quality/color-gamut).
  
* **Calibrer sa dalle :** même les dalles d'excellente qualité nécessitent un calibrage pour être les plus fidèles possibles. Pour ceci, utilisez [une sonde de calibration](https://www.creativebloq.com/features/best-monitor-calibrator) et son logiciel associé. Aux dires des professionnels, il faut répéter l'opération tout les 2-3 mois. Le coût élevé de la sonde la réserve aux professionnels exigeants et aux entreprises.

* **La HDR (High Dynamic Range) :** on utilise une plage de couleurs plus importante (codée sur 8 ou 10 bits, au lieu de 6 bits), ce qui donne une image aux couleurs plus vives. Malheureusement encore beaucoup de moniteurs utilisent de la "fausse" HDR (HDR 400 : l'écran est compatible avec un signal HDR, mais en pratique la dalle ne permet pas de l'afficher proprement). Si vous voulez profiter de la HDR sur vos jeux, il convient de choisir un moniteur avec du local-dimming performant, ou un OLED.

## Défauts potentiels des écrans

Malgré l'évolution des technologies de dalles, il reste des défauts qu'on peine encore à corriger. Certaines dépendent un peu d'une "lotterie de la dalle", donc je n'ai pas de conseils pour les éviter, mais sachez que ça existe, et que si vous tombez dessus vous pouvez utiliser votre droit de rétractation (mais pas forcément la garantie) :

**Sur les dalles IPS/VA :**

* **[Backlight bleed :](https://www.displayninja.com/what-is-backlight-bleed/)** fuites de lumières sur les bordures de l'écran, souvent signe d'un mauvais contrôle qualité. Exemple entre un [bon](https://imgur.com/a/WDHHL1r) et un [très mauvais](https://imgur.com/a/n8Merv3) élève (deux écrans que j'ai possédé).

* **[IPS glow :](https://www.youtube.com/watch?v=6TlOliiiwi8)** couleurs diffuses aux coins de l'écran, qui varient avec l'angle de vision (contrairement au backlight bleed). Beaucoup moins gênant que ce dernier, mais également signe d'un mauvais contrôle qualité.

* **[Ghosting/black smearing :](https://www.youtube.com/watch?v=D6g85vqdK2A)** une trace sombre laissée par les objets en mouvement, causée par un temps de transition trop élevé entre des couleurs sombres (temps de réponse). Typiquement présent sur les dalles VA d'ancienne génération.

* **[Overshoot :](https://blurbusters.com/faq/lcd-overdrive-artifacts/)** une couronne claire laissée par des objets en mouvement, causée par une exagération des corrections anti-ghosting (overdrive).

**Sur les dalles OLED :**

* **[Edge fringing](https://www.reddit.com/r/ultrawidemasterrace/comments/un40e6/the_alienware_oled_aw3423dw_fringing_does_effect/?share_id=T19m4F-cd3noQvjka8PYR)**, altérations de couleur causées par le [layout triangulaire](https://www.displayninja.com/wp-content/uploads/2023/05/Samsung-QD-OLED-2023-Panel-Subpixel-Layout.jpg) des subpixels QD-OLED. Ce n'est pas perceptible par tout le monde, et Samsung affine ses dalles à chaque itération, mais si vous voulez un écran QD-OLED essayez de tester avant d'acheter.

* **[Burn-in :](https://www.youtube.com/watch?v=wp87F6gczGw)** Les dalles OLED peuvent être marquées d'une image statique si elle reste affichée trop longtemps. Respectez donc bien les précautions d'utilisation et évitez d'afficher des éléments fixes (barres d'outils, icônes sur le bureau, fond d'écran fixe...).

*******

# Quel écran acheter ?

Ces catégories reflètent mon état d'esprit sur le marché des moniteurs, les omissions de certaines gammes sont volontaires, mais les guides en fin de post vous permettront de combler les trous si besoin. Les prix mentionnés sont **les prix recommandés** par rapport aux écrans concurrents, si l'écran est plus cher que le prix que je donne il n'est plus compétitif. Si il est moins cher, c'est tout bonus.


## IPS vs VA : bataille jusqu'en entrée de gamme (jeu/création, 27" QHD 165Hz+)

Autrefois le sweet spot pour les gamers, les écrans IPS voient leur prix baisser et se repositionnent sur l'entrée de gamme. Temps de réponse très faibles, bonnes performances et fidélité colorimétrique. Leur seul vrai défaut : le contraste. Pour ça, privilégiez les quelques écrans à dalle VA + rétroéclairage mini-LED, un peu plus chers que les IPS.

* **[Dell G2724D](https://www.rtings.com/monitor/reviews/dell/g2724d)** - [230€](https://www.dell.com/fr-fr/shop/%C3%A9cran-de-gaming-dell-27-g2724d/apd/210-bhtk/moniteurs-et-accessoires-de-moniteur) - S'il faudra faire une passe sur la HDR, c'est un moniteur IPS très réactif régulièrement bradé par Dell.

* **[AOC Q27G3XMN](https://www.rtings.com/monitor/reviews/aoc/q27g3xmn)** - [300€](https://www.idealo.fr/prix/203609538/aoc-q27g3xmn.html) - Les faibles angles de vision pourront être gênants pour certains, mais on a enfin des dalles VA aussi réactives que l'IPS, avec un contraste supérieur et du Mini-LED local dimming. Si vous voulez profiter de la HDR, c'est l'écran le moins cher de ce guide qui l'affiche correctement.

* **[MSI G274QPX](https://www.youtube.com/watch?v=-9gB-b8PkQw)** - [330€](https://www.idealo.fr/prix/203311220/msi-g274qpx.html) - Pour les joueurs compétitifs qui veulent absolument un 240Hz, mais sans passer sur de l'OLED. Un bon all-rounder qui gagne un peu par défaut, les autres IPS 240Hz étant trop chers par rapport aux OLED.


## OLED, le meilleur ami du gamer (jeu haute performance, 27" QHD OLED 240Hz+)

On s'approche enfin de mon rêve de voir de l'OLED quasi partout, même si les prix restent très élevés. J'ai retardé l'écriture de ce guide pour être sûr que l'OLED convenait à une utilisation gaming quotidienne, je pense qu'on y est enfin, mais malheureusement pour bosser dessus avec des applications statiques, le burn-in est encore un problème.

L'OLED permet deux bonds technologiques par rapport aux dalles LCD : un contraste exceptionnel (le noir correspond à un pixel éteint) et des temps de réponse imperceptibles (en moyenne 0.3 ms vs 3-10 ms sur des bons LCD). Vu le peu d'amélioration de perception des hautes fréquences au delà de 200Hz, c'est un bénéfice beaucoup plus important que l'augmentation de fréquence, et je n'hésiterai pas à conseiller aux joueurs compétitifs un écran OLED 240Hz plutôt qu'un IPS 360/480Hz.

Outre le prix, le deux critères de choix importants :

* **QD-OLED vs WOLED** : la technologie de la dalle OLED. Samsung utilise des dalles QD-OLED, offrant un color gamut plus élevé, des couleurs plus vives et une luminosité générale plus élevée. LG préfère les dalles WOLED, avec une luminosité plus consistante. Les deux ont des performances de jeu quasi identiques. [Comparaison WOLED/QD-OLED](https://www.youtube.com/watch?v=y4pHSaFo664)

* **Glossy vs mat** : Les fabricants recouvrent leur dalle d'un revêtement glossy ou mat, qui peuvent respectivement être des dealbreakers selon votre usage. [Comparaison des deux revêtements](https://tftcentral.co.uk/articles/glossy-vs-matte-oled-panel-coatings-compared-including-the-asus-rog-strix-xg27aqdmg). Typiquement Samsung préfère le glossy et LG le mat, mais les deux fabricants ont déjà fait l'inverse.

En pratique, **les moniteurs partageant la même dalle ont souvent des performances identiques**, j'ai donc choisi de donner la version la moins chère de chaque dalle pertinente, mais vous pouvez rarement vous tromper en prenant ceux partageant cette dalle si jamais vous les trouvez moins chers en promo. Notez que le revêtement peut être différent d'un modèle à l'autre, même sur la même dalle.


* **[Asus ROG Strix XG27AQDMG](https://www.rtings.com/monitor/reviews/asus/rog-strix-oled-xg27aqdmg)** (WOLED QHD) - [600€](https://www.idealo.fr/prix/204427524/asus-rog-strix-oled-xg27aqdmg.html) - Un des rares WOLED avec revêtement glossy, auquel Asus ajoute une couche Micro Lens Array+ pour améliorer la luminosité. Ca en fait un moniteur idéal pour jouer dans une pièce bien éclairée, avec un tarif très sympa. Alternatives avec la même dalle : [LG 27GS95QE](https://www.rtings.com/monitor/reviews/lg/27gs95qe-b) (mat).


* **[Dell AW2725DF](https://www.rtings.com/monitor/reviews/dell/alienware-aw2725df)** (QD-OLED QHD) - [700€](https://www.dell.com/fr-fr/shop/%C3%A9cran-de-gaming-qd-oled-360-hz-alienware-27-aw2725df/apd/210-blhh/moniteurs-et-accessoires-de-moniteur) - L'option compétitive : parfait pour jouer à 360Hz avec des temps de réponse imperceptibles. Alternatives avec la même dalle : [Gigabyte AORUS FO27Q3](https://www.rtings.com/monitor/reviews/asus/rog-strix-oled-xg27aqdmg), [MSI MPG 271QRX QD-OLED](https://www.rtings.com/monitor/reviews/msi/mpg-271qrx-qd-oled).

* **[Asus ROG Swift PG27AQDP](https://www.rtings.com/monitor/reviews/asus/rog-swift-oled-pg27aqdp)** (WOLED QHD) - [1100€](https://www.ldlc.com/en/product/PB00631796.html) - L'option ultra-compétitive : si d'une manière ou d'une autre vous arrivez à pousser votre carte graphique à 1440p @ 480Hz sans que votre jeu ne ressemble à Cyberpunk sur PS4, on ne fait pas plus rapide que cet écran. Par contre il est aux prix des modèles 4K.


## La 4K sinon rien (jeu haute performance, 32" 4K OLED 240Hz+)

S'il reste difficile de faire tourner les jeux en 4K à des fréquences jouables en 2024, si vous avez une utilisation mixte multimédia/jeu, jouez à des jeux peu lourds ou prévoyez de claquer le PEL sur une future RTX 5080, les écrans 32" 4K OLED ne sont pas beaucoup plus chers que les 27" QHD

* **[Samsung Odyssey G8 G80SD](https://www.rtings.com/monitor/reviews/samsung/odyssey-oled-g8-g80sd-s32dg80)** (QD-OLED 4K) - [1100€](https://www.samsung.com/fr/monitors/gaming/odyssey-oled-g8-g80sd-32-inch-240hz-oled-uhd-ls32dg800suxen/) - Les dalles Samsung de 3ème génération forment le gros de la gamme OLED 4K, mais si la plupart des fabricants l'utilisent avec un revêtement glossy, Samsung a fait le choix d'un revêtement mat. Alternatives avec la même dalle : [MSI MPG 321URX](https://www.rtings.com/monitor/reviews/msi/mpg-321urx-qd-oled), [Gigabyte FO32U2P](https://www.rtings.com/monitor/reviews/gigabyte/aorus-fo32u2p), [Asus ROG Swift PG32UCD**M**](https://www.rtings.com/monitor/reviews/asus/rog-swift-oled-pg32ucdm).


* **[Dell AW3225QF](https://www.rtings.com/monitor/reviews/dell/alienware-aw3225qf)** (QD-OLED 4K) - [1120€](https://www.dell.com/fr-fr/shop/%C3%A9cran-gaming-alienware-32-4k-qd-oled-aw3225qf/apd/210-bllv/moniteurs-et-accessoires-de-moniteur?tfcid=45113341) - Cet écran offre une alternative intéressante pour ceux qui préfèrent leur 32" avec un peu de courbes : même dalle que le Samsung G8 G80SD, mais sur une version glossy incurvée à 1700R. 


* **[LG 32GS95UE](https://www.rtings.com/monitor/reviews/lg/32gs95ue-b)** (WOLED 4K) - [1300€](https://www.idealo.fr/prix/204401826/lg-oled-ultragear-32gs95ue.html) - Ok, 200€ plus cher que le Samsung, qu'est-ce que j'y gagne ? Le Dual-Mode, permettant de basculer l'affichage 4K @ 240Hz en 1080p @ 480Hz pour vos jeux compétitifs. Pour ceux qui veulent le beurre et l'argent du beurre. Alternatives avec la même dalle : [Asus ROG Swift PG32UCD**P**](https://www.rtings.com/monitor/reviews/asus/rog-swift-oled-pg32ucdp).



## Création professionnelle (4K 60Hz+, couleurs fidèles)

Si l'OLED domine le haut de gamme pour les gamers, 3 choses l'empêchent d'être pertinent pour les créatifs :

* le risque de burn-in encore présent si vous utilisez beaucoup d'applications statiques. 

* le layout non standard des sous-pixels, très gênant sur le texte notamment.

* Pour les professionnels de la création papier, le contraste important s'éloigne trop de celui du medium papier.

Beaucoup d'écrans IPS 1440p gaming conviennent à la création pro, voici donc quelques options 27" 4K pour les plus exigeants :


* **[Dell S2722QC](https://www.rtings.com/monitor/reviews/dell/s2722qc)** - [290€](https://www.dell.com/fr-fr/shop/%C3%A9cran-dell-27-4k-uhd-usb-c-s2722qc/apd/210-bbrq/moniteurs-et-accessoires-de-moniteur) - un des rares moniteurs de l'ancien guide qui fait de la résistance, surtout grâce à son prix qui en fait un des écrans 4K les moins chers du marché.


* **[Asus ProArt PA279CRV](https://www.rtings.com/monitor/reviews/asus/proart-display-pa279crv)** - [500€](https://www.idealo.fr/prix/202606224/asus-proart-pa279crv.html) - S'il ne faudra pas trop compter sur le HDR faute de local-dimming convaincant, il a une excellente calibration d'usine, et le DisplayPort Alt-mode + power delivery ravira les utilisateurs de PC portables.


* **[Acer Nitro XV275K P3biipruzx](https://www.rtings.com/monitor/reviews/acer/nitro-xv275k-p3biipruzx)** - [700€](https://www.idealo.fr/prix/203256537/acer-nitro-xv275kp3.html) - Cet écran est là pour satisfaire une petite niche : les monteurs vidéos et autres créatifs qui veulent un peu tout sans passer à l'OLED : un taux de rafraichissement élevé et du local-dimming, mais sur un écran IPS 27" 4K. Acer fait payer le miniLED assez cher, si vous êtes ok pour un 27" QHD, privilégiez l'AOC Q27G3XMN recommandé plus haut.


## Ultrawide (34-38" 21:9)

Parfait pour la productivité, mais pour du gaming la compatibilité 21:9 dépendra beaucoup des jeux auquels vous jouez : ça variera de la simple déformation d'image ou recadrage "propre" sur les jeux récents (pour ne pas donner un avantage en multi), à des barres noires sur les côtés, et dans le pire des cas des jeux plus anciens (et non moddables) qui ne tournent tout simplement pas en 21:9 et seront déformés.

L'ultrawide restant un marché de niche pour utilisateurs exigeants et fortunés, les constructeurs ont totalement abandonné l'IPS et le VA pour se concentrer sur les dalles OLED.


* **[Gigabyte G34WQCA](https://www.techspinreview.com/2022-gigabyte-g34wqc-a/)** - [380€](https://www.idealo.fr/prix/201731572/gigabyte-g34wqc-a.html) - Ce refresh du [G34WQC](https://www.rtings.com/monitor/reviews/gigabyte/g34wqc) fait une bonne entrée de gamme ultrawide. Temps de réponse corrects pour un VA d'ancienne génération, mais si vous pouvez rajouter un peu je conseille plus le Dell ci-dessous. 


* **[Dell S3422DWG](https://www.rtings.com/monitor/reviews/dell/s3422dwg)** - [450€](https://www.dell.com/fr-fr/shop/%C3%A9cran-de-gaming-incurv%C3%A9-dell-34-s3422dwg/apd/210-azze/moniteurs-et-accessoires-de-moniteur) - Comme pour le Gigabyte, il ne brillera pas par ses temps de réponses, c'est surtout son contraste qui le rends compétitif, jusqu'à ce que les OLED ultrawides soient abordables.


* **[Dell AW3423DWF](https://www.rtings.com/monitor/reviews/dell/alienware-aw3423dwf)** (QD-OLED) - [900€](https://www.dell.com/fr-fr/shop/%C3%A9cran-de-gaming-incurv%C3%A9-qd-oled-alienware-34-aw3423dwf/apd/210-bfrq/moniteurs-et-accessoires-de-moniteur) - Refresh du tout premier moniteur gaming OLED, que j'avais par prudence surtout conseillé aux early-adopters à l'époque. Force est de constater que ce QD-OLED de Dell reste convaincant en 2024, avec un prix compétitif, un taux de 165Hz qui conviendra au plus grand nombre, et l'argument de la garantie burn-in de 3 ans. Alternatives avec la même dalle : [Samsung Odyssey G8 S34BG85](https://www.rtings.com/monitor/reviews/samsung/odyssey-oled-g8-g85sb-s34bg85), [MSI MEG 342C](https://www.rtings.com/monitor/reviews/msi/meg-342c-qd-oled), MPG 341CQPX.


* **[LG 34GS95QE-B](https://www.rtings.com/monitor/reviews/lg/34gs95qe-b)** (WOLED) - [1000€](https://www.idealo.fr/prix/204253646/lg-ultragear-34gs95qe-b.html) - L'excellente mais chère dalle WOLED de LG, en version ultrawide matte. Courbe de 800R très agressive qui ne conviendra pas à tout le monde. Alternatives avec la même dalle : [ASUS ROG Swift PG34WCDM](https://www.rtings.com/monitor/reviews/asus/rog-swift-oled-pg34wcdm), Acer Predator X34 X.


* **[Samsung Odyssey G9 G95SC](https://www.rtings.com/monitor/reviews/samsung/odyssey-oled-g9-g95sc-s49cg95)** (QD-OLED) - [1150€](https://www.samsung.com/fr/monitors/gaming/odyssey-oled-g9-g95sc-49-inch-240hz-curved-dual-qhd-ls49cg954suxen/) Vous trouvez que 34", ce n'est pas assez large ? Samsung vous propose cet écran 31:9 "ultra-ultrawide" de 49". Si certains jeux ne sont pas réellement jouables à cette définition à cause du crop ou des déformations latérales de la caméra, ça peut être très immersif dans certaines situations (racing, pilotage...), et utile pour bosser si vous aviez prévu deux écrans 27" de toute façon.



*****


**Sources et outils :**

[UFO Test (ghosting/rafraichissement)](https://www.testufo.com/ghosting)

[Viewsonic - Monitor resolution and aspect ratio](https://www.viewsonic.com/library/tech/monitor-resolution-aspect-ratio/)

[Eizo - Pixel density 4K](https://www.eizo.com/library/basics/pixel_density_4k/)

[Hardware Unboxed - Explication et comparaison des 3 principales technos](https://www.youtube.com/watch?v=luLS-I9lubg)

*****

**Autres guides d'achat :**

[Rtings - best monitors by category](https://www.rtings.com/monitor/reviews/best)

[Monitors Unboxed - Best 1440p gaming monitors of 2024](https://www.youtube.com/watch?v=akooca7My-o), n'hésitez pas à checker leurs reviews individuelles.

[Monitors Unboxed - Best 4K Gaming monitors of 2024](https://www.youtube.com/watch?v=zbMfDFq4loo)

[Monitor Hunter's fact sheet](https://docs.google.com/document/d/1illeNLsUfZ4KuJ9cIWKwTDUEXUVpplhUYHAiom-FaDo)

[Monitors Enthousiasts IPS/VA recommandations](https://docs.google.com/spreadsheets/d/1wBV0U3a1XuP1yFLvs_Ald3FE1y45bVxtS2zBXixsGLs/)