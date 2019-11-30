# DocPawnOverhaul

**WIP**

The goal of this mod is to make pawns feel damage. I found inspiration in [VE-CO](https://ludeon.com/forums/index.php?topic=30799.0) to overhaul the Vanilla combat in a mod-friendly way. The way in which this mod handles that are through these features:
- Increase pain and bleeding rates to Human pawns from most damage types
- Pawns are less spongey and bleed out faster
- Pawns are less likely to lose digits
- Pawns are more likely to be shot in the torso
- Organs are critical wounds and more likely to be hit
- Medical aid will be more necessary in the field
- Bionics and Armor become far more important
- Completely save-friendly to add or remove as you wish


### Bloodloss Pain
- When pawns lose a lot of blood, they get a bloodloss hediff. These values associate pain at varying degrees of bloodloss.
- This is a percentage, so 0.1=10% pain.

| **Blood Loss** | **Vanilla** | **DPO** |
| ------------- | :-------------: | :-------------: |
| ------------- | ------------- | ------------- |
| Minor | - | 0.1 |
| Moderate | - | 0.25 |
| Severe | - | 0.35 |
| Extreme | - | 0.5 |

### Organ Bleedrate
- Organs will now bleed severely when they are damaged.
- This is a percentage, so 2=200% bleedrate.

| **Organ** | **Vanilla Bleedrate** | **DPO Bleedrate** |
| ------------- | :-------------: | :-------------: |
| ------------- | ------------- | ------------- |
| Lung | - | 2 |
| Kidney | - | 2 |
| Liver | - | 2 |
| Stomach | - | 2 |

### Body Part Coverage
- These edits will cause pawns to be mostly shot in the torso, which means more organ damage, which means more bleeding and pain, which means they're more likely to be incapacitated or die from bleeding out.
- Body parts in bold are the parent parts of those beneath them. Likewise, the dashes demonstrate levels of children.

| **Body Part** | **Vanilla Coverage** | **DPO Coverage** |
| ------------- | :-------------: | :-------------: |
| ------------- | ------------- | ------------- |
| **Torso** | 0.036 | 0.06 |
| -Sternum | 0.015 | 0.02 |
| -Pelvis | 0.025 | 0.03 |
| -Spine | 0.025 | - |
| -Stomach | 0.025 | 0.04 |
| -Heart | 0.020 | - |
| -Lung | 0.025 | 0.05 |
| -Kidney | 0.017 | 0.02 |
| -Liver | 0.025 | 0.04 |
| **Neck** | 0.075 | 0.03 |
| -Head | 0.80 | - |
| --Skull | 0.18 | - |
| ---Brain | 0.8 | - |
| --Eye | 0.07 | 0.05 |
| --Ear | 0.07 | 0.05 |
| --Nose | 0.10 | 0.07 |
| --Jaw | 0.15 | 0.1 |
| **Shoulder** | 0.12 | - |
| -Clavicle | 0.09 | - |
| -Arm | 0.77 | 0.3 |
| --Humerus | 0.1 | - |
| --Radius | 0.1 | - |
| --Hand | 0.14 | 0.07 |
| ---Finger | 0.06 | 0.01 |
| **Waist** | - | - |
| **Leg** | 0.14 | - |
| -Femur | 0.1 | - |
| -Tibia | 0.1 | - |
| -Foot | 0.1 | 0.07 |
| --Toe | 0.06 | 0.01 |
