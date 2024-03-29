# Fortunas Mechanicus

<!-- I'm not sure I like the badges anymore
[![forthebadge](https://forthebadge.com/images/badges/built-with-science.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-electricity.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/oooo-kill-em.svg)](https://forthebadge.com)
-->

> From the moment I understood the weakness of my flesh, it disgusted me. I craved the strength and certainty of steel. I aspired to the purity of the Blessed Machine. Your kind cling to your flesh, as though it will not decay and fail you. One day the crude biomass you call the temple will wither, and you will beg my kind to save you. But I am already saved, for the Machine is immortal… Even in death I serve the Omnissiah.

A growing database of [Adeptus Mechanicus](https://warhammer40k.fandom.com/wiki/Adeptus_Mechanicus) quotes and scriptures for [fortune-mod](https://github.com/shlomif/fortune-mod).

PRs welcome! (just don't forget to run `strfile mechanicus` to update mechanicus.dat)

## Litany of Holy Installation

```sh
echo "Machine God, hear our prayers and grant us access."
sudo apt install git fortune-mod cowsay # or your distro's equivalent, if not already installed
git clone https://github.com/mathiscode/fortunes-mechanicus
cd fortunes-mechanicus
sudo ln -s $(pwd)/mechanicus* /usr/share/games/fortunes
sudo ln -s $(pwd)/tech-priest.cow /usr/share/cowsay/cows/ # optional if cowsay isn't needed
echo "By the Will of the Omnissiah, it is done."
```

## Litany of Divine Wisdom

```sh
$ fortune mechanicus

Knowledge will ever be a blessing and a curse. -Levistians, 9.22
```

## Litany of Bovine Wisdom

A custom Tech-Priest file is included to be used with [cowsay](https://en.wikipedia.org/wiki/Cowsay).

This cowfile is based on the wizard from [Paul Kaefer's cowfiles](https://github.com/paulkaefer/cowsay-files), and needs some more work from someone better at it than me.

```
$ fortune mechanicus | cowsay -f tech-priest

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

## Counsel

- If you want a Mechanicum-y font for your system, check out [Exocet](https://en.wikipedia.org/wiki/Exocet_(typeface))
- You may or may not like another project I'm working on: [web3os](https://github.com/web3os-org/kernel#readme)
- Or this one: [Imagined.Quest](https://imagined.quest)
- Like & subscribe; SMASH that Star button
- Don't do a heresy

<p align="center">
  <a href="https://www.mechanicus40k.com/">
    <img src="https://static.wixstatic.com/media/748239_ba839dbb0e8341baa7e9ed5460225997~mv2_d_3840_2160_s_2.png/v1/fit/w_2500,h_1330,al_c/748239_ba839dbb0e8341baa7e9ed5460225997~mv2_d_3840_2160_s_2.png" />
  </a>

  <p align="center">Praise the Omnissiah</p>
</p>
