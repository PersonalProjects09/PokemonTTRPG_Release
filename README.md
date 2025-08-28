# Overview:
This application is an attack calculator and stat management tool created for use with the Pokemon Tabletop United TTRPG. 
# Copyright/Licensing
All rights to this app belong solely to it's creator, Alex Porter.  
Pokemon icon(s) used were created by Nikita Golubev and retrieved from https://www.flaticon.com/free-icons/pokemon.
# Download:
1. Download the application as a zipped folder by selecting Code -> Download Zip
   <img width="497" height="417" alt="image" src="https://github.com/user-attachments/assets/2fb38cc7-eee5-4cc0-a7b6-6e00884ff908" />
2. Unzip the folder and place it on your desktop or within another public folder (Do not place it in a restricted folder, as it will not be able to create necessary files)
3. When first launching the application, you will likely be prompted to download the .Net Desktop Runtime, which is an optional windows componenet required to run the app. You can either follow the instructions provided in the app or download the Runtime from here: https://dotnet.microsoft.com/en-us/download/dotnet/8.0
4. Once the app is running, you will be prompted to install Git if it is not already installed. You can either allow the app to direct you to the download page, or use this link: https://git-scm.com/downloads
# Automatic Updates:
This app uses Git for automatic updates. Every time the app is launched, it will check this repository for an updated version of the app. If one is found, you will be prompted to update. Accepting the update will cause the app to close and a .bat file will be launched to run the Git commands necessary for the update. 
# Usage:
<img width="1131" height="737" alt="image" src="https://github.com/user-attachments/assets/78ffca48-464e-4154-b181-a9d193460b25" />    

- Both sides (attacking and defending) have six loadout slots, with the currently selected slot being a darker red. The information entered into the textboxes will be saved when switching to a different loadout or when closing the app, as long as the entered values can be parsed as integers (whole, non-decimal numbers).
- You will be prompted if you want to continue the current opperation if the entered values cannot be parsed. This can be disabled in the config file (AppData/Config.txt), but be aware that disabling it may result in accidental data loss. Certian actions, such as calculating attack damage, will require parsable data even with the setting disabled.
- When calculating an attack, enter the attack damage base and Attack effectiveness, and then designate whether it is a special attack, benefits from STAB (Same Type Attack Bonus), or is a critical hit.
- Click the Roll button to roll the dice and then calculate the resulting damage. Once the damage has been calculated, you can click the Apply Attack Damage button to subtract the damage from the defending Pokemon's HP.
# Feedback and Suggestions:
Feedback and suggestions should be sent to asporter09@gmail.com.  
All bug reports must include a detailed description of what action(s) you performed, what the result was, and the result you expected in order to be addressed. Please also imclude any relevant error messages or screenshots.
