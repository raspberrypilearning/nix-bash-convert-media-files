Puedes convertir fácilmente archivos multimedia en tu Raspberry Pi utilizando un software llamado **ffmpeg**. Este software está preinstalado en las últimas versiones de [Raspbian](https://www.raspberrypi.org/downloads/raspbian/).

- Para convertir archivos de sonido o video de un formato a otro, puedes usar este comando básico:

    ```bash
    ffmpeg -i entrada.ext1 salida.ext2
    ```

- Por ejemplo, para convertir un archivo wav (`.wav`) en un archivo mp3 (`.mp3`), debes escribir:

    ```bash
    ffmpeg -i mi_musica.wav mi_musica.mp3
    ```
