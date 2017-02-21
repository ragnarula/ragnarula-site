+++
Image = ""
Description = ""
date = "2017-02-19T00:54:39Z"
title = "GoButton"
banner_img = "/img/project/GoButton_banner.png"
Categories = []
Tags = ["Swift", "Arduino", "OSC"]
+++
QLab provides a simple software solution for arranging audio visual cues in a list that can be triggered manually or by timed interval. It is a popular choice in the theatre and events industries dues to its competitive pricing and daily rental model. It is designed to be operated by a dedicated technician during the running of a show.

The GoButton project provides a simple, robust hardware button to trigger the next cue in a QLab cue list. This makes it possible for actors to trigger their own audio and lighting cues, by using the button as a prop on the set as was recently demonstrated by Lost Watch Theatre Company in their productions Left My Desk at Cresent House and Flew the Coop (pictured above).

The hardware part of GoButton is made up of an Arduino Uno prototyping board with three foot switches attached to the digital input pins and is attached via USB to an Apple laptop.

The software part of GoButton is a custom Swift app which listens to messages from the Arduino sent via serial over USB and transmits them to QLab via OSC.
