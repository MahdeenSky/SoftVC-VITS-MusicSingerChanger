# SoftVC-VITS-MusicSingerChangerCollab
Google collab for testing SoftVC VITS Singing Voice Conversion for changing AI capable of changing the singer within music files.

The singing voice conversion model uses SoftVC content encoder to extract source audio speech features, then the vectors are directly fed into VITS instead of converting to a text based intermediate; thus the pitch and intonations are conserved. Additionally, the vocoder is changed to NSF HiFiGAN to solve the problem of sound interruption.

## Open In Collab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MahdeenSky/SoftVC-VITS-MusicSingerChanger/blob/main/so_vits_svc_4_0_inference.ipynb)

## Example of music made through SoftVC-VITS
[![Kanye West - Billie Jeans (AI Cover)](https://i.imgur.com/LHOd66c.png)](https://www.youtube.com/watch?v=CTgUPyxFoyk)

## Credits
https://github.com/svc-develop-team/so-vits-svc

https://www.youtube.com/@PluggingAI
