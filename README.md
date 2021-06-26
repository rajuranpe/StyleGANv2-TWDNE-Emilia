# StyleGANv2-TWDNE-Emilia
A GAN generating images of Emilia from the anime Re:Zero, trained with NVIDIA's StyleGANv2 by transfer-learning Gwern's ThisWaifuDoesNotExist v3. 

As source training data I used 500 Emilia faces from the web, auto-cropped the faces and removed all non-Emilia characters 
(but, as can be seen in the provided interpolation video at 0:39 at bottom-right, sometimes an half of someones face was left in the crop, most often Rem's 
(this was also the case in the network I used to continue on)).

This is done with NVIDIA's StyleGAN v2 by transfer-learning from Gwern's ThisWaifuDoesNotExist v3 for 200 kimgs on a RTX 2080 Ti. 
I give thanks to Gwern for their pre-trained weights and helpful guide at https://www.gwern.net/Faces.

The model checkpoint can be downloadedm from https://drive.google.com/drive/folders/1Ln2jbvYb-KWx848kN8iymgTtLKI9UMNQ?usp=sharing
