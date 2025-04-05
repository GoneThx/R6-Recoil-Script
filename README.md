/-------------------------------------------------------\
        Recoil Control Script - Made by GoneThx           
          GitHub: https://github.com/GoneThx              
\_______________________________________________________/ 

📘 ABOUT THIS SCRIPT:
This script helps reduce weapon recoil by dynamically 
controlling mouse movement while shooting. It supports 
multiple operator-based weapon profiles and can be 
customized or expanded by anyone who wants to fine-tune 
their setup.

TERMS OF USE:
If you use my code or share it on any platform (like YouTube, 
blogs, or social media), please make sure to credit me. A 
simple mention of my name or a link back to the original 
source is all I ask. It helps support my work and lets 
others know where the code came from. Thanks!

💡 SCRIPT FEATURES:
• Dynamic recoil stages that change over time
• Operator-specific profiles (e.g., Ela, Ash, Twitch, etc.)
• Toggle-based safety to enable/disable recoil assistance
• Simple GUI-style logging to display selected mode
• Easy to expand and customize for other weapons or patterns

🛠️ HOW TO USE:
1. Install Logitech G Hub and assign this script to your mouse.
2. Make sure CapsLock is **OFF** to activate the recoil control.
3. Hold **Right Mouse Button (ADS)** and **Left Mouse Button 
(Fire)** at the same time to activate the recoil pattern.
4. Use the mouse buttons below to switch between profiles.

🎯 KEYBINDS:
• **Mouse Button 4** → Resets to DEFAULT recoil pattern
• **Mouse Button 5** → Cycles through operator profiles
• **CapsLock (Toggle)** → When ON, disables recoil script 
(acts as a safety switch)

🧩 HOW TO EDIT OR ADD RECOIL PATTERNS:
Inside the script, each operator mode is defined like this:

["MY-OPERATOR"] = {
    pattern = {
        { ms = 100, strength = 8.0, horizontal = 0.3 },
        { ms = 300, strength = 7.5, horizontal = 0.1 }
    }
}

aswell as in the

local RecoilModes = {
    "DEFAULT", "HIBANA", "ASH", "TWITCH", "ELA",
    "SPEAR", "SMG-12", "SMG-11", "556X1", "Unused"
}

add your new operator with the new , "[MY-OPERATOR]"

should show up automatically in the console issues 
with numbers in he name or special characters 
include adding ["123gun.43"] as an example 
