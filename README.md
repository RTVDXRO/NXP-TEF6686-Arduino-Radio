  TEF6686HN/V102 AM FM for XDR-GTK
  by RTVDXRO

  ( for old "historical" versions visit rdi.boards.net ! )

    * by default audio output level is fixed -> 0dB or +2dB
    

    * On genuine XDR-GTK interface de-emphasis switch is acting now this way:

  50uS => NORMAL;

  75uS => FLAT ( 0uS );

  0uS  => MPX out mode ( DAC_Left : FM MPX (DARC) signal / DAC_Right : mono audio );


    * XDR-GTK Antenna Switch option:

  Ant A = Normal

  Ant B = iMS enabled ( FM multipath suppression when the receiver is in a moving vehicle )

  Ant C = EQ enabled ( FM channel equalizer for improved field performance )

  Ant D = Both enabled

  In some altered versions of XDR-GTK the word "Ant" has been replaced with others such as the funny "DX", which, apart from the word itself on a button,
  doesn't bring a plus of performance on weak fringe RF signals, being in fact only just to impress the ignorants :)

  Great special thanks to Konrad Kosmatka, author of the original & brilliant version for Sony XDR-F1HD
  https://fmdx.pl/xdr-i2c/
  https://fmdx.pl/xdr-gtk/

  Special thanks to NXP BU Automotive Car Entertainment Team
  and also to ( in alphabetical order ):
  - ace919
  - Brian Beezley
  - dxhdtv
  - eggplant886
  - fmdxbp
  - Jan Kolar
  - Marcin Woloszczuk
  - Mihai Popa          https://github.com/stailus/tef6686_rds
  - makserge            https://github.com/makserge/tef6686_radio
  - Nicu Florica        http://nicuflorica.blogspot.com/2020/02/radio-cu-tef6686.html
  - ODJeetje
  - Olivier Guillaume
  - Przemyslaw Korpas
  - VoXiTPro            https://github.com/voxit1512/Tef6686

  and many other enthusiasts ...

  Tested on Arduino Nano V3.0 at 5V

  Feel free to add your own contribution to this nice project !
