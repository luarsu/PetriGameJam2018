# PetriGameJam2018
Petri is a that I developed along a friend for the Global Game Jam 2018 during one weekend at the Goldmishts, University of London event.

# About the game

When the game starts, you find yourself controlling a syringe in a petri dish where 3 virus with different genetic codes are starting to move and reproduce. The game is mainly based on the genes mechanic and the behaviours of the virus and the beacterias that you can create.

​

First of all, both virus and bacterias have a "genetic code" that is based on 3 values: R, G and B. The sum of these values always sum 100, and the colour of each virus or bacteria changes depending on these. When a virus and a bacteria collide, the RGB values of both of them are compared, and the one that has 2 out of the R, G and B values greater than the other will win and kill the other. For example:

​

       Bacteria            Virus

R        33         <        80         

G        40         >        13         

B        27         >         7         

 

In this case the bacteria has grater G and B values so it kills the virus     

​

On other hand, the virus moves randomly by applying to it random inpulses, and ach 3 seconds it "lays" an egg with its genetic code. If a virus touches one of this eggs, it generates another virus which genes are a mix of the two parents. 

​

Finally, the bacterias move randomly but if they perceive a virus close they follow it until they catch it. If a bacteria kills a virus, it duplicates itself.

​

Taking these mechanics into account, the player has to create bacterias by sucking with the syringe different proportions of red, green and blue genetic material and then release them in the petri dish in the hope that they will be effective and kill the virus. The idea is that, by looking at the colours of the viruses you can have an idea of which combination of RGB will be effective against them.

# How to play it

1.- Clone the repository
2.- Go to PetriGameJam2018\GOODExecutableVersion\WindowsNoEditor
3.- Execute PetriGameJam2018.exe
4.- Enjoy!

# Controls
- Move with the mouse
- Right click and hold as much as you want close to the red, blue or green glasses to absorb some genetic material for your bacteria
- Release bacterias with T

# Edit the game with Unreal
The repository contains the whole unreal project, so feel free to explore it and change it to see how we made it!
