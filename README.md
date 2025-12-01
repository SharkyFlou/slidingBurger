# Welcome to the Sliding Burger Game !

Developed by **Charly Flu**, **Paolo Hoogland** and **Tom Prieto**. This game is the result of our **object-oriented programming** and **information systems methodology** coursework.

Have fun !

# How to launch the game
## Windows 

Go to the directory ```WIN-SlidingBurgers-V1``` and launch **SlidingBurgers-V1.exe**
## MACOS
Go to the directory ```MACOS-SlidingBurgers-V1``` and lauch **SlidingBurgers-V1.app**

If there is a pop-up "SlidingBurgerV1" is damaged and cannot be opened. 


just open a terminal in the folder ```MACOS-SlidingBurgers-V1``` and execute the command ```xattr -rd com.apple.quarantine SlidingBurgerV1.app```


# How to play 

Sliding Burger is inspired by **Geometry Dash**, but with our own twists and original levels.


## Keys 

- **Jump :** Spacebar or left mouse click

## Sound effect & music 

You can adjust the music and sound effects volume from the Settings menu.
![Settings screenshot](images/settings.png)

## Play a level 
Once you click the **"Play"** button on the main menu, you can choose the level you want to play from the level selection screen.  
Pick any available level and get ready to jump!

![Level selection screen](images/level-selection.png)

## Special sprites 

In **Sliding Burger**, some special sprites change the way the game is played. These elements add variety and challenge as you progress through the levels.

Here are the main ones:
- ![Normal portal](images/portal-normal.png) The normal portal is the default portal. It allows you to jump and move normally.
- ![UFO portal](images/portal-UFO.png) The UFO portal allows you to jump  in the air.
- ![JET portal](images/portal-JET.png) The JET portal allows you to fly in the air like a plane.
- ![Gravity portal](images/portal-gravity.png) The gravity portal inverts the gravity. 
- ![Speed portal 1](images/portal-speed-1.png) The speed portal "I" set the speed to 1.
- ![Speed portal 2](images/portal-speed-2.png) The speed portal "II" set the speed to 2.
- ![Speed portal 3](images/portal-speed-3.png) The speed portal "III" set the speed to 3.
- ![Speed portal 4](images/portal-speed-4.png) The speed portal "IV" set the speed to 4.
- ![Speed portal 5](images/portal-speed-5.png) The speed portal "V" set the speed to 5.


## How to play

### Pan
You can see floating pan in the air. If you touch it, it'll throw you high in the air.
![Pan](images/pan_1.png)
![Pan 2](images/pan_2.png)

### Spike
You can see spikes on the ground. If you touch it, you'll die.
![Spike](images/spike_1.png)
![Spike 2](images/spike_2.png)

### Orb
Sometimes there are strange floating meat orbs. You can jump on them to double jump.
![Orb](images/orb_1.png)
![Orb 2](images/orb_2.png)
![Orb 3](images/orb_3.png)

### Portals

Mysterious portals are scattered throughout the levels. Going through them will give you special powers (more on that later). This one inverts the gravity, allowing you to slide on the ceiling.
![Portal](images/portal_exemple_1.png)
![Portal 2](images/portal_exemple_2.png)
![Portal 3](images/portal_exemple_3.png)

### Checkpoint
Floating packets are checkpoints. Touch them to save your progress. If you die, you'll respawn at the last checkpoint you touched.
![Checkpoint](images/checkpoint_1.png)
![Checkpoint 2](images/checkpoint_2.png)

### End
A man is waiting for is food, touch him to sacrfice yourself and finish the level.

![End](images/end_1.png)
![End 2](images/end_2.png)


### Tricky double jump

For hard levels, you might need to do a tricky double jump.
To do this, you need to jump and aim for the corner of a block while keeping the jump button pressed. This will allow you to jump again.

![Tricky double jump](images/double_jump_1.png)
![Tricky double jump 2](images/double_jump_2.png)
![Tricky double jump 3](images/double_jump_3.png)


## Map editor
**Sliding Burger** includes a built-in **map editor** that allows you to create and test your own custom levels.

![map editor](images/map-editor.png)

To access the map editor, click on the **Map Editor** button in the level selection screen. This will open the map editor interface, where you can create your own levels.

### Creating a level

To create a level, you can use the following tools:

- **Select**: Select an object to place in the level.
- **Delete**: Delete an object from the level.
- **Zoom**: Zoom in or out of the level.
- **Move**: Move the camera around the level.
- **Test**: Test the level you created.
- **Save**: Save the level you created.
- **Load**: Load a level you created.
- **Exit**: Exit the map editor.

The saved level will be then available in the level selection screen.

# Diagrammes 

## Diagramme d'état
![Diagramme état](diagrammes/diagramme-etat.png)

## Diagramme de cas d'utilisation 
![Diagramme de cas d'utilisation](diagrammes/diagramme-utilisation.png)


## Diagramme d'activité
![Diagramme d'activité](diagrammes/diagramme-activite-1.png)
![Diagramme d'activité](diagrammes/diagramme-activite-2.png)
![Diagramme d'activité](diagrammes/diagramme-activite-3.png)

## Diagramme de classe complet 
![Diagramme de classe](diagrammes/diagramme-classe-complet.png)
Note : Les classes possédant ```<<MonoBehavior>>``` héritent de MonoBehavior.

## Diagramme de classe centré sur le jeu et la map 
![Diagramme de classe](diagrammes/diagramme-classe-jeumap.png)

## Diagramme de classe centré sur l'audio et le menu 
![Diagramme de classe](diagrammes/diagramme-classe-audiomenu.png)

## Diagramme de classe centré sur le map editor 
![Diagramme de classe](diagrammes/diagramme-classe-mapeditor.png)

## Diagramme de GANT
![Diagramme de GANT](diagrammes/diagramme-gant.png)


# Licence
Ce projet est soumis à la licence MIT. Se référer au document suivant : [LICENCE](LICENSE).






