---
title: "Compiler Warning (level 1) C4109 | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-tools"]
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: ["C4109"]
dev_langs: ["C++"]
helpviewer_keywords: ["C4109"]
ms.assetid: 9e8d95c6-e05d-47e0-bd87-78974b3cc06c
caps.latest.revision: 6
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
ms.workload: ["cplusplus"]
---
# Compiler Warning (level 1) C4109
unexpected identifier 'identifier'  
  
 The pragma containing the unexpected identifier is ignored.  
  
## Example  
  
```  
// C4109.cpp  
// compile with: /W1 /LD  
#pragma init_seg( abc ) // C4109  
```