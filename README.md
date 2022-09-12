# SecurityJukebox_v0.0
### an attempt to deliver an azure project on Microsoft Hackaton Sept/Oct 2022

Security Jukebox is supposed to be a smart and quick way to have a test and learning platform on Azure deployed easily through ARM or Biceps templates with a series of Security services based on your current IT environment. 

Anyone, even with zero Azure security skills, will be able to quickly build those environment through a Web GUI menu that will help you to select the pieces of your environment and behind the scenes will build to you two artifacts: 

1) a graphical diagram with an architecture that will contain your environment and Azure security services recommended to use

2) a biceps or ARM template that will be offered to you to simply deploy those recommended Azure security service on top of a basic Azure environment that mimic your current environment, so you will be able to use that environment to test and learn

This web interface will be designed so simple as a jukebox works with a menu of IT pieces that you will select, and after complete this selection, with a push of button, it will offer to you an architecture diagram with the pieces you select PLUS some Azure security services recommended to use with it

Additionally, it will be created behind the scenes an ARM template or Biceps to implement that environment on Azure.

