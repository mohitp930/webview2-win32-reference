---
description: This interface is a handler for the completion of the population of `imageStream`.
title: WebView2 Win32 C++ ICoreWebView2ExperimentalGetFaviconCompletedHandler
ms.date: 05/02/2022
keywords: IWebView2, IWebView2WebView, webview2, webview, win32 apps, win32, edge, ICoreWebView2, ICoreWebView2Controller, browser control, edge html, ICoreWebView2ExperimentalGetFaviconCompletedHandler
---

# interface ICoreWebView2ExperimentalGetFaviconCompletedHandler

[!INCLUDE [prerelease-note](../includes/prerelease-note.md)]

```
interface ICoreWebView2ExperimentalGetFaviconCompletedHandler
  : public IUnknown
```

This interface is a handler for the completion of the population of `imageStream`.

## Summary

 Members                        | Descriptions
--------------------------------|---------------------------------------------
[Invoke](#invoke) | Called to notify the favicon has been retrieved.

`errorCode` returns S_OK if the API succeeded. The image is returned in the `faviconStream` object. If there is no image then no data would be copied into the imageStream. For more details, see the `GetFavicon` API.

## Applies to

Product                         | Introduced
--------------------------------|---------------------------------------------
WebView2 Win32            |    N/A
WebView2 Win32 Prerelease |    1.0.1222

## Members

#### Invoke

Called to notify the favicon has been retrieved.

> public HRESULT [Invoke](#invoke)(HRESULT errorCode, IStream * faviconStream)

