**Description:**
Unlock the full potential of your FiveM server with our revolutionary script, the "Add-On Weapon Configuration Extractor." This powerful tool empowers server administrators to seamlessly integrate and configure add-on weapons with other scripts, such as recoil or customized weapon systems.

# Key Features:

**Universal Compatibility:**
The Add-On Weapon Configuration Extractor is designed to work with any add-on weapon, regardless of its source or origin. This versatility ensures that server administrators have the freedom to choose from a wide array of weapons and enhance their server's arsenal without limitations.

**Hash Code Extraction:**
With just a few simple commands, extract the hash code of any add-on weapon on your server. This vital information serves as the key to unlocking the potential for customization and configuration with other scripts, enabling administrators to fine-tune weapon behavior according to their server's unique requirements.

**Seamless Integration:**
Integrate the extracted hash codes effortlessly into recoil scripts or any other weapon-related scripts on your server. This seamless integration allows for a cohesive and immersive gaming experience, as weapon behaviors can be finely tuned to match the server's overall theme and gameplay dynamics.

**Dynamic Configuration Options:**
Empower administrators with the ability to configure various aspects of add-on weapons, such as recoil, fire rate, and damage. The dynamic configuration options provide unparalleled flexibility, allowing administrators to tailor the server's weapon systems to meet the preferences and balance requirements of their player community.

**Community-Driven Development:**
We value the input of the FiveM community. The Add-On Weapon Configuration Extractor is designed with adaptability in mind, and we actively encourage feedback from server administrators and script developers. This collaborative approach ensures that the script evolves in response to the diverse needs and creative ideas within the community.

Enhance the customization possibilities on your FiveM server by implementing the "Add-On Weapon Configuration Extractor." Elevate your server's weapon systems to new heights, offering players a tailored and immersive gameplay experience that sets your server apart.

Installation:
To change the add-on weapon hash code you want to extract, you have to change the following line:

    RegisterCommand('getgun', function(source, args, rawCommand)
        weapon = GetHashKey("WEAPON_M6IC") <-- Change WEAPON_M6IC with any other add-on weapon you want.
        print (weapon)
    end)
