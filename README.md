# ihp-sg13g2-charts

This repository contains some charts of devices in 
[IHP SH13G2](https://github.com/IHP-GmbH/IHP-Open-PDK) that were 
obtained with simulation via Cadence Spectre.
Unless otherwise stated:
- T=27°C
- nom. process

## npn13G2

- input characteristic without self-heating @ VCE=1.2V
  ![npn13G2-ib-vs-vbe_vce-1V2-no_selft-lin](img/npn13G2-ib-vs-vbe_vce-1V2-no_selft-lin.png)
  ![npn13G2-ib-vs-vbe_vce-1V2-no_selft-log](img/npn13G2-ib-vs-vbe_vce-1V2-no_selft-log.png)

- input characteristic with self-heating @ VCE=1.2V
  ![npn13G2-ib-vs-vbe_vce-1V2-no_selft-lin](img/npn13G2-ib-vs-vbe_vce-1V2-selft-lin.png)
  ![npn13G2-ib-vs-vbe_vce-1V2-no_selft-log](img/npn13G2-ib-vs-vbe_vce-1V2-selft-log.png)

- output characteristic without self-heating
  ![npn13G2-ic-vs-vce_ibe-sweep-no_selft](img/npn13G2-ic-vs-vce_ibe-sweep-no_selft.png)

- output characteristic with self-heating
  ![npn13G2-ic-vs-vce_ibe-sweep-selft](img/npn13G2-ic-vs-vce_ibe-sweep-selft.png)

- gain without self-heating
  ![npn13G2-beta-vs-ib_no-selft](img/npn13G2-beta-vs-ib_no-selft.png)

- gain with self-heating
  ![npn13G2-beta-vs-ib_selft](img/npn13G2-beta-vs-ib_selft.png)

- transit frequency without self-heating
  ![npn13G2-ft-vs-ic_ic-vce-sweep-no_selft](img/npn13G2-ft-vs-ic_ic-vce-sweep-no_selft.png)

- transit frequency with self-heating
  ![npn13G2-ft-vs-ic_ic-vce-sweep-selft](img/npn13G2-ft-vs-ic_ic-vce-sweep-selft.png)