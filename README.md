/~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\
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
• **Mouse Button 4** → Cycles forward through operator profiles
• **Mouse Button 5** → Cycles Backwords through operator profiles
• **CapsLock (Toggle)** → When ON, disables recoil script 
(acts as a safety switch)

🧩 HOW TO EDIT OR ADD RECOIL PATTERNS:
Inside the script, each operator mode is defined like this:

        {
        name = "three",
        stages = {
            {strength = 0, horizontal = 0, duration = 100},
            {strength = 0, horizontal = 0, duration = 100},
            {strength = 0, horizontal = 0, duration = 100},
        }
    },

Paste right below the }, and dont edit anything else it will add the new preset make sure it doesnt have the same name as the last profile it will make it harder to read and understand

Disclaimer
This tool is only for testing and academic purposes and can only be used where strict consent has been given. Do not use it for illegal purposes! It is the end user’s responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this tool and software in general.
