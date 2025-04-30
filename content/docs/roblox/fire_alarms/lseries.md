---
date: "2024-06-12T16:05:20-07:00"
draft: false
title: L-Series
weight: 3
---

![L-Series Main](/images/main_lseries.webp)

The **System Sensor L-Series** collection is PVC's most popular. It was first released in October 2019. The collection contains 58 devices.

These alarms were tested with moneyLAB's RSA2000 system and should also be compatible with other systems based on that standard.

**IMPORTANT:** With Release 25.04, these alarms now use CollectionService. As such, their scripts have been extensively restructured in a way that means that alarms no longer have individual scripts. All alarms are now controlled by the scripts in the "!Scripts_PVC_P03" folder. I recommend you place this folder to ServerScriptService, but because the alarms have no module calls – for which scripts are needed – this is by no means essential.
	
You should also remove tags from alarms that aren't part of a system to prevent an issue that, more often than not, prevents alarms that are actually part of a system from working correctly. The "Detagger" script handles this automatically.

{{< cards >}}
    {{< card link="https://create.roblox.com/store/asset/7031992297/" title="Roblox Creator Store" icon="robloxstudio" >}}
    {{< card link="https://ko-fi.com/s/af3470e12b" title="Ko-fi Shop" icon="kofi" >}}
{{< /cards >}}

