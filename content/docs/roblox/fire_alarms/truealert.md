---
date: "2024-06-13T12:35:55-07:00"
draft: false
title: TrueAlert
weight: 4
---

The **Simplex TrueAlert SmartSync** collection is PVC's first new collection in almost four years!

These alarms were tested with moneyLAB's RSA2000 system and should also be compatible with other systems based on that standard.

**IMPORTANT:**  With Release 25.02, these alarms now use CollectionService. As such, their scripts have been extensively restructured in a way that means that alarms no longer have individual scripts. All alarms are now controlled by the scripts in the "!Scripts_PVC_P10" folder. I recommend you place this folder to ServerScriptService, but because the alarms have no module calls – for which individual scripts are needed – this is by no means essential.

{{< cards >}}
    {{< card link="https://create.roblox.com/store/asset/13904668666/" title="Roblox Creator Store" icon="robloxstudio" >}}
    {{< card link="https://ko-fi.com/s/8417d72c37" title="Ko-fi Shop" icon="kofi" >}}
{{< /cards >}}

## Details
* **First release**: [23.07](#version-2307-4-july-2023) (4 July 2023)
* **Latest release**: [25.02a](#version-2502a-10-april-2025) (10 April 2025)

## Strobe intensities
| Strobe type       | Options         | Models |
| --------          | -------         | -------         | 
| Regular intensity | 15/30/75/110 cd | 9101, 9103, 9127, 9129, 9133, 9134, 9151, 9153 |
| High intensity    | 135/177/185 cd  | 9109, 9111, 9139, 9141 |
| Outdoor intensities (UL) | 15/60/75 cd | 9105, 9106, 9131, 9132 |
| Outdoor intensities (ULC) | 5/20/30 cd | 9113, 9143

## Contents
The pack contains 24 wall-mount devices.

{{< tabs items="Red, White">}}
{{< tab >}}
* **4901-9820** with **4905-9988 cover** – horn
* **4902-9210** – chime
* **4902-9716** – speaker
* **4906-9101** – strobe, regular intensity
* **4906-9105** – outdoor strobe, UL intensities
* **4906-9109** – strobe, high intensity
* **4906-9113** - outdoor strobe, ULC intensities
* **4906-9127** – combination horn/strobe, regular intensity
* **4906-9131** – outdoor combination horn/strobe, UL intensities
* **4906-9133** – chime/strobe, regular intensity
* **4906-9139** – combination horn/strobe, high intensity
* **4906-9143** – outdoor combination horn/strobe, ULC intensities 
* **4906-9151** – combination speaker/strobe, regular intensity
{{< /tab >}}
{{< tab >}}
* **4901-9820** with **4905-9989 cover** – horn
* **4902-9211** – chime
* **4902-9717** – speaker
* **4906-9103** – strobe, regular intensity
* **4906-9106** – outdoor strobe, UL intensities
* **4906-9111** – strobe, high intensity
* **4906-9129** – combination horn/strobe, regular intensity
* **4906-9132** – outdoor combination horn/strobe, UL intensities
* **4906-9134** – combination chime/strobe, regular intensity
* **4906-9141** – combination horn/strobe, high intensity
* **4906-9153** – combination speaker/strobe, regular intensity
{{< /tab >}}
{{< /tabs >}}

## Changelog
### Version 25.02a (10 April 2025)

{{% details title="Click me to reveal" closed="false" %}}

* Fixed issue where some alarms simply wouldn't work; this was traced back to improperly defined functions

{{% /details %}}

### Version 25.02 (1 February 2025)

{{% details title="Click me to reveal" closed="true" %}}

* Updated all models to use CollectionService. This will make things easier for you AND me!
* New attribute entitled "ContVisualCircuit" (boolean). Set to TRUE for strobe to flash continuously or FALSE for the strobe to flash if VisualCircuit is set to 1.
* 6 new models:
    * 4906-9105/-9106/-9113 weatherproof strobes
    * 4906-9131/-9132/-9143 weatherproof horn strobes

{{% /details %}}

### Version 24.12 (7 December 2024)

{{% details title="Click me to reveal" closed="true" %}}

* 2 new models: 4902-9210/-9211 chimes
* More detailed horn and speaker models. They should look better without ambient occlusion enabled... and maybe with, too.
* Upgraded all models to use Attributes (excl. 9820s)
* Label improvements! All models now feature make/model labels, and all labels now follow the curve of the alarms.
* Fixed an issue where strobes would only flash once with continuous visual circuits

{{% /details %}}

### Version 23.07 (4 July 2023)

{{% details title="Click me to reveal" closed="true" %}}

* First version released to the public.
* Happy fourth of July!

{{% /details %}}

## Known issues
* None