# Metrology
Vérification d'appareils électroniques


## 

I Méthode d'étalonnage et de vérification en laboratoire

Les étalonnages et vérifications sont réalisés dans un laboratoire climatisé :

\- température : 23°C ± 2 °C

\- hygrométrie : 50 % d'humidité relative ± 20 % HR

L'étalonnage des instruments est effectué par comparaison à des étalons raccordés aux chaînes d’étalonnage COFRAC ou un organisme signataire des accords de reconnaissance mutuelle européen.

Il est important de vérifier l'état physique des instruments à étalonner.

Les étalons sont placés au minimum 24 heures à l'avance dans le laboratoire de métrologie électrique, ils sont alimentés en 240 V alternatif (50 Hz) et mis sous tension au minimum 1 heure avant de procéder aux mesures.

Les instruments à étalonner ou à vérifier sont placés 12 heures minimum dans le laboratoire avant de commencer les mesures.

Dans le cadre "hors COFRAC" du laboratoire d'électricité de Velizy, suite à un étalonnage, un jugement peut être porté sur la conformité de l'appareil, suivant les critères d'acceptation définis par le donneur d'ordre.

## 

**Points de mesure**

• Le technicien doit préalablement à une intervention s’assurer de la date de validité des appareils utilisés.

• Les points de mesure définis dans les programmes techniques le sont pour certains appareils pour plusieurs niveaux de prestation :

\- soit une prestation avec programme de vérification partielle (fonctions principales),

\- soit une prestation avec programme d’étalonnage ou vérification dit standard (fonctions principales, annexes et complémentaires). Ces points peuvent être modifiés par le donneur d’ordre ou être limités par le domaine technique du laboratoire.

\- Un programme d'étalonnage ou de vérification à la carte peut être appliqué, les points de mesure de ce type de programme devront être définis d'un commun accord lors de la revue d'offre.

\- Un programme d'étalonnage ou de vérification suivant une procédure constructeur peut être réalisé si nous la possédons ou si le client nous la fournit.

La plupart des procédures sont effectuées en simulation ou par comparaison.

## 

**Amplificateur de charge**

L'amplificateur de charge amplifie le signal électrique d'un capteur piézoélectrique.

Un capteur piézoélectrique sert à mesurer la grandeur d'une vibration (Onde mécanique).

Lors de la procédure de vérification, une charge piézoélectrique est simulée par une capacité associée à une source de tension alternative. Cette charge simulé est appliquée sur l'entrée de l'instrument à étalonner. Une vibration à fréquence et charge constante est donc simulé.

La formule de la charge simulée est : Q = C x U.

• Utiliser une charge capacitive étalon (C)

• Générer à l'aide d'un calibrateur étalon une tension alternative de forme sinusoïdale et de fréquence inférieure à la bande passante de l'instrument à étalonner.

• Si l'instrument possède une sortie signal comme un amplificateur, connecter un mesureur étalon adapté au signal.

### 

**Incertitudes des moyens de référence :**

• Incertitudes données par le laboratoire d’étalonnage accrédité, sur l’étalonnage du calibrateur (fonction U~) de la charge capacitive et du mesureur étalon (sortie signal avec un voltmètre).

• Incertitude due à la résolution de l’appareil à étalonner.