## Details
* **First release** (overall): [Alpha 1](#alpha-1-25-october-2019) (25 October 2019)
* **First release** (PVC): [21.07](#version-2107-1-july-2021) (1 July 2021)
* **Latest release**: [25.04](#version-2504-30-april-2025) (30 April 2025)

## Contents
A total of 58 wall- and ceiling-mounted, indoor-rated alarm appliances are included, for both fire and general notification use.

### Fire

{{< tabs items="Red, White">}}
{{< tab >}}
* **P2RL** – full-width wall-mount combination horn/strobe with FIRE lettering
* **P2GRL** – single-gang wall-mount combination horn/strobe with FIRE lettering
* **PC2RL** – ceiling-mount combination horn/strobe with FIRE lettering
* **P2RL-LF** – full-width wall-mount combination 520 Hz sounder/strobe with FIRE lettering
* **SRL** – full-width wall-mount strobe with FIRE lettering
* **SGRL** – single-gang wall-mount strobe with FIRE lettering
* **SCRL** – ceiling-mount strobe with FIRE lettering
* **SPSRL** – wall-mount combination speaker/strobe with FIRE lettering
* **SPSCRL** – ceiling-mount combination speaker/strobe with FIRE lettering
{{< /tab >}}

{{< tab >}}
* **P2WL** – full-width wall-mount combination horn/strobe with FIRE lettering
* **P2GWL** – single-gang wall-mount combination horn/strobe with FIRE lettering
* **PC2WL** – ceiling-mount combination horn/strobe with FIRE lettering
* **P2WL-LF** – full-width wall-mount combination 520 Hz sounder/strobe with FIRE lettering
* **SWL** – full-width wall-mount strobe with FIRE lettering
* **SGWL** – single-gang wall-mount strobe with FIRE lettering
* **SCWL** – ceiling-mount strobe with FIRE lettering
* **SPSWL** – wall-mount combination speaker/strobe with FIRE lettering
* **SPSCWL** – ceiling-mount combination speaker/strobe with FIRE lettering
{{< /tab >}}
{{< /tabs >}}

### Fuego (Spanish)
{{< tabs items="Red, White">}}
{{< tab >}}
* **P2RL-SP** – full-width wall-mount combination horn/strobe with FUEGO lettering
* **P2GRL-SP** – single-gang wall-mount combination horn/strobe with FUEGO lettering
* **SRL-SP** – full-width wall-mount strobe with FUEGO lettering
* **SGRL-SP** – single-gang wall-mount strobe with FUEGO lettering
* **SPSRL-SP** – wall-mount combination speaker/strobe with FUEGO lettering
{{< /tab >}}

{{< tab >}}
* **P2WL-SP** – full-width wall-mount combination horn/strobe with FUEGO lettering
* **P2GWL-SP** – single-gang wall-mount combination horn/strobe with FUEGO lettering
* **SWL-SP** – full-width wall-mount strobe with FUEGO lettering
* **SGWL-SP** – single-gang wall-mount strobe with FUEGO lettering
* **SPSWL-SP** – wall-mount combination speaker/strobe with FUEGO lettering
{{< /tab >}}
{{< /tabs >}}

### Unmarked
The label parts weren't removed from these models, allowing you to easily add labels to them if you wish.

{{< tabs items="Red, White">}}
{{< tab >}}
* **CHRL** – full-width wall-mount chime
* **CHSRL** – full-width wall-mount combination chime/strobe
* **CHSCRL** – ceiling-mount combination chime/strobe
* **HRL** – full-width wall-mount horn
* **HGRL** – single-gang wall-mount horn
* **P2RL-P** – full-width wall-mount combination horn/strobe
* **PC2RL-P** – ceiling-mount combination horn/strobe
* **SRL-P** – full-width wall-mount strobe
* **SCRL-P** – ceiling-mount strobe
* **SPRL** – wall-mount speaker
* **SPSRL-P** – wall-mount combination speaker/strobe
* **SPSCRL-P** – ceiling mount combination speaker/strobe
{{< /tab >}}

{{< tab >}}
* **CHWL** – full-width wall-mount chime
* **CHSWL** – full-width wall-mount combination chime/strobe
* **CHSCWL** – ceiling-mount combination chime/strobe
* **HWL** – full-width wall-mount horn
* **HGWL** – single-gang wall-mount horn
* **P2WL-P** – full-width wall-mount combination horn/strobe
* **PC2WL-P** – ceiling-mount combination horn/strobe
* **SWL-P** – full-width wall-mount strobe
* **SCWL-P** – ceiling-mount strobe
* **SPWL** – wall-mount speaker
* **SPSWL-P** – wall-mount combination speaker/strobe
* **SPSCWL-P** – ceiling mount combination speaker/strobe
{{< /tab >}}
{{< /tabs >}}

### General notification

* **SWL-ALERT** – full-width wall-mount strobe with {{< colorbox background-color="#ffb00099" font-weight="bolder">}}amber{{< /colorbox >}} lens and ALERT lettering
* **SWL-CLR-ALERT** – full-width wall-mount strobe with clear lens and ALERT lettering
* **SCWL-CLR-ALERT** – ceiling-mount strobe with clear lens and ALERT lettering
* **SPSWL-ALERT** – wall-mount combination speaker/strobe with {{< colorbox background-color="#ffb00099" font-weight="bolder">}}amber{{< /colorbox >}} lens and ALERT lettering
* **SPSWL-CLR-ALERT** – wall-mount combination speaker/strobe with clear lens and ALERT lettering
* **SPSWL-CLR-ALERT** – ceiling-mount combination speaker/strobe with clear lens and ALERT lettering

## Changelog
### Version 25.04 (30 April 2025)

{{% details title="Click me to reveal" closed="false" %}}

* Upgraded all models to use CollectionService, Attributes, and tone/strobe intensity modules
* New tone samples, plus new Temporal 4 tone, for low-frequency models 

{{% /details %}}

### Version 24.07 (18 July 2024)

{{% details title="Click me to reveal" closed="true" %}}

* Fixed some model names

{{% /details %}}

### Version 24.07 (5 July 2024)

{{% details title="Click me to reveal" closed="true" %}}

* Adjusted label dimensions
* Fixed an issue where strobes would only flash once with continuous visual circuits
* Red labels brighter
* NEW alarms with Spanish FUEGO labels:
    * P2RL-SP, P2GRL-SP, SRL-SP, SGRL-SP, SPSRL-SP and their white counterparts

{{% /details %}}

### Version 24.01 (24 January 2024)

{{% details title="Click me to reveal" closed="true" %}}

* Updated strobes for wall-mounts. GOD those were awful
* Corrected some model names (backboxes for low-frequency models)

{{% /details %}}

### Version 21.12 (24 December 2021)

{{% details title="Click me to reveal" closed="true" %}}

* All instances of wait() replaced with task.wait()
* Tagged all appliances with release code; please preserve this!

{{% /details %}}

### Version 21.07 (1 July 2021)

{{% details title="Click me to reveal" closed="true" %}}

* Migrated to group ownership
* Strobe lights now emit from the front of the strobe part! They used to emit from the top for whatever reason…
* Fixed backbox name for PC2WL and SCWL — changed name to SBBCWL from SBBCRL
* NEW alarms:
    * P2RL-P, SPSRL-P, PC2RL-P, SPSCRL-P, CHSRL, CHRL, CHSCRL, and their white counterparts.
    * Six more that are reskins of pre-existing stuff: SCWL-CLR-ALERT, SPSCWL-CLR-ALERT, SPSWL-(CLR-)ALERT, SWL-(CLR-)-ALERT

{{% /details %}}

### Beta 0.2 (25 December 2020)

{{% details title="Click me to reveal" closed="true" %}}

* NEW alarms:
    * HRL-LF, HGRL-LF, and their white counterparts
	* P2RL-LF and its white counterpart
* The above appliances can be independently set to Temporal 3, but they work best if your panel is set to continuous. Using these should also help improve game performance.
* Fixed incorrect intensity settings for wall-mounts

{{% /details %}}

### Beta 0.15 (6 April 2020)

{{% details title="Click me to reveal" closed="true" %}}

* NEW alarms:
    * SPSCRL & SPSCWL

{{% /details %}}

### Beta 0.1 (17 March 2020)

{{% details title="Click me to reveal" closed="true" %}}

* Fixed issue with PC2RL having an extra part

{{% /details %}}


### Beta 0.1 (1 March 2020)

{{% details title="Click me to reveal" closed="true" %}}

* NEW alarms:
    * SPS & SP 
* 3100Hz tone for L-Series horns & horn/strobes. It's not the default setting, and I don't recommend using it.
* Labels for PC and SC are now derived from craigery96's SpectrAlert alarms.
* Outer ring for ceiling-mounts has been improved
* BillboardGuis for strobes are slightly offset forward

{{% /details %}}

### Alpha 2.1 (28 November 2019)

{{% details title="Click me to reveal" closed="true" %}}

* The last Alpha update and the last update for the L-Series of the year 2019. More variants will be added between January and April 2020.
* NEW alarms:
    * Ceiling mount horn/strobes and strobes. System Sensor does not produce L-Series (or SpectrAlert Advance) ceiling-mount horns.

{{% /details %}}

### Alpha 2 (25 November 2019)

{{% details title="Click me to reveal" closed="true" %}}

* NEW alarms:
    * P2G family (P2GRL & P2GWL) and their corresponding surface-mount backboxes - SBBGRL and SBBGWL!
    * H and HG family

{{% /details %}}

### Alpha 1.1 (26 October 2019)

{{% details title="Click me to reveal" closed="true" %}}

* Fixed horn sound not fading out

{{% /details %}}

### Alpha 1 (25 October 2019)

{{% details title="Click me to reveal" closed="true" %}}

* First version ever released to the public.
* 4 alarms are included in α 1. More will be included in α 2.

{{% /details %}}

## Known issues
* None