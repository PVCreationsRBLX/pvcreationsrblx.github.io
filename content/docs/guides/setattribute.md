---
date: "2024-09-05T21:14:17-07:00"
draft: false
title: Setting an attribute
weight: 1
---

This guide shows you how to set an attribute for any Roblox instance. Beginning with PVC's [MT4 series](/docs/roblox/fire_alarms/mt4), this method has been adopted for changing alarm parameters such as tone and strobe intensity (some models only), instead of using the traditional method of havivng all parameters defined in a script. This allows developers to more easily make use of services like [CollectionService](https://create.roblox.com/docs/reference/engine/classes/CollectionService), if necessary, while maintaining individuality between multiple alarms.

## Prerequisites

You will need:
* Roblox Studio
    * Object Explorer panel
    * Properties panel

Already have these? Skip to the [main section](#setting-an-attribute).

## Assumptions
This guide assumes you are not enrolled in the [Next Generation Studio Preview beta](https://devforum.roblox.com/t/next-gen-studio-ui-preview-is-here-beta/3075390), but if you are, the instructions here should be mostly similar.


## Steps

{{% steps %}}

### Toggle the Object Explorer panel

On the ribbon, in the **View** group, click the **Explorer** button. Alternatively, you can press Alt+X (Windows) or Option+X (macOS).

### Toggle the Properties panel

On the ribbon, in the **View** group, click the **Properties** button.

### Setting an attribute

Select the desired instance in the viewport or the Object Explorer. The instance's properties appear in the Properties panel.
If necessary, scroll down to the **Attributes** section.
Set the desired attributes.

{{% /steps %}}