![](https://1099626939-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-MhdSzY_7K9n5aQAlJq8%2F-Mhew0NtWekoXIzNBxw4%2F-Mhf-qlhqVHM63dV6rK6%2Fimage.png?alt=media&token=8640ce72-c649-48f1-a506-4b9efdb589cc)

![](https://1099626939-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-MhdSzY_7K9n5aQAlJq8%2F-Mhew0NtWekoXIzNBxw4%2F-MhfLKg-oLhwdcsCrSgZ%2Fimage.png?alt=media&token=d68c897f-1593-4499-a52b-a2312a80c9c2)

Spécification du constructeur: écart < 2% à 1000 Hz

Une liaison GPIB connecte le calibreur Fluke et le voltmètre à l'ordinateur. Un programme de saisie Excel est crée afin de faire l'acquisition des données qui serviront à rédiger le constat de vérification ou le certificat d'étalonnage.

## 

**Ohmmètre**

La technique de base utilisée pour mesurer une résistance repose sur l'application de la loi d'Ohm V=RI.

On applique une tension ou un courant à la résistance à contrôler et on mesure alors le courant ou la tension qui en résulte à l'aide d'un voltmètre ou d'un ampèremètre.

La meilleure configuration pour les mesures basse résistance est celle à 4 fils. Une telle configuration utilise quatre fils : deux fils pour conduire le courant à travers une résistance et deux fils pour mesurer la chute de tension à travers cette résistance. Les mesures à 4 fils traditionnelles nécessitent que le circuit soit hors tension afin que la chute de tension mesurée soit uniquement due au courant fourni. Ainsi, habituellement, le courant vers un circuit doit être éteint avant qu’une mesure soit prise. La figure du dessous illustre une configuration à 4 fils. Les fils connecté au voltmètre mesurent la chute de tension. Les fils sortant du générateur de courant connectent le courant de test.

Ce montage permet de limiter les effets de la résistance des fils de liaison, de contact et de la résistance interne du voltmètre qui peuvent affecter la mesure lorsque l'on a des résistances de faible valeur à mesurer.

Pour les moyennes et grandes valeurs de résistances, le montage deux fils peut suffire suivant les spécifications du client.

• Réglage du zéro mécanique de l’appareil.

• Pour chaque point de mesure, si on utilise un calibrateur : ajuster la grandeur délivrée par le calibrateur afin de positionner précisément l’aiguille de l’appareil sur la graduation la plus proche.

• L’erreur de lecture est due à l’appréciation de la position de l’aiguille.

• La stabilité correspond à l’amplitude de la variation de la position de l’aiguille.

• Si l’appareil le permet, réglage du zéro électrique avec la touche ou le potentiomètre prévu à cet effet en appliquant une valeur nulle grâce au calibrateur.

• La résolution correspond à la valeur du dernier digit.

• La stabilité correspond à l’amplitude de variation de l’affichage de l’appareil.

**Génération de valeurs fixes à l'aide du calibrateur 5700A Fluke, multiples de 1 et 1,9.**

• La mesure de résistance étalon s'effectue en mode "4 fils" pour les valeurs inférieures ou égales à 190 kΩ sur le calibrateur étalon. Les bornes (HI, LO) correspondent aux bornes tension. Les bornes (I+, I-) correspondent aux bornes courant. "EX SNS" est activé.

• Pour les valeurs supérieures à 190 kΩ , les mesures s'effectuent en mode "2 fils".

• La "Ω GUARD" de l’ohmmètre à étalonner est reliée à la "GUARD" du calibrateur , reliée à la terre.

**Génération de valeurs intermédiaires à l’aide boîtes à décades, de 0.01 Ω à 10 MΩ**

• Selon l'instrument à étalonner, la mesure s'effectue en mode "4 fils" ou "2 fils". En mode "4 fils" les bornes tension sont connectées les premières sur les boîtes à décades.

• Les bornes terre des boîtes sont reliées à la garde du système (si possible) sinon à la terre.

• Si possible, faire le zéro du mesureur à étalonner en mettant toutes les décades de l’étalon à zéro.

• Avant d'utiliser les boîtes à décades, tourner toutes les décades plusieurs fois afin d'améliorer les contacts des sélecteurs (dégrippage). Attendre la stabilité thermique après cette

**Génération de valeurs variables à l’aide du calibrateur Fluke 5500A ou 5520A, de 1 Ω à 10 MΩ**

• La mesure des résistances étalon doit obligatoirement s'effectuer en mode "4 fils" pour les valeurs inférieures à 10 kΩ sur le calibrateur étalon. Les bornes (HI, LO) correspondent aux bornes tension. Les bornes (I+, I-) correspondent aux bornes courant.

• Pour les valeurs supérieures ou égales à 1 MΩ, les mesures s'effectuent en mode dit "3 fils". La "GUARD" de l’ohmmètre à étalonner est reliée à la "GUARD" du calibrateur.

**Génération de valeurs fixes à l’aide de résistances à valeurs ponctuelles, de 0.001 Ω à 10 MΩ**

• Relier l’appareil à étalonner à la résistance étalon en mode 4 fils(1 milliohm à 10 kilohms) ou en mode 2 fils(à partir de 100 kilohms).

• Faire le zéro des cordons. Relier les cordons à leur extrémité, faire le « NULL » interne si existant, sinon, relever la valeur sur l’appareil et la déduire des mesures suivantes.

• Régler l’étalon à la valeur désirée (résistance fixe ou boîte à décades).

• Corriger cette valeur à l’aide de son certificat d’étalonnage.

• Lancer la mesure sur l’appareil.

• Relever la valeur indiquée par l’appareil à étalonner.

• Répéter ces opérations à chaque point de mesure.

**Incertitudes des moyens de référence**

• Incertitude due à la répétabilité du calibrateur.

La répétabilité est estimée à partir de la valeur maximale des écarts types calculés aux différents points. Cette valeur est combinée avec les incertitudes types estimées pour les autres

Incertitude donnée par la laboratoire sur l’étalonnage du calibrateur ou la résistance de référence.

• Incertitude due à la dérive du calibrateur ou la résistance de référence entre 2 étalonnages. Sur l'ensemble des dérives entre deux étalonnages successifs, la dérive maximale δD estretenue.

• Incertitude due au coefficient de température du calibrateur ou de la résistance d'incertitudes référence.

**Incertitudes de l’appareil étalonné ou vérifié**

• Incertitude due à la résolution de l’appareil (appareil numérique).

• Incertitude due à l’erreur de lecture du zéro et des points de mesures (appareil analogique).

![](https://1099626939-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-MhdSzY_7K9n5aQAlJq8%2F-Mhew0NtWekoXIzNBxw4%2F-MhfMk_h8ETme7hRIVnD%2Fimage.png?alt=media&token=25bae922-b484-4676-90c8-5eb675808e75)

![](https://1099626939-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-MhdSzY_7K9n5aQAlJq8%2F-Mhew0NtWekoXIzNBxw4%2F-MhfMlxJy8TfVfwm6DS1%2Fimage.png?alt=media&token=ded4f8aa-ad8b-4cf0-a0dc-41676c9941b1)

## 

**II Exploitation des résultats**

**Cas de l'utilisation d'un certificat d'étalonnage**

L'erreur de justesse E décrite dans le certificat d'étalonnage peut être corrigée (C=-E), l'incertitude sur cette correction est l'incertitude d'étalonnage U,

**Cas de l'utilisation du constat de vérification**

L'erreur de justesse E n'est pas connue donc pas corrigée mais l'on sait que l'instrument est conforme aux spécifications attendues (EMT : écart maximal toléré), à savoir :

|E| + u ≤ EMT (conformité sans risque).

Le constat de vérification fournit une information sur la conformité de l'instrument à une spécification formalisée sous la forme d'Erreurs Maximales Tolérées (EMT). Ces EMT s'apparentent à une correction non effectuée qui entraîne une erreur sur le résultat de mesure. En conséquence, il convient dans ce cas d'ajouter linéairement l'incertitude aux Erreurs Maximales Tolérées :

**En règle général, à partir des relevés bruts, on peut :**

\- tenir compte des résultats d'étalonnage de la chaîne de référence et corriger les valeurs de référence,

\- calculer la valeur moyenne (et l'écart-type associés à la une série de mesures),

\- calculer l'étendue de mesure (phénomène d'hystérésis de l'instrument),

\- calculer l'écart entre les valeurs de l'instrument et de l'étalon,

\- calculer la sensibilité de l'instrument (Avec courbe de régression),

\- calculer l'incertitude de mesure.

## 

**III Réalisation de procédure Metcal et d'injection des calculs d'incertitudes**

METCAL est un logiciel qui permet d’automatiser et de gérer le travail des laboratoires de métrologie, en mettant à disposition tous les outils nécessaires pour :

-   Automatiser les procédures, y compris pour les étalonnage et pour la vérification, sur tous types d’outils et d’équipements de test et de mesure, incluant générateurs de signaux, de fonctions, micro-ondes et radiofréquences.
    

En collaboration avec la responsable du laboratoire d'électricité, Nadège Pottier, nous avons mis au point un fichier Excel permettant d'injecter les incertitudes pour chaque calibre et pour chaque fonction d'un calibrateur Fluke 5500 dans les matrices des procédures Metcal.

Le fichier Excel "incertitude et dérive" représenté ci-dessus est crée à partir un certificat d'étalonnage.

Ainsi les coefficient d'incertitudes proviennent du certificat. L'incertitude élargie est la (tension lue 2001 X coefficient variable) + coefficient absolue.

La dérive est la différence des écarts de deux années successives puis la dérive max retenue et l'incertitude max retenue sont arrondis. La dérive max et les résidus max suivent une distribution uniforme rectangulaire : (u= U/)

L'incertitude max est donnée par le certificat d'étalonnage. L'incertitude type (u(xi) est alors égale à la valeur de l'incertitude d'étalonnage U divisée par k. Dans le cas de certificats d'étalonnages COFRAC :

Puis la somme quadratique des incertitudes types est effectuée pour obtenir l'incertitude type composée. Rédiger une procédure Metcal tient en partie du langage de programmation (cf. annexe 3) et une fois avoir injecté le fichier .COR (cf. annexe) crée à l'aide du fichier Excel, dans Metcal, voici un exemple de ce que donne le résultat final sans les pages de présentations.

## 

**IV Annexe : Procédure METCAL**

\=============================================================================

INSTRUMENT: Fluke 21-2: (1 year) CAL VER /5520

INSTRUMENT: Fluke 23-2: (1 year) CAL VER /5520

INSTRUMENT: Fluke 70-2: (1 year) CAL VER /5520

INSTRUMENT: Fluke 73-2: (1 year) CAL VER /5520

INSTRUMENT: Fluke 75-2: (1 year) CAL VER /5520

INSTRUMENT: Fluke 77-2: (1 year) CAL VER /5520

AUTHOR: Fluke Corporation

REVISION: $Revision: 1.4 $

ADJUSTMENT THRESHOLD: 70%

CONFIGURATION: Fluke 5520A

\=============================================================================

\# Fluke 77/75/73/70/23/21 Series II Service Manual

\# (PN 896204 July 1991, Rev. 1, 9/92, Errata No. 1 1/93)

\# 5520/CAL 5.1 or MET/CAL 5.1 or later

\# TUR calculation is based on specification interval of the accuracy file.

\# The default 5520A accuracy file contains 90 day specs.

\# Fluke makes no warranty, expressed or implied, as to the fitness

\# or suitability of this procedure in the customer's application.

\# The 90 day specifications of the 5520A are used in TUR computations.

STEP FSC RANGE NOMINAL TOLERANCE MOD1 MOD2 3 4 CON

1.003 HEAD EQUIPMENT SETUP

1.004 DISP HIGH VOLTAGE is used or exposed during the performance

1.004 DISP of this calibration. DEATH ON CONTACT may result if

1.004 DISP personnel fail to observe safety precautions.

1.005 DISP Allow the UUT to stablize to room temperature

1.005 DISP 23degC +/-5degC (73degF +/-9degF).

1.005 DISP Check the fuses and battery, and replace them if

1.006 HEAD {DISPLAY TEST}

2.001 HEAD {RESISTANCE TESTS}

2.002 DISP Select the Ohms Function.

2.003 DISP Connect the 5520 to the UUT as follows:

2.003 DISP \[32\] 5520A NORMAL HI to UUT V/Ohm/Diode

2.003 DISP \[32\] 5520A NORMAL LO to UUT COM

2.003 DISP \[32\] 5520A AUX HI to UUT V/Ohm/Diode

2.003 DISP \[32\] 5520A AUX LO to UUT COM

2.004 HEAD RESISTANCE TESTS: {320 Ohm Range}

2.005 5520 320 0.0Z +0.2U CW

3.001 5520 320 270.0Z 1.6U CW

4.001 HEAD RESISTANCE TESTS: {3200 Ohm Range}

4.002 5520 3200 2700Z 15U CW

5.001 HEAD RESISTANCE TESTS: {32 kOhm Range}

5.002 5520 32 27.00kZ 0.15U CW

6.001 HEAD RESISTANCE TESTS: {320 kOhm Range}

6.002 DISP Connect the 5520 to the UUT as follows:

6.002 DISP \[32\] 5520A NORMAL HI to UUT V/Ohm/Diode

6.002 DISP \[32\] 5520A NORMAL LO to UUT COM

6.003 5520 320 270.0kZ 1.5U 2W

7.001 HEAD RESISTANCE TESTS: {3.2 MOhm Range}

7.002 5520 3.2 2.700MZ 0.015U 2W

8.001 HEAD RESISTANCE TESTS: {32 MOhm Range}

8.002 5520 32 27.00MZ 0.55U 2W

9.003 DISP Select the Diode/Audible-tone Function.

9.005 EVAL -s "Beeper On" : Is the beeper on?

10.002 EVAL -s "Beeper Off" : Is the beeper off?

11.002 HEAD {DC MILLIVOLT TEST}

11.003 DISP Select the 300mV DC Function.

11.004 HEAD DC MILLIVOLT TEST: {320mV Range}

11.005 JMPT 12.003 Fluke 21-2: (1 year) CAL VER /5520

11.006 JMPT 13.003 Fluke 23-2: (1 year) CAL VER /5520

11.007 JMPT 12.003 Fluke 73-2: (1 year) CAL VER /5520

11.008 JMPT 12.003 Fluke 75-2: (1 year) CAL VER /5520

11.009 JMPT 13.003 Fluke 77-2: (1 year) CAL VER /5520

11.011 5520 350 300.0mV 1.6U 2W

12.003 5520 350 300.0mV 1.3U 2W

13.003 5520 350 300.0mV 1.0U 2W

14.001 HEAD {DC VOLTAGE TESTS}

14.002 DISP Select the V DC Function.

14.003 JMPT 18.003 Fluke 21-2: (1 year) CAL VER /5520

14.004 JMPT 22.003 Fluke 23-2: (1 year) CAL VER /5520

14.005 JMPT 18.003 Fluke 73-2: (1 year) CAL VER /5520

14.006 JMPT 18.003 Fluke 75-2: (1 year) CAL VER /5520

14.007 JMPT 22.003 Fluke 77-2: (1 year) CAL VER /5520

14.009 HEAD DC VOLTAGE TESTS: {3.2V Range}

14.010 5520 3.2 2.700V 0.015U 2W

15.001 HEAD DC VOLTAGE TESTS: {32V Range}

15.002 5520 32 27.00V 0.15U 2W

16.001 HEAD DC VOLTAGE TESTS: {320V Range}

16.002 5520 320 270.0V 1.5U 2W

17.001 HEAD DC VOLTAGE TESTS: {1000V Range}

17.002 5520 1000 1000V 7U 2W

18.003 HEAD DC VOLTAGE TESTS: {3.2V Range}

18.004 5520 3.2 2.700V 0.012U 2W

19.001 HEAD DC VOLTAGE TESTS: {32V Range}

19.002 5520 32 27.00V 0.12U 2W

20.001 HEAD DC VOLTAGE TESTS: {320V Range}

20.002 5520 320 270.0V 1.2U 2W

21.001 HEAD DC VOLTAGE TESTS: {1000V Range}

21.002 5520 1000 1000V 5U 2W

22.003 HEAD DC VOLTAGE TESTS: {3.2V Range}

22.004 5520 3.2 2.700V 0.009U 2W

23.001 HEAD DC VOLTAGE TESTS: {32V Range}

23.002 5520 32 27.00V 0.09U 2W

24.001 HEAD DC VOLTAGE TESTS: {320V Range}

24.002 5520 320 270.0V 0.9U 2W

25.001 HEAD DC VOLTAGE TESTS: {1000V Range}

25.002 5520 1000 1000V 5U 2W

26.001 HEAD {AC VOLTAGE TESTS}

26.002 DISP Select the V AC Function.

26.003 HEAD AC VOLTAGE TEST: {3.2V Range}

26.004 5520 3.2 2.700V 0.056U 100H SI 2W

27.001 5520 3.2 2.700V 0.056U 500H SI 2W

28.001 HEAD AC VOLTAGE TEST: {750V Range}

28.002 5520 750 750V 17U 100H SI 2W

29.001 5520 750 750V 17U 1000H SI 2W

30.001 JMPT 33.001 Fluke 70-2: (1 year) CAL VER /5520

30.002 JMPT 32.002 Fluke 73-2: (1 year) CAL VER /5520

30.004 HEAD {LOW CURRENT TESTS}

30.005 DISP Select the A DC Function.

30.006 DISP Connect the 5520 to the UUT as follows:

30.006 DISP \[32\] 5520A AUX HI to UUT 300mA

30.006 DISP \[32\] 5520A AUX LO to UUT COM

30.007 HEAD LOW CURRENT TESTS: {32mA Range}

30.008 5520 32 27.00mA 0.43U 2W

31.001 HEAD LOW CURRENT TESTS: {320mA Range}

31.002 5520 320 200.0mA 3.2U 2W

\# D'après le certificat d'étalonnage n°: 08/150175/01A

\# Date d'étalonnage: du 05/07/09 au 10/07/09

\# Approuvé par: N. POTTIER

\# Fichier acc du fluke 5700A

\# Range Locked (DC Voltage only)

\# Nominal Mod 1 Tol. Floor Resolution

\# ------------------------ -------------- ------- -------- ----------

\-219.99999e-3 219.99999e-3 NA NA 2.2e6 1.9e-3 10e-9

\-2.1999999 0.3999999 NA NA 2.2e-6 3.7 e-6 100e-9

4.0000000 0.9999999 NA NA 2.2e-6 2.0 e-6 100e-9

1.0000000 2.1999999 NA NA 1.5e-6 7.9 e-6 100e-9

\-10.999999 0.699999 NA NA 1.5e-6 2.3e-5 1e-6

7.000000 10.999999 NA NA 1.5e-5 9.5e-5 1e-6

\-21.999999 21.999999 NA NA 2.26e-7 2.03e-4 1e-6

\-219.99999 219.99999 NA NA 1.68e-5 1.37e-3 10e-6

\-1100.0000 1100.0000 NA NA 5.20e-5 1.28e-2 100e-6

\# Autorange (AC & DC Voltage)

\# Basic 5700A accuracy DC Volts with internal divider

\# for low values < 220 mV (more accurate).

\# Nominal Mod 1 Tol. Floor Resolution

\# ------------------------ -------------- ------- -------- ----------

\-219.99999e-3 219.99999e-3 NA NA 2.44e-5 2.35e-6 10e-9

\-2.1999999 2.1999999 NA NA 4.74e-6 1.07e-5 100e-9

\-10.999999 10.999999 NA NA -3.69e-5 1.14e-4 1e-6

\-21.999999 21.999999 NA NA 2.26e-7 2.03e-4 1e-6

\-219.99999 219.99999 NA NA 1.68e-5 1.37e-3 10e-6

\-1100.0000 1100.0000 NA NA 5.20e-5 1.28e-2 100e-6

\# AC Volts less than 22mV with external AC divider

\# Fluke Corporation part number 7405A-4207

\# (not as accurate as divider override, but less noise)

\# Nominal Mod 1 Tol. Floor Resolution

\# ------------------------ -------------- ------- -------- ----------

\# 0.220000e-3 2.199999e-3 10 10e3 0.08 1e-6 1e-9

\# 0.220000e-3 2.199999e-3 10e3 50e3 0.12 1e-6 1e-9

\# 0.220000e-3 2.199999e-3 50e3 1.1999e6 NA NA 1e-9

\# 2.20000e-3 21.99999e-3 10 10e3 0.08 1e-6 10e-9

\# 2.20000e-3 21.99999e-3 10e3 50e3 0.12 1e-6 10e-9

\# 2.20000e-3 21.99999e-3 50e3 1.1999e6 NA NA 10e-9

\# AC Volts, no external divider applicable

5.0000e-3 219.9999e-3 10 19.99 1200e-4 32e-6 100e-9

5.0000e-3 219.9999e-3 20 39.99 480e-4 20e-6 100e-9

5.0000e-3 219.9999e-3 40 10e3 8.63e-2 1.5e-5 100e-9

5.0000e-3 219.9999e-3 10e3 50e3 720e-4 20e-6 100e-9

5.0000e-3 219.9999e-3 50e3 100e3 1800e-4 60e-6 100e-9

5.0000e-3 219.9999e-3 100e3 300e3 2200e-4 60e-6 100e-9

5.0000e-3 219.9999e-3 300e3 500e3 3600e-4 80e-6 100e-9

5.0000e-3 219.9999e-3 500e3 1e6 7200e-4 200e-6 100e-9

5.0000e-3 219.9999e-3 1e6 1.1999e6 NA NA 100e-9

0.220000 2.199999 10 19.99 1200e-4 200e-6 1e-6

0.220000 2.199999 20 39.99 360e-4 60e-6 1e-6

0.220000 2.199999 40 10e3 1.2e-2 5e-5 1e-6

0.220000 2.199999 10e3 50e3 280e-4 40e-6 1e-6

0.220000 2.199999 50e3 100e3 560e-4 160e-6 1e-6

0.220000 2.199999 100e3 300e3 960e-4 300e-6 1e-6

0.220000 2.199999 300e3 500e3 2400e-4 800e-6 1e-6

0.220000 2.199999 500e3 1e6 4800e-4 2e-3 1e-6

0.220000 2.199999 1e6 1.1999e6 NA NA 1e-6

2.20000 21.99999 10 19.99 1200e-4 2e-3 10e-6

2.20000 21.99999 20 39.99 360e-4 600e-6 10e-6

2.20000 21.99999 40 10e3 8.55e-3 1.1e-4 10e-6

2.20000 21.99999 10e3 50e3 280e-4 400e-6 10e-6

2.20000 21.99999 50e3 100e3 560e-4 800e-6 10e-6

2.20000 21.99999 100e3 300e3 1200e-4 3.4e-3 10e-6

2.20000 21.99999 300e3 500e3 2800e-4 10e-3 10e-6

2.20000 21.99999 500e3 1e6 6000e-4 18e-3 10e-6

2.20000 21.99999 1e6 1.1999e6 NA NA 10e-6

22.0000 219.9999 10 19.99 1200e-4 10e-3 100e-6

22.0000 219.9999 20 39.99 360e-4 3e-3 100e-6

22.0000 219.9999 40 10e3 5.30e-2 1.79e-2 100e-6

22.0000 219.9999 10e3 50e3 500e-4 4e-3 100e-6

22.0000 219.9999 50e3 100e3 1200e-4 10e-3 100e-6

22.0000 219.9999 100e3 300e3 3200e-4 110e-3 100e-6

22.0000 219.9999 300e3 500e3 10800e-4 110e-3 100e-6

22.0000 219.9999 500e3 1e6 2.6 440e-3 100e-6

22.0000 219.9999 1e6 1.1999e6 NA NA 100e-6

220.000 250.000 15 49.99 920e-4 40e-3 1e-3

220.000 1100.000 50 1e3 6.2e-2 2.1e-2 1e-3

\# Basic 5700A accuracy DC Volts with divider override

\# Nominal Mod 1 Tol. Floor Resolution

\# ------------------------ -------------- ------- -------- ----------

\# -0.2199999 0.2199999 NA NA 6e-4 1.2e-6 100e-9

\# AC Volts with external divider override up to 22mV (is more accurate)

\# 0.220000e-3 2.199999e-3 10 19.99 600e-4 5e-6 1e-9

\# 0.220000e-3 2.199999e-3 20 39.99 240e-4 5e-6 1e-9

\# 0.220000e-3 2.199999e-3 40 20e3 120e-4 5e-6 1e-9

\# 0.220000e-3 2.199999e-3 20e3 50e3 410e-4 5e-6 1e-9

\# 0.220000e-3 2.199999e-3 50e3 100e3 950e-4 8e-6 1e-9

\# 0.220000e-3 2.199999e-3 100e3 300e3 1300e-4 15e-6 1e-9

\# 0.220000e-3 2.199999e-3 300e3 500e3 1800e-4 30e-6 1e-9

\# 0.220000e-3 2.199999e-3 500e3 1e6 4800e-4 40e-6 1e-9

\# 0.220000e-3 2.199999e-3 1e6 1.1999e6 NA NA 1e-9

\# 2.20000e-3 21.99999e-3 10 19.99 600e-4 6e-6 10e-9

\# 2.20000e-3 21.99999e-3 20 39.99 240e-4 6e-6 10e-9

\# 2.20000e-3 21.99999e-3 40 20e3 120e-4 6e-6 10e-9

\# 2.20000e-3 21.99999e-3 20e3 50e3 410e-4 6e-6 10e-9

\# 2.20000e-3 21.99999e-3 50e3 100e3 950e-4 8e-6 10e-9

\# 2.20000e-3 21.99999e-3 100e3 300e3 1300e-4 15e-6 10e-9

\# 2.20000e-3 21.99999e-3 300e3 500e3 1800e-4 30e-6 10e-9

\# 2.20000e-3 21.99999e-3 500e3 1e6 4800e-4 40e-6 10e-9

\# 2.20000e-3 21.99999e-3 1e6 1.1999e6 NA NA 10e-9

\# Voltage from 5725A Boost Voltage Amplifier

\# Nominal Mod 1 Tol. Floor Resolution

\# ------------------------ -------------- ------- -------- ----------

\# 220.000 1100.000 40 1e3 90e-4 4e-3 1e-3

\# 220.000 1100.000 1e3 20e3 165e-4 6e-3 1e-3

\# 220.000 1100.000 20e3 30e3 600e-4 11e-3 1e-3

\# 220.000 750.000 30e3 50e3 600e-4 11e-3 1e-3

\# 220.000 750.000 50e3 100e3 2300e-4 45e-3 1e-3

\# Voltage from 5205A Boost Voltage Amplifier

\# Nominal Mod 1 Tol. Floor Resolution

\# ------------------------ -------------- ------- -------- ----------

\# -1100.00 1100.00 NA NA 0.05 0.055 0.01

\# 220.00 1100.00 10 39.99 0.15 0.055 0.01

\# 220.00 1100.00 40 20e3 0.04 0.044 0.01

\# 220.00 1100.00 20e3 50e3 0.08 0.066 0.01

\# 220.00 1100.00 50e3 100e3 0.10 0.11 0.01

\# Voltage from 5215A Boost Voltage Amplifier

\# Nominal Mod 1 Tol. Floor Resolution

\# ------------------------ -------------- ------- -------- ----------

\# 220.00 1100.00 10 39.99 0.15 0.055 0.01

\# 220.00 1100.00 40 20e3 0.04 0.044 0.01

\# 220.00 1100.00 20e3 50e3 0.08 0.066 0.01

\# 220.00 1100.00 50e3 100e3 0.10 0.11 0.01

\# Includes accuracy + flatness specifications

\# Nominal Mod 1 Tolerance Floor Resolution

\# ------------------------ --------------- --------- ------- ----------

\# 0.30000e-3 1.09999e-3 10 29.99 1.1 2e-6 10e-9

\# 0.30000e-3 1.09999e-3 30 120e3 0.9 2e-6 10e-9

\# 0.30000e-3 1.09999e-3 120e3 2e6 1.0 5e-6 10e-9

\# 0.30000e-3 1.09999e-3 2e6 10e6 1.2 5e-6 10e-9

\# 0.30000e-3 1.09999e-3 10e6 20e6 1.4 5e-6 10e-9

\# 0.30000e-3 1.09999e-3 20e6 30e6 2.3 17e-6 10e-9

\# 1.10000e-3 3.29999e-3 10 29.99 1.0 3e-6 10e-9

\# 1.10000e-3 3.29999e-3 30 120e3 0.8 3e-6 10e-9

\# 1.10000e-3 3.29999e-3 120e3 2e6 0.8 6e-6 10e-9

\# 1.10000e-3 3.29999e-3 2e6 10e6 1.0 6e-6 10e-9

\# 1.10000e-3 3.29999e-3 10e6 20e6 1.2 6e-6 10e-9

\# 1.10000e-3 3.29999e-3 20e6 30e6 2.2 6e-6 10e-9

\# 3.3000e-3 10.9999e-3 10 29.99 1.0 8e-6 100e-9

\# 3.3000e-3 10.9999e-3 30 120e3 0.8 8e-6 100e-9

\# 3.3000e-3 10.9999e-3 120e3 2e6 0.8 11e-6 100e-9

\# 3.3000e-3 10.9999e-3 2e6 10e6 0.9 11e-6 100e-9

\# 3.3000e-3 10.9999e-3 10e6 20e6 1.1 11e-6 100e-9

\# 3.3000e-3 10.9999e-3 20e6 30e6 1.7 11e-6 100e-9

\# 11.0000e-3 32.9999e-3 10 29.99 0.9 16e-6 100e-9

\# 11.0000e-3 32.9999e-3 30 120e3 0.7 16e-6 100e-9

\# 11.0000e-3 32.9999e-3 120e3 2e6 0.7 19e-6 100e-9

\# 11.0000e-3 32.9999e-3 2e6 10e6 0.8 19e-6 100e-9

\# 11.0000e-3 32.9999e-3 10e6 20e6 1.0 19e-6 100e-9

\# 11.0000e-3 32.9999e-3 20e6 30e6 1.6 19e-6 100e-9

\# 33.000e-3 109.999e-3 10 29.99 0.9 40e-6 1e-6

\# 33.000e-3 109.999e-3 30 120e3 0.7 40e-6 1e-6

\# 33.000e-3 109.999e-3 120e3 2e6 0.7 43e-6 1e-6

\# 33.000e-3 109.999e-3 2e6 10e6 0.8 43e-6 1e-6

\# 33.000e-3 109.999e-3 10e6 20e6 1.0 43e-6 1e-6

\# 33.000e-3 109.999e-3 20e6 30e6 1.6 43e-6 1e-6

\# 110.000e-3 329.999e-3 10 29.99 0.8 100e-6 1e-6

\# 110.000e-3 329.999e-3 30 120e3 0.6 100e-6 1e-6

\# 110.000e-3 329.999e-3 120e3 2e6 0.6 103e-6 1e-6

\# 110.000e-3 329.999e-3 2e6 10e6 0.7 103e-6 1e-6

\# 110.000e-3 329.999e-3 10e6 20e6 0.9 103e-6 1e-6

\# 110.000e-3 329.999e-3 20e6 30e6 1.5 103e-6 1e-6

\# 0.33000 1.09999 10 29.99 0.8 400e-6 10e-6

\# 0.33000 1.09999 30 120e3 0.6 400e-6 10e-6

\# 0.33000 1.09999 120e3 2e6 0.6 403e-6 10e-6

\# 0.33000 1.09999 2e6 10e6 0.7 403e-6 10e-6

\# 0.33000 1.09999 10e6 20e6 0.9 403e-6 10e-6

\# 0.33000 1.09999 20e6 30e6 1.5 403e-6 10e-6

\# 1.10000 3.50000 10 29.99 0.7 500e-6 10e-6

\# 1.10000 3.50000 30 500e3 0.5 500e-6 10e-6

\# 1.10000 3.50000 500e3 2e6 0.5 503e-6 10e-6

\# 1.10000 3.50000 2e6 10e6 0.6 503e-6 10e-6

\# 1.10000 3.50000 10e6 20e6 0.8 503e-6 10e-6

\# 1.10000 3.50000 20e6 30e6 1.4 503e-6 10e-6

\# Range Locked (DC Current only)

\# Nominal Mod 1 Tol. Floor Resolution

\# ----------------------- -------------- ------- -------- ----------

\-219.9999e-6 219.9999e-6 NA NA 1.8e-2 1.4e-8 0.1e-9

\-2.199999e-3 2.199999e-3 NA NA 1.8e-2 1.4e-8 1e-9

\-21.99999e-3 21.99999e-3 NA NA 3.79e-3 1.5e-7 10e-9

\-219.9999e-3 219.9999e-3 NA NA 1.22e-2 8.2e-7 100e-9

\-2.2 2.2 NA NA 8.33e-3 9.5e-5 1e-6

\# Autorange (AC & DC Current)

\# Basic 5700A DC Current Accuracy

\# Nominal Mod 1 Tol. Floor Resolution

\# ----------------------- -------------- ------- -------- ----------

\-219.9999e-6 219.9999e-6 NA NA 1.8e-2 1.4e-8 0.1e-9

\-2.199999e-3 2.199999e-3 NA NA 1.8e-2 1.4e-8 1e-9

\-21.99999e-3 21.99999e-3 NA NA 3.79e-3 1.5e-7 10e-9

\-219.9999e-3 219.9999e-3 NA NA 1.22e-2 8.2e-7 100e-9

\-2.2 2.2 NA NA 8.33e-3 9.5e-5 1e-6

\# Basic 5700A AC Current Accuracy \*/

\# Nominal Mod 1 Tol. Floor Resolution

\# ----------------------- -------------- ------- -------- ----------

9.000e-6 219.999e-6 10 19.99 1600e-4 60e-9 1e-9

9.000e-6 219.999e-6 20 39.99 840e-4 50e-9 1e-9

9.000e-6 219.999e-6 40 1e3 320e-4 40e-9 1e-9

9.000e-6 219.999e-6 1e3 5e3 1400e-4 100e-9 1e-9

9.000e-6 219.999e-6 5e3 10e3 3600e-4 200e-9 1e-9

0.22000e-3 2.19999e-3 10 19.99 1600e-4 100e-9 10e-9

0.22000e-3 2.19999e-3 20 39.99 840e-4 80e-9 10e-9

0.22000e-3 2.19999e-3 40 1e3 1.82e-1 3.4e-5 10e-9

0.22000e-3 2.19999e-3 1e3 5e3 1400e-4 1000e-9 10e-9

0.22000e-3 2.19999e-3 5e3 10e3 3600e-4 2e-6 10e-9

2.2000e-3 21.9999e-3 10 19.99 1600e-4 100e-9 100e-9

2.2000e-3 21.9999e-3 20 39.99 840e-4 800e-9 100e-9

2.2000e-3 21.9999e-3 40 1e3 1.4e-1 4.3e-6 100e-9

2.2000e-3 21.9999e-3 1e3 5e3 140e-4 10e-6 100e-9

2.2000e-3 21.9999e-3 5e3 10e3 3600e-4 20e-6 100e-9

22.000e-3 219.999e-3 10 19.99 160e-4 10e-6 1e-6

22.000e-3 219.999e-3 20 39.99 840e-4 8e-6 1e-6

22.000e-3 219.999e-3 40 1e3 1.69e-1 6.5e-5 1e-6

22.000e-3 219.999e-3 1e3 5e3 140e-4 100e-6 1e-6

22.000e-3 219.999e-3 5e3 10e3 3600e-4 200e-6 1e-6

0.22000 2.2 20 1e3 6.43e-1 -4e-3 10e-6

0.22000 2.2 1e3 5e3 1700e-4 200e-6 10e-6

0.22000 2.2 5e3 10e3 2.0 400e-6 10e-6

\# 5700A Current out the 5725A terminals with boost off

\# Range Locked (DC Current only)

\# Nominal Mod 1 Tol. Floor Resolution

\# ----------------------- -------------- ------- -------- ----------

#-219.9999e-6 219.9999e-6 NA NA 78e-4 13e-9 0.1e-9

#-2.199999e-3 2.199999e-3 NA NA 78e-4 13e-9 1e-9

#-21.99999e-3 21.99999e-3 NA NA 60e-4 100e-9 10e-9

#-219.9999e-3 219.9999e-3 NA NA 70e-4 1e-6 100e-9

#-2.2 2.2 NA NA 95e-4 30e-6 1e-6

\# Autorange (AC & DC Current)

\# Basic 5700A DC Current Accuracy

\# Nominal Mod 1 Tol. Floor Resolution

\# ----------------------- -------------- ------- -------- ----------

#-219.9999e-6 219.9999e-6 NA NA 78e-4 13e-9 0.1e-9

#-2.199999e-3 2.199999e-3 NA NA 78e-4 13e-9 1e-9

#-21.99999e-3 21.99999e-3 NA NA 60e-4 100e-9 10e-9

#-219.9999e-3 219.9999e-3 NA NA 70e-4 1e-6 100e-9

#-2.2 2.2 NA NA 95e-4 30e-6 1e-6

\# Basic 5700A AC Current Accuracy \*/

#9.000e-6 219.999e-6 10 19.99 1040e-4 2.039e-6 1e-9

#9.000e-6 219.999e-6 20 39.99 546e-4 2.0325e-6 1e-9

#9.000e-6 219.999e-6 40 1e3 208e-4 2.026e-6 1e-9

#9.000e-6 219.999e-6 1e3 5e3 910e-4 2.065e-6 1e-9

#9.000e-6 219.999e-6 5e3 10e3 2340e-4 2.13e-6 1e-9

#0.22000e-3 2.19999e-3 10 19.99 1040e-4 2.065e-6 10e-9

#0.22000e-3 2.19999e-3 20 39.99 546e-4 2.052e-6 10e-9

#0.22000e-3 2.19999e-3 40 1e3 208e-4 2.052e-6 10e-9

#0.22000e-3 2.19999e-3 1e3 5e3 910e-4 2.65e-6 10e-9

#0.22000e-3 2.19999e-3 5e3 10e3 2340e-4 3.3e-6 10e-9

#2.2000e-3 21.9999e-3 10 19.99 800e-4 500e-9 100e-9

#2.2000e-3 21.9999e-3 20 39.99 420e-4 400e-9 100e-9

#2.2000e-3 21.9999e-3 40 1e3 160e-4 400e-9 100e-9

#2.2000e-3 21.9999e-3 1e3 5e3 700e-4 5e-6 100e-9

#2.2000e-3 21.9999e-3 5e3 10e3 1800e-4 10e-6 100e-9

#22.000e-3 219.999e-3 10 19.99 800e-4 5e-6 1e-6

#22.000e-3 219.999e-3 20 39.99 420e-4 4e-6 1e-6

#22.000e-3 219.999e-3 40 1e3 180e-4 4e-6 1e-6

#22.000e-3 219.999e-3 1e3 5e3 700e-4 50e-6 1e-6

#22.000e-3 219.999e-3 5e3 10e3 1800e-4 100e-6 1e-6

#0.22000 2.2 20 1e3 750e-4 40e-6 10e-6

#0.22000 2.2 1e3 5e3 850e-4 100e-6 10e-6

#0.22000 2.2 5e3 10e3 1.0 200e-6 10e-6

\# DC Current from 5725A Boost Current Amplifier

\# Nominal Mod 1 Tol. Floor Resolution

\# ----------------------- -------------- ------- -------- ----------

#-11.00000 11.00000 NA NA 360e-4 480e-6 10e-6

\# AC Current from 5725A Boost Current Amplifier

1.0000 11.0000 40 1e3 460e-4 170e-6 100e-6

1.0000 11.0000 1e3 5e3 950e-4 380e-6 100e-6

1.0000 11.0000 5e3 10e3 3600e-4 750e-6 100e-6

\# Basic 5700A accuracy driven by the 5220A in Amps

\# 5220A, 180 day accuracy specifications, 99% Confidence Interval

\# Nominal Mod 1 Tol. Floor Resolution

\# ----------------------- -------------- ------- -------- ----------

#-20.0000 20.0000 NA NA 250e-4 0.001 100e-6

#1.0000 20.0000 20 1000 700e-4 0.001 100e-6

#1.0000 20.0000 1000 2000 0.14 0.002 100e-6

#1.0000 20.0000 2000 3000 0.21 0.003 100e-6

#1.0000 20.0000 3000 4000 0.28 0.004 100e-6

#1.0000 20.0000 4000 5000 0.35 0.005 100e-6

\# Resistance accuracies of the 5700A in 2-wire mode

\# Ranges represent maximum difference

\# of characterized to nominal value.

\# Nominal Mod 1 Tol. Floor Resolution

\# ----------------------- -------------- ------- -------- ----------

0 19.00285e3 NA NA NA NA NA

99.9850e3 100.0150e3 NA NA 32e-4 0 NA

189.9715e3 190.0285e3 NA NA 32e-4 0 NA

0.999800e6 1.000200e6 NA NA 46e-4 0 NA

1.899620e6 1.900380e6 NA NA 48e-4 0 NA

9.99700e6 10.00300e6 NA NA 1e-2 -1.6E2 NA

18.99430e6 19.00570e6 NA NA 110e-4 -1.6E2 NA

99.9500e6 100.0500e6 NA NA 500e-3 -1.6E2 NA

\# Resistance accuracies of the 5700A in 4-wire mode.

\# Ranges represent maximum difference

\# of characterized to nominal value.

\# Nominal Mod 1 Tol. Floor Resolution

\# ----------------------- -------------- ------- -------- ----------

0.999500 1.000500 NA NA 6.21e-3 6.45E-4 NA

1.899050 1.900950 NA NA 6.21e-3 6.45E-4 NA

9.99700 10.00300 NA NA 6.21e-3 6.45E-4 NA

18.99430 19.00570 NA NA 6.21e-3 6.45E-4 NA

99.9850 100.0050 NA NA 6.21e-3 6.45E-4 NA

189.9715 190.0285 NA NA 6.21e-3 6.45E-4 NA

0.999850e3 1.000015e3 NA NA 8.98e-4 -1.08E-2 NA

1.899715e3 1.900285e3 NA NA 8.98e-4 -1.08E-2 NA

9.99850e3 10.00150e3 NA NA 8.98e-4 -1.08E-2 NA

18.99715e3 19.00285e3 NA NA 8.98e-4 -1.08E-2 NA

99.9850e3 100.0150e3 NA NA 8.98e-4 -1.08E-2 NA

189.9715e3 190.0285e3 NA NA 8.98e-4 -1.08E-2 NA

0.999800e6 1.000200e6 NA NA 46e-4 0 NA

1.89962e6 1.900380e6 NA NA 48e-4 0 NA

9.99700e6 10.00300e6 NA NA 92e-4 0 NA

18.9943e6 19.00570e6 NA NA 500e-4 0 NA

\# Resistance accuracies of the 5700A in 2-wire

\# compensation mode at the 5700A

\# Ranges represent maximum difference

\# of characterized to nominal value.

\# Nominal Mod 1 Tol. Floor Resolution

\# ----------------------- -------------- ------- -------- ----------

0.999500 1.000500 NA NA 220e-4 4e-3 NA

1.899050 1.900950 NA NA 220e-4 4e-3 NA

9.99700 10.00300 NA NA 66e-4 4e-3 NA

18.99430 19.00570 NA NA 62e-4 4e-3 NA

99.9850 100.0050 NA NA 40e-4 4e-3 NA

189.9715 190.0285 NA NA 40e-4 4e-3 NA

0.999850e3 1.000015e3 NA NA 30e-4 20e-3 NA

1.899715e3 1.900285e3 NA NA 30e-4 20e-3 NA

9.99850e3 10.00150e3 NA NA 28e-4 100e-3 NA

18.9971e3 19.00290e3 NA NA 28e-4 200e-3 NA
