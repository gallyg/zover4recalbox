ZOVER4RECALBOX Collection - Packs bezels/overlays pour Recalbox 4.1 et +
========================================================================
Ces packs sont destinés aux écrans ayant une résolution de 1280x720 pixels ou 1920x1080 pixels pour Recalbox 4.1 et +.

Ces packs sont une compilation et adapation de differentes sources et artistes (voir Crédits).


Activer le "game ratio" personnalisé
====================================
- Options > Options des jeux > Format jeux : auto
- Options > Options des jeux > Integer scale" (pixel perfect) : off


Installer le pack de d'overlay
==============================
En raison des nombreux presets, la ZOVER4RECALBOX Collection est séparée en plusieurs volumes.

- [Téléchargez ici pour le volume 1](https://github.com/gallyg/zover4recalBox-vol-1/archive/master.zip)
- [Téléchargez ici pour le volume 2](https://github.com/gallyg/zover4recalBox-vol-2/archive/master.zip)

- Copier les répertoires du pack dans le répertoire suivant de votre Recalbox : /recalbox/share/system/configs/retroarch/
- Le répertoire 'overlays' contient les élements graphiques
- Le répertoire 'zover4recalbox-presets' contient les préconfigurations


Choisir les fichiers de configuration adaptés (.cfg)
====================================================
Nomenclature des répertoires : pack[NUMERO]-[STYLE]-systems-[TAILLE] :
- [NUMERO] correspond au numéro du pack,
- [STYLE] Deux styles selon les variantes. Le style 'grid' qui inclus un effet de grille/CRT. Le style 'clean' sans effet de grille.
- [TAILLE] à la résolution en hauteur de votre écran

Exemple avec le pack 01 sans effet de grille/CRT :
- Si vous utilisez une resolution de 1280x720 pixels, aller dans : /recalbox/share/system/configs/retroarch/zover4recalbox-presets/pack01-clean-systems-720
- Si vous utilisez une résolution de 1920x1080 pixels aller dans : /recalbox/share/system/configs/retroarch/zover4recalbox-presets/pack01-clean-systems-1080

- Copier les fichiers .cfg des machines que vous souhaitez habiller (3do.cfg, amstradcpc.cfg, etc) dans : /recalbox/share/system/configs/retroarch


Arcade affichage vertical
=========================
Certains packs contiennent des dossiers 'fba_libretro' et 'mame' pour gerer de façon spécifique les titres ayants un affichage vertical (Exemple : 1941, 1942 ou 1943).

Ces dossiers sont à copier dans le répertoire suivant de votre Recalbox : /recalbox/share/system/configs/retroarch/


Aperçu pack 01 (volume 1)
=========================
![3DO pack 01](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-1/master/overlays/pack01-clean-720/3do.png)
![Atari 2600 pack 01](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-1/master/overlays/pack01-clean-720/atari2600.png)
![Megadrive pack 01](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-1/master/overlays/pack01-clean-720/megadrive.png)
![Super Nintendo pack 01](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-1/master/overlays/pack01-clean-720/snes.png)


Aperçu pack 02 (4/3 - pixel perfect) (volume 1)
===============================================
Machines pixel perfect : Master System, Megadrive, Neo-Geo, NES, PC Engine, PC Engine CD, Sega 32X, Sega CD, SuperGrafx.
Pour les machines "pixel perfect" citées ci-dessus, les presets 4/3 sont disponibles dans le sous-répertoire '4-3-presets'.

![4/3 pack 02](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-1/master/overlays/pack02-clean-720/4-3.png)
![GBA pack 02](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-1/master/overlays/pack02-clean-720/gba-lg.png)


Aperçu pack 03 (4/3 - pixel perfect) (volume 1)
===============================================
Machines pixel perfect : Master System, Megadrive, Neo-Geo, NES, PC Engine, PC Engine CD, Sega 32X, Sega CD, SuperGrafx.
Pour les machines "pixel perfect" citées ci-dessus, les presets 4/3 sont disponibles dans le sous-répertoire '4-3-presets'.

![4/3 pack 03](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-1/master/overlays/pack03-clean-720/4-3.png)
![GBA pack 03](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-1/master/overlays/pack03-clean-720/gba-lg.png)


Aperçu pack 04 (4/3 - pixel perfect) (volume 1)
===============================================
Machines pixel perfect : Master System, Megadrive, Neo-Geo, NES, PC Engine, PC Engine CD, Sega 32X, Sega CD, SuperGrafx.
Pour les machines "pixel perfect" citées ci-dessus, les presets 4/3 sont disponibles dans le sous-répertoire '4-3-presets'.

![4/3 pack 04](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-1/master/overlays/pack04-clean-720/4-3.png)
![GBA pack 04](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-1/master/overlays/pack04-clean-720/gba-lg.png)


Aperçu pack 05 - Arcade (4/3) (volume 1)
========================================
![4/3 pack 05](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-1/master/overlays/pack05-grid-1080/4-3.png)
![3/4 pack 05](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-1/master/overlays/pack05-grid-1080/3-4.png)


Aperçu pack handhelds (consoles portables) (volume 1)
=====================================================
![Gameboy pack handhelds](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-1/master/overlays/pack-handhelds-clean-720/gb.png)
![Gameboy Color pack handhelds](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-1/master/overlays/pack-handhelds-clean-720/gbc.png)
![Game Gear pack handhelds](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-1/master/overlays/pack-handhelds-clean-720/gg.png)


Vectrex (volume 1)
==================
Bien que l'écran soit monochrome noir et blanc, tous les jeux de la Vectrex étaient fournis avec un filtre en plastique coloré qui devait être glissé devant l'écran.

Les overlays inclus dans ce pack permettent de simuler ces filtres.

Activer les overlays Vectrex :
- Si vous utilisez une resolution de 1280x720 pixels, aller dans : /recalbox/share/system/configs/retroarch/rb-pack-vectrex-720
- Si vous utilisez une résolution de 1920x1080 pixels aller dans : /recalbox/share/system/configs/retroarch/rb-pack-vectrex-1080

- Copier le répertoire 'vectrex' dans : /recalbox/share/system/configs/retroarch

- ATTENTION : Le nom de vos ROM Vectrex doit correspondre à la préconfiguration de l'overlay.

Exemple : Pour afficher l'overlay de Bedlam votre ROM doit être nommée ainsi 'Bedlam (USA, Europe).zip'.

![Bedlam pack Vectrex](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-1/master/rb-pack-vectrex-720/vectrex/Bedlam%20(USA%2C%20Europe).png)


Aperçu pack 06 - SNES mini (4/3) (volume 2)
===========================================
Les 11 styles de SNES mini sont disponibles pour un affichage 4/3.

Le pack 06 contient des sous-répertoires qui correspondent à chaque style.

Copier l'ensemble les fichiers .cfg (3do.cfg, amstradcpc.cfg, etc) dans : /recalbox/share/system/configs/retroarch

01-ambient
----------
![4/3 01-ambient pack 06](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-2/master/overlays/pack06-grid-720/01-ambient/4-3.png)
02-wire
-------
![4/3 02-wire pack 06](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-2/master/overlays/pack06-grid-720/02-wire/4-3.png)
03-crystal
----------
![4/3 03-crystal pack 06](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-2/master/overlays/pack06-grid-720/03-crystal/4-3.png)
04-dot
------
![4/3 04-dot pack 06](https://raw.githubusercontent.com/gallyg/zover4recalBox/master-vol-2/overlays/pack06-grid-720/04-dot/4-3.png)
05-mosaic
---------
![4/3 05-mosaic pack 06](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-2/master/overlays/pack06-grid-720/05-mosaic/4-3.png)
06-dot2
-------
![4/3 06-dot2 pack 06](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-2/master/overlays/pack06-grid-720/06-dot2/4-3.png)
07-wood
-------
![4/3 07-wood pack 06](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-2/master/overlays/pack06-grid-720/07-wood/4-3.png)
08-space
--------
![4/3 08-space pack 06](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-2/master/overlays/pack06-grid-720/08-space/4-3.png)
09-speaker
----------
![4/3 09-speaker pack 06](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-2/master/overlays/pack06-grid-720/09-speaker/4-3.png)
10-curtain
----------
![4/3 10-curtain pack 06](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-2/master/overlays/pack06-grid-720/10-curtain/4-3.png)
11-midnight
-----------
![4/3 11-midnight pack 06](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-2/master/overlays/pack06-grid-720/11-midnight/4-3.png)

Aperçu pack 07 (4/3) (volume 2)
===============================
Coming soon...

Aperçu pack 08 (4/3) (volume 2)
===============================
01-Retour vers le futur
-----------------------
![4/3 01-Retour vers le futur pack 08](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-2/master/overlays/pack08-clean-720/01-retour-vers-le-futur/4-3.png)
02-Cobra
--------
![4/3 02-Cobra pack 08](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-2/master/overlays/pack08-clean-720/02-cobra/4-3.png)
03-Gally
--------
![4/3 03-Gally pack 08](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-2/master/overlays/pack08-clean-720/03-gally/4-3.png)
04-Ken le survivant
-------------------
![4/3 04-Ken le survivant pack 08](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-2/master/overlays/pack08-clean-720/04-ken-le-survivant/4-3.png)
05-Ghost in the shell
---------------------
![4/3 05-Ghost in the shell pack 08](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-2/master/overlays/pack08-clean-720/05-ghost-in-the-shell/4-3.png)
06 My little poney
------------------
![4/3 06 My little poney pack 08](https://raw.githubusercontent.com/gallyg/zover4recalBox-vol-2/master/overlays/pack08-clean-720/06-my-little-poney/4-3.png)


Changelog
=========

version 1.3.
- Split in two volumes

version 1.3.0
- Add pack 08

version 1.2.0
- Add pack handhelds

version 1.1.1
- Fix pack 02, pack 03, pack 04 : grid images, NES et Master System presets

version 1.1.0
- Fix arcade vertical pack 02
- Add 4/3 presets pack 05

version 1.0.0
- Initial release


Credits
=======
https://github.com/recalbox/recalbox-os/wiki/Retroarch-setup-overlays-(FR)

Bezels Systèmes :
- MarbleMad (Team ScreenZone)
- Kam3leon (Team ScreenZone)
- Orions angel (https://www.youtube.com/channel/UCG1g7PE9yzd4MboQQa9OYWA)
- MezzB's (https://sites.google.com/view/mezzb-overlay/home)

Bezels Vectrex :
- MarbleMad (Team ScreenZone)
- Chris Parsons (https://drive.google.com/drive/u/0/folders/0BwUJ62zB09ZVakg1b0tuM0VUNFE)


License
=======

-------------------------------------------------------------------------

Summary of the license below:

ALLOWED:      - Share and duplicate as it is
- Edit, alter, change it

REQUIREMENTS: - Attribution, give credit to the creator
- Indicate changes to it
- Publish the changes under the same license

PROHIBITED:   - Commercial distribution

-------------------------------------------------------------------------

LOGO NOTICE

The used logos and trademarks are copyright of their respective owners.

-------------------------------------------------------------------------

Attribution-NonCommercial-ShareAlike 2.0 (CC-BY-NC-SA)

By exercising the Licensed Rights (defined below), You accept and agree
to be bound by the terms and conditions of this Creative Commons
Attribution-NonCommercial-ShareAlike 4.0 International Public License
("Public License"). To the extent this Public License may be interpreted
as a contract, You are granted the Licensed Rights in consideration of
Your acceptance of these terms and conditions, and the Licensor grants
You such rights in consideration of benefits the Licensor receives from
making the Licensed Material available under these terms and conditions.

Section 1 – Definitions.

Adapted Material means material subject to Copyright and Similar Rights
that is derived from or based upon the Licensed Material and in which
the Licensed Material is translated, altered, arranged, transformed, or
otherwise modified in a manner requiring permission under the Copyright
and Similar Rights held by the Licensor. For purposes of this Public
License, where the Licensed Material is a musical work, performance, or
sound recording, Adapted Material is always produced where the Licensed
Material is synched in timed relation with a moving image. Adapter's
License means the license You apply to Your Copyright and Similar Rights
in Your contributions to Adapted Material in accordance with the terms
and conditions of this Public License. BY-NC-SA Compatible License means
a license listed at creativecommons.org/compatiblelicenses, approved by
Creative Commons as essentially the equivalent of this Public License.
Copyright and Similar Rights means copyright and/or similar rights
closely related to copyright including, without limitation, performance,
broadcast, sound recording, and Sui Generis Database Rights, without
regard to how the rights are labeled or categorized. For purposes of
this Public License, the rights specified in Section 2(b)(1)-(2) are not
Copyright and Similar Rights. Effective Technological Measures means
those measures that, in the absence of proper authority, may not be
circumvented under laws fulfilling obligations under Article 11 of the
WIPO Copyright Treaty adopted on December 20, 1996, and/or similar
international agreements. Exceptions and Limitations means fair use,
fair dealing, and/or any other exception or limitation to Copyright and
Similar Rights that applies to Your use of the Licensed Material.
License Elements means the license attributes listed in the name of a
Creative Commons Public License. The License Elements of this Public
License are Attribution, NonCommercial, and ShareAlike. Licensed
Material means the artistic or literary work, database, or other
material to which the Licensor applied this Public License. Licensed
Rights means the rights granted to You subject to the terms and
conditions of this Public License, which are limited to all Copyright
and Similar Rights that apply to Your use of the Licensed Material and
that the Licensor has authority to license. Licensor means the
individual(s) or entity(ies) granting rights under this Public License.
NonCommercial means not primarily intended for or directed towards
commercial advantage or monetary compensation. For purposes of this
Public License, the exchange of the Licensed Material for other material
subject to Copyright and Similar Rights by digital file-sharing or
similar means is NonCommercial provided there is no payment of monetary
compensation in connection with the exchange. Share means to provide
material to the public by any means or process that requires permission
under the Licensed Rights, such as reproduction, public display, public
performance, distribution, dissemination, communication, or importation,
and to make material available to the public including in ways that
members of the public may access the material from a place and at a time
individually chosen by them. Sui Generis Database Rights means rights
other than copyright resulting from Directive 96/9/EC of the European
Parliament and of the Council of 11 March 1996 on the legal protection
of databases, as amended and/or succeeded, as well as other essentially
equivalent rights anywhere in the world. You means the individual or
entity exercising the Licensed Rights under this Public License. Your
has a corresponding meaning. Section 2 – Scope.

License grant. Subject to the terms and conditions of this Public
License, the Licensor hereby grants You a worldwide, royalty-free,
non-sublicensable, non-exclusive, irrevocable license to exercise the
Licensed Rights in the Licensed Material to: reproduce and Share the
Licensed Material, in whole or in part, for NonCommercial purposes only;
and produce, reproduce, and Share Adapted Material for NonCommercial
purposes only. Exceptions and Limitations. For the avoidance of doubt,
where Exceptions and Limitations apply to Your use, this Public License
does not apply, and You do not need to comply with its terms and
conditions. Term. The term of this Public License is specified in
Section 6(a). Media and formats; technical modifications allowed. The
Licensor authorizes You to exercise the Licensed Rights in all media and
formats whether now known or hereafter created, and to make technical
modifications necessary to do so. The Licensor waives and/or agrees not
to assert any right or authority to forbid You from making technical
modifications necessary to exercise the Licensed Rights, including
technical modifications necessary to circumvent Effective Technological
Measures. For purposes of this Public License, simply making
modifications authorized by this Section 2(a)(4) never produces Adapted
Material. Downstream recipients. Offer from the Licensor – Licensed
Material. Every recipient of the Licensed Material automatically
receives an offer from the Licensor to exercise the Licensed Rights
under the terms and conditions of this Public License. Additional offer
from the Licensor – Adapted Material. Every recipient of Adapted
Material from You automatically receives an offer from the Licensor to
exercise the Licensed Rights in the Adapted Material under the
conditions of the Adapter’s License You apply. No downstream
restrictions. You may not offer or impose any additional or different
terms or conditions on, or apply any Effective Technological Measures
to, the Licensed Material if doing so restricts exercise of the Licensed
Rights by any recipient of the Licensed Material. No endorsement.
Nothing in this Public License constitutes or may be construed as
permission to assert or imply that You are, or that Your use of the
Licensed Material is, connected with, or sponsored, endorsed, or granted
official status by, the Licensor or others designated to receive
attribution as provided in Section 3(a)(1)(A)(i). Other rights.

Moral rights, such as the right of integrity, are not licensed under
this Public License, nor are publicity, privacy, and/or other similar
personality rights; however, to the extent possible, the Licensor waives
and/or agrees not to assert any such rights held by the Licensor to the
limited extent necessary to allow You to exercise the Licensed Rights,
but not otherwise. Patent and trademark rights are not licensed under
this Public License. To the extent possible, the Licensor waives any
right to collect royalties from You for the exercise of the Licensed
Rights, whether directly or through a collecting society under any
voluntary or waivable statutory or compulsory licensing scheme. In all
other cases the Licensor expressly reserves any right to collect such
royalties, including when the Licensed Material is used other than for
NonCommercial purposes. Section 3 – License Conditions.

Your exercise of the Licensed Rights is expressly made subject to the
following conditions.

Attribution.

If You Share the Licensed Material (including in modified form), You
must:

retain the following if it is supplied by the Licensor with the Licensed
Material: identification of the creator(s) of the Licensed Material and
any others designated to receive attribution, in any reasonable manner
requested by the Licensor (including by pseudonym if designated); a
copyright notice; a notice that refers to this Public License; a notice
that refers to the disclaimer of warranties; a URI or hyperlink to the
Licensed Material to the extent reasonably practicable; indicate if You
modified the Licensed Material and retain an indication of any previous
modifications; and indicate the Licensed Material is licensed under this
Public License, and include the text of, or the URI or hyperlink to,
this Public License. You may satisfy the conditions in Section 3(a)(1)
in any reasonable manner based on the medium, means, and context in
which You Share the Licensed Material. For example, it may be reasonable
to satisfy the conditions by providing a URI or hyperlink to a resource
that includes the required information. If requested by the Licensor,
You must remove any of the information required by Section 3(a)(1)(A) to
the extent reasonably practicable. ShareAlike. In addition to the
conditions in Section 3(a), if You Share Adapted Material You produce,
the following conditions also apply.

The Adapter’s License You apply must be a Creative Commons license with
the same License Elements, this version or later, or a BY-NC-SA
Compatible License. You must include the text of, or the URI or
hyperlink to, the Adapter's License You apply. You may satisfy this
condition in any reasonable manner based on the medium, means, and
context in which You Share Adapted Material. You may not offer or impose
any additional or different terms or conditions on, or apply any
Effective Technological Measures to, Adapted Material that restrict
exercise of the rights granted under the Adapter's License You apply.
Section 4 – Sui Generis Database Rights.

Where the Licensed Rights include Sui Generis Database Rights that apply
to Your use of the Licensed Material:

for the avoidance of doubt, Section 2(a)(1) grants You the right to
extract, reuse, reproduce, and Share all or a substantial portion of the
contents of the database for NonCommercial purposes only; if You include
all or a substantial portion of the database contents in a database in
which You have Sui Generis Database Rights, then the database in which
You have Sui Generis Database Rights (but not its individual contents)
is Adapted Material, including for purposes of Section 3(b); and You
must comply with the conditions in Section 3(a) if You Share all or a
substantial portion of the contents of the database. For the avoidance
of doubt, this Section 4 supplements and does not replace Your
obligations under this Public License where the Licensed Rights include
other Copyright and Similar Rights. Section 5 – Disclaimer of Warranties
and Limitation of Liability.

Unless otherwise separately undertaken by the Licensor, to the extent
possible, the Licensor offers the Licensed Material as-is and
as-available, and makes no representations or warranties of any kind
concerning the Licensed Material, whether express, implied, statutory,
or other. This includes, without limitation, warranties of title,
merchantability, fitness for a particular purpose, non-infringement,
absence of latent or other defects, accuracy, or the presence or absence
of errors, whether or not known or discoverable. Where disclaimers of
warranties are not allowed in full or in part, this disclaimer may not
apply to You. To the extent possible, in no event will the Licensor be
liable to You on any legal theory (including, without limitation,
negligence) or otherwise for any direct, special, indirect, incidental,
consequential, punitive, exemplary, or other losses, costs, expenses, or
damages arising out of this Public License or use of the Licensed
Material, even if the Licensor has been advised of the possibility of
such losses, costs, expenses, or damages. Where a limitation of
liability is not allowed in full or in part, this limitation may not
apply to You. The disclaimer of warranties and limitation of liability
provided above shall be interpreted in a manner that, to the extent
possible, most closely approximates an absolute disclaimer and waiver of
all liability. Section 6 – Term and Termination.

This Public License applies for the term of the Copyright and Similar
Rights licensed here. However, if You fail to comply with this Public
License, then Your rights under this Public License terminate
automatically. Where Your right to use the Licensed Material has
terminated under Section 6(a), it reinstates:

automatically as of the date the violation is cured, provided it is
cured within 30 days of Your discovery of the violation; or upon express
reinstatement by the Licensor. For the avoidance of doubt, this Section
6(b) does not affect any right the Licensor may have to seek remedies
for Your violations of this Public License. For the avoidance of doubt,
the Licensor may also offer the Licensed Material under separate terms
or conditions or stop distributing the Licensed Material at any time;
however, doing so will not terminate this Public License. Sections 1, 5,
6, 7, and 8 survive termination of this Public License. Section 7 –
Other Terms and Conditions.

The Licensor shall not be bound by any additional or different terms or
conditions communicated by You unless expressly agreed. Any
arrangements, understandings, or agreements regarding the Licensed
Material not stated herein are separate from and independent of the
terms and conditions of this Public License. Section 8 – Interpretation.

For the avoidance of doubt, this Public License does not, and shall not
be interpreted to, reduce, limit, restrict, or impose conditions on any
use of the Licensed Material that could lawfully be made without
permission under this Public License. To the extent possible, if any
provision of this Public License is deemed unenforceable, it shall be
automatically reformed to the minimum extent necessary to make it
enforceable. If the provision cannot be reformed, it shall be severed
from this Public License without affecting the enforceability of the
remaining terms and conditions. No term or condition of this Public
License will be waived and no failure to comply consented to unless
expressly agreed to by the Licensor. Nothing in this Public License
constitutes or may be interpreted as a limitation upon, or waiver of,
any privileges and immunities that apply to the Licensor or You,
including from the legal processes of any jurisdiction or authority.
Creative Commons is not a party to its public licenses. Notwithstanding,
Creative Commons may elect to apply one of its public licenses to
material it publishes and in those instances will be considered the
“Licensor.” Except for the limited purpose of indicating that material
is shared under a Creative Commons public license or as otherwise
permitted by the Creative Commons policies published at
creativecommons.org/policies, Creative Commons does not authorize the
use of the trademark “Creative Commons” or any other trademark or logo
of Creative Commons without its prior written consent including, without
limitation, in connection with any unauthorized modifications to any of
its public licenses or any other arrangements, understandings, or
agreements concerning use of licensed material. For the avoidance of
doubt, this paragraph does not form part of the public licenses.

Creative Commons may be contacted at creativecommons.org.
