---
description: An event handler for the `ServerCertificateErrorDetected` event.
title: WebView2 Win32 C++ ICoreWebView2ServerCertificateErrorDetectedEventHandler
ms.date: 05/02/2022
keywords: IWebView2, IWebView2WebView, webview2, webview, win32 apps, win32, edge, ICoreWebView2, ICoreWebView2Controller, browser control, edge html, ICoreWebView2ServerCertificateErrorDetectedEventHandler
---

# interface ICoreWebView2ServerCertificateErrorDetectedEventHandler

```
interface ICoreWebView2ServerCertificateErrorDetectedEventHandler
  : public IUnknown
```

An event handler for the `ServerCertificateErrorDetected` event.

## Summary

 Members                        | Descriptions
--------------------------------|---------------------------------------------
[Invoke](#invoke) | Provides the event args for the corresponding event.

## Applies to

Product                         | Introduced
--------------------------------|---------------------------------------------
WebView2 Win32            |    N/A
WebView2 Win32 Prerelease |    

## Members

#### Invoke

Provides the event args for the corresponding event.

> public HRESULT [Invoke](#invoke)(ICoreWebView2 * sender, ICoreWebView2ServerCertificateErrorDetectedEventArgs * args)

