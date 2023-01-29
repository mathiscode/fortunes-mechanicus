# Fortunas Mechanicus

[![forthebadge](https://forthebadge.com/images/badges/built-with-science.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-electricity.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/oooo-kill-em.svg)](https://forthebadge.com)

> From the moment I understood the weakness of my flesh, it disgusted me. I craved the strength and certainty of steel. I aspired to the purity of the Blessed Machine. Your kind cling to your flesh, as though it will not decay and fail you. One day the crude biomass you call the temple will wither, and you will beg my kind to save you. But I am already saved, for the Machine is immortal… Even in death I serve the Omnissiah.

A growing database of [Adeptus Mechanicus](https://warhammer40k.fandom.com/wiki/Adeptus_Mechanicus) quotes and scriptures for [fortune-mod](https://github.com/shlomif/fortune-mod).

PRs welcome! (just don't forget to run `strfile mechanicus` to update mechanicus.dat)

## Litany of Holy Installation

```sh
echo "Machine God, hear our prayers and grant us access."
sudo apt install fortune-mod # or your distro's equivalent
git clone https://github.com/mathiscode/fortunes-mechanicus
cd fortunes-mechanicus
sudo ln -s $(pwd)/mechanicus* /usr/share/games/fortunes
echo "By the Will of the Omnissiah, it is done."
```

## Litany of Divine Wisdom

```sh
$ fortune mechanicus
```

## Litany of Bovine Wisdom

A custom Tech-Priest file is included to be used with [cowsay](https://en.wikipedia.org/wiki/Cowsay).

This cowfile is based on the wizard from [Paul Kaefer's cowfiles](https://github.com/paulkaefer/cowsay-files), and needs some more work from someone better at it than me.

```txt
$ fortune mechanicus | cowsay -f ./tech-priest.cow

/ Verily it is written that the Omnissiah \
| grants His blessing to those who come   |
| well-equipped with explosives.          |
\ -Aphorisms 96.9                         /
 -----------------------------------------
  \
   \
                   |^|  
      |            |-|
      (0.o)    ___/_*_\__     |
        \\    /   ____   \(0.o)
         \\_\_) /_____\ /_|//
      /\     /_((\0_0/))_\// /^\
     //\\    \ \()[ ])(()// > 0 }
    //  \\// ' \(([_]))/ /   \ /
   < >   \/ / ' \)).))\ '\  =//=
           / _ \ - | - /_ \ //
          (   ( .;''';. .'  )
          _\"__ /    )\ __"/_
            \/  \   ' /  \/
             .'  '...' '  )
              / /  |   \  \
             / .   .    .  \
            /   .      .    \
           /   /   |    \    \
         .'   /    b     '.   '.
     _.-'    /     Bb      '-.  '-_
 _.-'       |      BBb        '-.  '-.
(_______________.dBBBb._________)____)
```

<p align="center">
  <img src="https://static.wixstatic.com/media/748239_ba839dbb0e8341baa7e9ed5460225997~mv2_d_3840_2160_s_2.png/v1/fit/w_2500,h_1330,al_c/748239_ba839dbb0e8341baa7e9ed5460225997~mv2_d_3840_2160_s_2.png" />

  <p align="center">Praise the Omnissiah</p>
</p>
