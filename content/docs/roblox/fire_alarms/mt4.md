---
date: "2024-06-12T17:02:00-07:00"
draft: false
title: MT4
weight: 5
---

The **Wheelock MT4** collection is PVC's most recent, having first been released on 24 April 2024. The collection contains 5 devices. If you want to be more technical, it contains 7, as one device combines three models. 

These alarms were tested with moneyLAB's RSA2000 system and should also be compatible with other systems based on that standard.

**IMPORTANT:** With Release 25.08, these alarms now use CollectionService. As such, their scripts have been extensively restructured in a way that means that alarms no longer have individual scripts. All alarms are now controlled by the scripts in the "!Scripts_PVC_P11" folder. I recommend you place this folder to ServerScriptService, but because the alarms have no module calls – for which scripts are needed – this is by no means essential.

{{< cards >}}
    {{< card link="https://create.roblox.com/store/asset/17060055555/" title="Roblox Creator Store" icon="robloxstudio" >}}
    {{< card link="https://ko-fi.com/s/0657643245" title="Ko-fi Shop" icon="kofi" >}}
{{< /cards >}}

## Details
* **First release**: [24.04](#version-2404-24-april-2024) (24 April 2024)
* **Latest release**: [25.08](#version-2508-6-august-2025) (6 August 2025)

## Strobe intensities
| Strobe type       | Intensity       |
| --------          | -------         |
| WH, LS | 15 cd |
| MS     | 30 cd |
| IS     | 75 cd |

## Contents
A total of five wall-mount devices are included.
* **MT4-115-R** – red horn
* **MT4-115-S** – silver horn
* **MT4-115-WH-VFR** – red horn + white 15cd strobe with FIRE lettering
* **MT4-115-WH-VNS** – silver horn + white 15cd unlettered strobe
* **MT4-24-LS/MS/IS-VFR** – red horn + UL 1971-compliant 15/30/75cd strobe with FIRE lettering

## Changelog

### Version 25.08 (6 August 2025)

{{% details title="Click me to reveal" closed="false" %}}

* Tone logic closer to that of other alarms. No more BindableEvents!
* Updated all alarms to use CollectionService

{{% /details %}}


### Version 24.08 (4 August 2024)

{{% details title="Click me to reveal" closed="true" %}}

* Updated horn model

{{% /details %}}

### Version 24.05 (27 May 2024)

{{% details title="Click me to reveal" closed="true" %}}

* Added flashtube click SFX.
* Added MT4-24-LS/MS/IS-VFR.

{{% /details %}}

### Version 24.04 (24 April 2024)

{{% details title="Click me to reveal" closed="true" %}}

* First version to be released.

{{% /details %}}

## Known issues
* None