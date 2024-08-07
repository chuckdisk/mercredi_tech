# Guide écrans 2023

Ce guide remplace l'ancien guide moniteurs de 2019 en deux parties, car j'ai constaté que beaucoup lisaient le guide d'achat mais pas forcément les explications techniques de la partie 1. J'ai laissé les anciens posts : (partie [1](https://www.reddit.com/r/france/comments/ebdgh8/guide_moniteurs_12_r%C3%A9solutiond%C3%A9finition_type_de/) et [2](https://www.reddit.com/r/france/comments/ebtwr7/guide_moniteurs_22_guide_dachat_selon_budget_et/))

[Les autres guides d'achat](https://www.reddit.com/r/france/search?q=guide+author%3Achuckmauricefacts+flair%3Ascience&restrict_sr=on&sort=relevance&t=all)

[Les guides sur Github](https://github.com/chuckdisk/mercredi_tech)

*dernière maj: décembre 2023*

## Taille et définition

Déjà on va commencer par une petite erreur de français : 

* La [définition](https://fr.wikipedia.org/wiki/D%C3%A9finition_d%27%C3%A9cran), c'est le nombre de pixels affichés à l'écran (appelée couremment à tort résolution). Ex : *1920x1080 pixels*.

* La [résolution](https://fr.wikipedia.org/wiki/R%C3%A9solution_spatiale_des_images_matricielles), c'est la définition divisée par la taille de l'écran. Ex : *1920x1080 à 24" (92 pixels par inch ou ppi)*

Parlons d'abord de définitions. Tout ça c'est [standardisé évidemment](https://en.wikipedia.org/wiki/Graphics_display_resolution), voici les plus communes :

| 16:9                 | Ultrawide (21:9)      |
| -------------------- | --------------------- |
| 1920 x 1080 (FHD)    | 2560 x 1080 (UW-FHD)  |
| 2560 x 1440 (QHD)    | 3440 x 1440 (UW-QHD)  |
| 3840 x 2160 (4K UHD) | 3840 x 1600 (UW-QHD+) |

Évidemment pour les joueurs, **plus la définition est élevée, plus la carte graphique doit travailler.** L'incrément n'est pas linéaire grâce à différentes optimisations, mais faire tourner un jeu en QHD ou en 4K sera nettement plus lourd qu'en FHD (mais sans solliciter plus le CPU).

> **Trigger warning sur la définition 2K :** ça ne veut rien dire, arrêtez de dire 2K pour dire QHD, c'est [une définition pour le mastering cinéma](https://videocide.com/glossary/dci-2k/) proche du FHD. Même les vendeurs s'y mettent maintenant, donc je me sens obligé de dire que ça signifie souvent **QHD**, mais c'est une erreur.

## Résolution (=définition/taille)

Ce qui est important donc, c'est **la résolution**, le rapport entre la **taille de l'écran** et sa **définition** (en ppi, pixel par inch). De mon expérience, on ne distingue plus les pixels à partir d'un taux d'environ 100 ppi. A l'inverse, un taux de ppi trop élevé va rendre les éléments illisibles.

Ça varie selon les gens et des dalles, ça dépends de facteurs différent comme votre acuité visuelle, le type de dalle, la distance oeil-écran, l'habitude ou tout simplement l'utilisation que vous faites de votre écran (un graphiste sera plus exigeant qu'un gamer sur ce point).

En partant de ce postulat, on peut définir **les résolutions idéales pour un écran confortable :**

* 24" : 1920x1080 -> 91 ppi

* 27" : 2560x1440 -> 108 ppi

* 32" : 3840x2160 -> 138 ppi

Un site pratique pour calculer la densité de pixels : **[sven.de/dpi](https://www.sven.de/dpi/)**

L'augmentation de la définition permet également de profiter de plus de superficie sur son bureau pour afficher des fenêtes, ce qu'on appelle le *real estate*. Comparaison du nombre de fenêtres qu'on peut afficher sur ces 3 définitions : [FHD](https://imgur.com/3lxAmGi), [QHD](https://imgur.com/cBNLWFJ), [4K](https://imgur.com/1kH7ONC). 

Pour la productivité, c'est génial car vous pourrez afficher plus d'éléments sur l'écran. Pour le gaming, l'image affichée aura toujours la même taille, c'est surtout une augmentation des détails (même si certains jeux permettent d'ajuster la taille de l'interface).

**Le scaling/HiDPI/Retina**

Les définitions trop élevées, si on laisse l'affichage en 100% natif, rendent le texte et les éléments [trop petits](https://www.memesmonkey.com/images/memesmonkey/08/084f157e54694987ecb05a49eee33e86.jpeg) pour les lire correctement. Heureusement, on peut changer la mise à l'échelle (scaling) : x1.25, 1.50, 1.75, 2.00... L'idéal étant un facteur entier de x2 ou plus (HiDPI/Retina), car [doubler les pixels se fait proprement](https://medium.com/elementaryos/what-is-hidpi-and-why-does-it-matter-b024eabea20d) (4 pixels = 1 pixel HiDPI), alors qu'avec un facteur fractionnel va utiliser des algorithmes d'anti-aliasing pour tricher. Attention : toutes les applications ne supportent pas le HiDPI.


## Technologies de dalle

Je vous fais grâce de la science, retenez que c'est des **grilles de cellules à cristaux liquides** (LCD) à [matrices actives](https://en.wikipedia.org/wiki/Liquid-crystal_display#Active-matrix_technologies) avec différentes façon d'activer chaque cellule (envoyer une tension) et de les rétro-éclairer.

* **TN :** (Twisted Nematic) : très populaire du temps où on n'arrivait pas à faire des dalles haute fréquence avec les autres technos, c'est maintenant une technologie obsolète qui a de gros défauts (faibles angles de visions, couleurs exécrables). A oublier pour tout nouvel achat.

* **VA :** (Vertical Alignment) : des dalles qui brillent par leur contraste (enfin, je me comprends), mais pèchent sur les temps de réponse, induisant souvent du ghosting à haute fréquence. Les angles de vision et la fidélité colorimétrique sont également limités. Utile surtout si vous jouez à des jeux immersifs dans des environnements sombre (horreur, thriller...).

* **IPS :** (In-Plane Switching) : les meilleures sur la fidélité colorimétrique, les temps de réponse et les angles de vision. Elles ont cependant un contraste inférieur aux dalles VA, et sont plus sujettes aux fuites de lumière (backlight bleed). Pour jouer et travailler, c'est le meilleur des deux mondes.

* **OLED :** (Organic Light-Emitting Diode) : contrairement aux autres dalles à cristaux liquides, une dalle OLED est une grille de diodes microscopiques qui émettent leur propre lumière. La technologie OLED est émergente et donc onéreuse mais promet de nombreux avantages : noirs parfaits, basse conso, pas de fuite de lumière... On espère juste que les problèmes de [burn-in](https://www.youtube.com/watch?v=hWrFEU_605g) seront réglés.

**Tableau récapitulatif :**

| **Dalle** | **Taux de contraste** | **Rendu des couleurs** | **Rapidité** | **Angles de vision** | **Prix**  |
|-----------|------------|-------------|----------------|------------|------------|
| TN        | Moyen      | Moyen       | Excellent      | Mauvais    | Abordable  |
| VA        | Bon        | Bon         | Moyen          | Moyen      | Abordable  |
| IPS       | Moyen      | Bon         | Excellent      | Excellent  | Elevé      |
| OLED      | Excellent  | Excellent   | Excellent      | Excellent  | Prohibitif |

[Explication des différentes technologies avec vues au microscope](https://tftcentral.co.uk/articles/panel_technologies).

> Note sur les dalles incurvées : en ultrawide (21:9 et plus), la courbe est là pour mieux épouser la vision en arc de l'oeil humain. **En 16:9 par contre, la courbe ne procure aucun avantage, elle existe pour réduire un défaut des dalles VA : les couleurs deviennent ternes sur les côtés.**


## Performance

Les paramètres à prendre en compte pour du gaming :

* **Fréquence de rafraichissement (en Hertz) :** le nombre de fois que l'image peut être actualisée en une seconde. 60-75Hz pour de la bureautique, 120-170Hz pour du gaming, éventuellement 240Hz+ pour le gaming compétitif. 

* **Temps de réponse (en ms) :** le temps qu'il faut pour qu'[un pixel change complètement de couleur](https://www.rtings.com/monitor/tests/motion/motion-blur-and-response-time). C'est le principal critère différenciateur pour les écrans gaming. Le marketing utilise parfois le chiffre un peu menteur de 1ms, alors que le vrai temps de réponse moyen est plus proche des 6 ms sur une très bonne dalle.

* **Input lag (en ms) :** le délai entre l'action que vous effectuez et son affichage à l'écran. [Plus d'infos ici](https://www.rtings.com/monitor/tests/inputs/input-lag).

* **AdaptiveSync :** permet d'adapter la fréquence de rafraichissement aux fps que peut générer la carte graphique. Auparavant il fallait choisir entre Freesync (AMD, Intel) et G-Sync (Nvidia), maintenant **l'écrasante majorité des écrans récents sont Freesync + compatibles G-Sync.**


Pour des performances optimales en jeu, on recherche évidemment l'écran avec la plus haute fréquence de rafraichissement et le plus bas input lag & temps de réponse possible. 

En pratique, la différence entre 60 et 144Hz est assez impressionnante (surtout si on revient à 60Hz après, c'est saccadé !). La différence entre 144Hz et 240Hz, en comparaison, n'est pas énorme, et même certains joueurs compétitifs se trompent en blind-test. Si votre budget est serré, privilégiez donc le 144Hz et un plus grand écran plutôt qu'un écran 24" 240Hz.

[Comparaison de fréquence filmée en slow motion](https://www.youtube.com/watch?v=Q1cmhZs1P54).




## Couleurs

Ici, le RGB ce n'est pas des bandes de LED sur l'écran, mais la fidélité colorimétrique, critère essentiel pour les professionnels de l'image et de la vidéo. 

* **Espaces colorimétriques :** on mesure en "pourcentage de couverture" la capacité d'un écran à afficher correctement une plage de couleur. Il en existe plusieurs : **sRGB** ou **Adobe RGB** pour la photo, **REC 709** ou **DCI-P3** pour la vidéo. La grande majorité des écrans IPS récents ont une excellente couverture du sRGB, mais pas forcément des autres espaces. [Explications](https://www.rtings.com/monitor/tests/picture-quality/color-gamut).
  
* **Calibrer sa dalle :** même les dalles d'excellente qualité nécessitent un calibrage pour être les plus fidèles possibles. Pour ceci, utilisez [une sonde de calibration](https://www.creativebloq.com/features/best-monitor-calibrator) et son logiciel associé. Aux dires des professionnels, il faut répéter l'opération tout les 2-3 mois. Le coût élevé de la sonde la réserve aux professionnels exigeants et aux entreprises.

* **La HDR (High Dynamic Range) :** on utilise une plage de couleurs plus importante (codée sur 8 ou 10 bits, au lieu de 6 bits), ce qui donne une image aux couleurs plus vives. Malheureusement la plupart des moniteurs actuels utilisent de la "fausse" HDR (HDR 400 : l'écran est compatible avec un signal HDR, mais en pratique la dalle ne permet pas de l'afficher proprement). Seuls quelques chers écrans 4K avec **local dimming** permettent d'afficher de la HDR digne de ce nom, dommage.

## Défauts potentiels des écrans

Malgré l'évolution des technologies de dalles, il reste des défauts présents sur les dalles LCD haute fréquence qu'on peine encore à corriger. Certaines dépendent un peu d'une "lotterie de la dalle", donc je n'ai pas de conseils pour les éviter, mais sachez que ça existe, et que si vous tombez dessus vous pouvez utiliser votre droit de rétractation (mais pas forcément la garantie) :

* **[Backlight bleed :](https://www.displayninja.com/what-is-backlight-bleed/)** fuites de lumières sur les bordures de l'écran, souvent signe d'un mauvais contrôle qualité. Exemple entre un [bon](https://imgur.com/a/WDHHL1r) et un [très mauvais](https://imgur.com/a/n8Merv3) élève (deux écrans que j'ai possédé).

* **[IPS glow :](https://www.limscave.com/reduce-ips-glow)** couleurs diffuses aux coins de l'écran, qui varient avec l'angle de vision (contrairement au backlight bleed). Beaucoup moins gênant que ce dernier, mais également signe d'un mauvais contrôle qualité.

* **[Ghosting/black smearing :](https://www.youtube.com/watch?v=D6g85vqdK2A)** une trace sombre laissée par les objets en mouvement, causée par un temps de transition trop élevé entre des couleurs sombres (temps de réponse). Typiquement présent sur les dalles VA.

* **[Overshoot :](https://blurbusters.com/faq/lcd-overdrive-artifacts/)** une couronne claire laissée par des objets en mouvement, causée par une exagération des corrections anti-ghosting (overdrive).


*******

# Quel écran acheter ?

Ces catégories reflètent mon état d'esprit sur le marché des moniteurs, les omissions de certaines gammes sont volontaires, mais les guides en fin de post vous permettront de combler les trous si besoin. Les prix mentionnés sont **les prix recommandés** par rapport aux écrans concurrents, si l'écran est plus cher que le prix que je donne il n'est plus compétitif. Si il est moins cher, c'est tout bonus.

## C'est pas la taille qui compte (jeu/bureautique, 24" FHD 144Hz+)

A petit budget, privilégiez la performance à la taille. Le procédé est maitrisé :  la plupart des écrans IPS à 200€ se valent et la gamme a peu évolué ces dernières années. J'ai fais une sélection basée sur les fonctionnalités et l'ergonomie, mais il est possible de trouver des moniteurs aux performances similaires dans les 140-160€ en faisant des compromis là dessus.

* **AOC 24G2SP(U)** - [190€](https://www.idealo.fr/prix/201920459/aoc-24g2spu.html) - [review](https://www.youtube.com/watch?v=cUoxwTWo7Fg) - Une évolution du très bon 24G2 avec une dalle 165Hz et un meilleur contraste. Très bon choix à moins de 200€. N'hésitez pas à rechercher les variantes (SP/AE...) qui auront une connectique et un pied plus limités, mais un prix encore moins élevé. Méfiez vous des variantes VA par contre.

* **Gigabyte G24F-2** - [200€](https://www.idealo.fr/prix/201385408/gigabyte-g24f.html) - [review](https://www.youtube.com/watch?v=HlsGvOV-Y74) - Gigabyte pousse la fréquence jusqu'à 170Hz sans faire de compromis, ce qui en fait un des meilleurs choix à ce tarif, et une bonne alternative aux écrans "jeu compétitif" de 240Hz+.

* **Viewsonic XG2431** - [350€](https://www.idealo.fr/prix/202445879/viewsonic-xg2431.html) - [review](https://www.rtings.com/monitor/reviews/viewsonic/xg2431) - remplace le Dell AW2521HFA comme option "24" pour jeu compétitif". Son gros avantage : le backlight strobing customisable pour les joueurs les plus exigeants.

*Intéressant en promo dans les 200-220€ : [BenQ EX2510](https://www.youtube.com/watch?v=vByC1RfUJSo), Asus VP249QGR, MSI G242*


## Le sweet spot (jeu/création, 27"-32" QHD 144Hz+)

Le sweet spot pour les gamers et créatifs exigeants. Au départ limités à 144Hz, ces écrans tendent de plus en plus vers les 170-180Hz au fur et à mesure que les technologies de fabrication de dalles évoluent.

* **Dell G2724D** - [320€](https://www.dell.com/fr-fr/shop/%C3%A9cran-de-gaming-dell-27-g2724d/apd/210-bhtk/moniteurs-et-accessoires-de-moniteur) - [review](https://www.rtings.com/monitor/reviews/dell/g2724d) - remplace le S2721DGF, on passe d'une dalle LG nano-IPS à une dalle AU Optronics, mais on gagne en contraste sans perdre en performance. La connectique est plus chiche : on perds le hub USB. **Meilleur rapport qualité/prix de sa catégorie**.

* **LG 27GP850P-B** - [320€](https://www.ldlc.com/fiche/PB00547396.html) - [review](https://www.rtings.com/monitor/reviews/lg/27gp850-b) - Le flagship de LG, rafraichi pour 2023. Quelques petits avantages qui le placent au dessus du marché : le Black Frame Insertion, l'overclock à 180Hz et le support du DCI-P3 à 98%. A vous de voir si ça vaut la différence de prix. Existe en 32" (32GP850).

* **MSI MAG274QPF-QD** - [350€](https://www.ldlc.com/fiche/PB00559818.html) - [review](https://www.youtube.com/watch?v=oZljHL_izEw) - Avec une dalle d'AU Optronics qui rivalise en performance avec les nano-IPS de LG en proposant un contraste supérieur. Refresh du QRF-QD qu'on ne trouve plus à des prix intéressants en France.

* **Gigabyte M27QX** - [500€](https://www.ldlc.com/fiche/PB00479459.html) - [review](https://www.rtings.com/monitor/reviews/gigabyte/m27q-x) - L'upgrade "jeu compétitif" 240Hz de cette catégorie, avec un switch KVM en bonus. Les temps de réponse sont excellents et il faudrait passer sur de l'OLED poura voir mieux. 


*Intéressants en promo dans les 300€ ou moins : [Acer Nitro XV272U](https://www.rtings.com/monitor/reviews/acer/nitro-xv272u-kvbmiiprzx), [MSI Optix G273QF](https://www.rtings.com/monitor/reviews/msi/optix-g273qf) + pied*


## Création professionnelle (4K 60Hz, couleurs fidèles)

Je retire les écrans 1440p de cette catégorie, beaucoup d'écrans gaming 1440p sont assez bons pour un usage créatif et sont à des prix compétitifs. Les programmeurs acharnés peuvent être intéressés par des écrans 4K pour la netteté du texte, même si ça sera difficile à justifier à son patron.

* **LG 27UP850N-W** - [375€](https://www.idealo.fr/prix/202041305/lg-27up850n-w.html) - [review](https://monitornerds.com/lg-27up850-w-review/) - Surtout intéressant pour son prix plancher, mais si vous êtes exigeants sur les couleurs je rajouterais un peu pour prendre le Dell.

* **Dell S2722QC** - [430€](https://www.dell.com/fr-fr/shop/%C3%A9cran-dell-27-4k-uhd-usb-c-s2722qc/apd/210-bbrq/moniteurs-et-accessoires-de-moniteur) - [review](https://www.rtings.com/monitor/reviews/dell/s2722qc) - Dell propose un moniteur 4K haute fidélité, qui rends basiquement obsolète toute sa gamme Ultrasharp (significativement plus chère) tant il est bon. Si vous trouvez l'ancienne version ([S2721QS](https://www.rtings.com/monitor/reviews/dell/s2721qs)) pour 100€ moins cher, elle est également très intéressante.

* **Asus ProArt PA279CV** [500€](https://www.idealo.fr/prix/200936888/asus-proart-pa279cv.html) - [review](https://www.youtube.com/watch?v=GhZklThcxkA&ab_channel=Techtesters) - Excellente calibration d'usine mesurée sur la plupart des modèles. Mais son coût supplémentaire le rends difficile à justifier face au S2722QC. 


## Ultrawide mon amour (34-38" 21:9)

Parfait pour la productivité, mais pour du gaming la compatibilité 21:9 dépendra beaucoup des jeux auquels vous jouez : ça variera de la simple déformation d'image ou recadrage "propre" sur les jeux récents (pour ne pas donner un avantage en multi), à des barres noires sur les côtés, et dans le pire des cas des jeux plus anciens qui ne tournent tout simplement pas en 21:9 et seront déformés.

L'ultrawide reste un marché de niche, le prix reste donc très élevé surtout depuis l'arrivée de modèles 38" et la quasi disparition des 60Hz. En plus il y a peu de modèles dispo, donc j'ai 3 grosses recommandations à 3 budgets différents, et seulement quelques alternatives :

* **Dell S3422DWG** - [500€](https://www.dell.com/fr-fr/shop/%C3%A9cran-de-gaming-incurv%C3%A9-dell-34-s3422dwg/apd/210-azze/moniteurs-et-accessoires-de-moniteur) - [review](https://www.rtings.com/monitor/reviews/dell/s3422dwg) - Malgré une ergonomie restrictive qui ne gênera pas trop pour un ultrawide, c'est l'écran VA le plus performant de cette sélection (meilleurs temps de réponse). Si vous avez un budget serré mais voulez absolument de l'ultrawide, le VA est un compromis acceptable.

*Alternatives VA 34" intéressantes en promo : [AOC CU34G2X](https://www.rtings.com/monitor/reviews/aoc/cu34g2x), [Gigabyte G34WQC](https://www.rtings.com/monitor/reviews/gigabyte/g34wqc)*

* **LG 34GN850-B** - [800€](https://fr.pcpartpicker.com/product/7Qn8TW/lg-34gn850-b-340-3440x1440-160-hz-monitor-34gn850-b) - [review](https://www.rtings.com/monitor/reviews/lg/34gn850-b) - Probablement celui que je prendrais si je devais choisir : on reste sur un tarif raisonnable, les temps de réponse sont excellents et il n'a vraiment de défauts. D'autres font mieux, mais pas à son prix.

*Alternatives IPS 34" intéressantes en promo : [LG 34GP950G-B](https://www.rtings.com/monitor/reviews/lg/34gp950g-b)*

* **LG 38GN950-B** - [1200€](https://fr.pcpartpicker.com/product/2srYcf/lg-ultragear-38gn950-b-380-3840x1600-160-hz-monitor-38gn950-b) - [review](https://www.rtings.com/monitor/reviews/lg/38gn950-b) - Le meilleur 38" de la sélection pour les gamers exigeants, mais avec le prix qui va avec. LG dispose d'un écran similaire orienté "bureau", le [38WN95C-W](https://www.rtings.com/monitor/reviews/lg/38wn95c-w) qui ajoute une connectique moderne et un pied un peu plus sobre, mais passe de 160 à 144Hz.

*Alternatives IPS 38" intéressantes en promo : [LG 38GL950G-B](https://www.rtings.com/monitor/reviews/lg/38gl950g-b), [Dell AW3821DW](https://www.rtings.com/monitor/reviews/dell/alienware-aw3821dw)*

## Moniteurs spéciaux

Dernières technologies, écrans excellents mais avec un défaut problématique, alternatives insolites... c'est ici.

* **Samsung Odyssey G9** - [1300€](https://fr.pcpartpicker.com/product/WQvqqs/samsung-odyssey-g9-490-5120x1440-240-hz-monitor-lc49g95tssnxza) - [review](https://www.rtings.com/monitor/reviews/samsung/odyssey-g9) - Le G7, mais en "super-ultrawide" (49"), soit deux écrans 27" QHD côte à côte. C'est inutilisable sur certains jeux qui seront trop déformés pour être appréciables, mais pour la productivité, si vous trouvez que les ultrawides standard c'est pas assez et que vous aimez tourner la tête, pourquoi pas. Samsung a aussi sorti le Neo G9 en Mini LED, mais la fiabilité laisse à désirer pour l'instant, et le prix de 1900€ est un ticket bien trop lourd à payer pour jouer les early-adopters.

* **Dell AW3423DWF** - [1100€](https://www.dell.com/fr-fr/shop/%C3%A9cran-de-gaming-incurv%C3%A9-qd-oled-alienware-34-aw3423dwf/apd/210-bfrq/moniteurs-et-accessoires-de-moniteur) - [review](https://www.rtings.com/monitor/reviews/dell/alienware-aw3423dwf) - Le premier moniteur gaming OLED est un ultrawide ! Les couleurs sont excellentes et le contraste parfait, enfin de la HDR utilisable sur PC, mais il vient avec sa liste de défauts : potentiel burn-in (garantie burn-in 3 ans, mais c'est pas beaucoup), un revêtement glossy très réflectif qui tends vers le gris même à l'arrêt, mais surtout le [edge fringing](https://www.reddit.com/r/ultrawidemasterrace/comments/tgo81f/the_achilles_heel_of_the_aw3423dw_the_aw3423dw/) causé par le layout triangulaire des pixels QD-OLED qui, si tout le monde ne le vois pas, peut être très gênant pour certains. C'est un produit pour les early-adopters que ces défauts ne gêneront pas, pour les autres on espère que les prochaines dalles QD-OLED de Samsung corrigeront ces défauts. [Review de HardwareUnboxed](https://www.youtube.com/watch?v=YleSuwK8vR4) qui rentre dans les détails. Attention : n'achetez pas le AW3423DW (sans le F), c'est littéralement le même en moins bien et plus cher à cause du module G-Sync)

* **LG 42C2** - [1400€](https://www.iacono.fr/fr/26751-lg-oled42c26lb.html) - [review](https://www.rtings.com/monitor/reviews/lg/42-c2-oled) - Les qualités des dalles W-OLED de LG sont connues depuis longtemps par les amateurs de bonnes TV (dont moi avec ma fidèle 65CX), mais les TV étaient jusque là trop grandes pour être vraiment utilisables en lieu et place d'un moniteur. La nouvelle C2 en 42" rends enfin ça possible, sous réserve d'avoir un bureau profond et de coller la TV au mur. A vous les contrastes parfaits et les temps de réponse minimes. Reste le burn-in qui est toujours un problème, donc prenez vos précautions : cachez les barres d'outils et icônes, mettez des fonds d'écrans aléatoires et ne laissez jamais trop longtemps la même fenêtre affichée. 

*****


**Sources et outils :**

[UFO Test (ghosting/rafraichissement)](https://www.testufo.com/ghosting)

[Viewsonic - Monitor resolution and aspect ratio](https://www.viewsonic.com/library/tech/monitor-resolution-aspect-ratio/)

[Eizo - Pixel density 4K](https://www.eizo.com/library/basics/pixel_density_4k/)

[Hardware Unboxed - Explication et comparaison des 3 principales technos](https://www.youtube.com/watch?v=luLS-I9lubg)

[Why your HDR monitor is probably not HDR at all](https://www.tftcentral.co.uk/blog/why-your-hdr-monitor-is-probably-not-hdr-at-all-and-why-displayhdr-400-needs-to-go/)

*****

**Autres guides d'achat :**

[Rtings - Best gaming monitors under $300](https://www.rtings.com/monitor/reviews/best/gaming-monitors-under-300)

[Rtings - Best 1440p monitors](https://www.rtings.com/monitor/reviews/best/1440p-gaming-monitors)

[Rtings - Best Monitors For Photo Editing And Video Editing](https://www.rtings.com/monitor/reviews/best/by-usage/photo-editing-graphic-design)

[Hardware Unboxed - Best gaming monitors of 2023](https://www.youtube.com/watch?v=Z8rJxJo3cfI)

[Monitor Hunter's fact sheet](https://docs.google.com/document/d/1illeNLsUfZ4KuJ9cIWKwTDUEXUVpplhUYHAiom-FaDo)

[Monitors Enthousiasts recommandations](https://docs.google.com/spreadsheets/d/1wBV0U3a1XuP1yFLvs_Ald3FE1y45bVxtS2zBXixsGLs/)