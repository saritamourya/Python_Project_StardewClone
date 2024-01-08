
# Stardew Valley Clone

This is a desktop game, which is similar to the famous game "Stardew Valley".  
You play a farmer who needs to grow crops and expand their fields. You make money by selling your products, to improve your home or buy new crops or materials.  
There are a day-and-night cycle, different types of weather, different crops harvestable resources, and a merchant.  
Contrary to the original game, you don't have a mine with monsters and minerals, no village with NPCs, no fishing. This is a simplified game.   

# Installation (for Windows)

## Install python (if you dont have python 3.11.7. You need an internet connection)

### 64-bit
- Open the Powershell and execute '**Invoke-WebRequest -Uri https://www.python.org/ftp/python/3.11.7/python-3.11.7-amd64.exe -OutFile python-3.11.7-amd64.msi**' to download the python 3.11.7 installer (or click directly on the link)
- Execute '**Join-Path -Path $pwd -ChildPath "python-3.11.7-amd64.msi"**' to find the path to the installer. Copy the path.
- Go to the path in your file browser. Open a Command line in administrator mode and execute '**msiexec /i python-3.11.7-amd64.msi /qn ADDLOCAL=ALL**' (or double-click on the .msi file) 
- Verify the installation by executing '**python --version**' 

### 32-bit
- Open the Powershell and execute '**Invoke-WebRequest -Uri https://www.python.org/ftp/python/3.11.7/python-3.11.7-amd32.exe -OutFile python-3.11.7-amd32.msi**' to download the python 3.11.7 installer (or click directly on the link)
- Execute '**Join-Path -Path $pwd -ChildPath "python-3.11.7-amd32.msi"**' to find the path to the installer. Copy the path.
- Go to the path in your file browser. Open a Command line in administrator mode and execute '**msiexec /i python-3.11.7-amd32.msi /qn ADDLOCAL=ALL**' (or double-click on the .msi file)
- Verify the installation by executing '**python --version**' 

## Install Pygame
- In the Command line, execute '**pip install pygame**' and '**pip install pytmx**'

## Download and launch the game
- On the project page, click on the green button **Download** then click on **Download ZIP**.  
- In you file browser, un-zip the folder using your prefered method.  
- Navigate to the directory where the Python script **main.py** is located  
- Open a *Terminal* or *Command Prompt*
- Execute the script by typing '**python main.py**' in the Command prompt/Terminal.  
- You can now play!

# Gaming info
Here is all you need to know to play this game
## Keys
Move the character: Arrows   
Use tool: *Space*   
Change tool: *Q*  
Plant seed: left *Ctrl*   
Change seed: *E*  
Open merchant menu: *Enter* , next to the merchant  
Select items in merchant menu: Arrows  
Sell and buy from merchant: *Space*  
Exit merchant menu: *Escape*  
Sleep: *Enter*   
Show game menu: *Escape*
## Tools
You have different tools:
- a watering can to water crops
- a hoe to prepare the soil for planting crops
- an axe to cut down trees for wood
## Crops
You can grow corn and tomatoes, and harvest apples and mushrooms in the wild.  
You need to use the hoe on a the soil to be able to plant seeds.  
Rain waters all the crops.  
If you don't water your crops, everyday they won't grow.
## Selling
There is a merchant to whom you can sell your crops and foraged items, and you can buy seeds.  
See **Keys** to know how to interact with the merchant.

# Authors
Sarita Mourya & Camille Auchère 

# Acknowledgment
Thank you to *Clear Code* Youtube tutorials 

# Assets credits
*Sprout Lands* asset pack by Cup Nooble (free version licence)

# Languages and libraries
Python (3.11.7)  
*Pygame* library
