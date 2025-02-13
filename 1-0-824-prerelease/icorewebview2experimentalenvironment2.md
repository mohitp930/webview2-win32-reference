---
description: This interface is an extension of the ICoreWebView2Environment.
title: WebView2 Win32 C++ ICoreWebView2ExperimentalEnvironment2
author: MSEdgeTeam
ms.author: msedgedevrel
ms.date: 04/23/2021
ms.topic: reference
ms.prod: microsoft-edge
ms.technology: webview
keywords: IWebView2, IWebView2WebView, webview2, webview, win32 apps, win32, edge, ICoreWebView2, ICoreWebView2Controller, browser control, edge html, ICoreWebView2ExperimentalEnvironment2
---

# interface ICoreWebView2ExperimentalEnvironment2

[!INCLUDE [deprecation-note](../includes/deprecation-note.md)]

[!INCLUDE [prerelease-note](../includes/prerelease-note.md)]

```
interface ICoreWebView2ExperimentalEnvironment2
  : public IUnknown
```

This interface is an extension of the [ICoreWebView2Environment](icorewebview2environment.md).

## Summary

 Members                        | Descriptions
--------------------------------|---------------------------------------------
[GetProviderForHwnd](#getproviderforhwnd) | Returns the UI Automation Provider for the [ICoreWebView2CompositionController](icorewebview2compositioncontroller.md) that corresponds with the given HWND.

An object implementing the ICoreWebView2ExperimentalEnvironment2 interface will also implement [ICoreWebView2Environment](icorewebview2environment.md).

## Applies to

Product                         | Introduced
--------------------------------|---------------------------------------------
WebView2 Win32            |    N/A
WebView2 Win32 Prerelease |    1.0.790

## Members

#### GetProviderForHwnd

Returns the UI Automation Provider for the [ICoreWebView2CompositionController](icorewebview2compositioncontroller.md) that corresponds with the given HWND.

> public HRESULT [GetProviderForHwnd](#getproviderforhwnd)(HWND hwnd, IUnknown ** provider)

