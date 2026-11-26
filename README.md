# Firmware da Jukeboox

Versão testada no protótipo com ESP32, leitor RC522 e DFPlayer Mini. O painel web da placa está integrado ao sketch.

1. Baixe [Jukeboox_Produto.ino](Jukeboox_Produto/Jukeboox_Produto.ino), salve na pasta `Jukeboox_Produto` e abra no Arduino IDE.
2. Instale **MFRC522** e **DFRobotDFPlayerMini**. Selecione a placa ESP32.
3. Preencha `SENHA_WIFI` com uma senha de 8 a 63 caracteres e grave o sketch.
4. Coloque `0001.mp3` a `0004.mp3` na pasta `MP3` do microSD FAT32.
5. Conecte-se ao Wi-Fi **Jukeboox** e abra [o painel da placa](http://192.168.4.1/).

[Circuito, simulador e documentação](https://gusstavovp.github.io/jukeboox-circuito-3d/)
