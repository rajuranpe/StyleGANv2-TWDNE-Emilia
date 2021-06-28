# StyleGANv2-TWDNE-Emilia
Results (in a form of interpolation video constructed by a random-walk trough the latent space of the Generator) and model checkpoint of a GAN generating images of Emilia from the anime Re:Zero, trained with NVIDIA's StyleGANv2 by transfer-learning Gwern's ThisWaifuDoesNotExist v3 on a RTX 2080 Ti for 200 kimgs. 

As source training data I used 500 Emilia faces from the web, auto-cropped the faces and removed all non-Emilia characters 
(but, as can be seen in the provided interpolation video at 0:39 at bottom-right, sometimes a half of someones face was left in the crop, most often Rem's 
(this was also the case in the network I used to continue on)).

I give thanks to Gwern for their pre-trained weights and helpful guide for data preprocessing at https://www.gwern.net/Faces.

The model checkpoint can be downloaded from https://drive.google.com/drive/folders/1Ln2jbvYb-KWx848kN8iymgTtLKI9UMNQ?usp=sharing
