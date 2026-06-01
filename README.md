# Mood-Display
## A Round Pin badge display! Powered by an Integrated ESP32-S3-WROOM-1 and a 1.28 in round display MoodBadge clips easily to your ID lanyard, keychain, belt, Bag, and so many more. You can easily express your mood or any animations you want to play on the display!

> Hiya! This project is still in its designing stage! When i build it, I will make a step by step video how to assemble 

<img src = "Main/Zine/Mooddisplay Zine.png">

> PDF is available in Zine folder!

### I made this project because i was inspired by those mini circular displays that you can bring anywhere! 
### This exsist since i wanted a badge that i can interact with.
### This project is pretty easy to do, All you need to do is follow the tutorial (Scoll down)

## Schematic
<img width="1164" height="656" alt="image" src="https://github.com/user-attachments/assets/085512ab-89a7-46d8-b458-bb92335da158" />

> for a much better image check the pdf in extras!

## PCB
<img width="520" height="474" alt="image" src="https://github.com/user-attachments/assets/ff51f18b-43ec-4078-8ea7-efe8398f820e" />

## PCB Render
- back
<img width="705" height="560" alt="image" src="https://github.com/user-attachments/assets/d2837197-6594-422b-b6f4-651c64477f2b" />

- Front
<img width="705" height="560" alt="image" src="https://github.com/user-attachments/assets/33190993-d27c-400f-bd45-9431f358e983" />

## Cad
- Onshape link:https://cad.onshape.com/documents/fe18899c0fc823d496ae247b/w/1ef647bd25a6a14e89f050fb/e/3a17c80e85047fb88fb13b3e?renderMode=0&uiState=6a0dad73ebc90dae0eac1fbd

> I love Onshape Man

<img width="870" height="283" alt="image" src="https://github.com/user-attachments/assets/36ff0a0e-4fc7-4a91-86a2-406f5e9618ff" />
<img width="549" height="528" alt="image" src="https://github.com/user-attachments/assets/f49427e2-ff62-43da-8c27-2183ec5aa755" />
<img width="541" height="461" alt="image" src="https://github.com/user-attachments/assets/74840a17-c0a8-4be2-b50b-27c1ef1dca60" />

## How to Build it 
- 1st step: Get the Requied materials in BOM.CSV and get the Gerber file in the folder production.
- 2nd Step: Pay JLC PCB to Fabricate the PCB and Use the links in the BOM.CSV to order parts
> You should def order a stencil! But for this tutorial i will be doing it manualy

- 3rd Step: Get your solder paste then manualy little solder to each pad that needs a connection. Also have a tissue nearby!
> Remember Patience is better than Crashing Out!

- 4th step: Start placing the compoments then when you are ready, use a hot plate to reflow all of the connections!
> For this part you would be Placing compoments at the back of the pcb so that means the front side of the pcb is facing flat on the hotplate
> When reflowing feel free to gently adjust the possiton of the compoments!

- 5th step: Now you have the backside of the pcb done! After letting the PCB rest now flip it to the other side, you should see some pads there. You are going to use a normal soldering iron to solder the buttons and other DIP compoments like the power Headers!

- 6th Step: Congradulations! You are done with the PCB!! Now kindly please test it by powering it on with a type C cable (please make sure it gets enough power to boot). Flash the test firmware i have provided it should light up the leds!

- if you like the bare PCB you can now stop here and use any of the mounting holes to attach the Mood-Display with anything!

- After this it would be Optional to do the case!

- 7th Step: Print all of the Case Parts then start assembling it by starting with the bottom. With the Bottom place the pcb on top and it line up with the mounting holes! When it is fully alligned screw the holes! Now get your assembles Bottom Case and carefully insert it up to the "middle case part" then super glue it! Now place and glue the Top Cover!
> i have used the terms "bottom case" "Middle Part" "Top Cover" why? because i have provided three parts in the CAD. 

- Final Step: There is no final step Lmao. Enjoy your own Mood display!
