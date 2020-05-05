---
title: Train and publish your custom entity extraction AI model -  AI Builder | Microsoft Docs
description: Provides steps to train and publish your custom entity extraction AI model in AI Builder.
author: mfotedar
manager: kvivek
ms.service: powerapps
ms.topic: conceptual
ms.custom: 
ms.date: 04/08/2020
ms.author: mfotedar
ms.reviewer: v-dehaas
---

# Train and publish your custom entity extraction AI model 

[!INCLUDE[cc-beta-prerelease-disclaimer](./includes/cc-beta-prerelease-disclaimer.md)]

After you create your entity extraction model, you can train and publish it to make it available.

## Train and validate your model

1. After you create your model, select **Next** to check your selected entities. If everything looks good, select **Train** to train your model.
1. When training completes, select **Go to Details page** in the **Training complete** screen.

## Quick test your model

The **Details** page allows you to test your model before you publish or use it:

1. On the **Details** page, you can enter the text you want to test.
1. The quick test should only take a few seconds before displaying the results.

## Publish your model

If you're happy with your model, you can select **Publish** to publish it. When publishing completes, your model is promoted as published and is ready to be used. For more information about publishing your model, see [Publish your model](publish-model.md).

After you've published your model, you can use it in a Power Apps canvas app or in Power Automate.

## Edit your model
 You can create a new version of your published model by clicking on **Edit model** on the model details page. You can create new entity types and modify existing entity types.

### Related content

[Feature availability by region](availability-region.md)