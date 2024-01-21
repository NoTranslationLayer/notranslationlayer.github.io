---
layout: page
title: Creating Reflection Templates
permalink: /reflect/tutorials/creating-reflections
---

A **Reflection Form** is a type of form that allows you to conveniently and regularly record metrics you'd like to track. You can create or modify the metrics and settings for a **Reflection Form** by editing the associated **Reflection Template**.

## Start a New Reflection Template

1. In the top right of the **Reflect** page, press the ![doc.badge.plus](/assets/icons/doc.badge.plus-1.png) button to open up the template creation page.

<img src="/assets/creating-reflections-screenshots/IMG_0992.PNG" alt="Template Creation Page" style="width: 50%; height: 50%; margin: 0 auto; display: block; padding: 10px">

## Give your Reflection Template a Name

**Reflection Template** names must be unique.

<img src="/assets/creating-reflections-screenshots/IMG_1007.PNG" alt="Naming Reflection" style="width: 50%; height: 50%; margin: 0 auto; display: block; padding: 10px">

## Set Reflection Template Settings

The rest of the settings in this section are all optional.

### Default Metric Type

You may record durations, ratings, yes/no responses, numbers, text, numbers with units, or selecting from a list of choices. Here you choose the type of metric to default to when adding a new metric to your **Reflection Template**.

<img src="/assets/creating-reflections-screenshots/IMG_0994.PNG" alt="Default Metric Type" style="width: 50%; height: 50%; margin: 0 auto; display: block; padding: 10px">

### Daily Reflection

This setting affects data analysis because it tells the analysis to expect exactly one recording of this Reflection per day. If you miss this sort of Reflection on a particular day, there will be a yellow calendar indicator next to the Reflection name on the **Reflect** page the next day. There will also be a popup when you open the Reflection giving you the option to fill out your data for the missed day.

<img src="/assets/creating-reflections-screenshots/IMG_0995.PNG" alt="Daily Reflection" style="width: 50%; height: 50%; margin: 0 auto; display: block; padding: 10px">

### Allow Ad-Hoc Metrics

Ad-hoc metrics are ones you can record on-the-fly without having them as part of your **Reflection Template**. They're useful for unplanned recordings that aren't very common.

<img src="/assets/creating-reflections-screenshots/IMG_0997.PNG" alt="Ad-hoc Metrics" style="width: 50%; height: 50%; margin: 0 auto; display: block; padding: 10px">

### Stay in Form After Saving

Sometimes you may want to record multiple instances of a Reflection back-to-back without having to navigate to the **Reflection Form** each time. Toggling this option on will allow the **Reflection Form** to remain on your screen once you save your metrics' recordings.

<img src="/assets/creating-reflections-screenshots/IMG_0998.PNG" alt="Stay in Form After Saving" style="width: 50%; height: 50%; margin: 0 auto; display: block; padding: 10px">

### Copy Reflection After Saving

If your metric values are almost always the same, copying the values from the last Reflection can save you time.

<img src="/assets/creating-reflections-screenshots/IMG_0999.PNG" alt="Copy Reflection After Saving" style="width: 50%; height: 50%; margin: 0 auto; display: block; padding: 10px">

## Set Analysis Settings

### Default Aggregate type

<img src="/assets/creating-reflections-screenshots/IMG_1002.PNG" alt="Default Aggregate Type" style="width: 50%; height: 50%; margin: 0 auto; display: block; padding: 10px">

This setting determines how multiple recordings over the course of a day get evaluated in data analysis that spans multiple days. The options are taking the sum, the min, the max, or the average (mean) of all recordings. For example, you may want to analyze how the sum of your coffee consumption affects your average tiredness score for the last week. This setting is just the default for metrics in this Reflection. When you start to add metrics, this setting can be overridden.

### Treat Empty Values As Zero

Filling out your metrics in a given Reflection can be optional. When toggled **ON** this setting applies default value treatment to metrics that are not filled out in a Reflection that has been recorded. For example, if you fill out that you had 1000 mg of Vitamin C in your **Supplements** Reflection but didn't fill out a value for Vitamin D (mcg), toggling this setting on will result in analysis and plots that assume you had 0 mcg Vitamin D for that Reflection. This setting is just the default for metrics in this Reflection. When you start to add metrics, this setting can be overridden.

<img src="/assets/creating-reflections-screenshots/IMG_1003.PNG" alt="Treat Empty Values As Zero" style="width: 50%; height: 50%; margin: 0 auto; display: block; padding: 10px">

### Treat Empty Days As Zero

Sometimes you have metrics that you only record occasionally, and you only want to record them when they occur. For example, suppose you track a Yes/No **Party** metric and a 0-4 Rating **Extrovert** metric as part of your "Social" Reflection. When this setting is toggled **ON** and you don't fill out the **Social** Reflection on a given day, it will be as if you had recorded "No" for **Party** and "0" for **Extroverted** on that day. When you start to add metrics, this setting can be overridden.

<img src="/assets/creating-reflections-screenshots/IMG_1004.PNG" alt="Treat Empty Days As Zero" style="width: 50%; height: 50%; margin: 0 auto; display: block; padding: 10px">

### Exempt From Data Analysis

Some metrics are useful to track but you don't want them informing any causal inference, correlations, or other form of analysis. Toggling this setting **ON** accomplishes this. All analysis is private and remains on your device, so this feature adds another layer of privacy and convenience by preventing sensitive metrics from appearing in your analysis results. This setting is just the default for metrics in this Reflection. When you start to add metrics, this setting can be overridden.

<img src="/assets/creating-reflections-screenshots/IMG_1004.PNG" alt="Exempt From Data Analysis" style="width: 50%; height: 50%; margin: 0 auto; display: block; padding: 10px">

## Adding a Metric to Your Reflection Template

The settings for individual metrics are very similar to the **Reflection Template** settings. Specifying a different value of a setting in the metric template will override that same setting in the Reflection template. For example, if in your **Social** Reflection you exempt all metrics from data analysis but have this setting toggled off for **Extroverted**, then Extroverted will be incorporated into data analysis. Otherwise, there are metric-specific template settings such as:

### Required

Toggling **Required** to **ON** will make it so that you cannot successfully save a Reflection without recording this metric type. If Required is **OFF** and you do not fill out a metric, its value will be empty.

### Group

Assigning a group to your metric does nothing more than allow your Reflection to categorize it in a way that saves screen space by placing it in a dropdown group with other metrics belonging to the same group.

<img src="/assets/creating-reflections-screenshots/IMG_3CD47B259E41-1.jpeg" alt="Metric Group" style="width: 50%; height: 50%; margin: 0 auto; display: block; padding: 10px">

## Finishing Up

You may save a metric to a Reflection by pressing ![checkmark.circle](/assets/icons/checkmark.circle.png) at the top right of your screen. If the checkmark is disabled, it means you need to finalize some aspect of the metric, such as its name. Once saved, you may continue to add as many metrics as you'd like to a Reflection. When finished adding your metrics, you may save the Reflection by pressing ![checkmark.circle](/assets/icons/checkmark.circle.png) at the top right of your screen again.