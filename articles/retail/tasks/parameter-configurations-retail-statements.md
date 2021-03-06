--- 
# required metadata 
 
title: Configure Retail parameters that affect retail statements
description: This topic demonstrates configurations for Retail parameters that affect how Retail statements get created and posted. 
author: josaw1
manager: AnnBe 
ms.date: 08/01/2019
ms.topic: business-process 
ms.prod:  
ms.service: dynamics-ax-applications 
ms.technology:  
 
# optional metadata 
 
ms.search.form: RetailParameters   
audience: Application User 
# ms.devlang:  
ms.reviewer: josaw
ms.search.scope: Core, Operations 
# ms.tgt_pltfrm:  
# ms.custom:  
ms.search.region: Global
ms.search.industry: Retail
ms.author: josaw
ms.search.validFrom: 2016-06-30 
ms.dyn365.ops.version: Version 7.0.0 
---
# Configure Retail parameters that affect retail statements

[!include[task guide banner](../includes/task-guide-banner.md)]

This topic demonstrates configurations for Retail parameters that affect how Retail statements get created and posted. This procedure uses the USRT demo company.

1. In the navigation pane, go to **Modules > Retail and commerce > Headquarters setup  > Parameters > Retail parameters**.
2. Select the **Posting** tab.
    - Select **Yes** if you want to post the periodic discount amounts specifically.  
    - Select **Standard** to use default accounts, or select **Periodic** if you want to define which account to use for each periodic discount.  
      - Select **Summary** if inventory lines should get aggregated whenever possible.  
      - Select **Yes** if Invoices and Payments should get automatically settled as part of the Statement posting process.  
      - Select **Yes** if Safe drop transactions should get aggregated.  
      - Select **Yes** if Bank drop transactions should get aggregated.  
      - Select **Yes** to turn aggregation on for Statement posting.  
      - Select **Yes** to create and process orders in parallel when statements are posted.  
      - Enter the maximum orders to be processed in each batch job task.  
3. Select **Save**.

