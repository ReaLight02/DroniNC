# Introduction
⠉⡛⠛⠛⠿⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿<br />
⣸⡀⡀⡀⡀⠄⠹⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿<br />
⣿⡀⡀⡀⡀⡀⠄⠄⠉⠛⠿⢿⣿⣿⣿⣿⡿⠿⠛⠻⠿⢿⣿⣿⣿⣿⣿⣿<br />
⣿⡀⡀⡀⡀⡀⡀⡀⡀⡀⠄⠉⢉⣴⠏⠉⢁⡀⡀⠄⠄⠄⠄⠄⣄⠄⣸  <br />
⣯⡀⡀⠄⠄⠄⠄⠄⠄⢀⣴⣶⡤⠿⢉⡀⡀⡀⡀⡀⡀⡀⠄⠄⢠⡄⣸  <br />
⣿⣿⣷⣤⣀⠄⠄⠄⣠⣾⣿⣿⣧⠄⠄⠄⠄⠄⡀⡀⡀⡀⠠⢀⣾⢟⣿⣿<br />
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣞⣧⡀⠄⠄⠄⢀⣀⣷⣽⣴⣋⣥⣾⣿⣿<br />
⣿⣿⣿⣿⣿⢟⣿⣿⣿⡿⠋⠄⠄⠉⠉⠉⠒⠲⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿<br />
⣿⣿⣿⣿⣷⡿⠋⠉⠁⠄⠄⠄⠄⠄⠄⠄⠄⠄⠙⣿⣿⣿⣿⣿⣿⣿⣿⣿<br />
⣿⣿⣿⣿⡋⠄⣀⢀⣤⣤⣌⣁⣀⣀⡀⡀⠄⠄⠄⠘⢿⣿⣿⣿⣿⣿⣿⣿<br />
⣿⣿⣿⣿⣿⣾⣿⣿⣶⣾⣿⣿⣿⣾⣷⣶⣶⣶⣦⣄⣨⣿⣿⣿⣿⣿⣿⣿<br />
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿<br />
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿<br />
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿<br />


Lets talk about me... Lets talk about the 6 foot 8 frame, the 37 inch vertical leap, the black steel that drips down my back AKA the bullet proof mullet, the Google prototype scopes with built in LCD LED 1080p 3D Sony technology, the Ethiopian poisonous caterpillar AKA slick daddy. Lets talk about the cabinets right behind me that go 40 feet deep into the wall that houses the other 95 percent of my trophies, the awards, the certificates all claiming first place, right? Let me give you a little inside glimpse into the hotshot video gaming lifestyle of the two-time international video gaming superstar. Because that's what this channels about, that's what this domains about, that's what this society is about. You're looking at the face of Twitch and god damn. Twitch is lucky.

## Repository organization
&nbsp;&nbsp;&nbsp;&nbsp;CNN <br>   	
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CNN.py &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*CNN model and its training* <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;cropping.py &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*function needed to crop the images using haar cascade* <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;data_loader.py &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*data augmentation and creation of the training/validation data* <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;mapping.py &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*creation of classes and mapping of face to ID* <br>
&nbsp;&nbsp;&nbsp;&nbsp;Dataset &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *original dataset* <br>
&nbsp;&nbsp;&nbsp;&nbsp;Filters <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;filters.py &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*functions needed in order to apply filters to an image* <br>
&nbsp;&nbsp;&nbsp;&nbsp;Prediction <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;InPrediction.py &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*functions needed in order to use a previously trained model to predict an input image* <br>
&nbsp;&nbsp;&nbsp;&nbsp;Utilites <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;haarcascade_eye.xml <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;haarcascade_frontalface_default.xml <br>
&nbsp;&nbsp;&nbsp;&nbsp;README.md <br>

## Team members
[Mocanu Alecsandru](https://github.com/ReaLight02) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Ene Alexandru](https://github.com/ScherzoNo) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Frau Antonio](https://github.com/ShinobuSmile) <br>
