---
UID: NF:commctrl.TreeView_GetFirstVisible
title: TreeView_GetFirstVisible macro (commctrl.h)
description: Retrieves the first visible item in a tree-view control window. You can use this macro, or you can explicitly send the TVM_GETNEXTITEM message with the TVGN_FIRSTVISIBLE flag.
helpviewer_keywords: ["TreeView_GetFirstVisible","TreeView_GetFirstVisible macro [Windows Controls]","_win32_TreeView_GetFirstVisible","_win32_TreeView_GetFirstVisible_cpp","commctrl/TreeView_GetFirstVisible","controls.TreeView_GetFirstVisible","controls._win32_TreeView_GetFirstVisible"]
old-location: controls\TreeView_GetFirstVisible.htm
tech.root: Controls
ms.assetid: VS|Controls|~\controls\treeview\macros\treeview_getfirstvisible.htm
ms.date: 12/05/2018
ms.keywords: TreeView_GetFirstVisible, TreeView_GetFirstVisible macro [Windows Controls], _win32_TreeView_GetFirstVisible, _win32_TreeView_GetFirstVisible_cpp, commctrl/TreeView_GetFirstVisible, controls.TreeView_GetFirstVisible, controls._win32_TreeView_GetFirstVisible
req.header: commctrl.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - TreeView_GetFirstVisible
 - commctrl/TreeView_GetFirstVisible
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - Commctrl.h
api_name:
 - TreeView_GetFirstVisible
---

# TreeView_GetFirstVisible macro


## -description

Retrieves the first visible item in a tree-view control window. You can use this macro, or you can explicitly send the <a href="https://docs.microsoft.com/windows/desktop/Controls/tvm-getnextitem">TVM_GETNEXTITEM</a> message with the TVGN_FIRSTVISIBLE flag.

## -parameters

### -param hwnd

Type: <b><a href="https://docs.microsoft.com/windows/desktop/WinProg/windows-data-types">HWND</a></b>

Handle to the tree-view control.

## -see-also

<b>Reference</b>



<a href="https://docs.microsoft.com/windows/desktop/Controls/tvm-getitemrect">TVM_GETITEMRECT</a>



<a href="https://docs.microsoft.com/windows/desktop/api/commctrl/nf-commctrl-treeview_getlastvisible">TreeView_GetLastVisible</a>



<a href="https://docs.microsoft.com/windows/desktop/api/commctrl/nf-commctrl-treeview_getnextvisible">TreeView_GetNextVisible</a>



<a href="https://docs.microsoft.com/windows/desktop/api/commctrl/nf-commctrl-treeview_getprevvisible">TreeView_GetPrevVisible</a>

