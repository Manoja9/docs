---
title: "ICorDebugFrame::GetFunctionToken Method | Microsoft Docs"
ms.custom: ""
ms.date: "03/30/2017"
ms.prod: ".net-framework"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "dotnet-clr"
ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "ICorDebugFrame.GetFunctionToken"
apilocation: 
  - "mscordbi.dll"
apitype: "COM"
f1_keywords: 
  - "ICorDebugFrame::GetFunctionToken"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "ICorDebugFrame::GetFunctionToken method [.NET Framework debugging]"
  - "GetFunctionToken method [.NET Framework debugging]"
ms.assetid: a46925b3-3bf8-404f-9f30-a86ae41032c1
caps.latest.revision: 12
author: "rpetrusha"
ms.author: "ronpet"
manager: "wpickett"
---
# ICorDebugFrame::GetFunctionToken Method
Gets the metadata token for the function that contains the code associated with this stack frame.  
  
## Syntax  
  
```  
HRESULT GetFunctionToken (  
    [out] mdMethodDef        *pToken  
);  
```  
  
#### Parameters  
 `pToken`  
 [out] A pointer to an `mdMethodDef` token that references the metadata for the function.  
  
## Requirements  
 **Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).  
  
 **Header:** CorDebug.idl, CorDebug.h  
  
 **Library:** CorGuids.lib  
  
 **.NET Framework Versions:** [!INCLUDE[net_current_v10plus](../../../../includes/net-current-v10plus-md.md)]