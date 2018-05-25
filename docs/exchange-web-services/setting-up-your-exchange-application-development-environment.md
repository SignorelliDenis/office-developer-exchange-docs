---
title: "Setting up your Exchange application development environment"
 
 
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
 
 
localization_priority: Normal
ms.assetid: 91b86e93-bdde-41c3-9680-45cf61420592
description: "Learn about how to set up your development environment to create an EWS application that communicates with Exchange."
---

# Setting up your Exchange application development environment

Learn about how to set up your development environment to create an EWS application that communicates with Exchange.
  
Before you start writing your Exchange Web Services (EWS) application, you'll need to make sure that your development environment meets a few minimum requirements. You can use the EWS Managed API, the standard client access API for .NET Framework applications, to develop your application, or you can use EWS on its own, with our without an autogenerated proxy. In general, we recommend that you use the EWS Managed API; however, you can [explore the difference between these two options](ews-client-design-overview-for-exchange.md) in more detail to find out which one is right for you. 
  
> [!NOTE]
>  The EWS Managed API is now available as an open source project on [GitHub](https://github.com/officedev/ews-managed-api). You can use the open source library to: >  Contribute bug fixes and enhancements to the API. >  Get fixes and enhancements before they are available in an official release. >  Access the most comprehensive and up-to-date implementation of the API, to use as a reference or to create new libraries on new platforms. >  We welcome your [contributions](https://github.com/OfficeDev/ews-managed-api/blob/master/CONTRIBUTING.md) via GitHub. 
  
## Development environment for the EWS Managed API
<a name="bk_EWSMA"> </a>

To create an EWS Managed API application, you'll need access to the following:
  
- The [EWS Managed API](http://aka.ms/ews-managed-api-readme). 
    
    You can store the EWS Managed API files anywhere on your computer; by default, they are installed in the Program Files\Microsoft\Exchange\Web Services\\<version number\> folder.
    
- A mailbox on an Exchange server that is running Exchange Online, Exchange Online as part of Office 365, or a version of Exchange starting with Exchange Server 2007. 
    
    You can get an Exchange Online plan for business, including a free trial, from the [Office 365 site](http://office.microsoft.com/en-us/business/compare-office-365-for-business-plans-FX102918419.aspx#fbid=1tsGNIE7e3a). In order to connect to the mailbox you must have the user name and credentials of the account associated with the mailbox.
    
- A version of Visual Studio starting with Visual Studio 2005. If you don't currently have Visual Studio, you can download a free version of [Visual Studio 2010 Express](http://www.microsoft.com/visualstudio/eng/products/visual-studio-2010-express).
    
- A version of the .NET Framework starting with the .NET Framework 3.5. You can download the .NET Framework 3.5 from the [Microsoft Download Center](http://go.microsoft.com/fwlink/?LinkId=191777).
    
In addition, it is helpful if you have some familiarity with C#. Although Visual Studio supports other languages in addition to C#, most of the sample code available for the EWS Managed API is written in C#.
  
## Development environment for EWS
<a name="bk_EWS"> </a>

You can use EWS to develop your application in a couple of different ways. The simplest way to use EWS is to create text files that contain your XML requests, and transmit them to Exchange. To do this, here is what you need: 
  
- A simple text editor, like Notepad, to edit your XML request. Any text editor will do, although you might want one that will help with your XML syntax validation like XMetal.
    
- A tool or application that can send and receive SOAP XML requests and responses, in order to communicate with Exchange.
    
When you work with raw XML, it's also helpful to have a basic understanding of XML formatting.
  
The second way to use EWS is to create an autogenerated proxy that enables you to work with the operations by using a .NET language like C#. Here is what you need to work with an autogenerated proxy:
  
- A version of Visual Studio starting with Visual Studio 2005, to create a proxy reference. You can download a free version of [Visual Studio 2010 Express](http://www.microsoft.com/visualstudio/eng/products/visual-studio-2010-express).
    
- A version of the .NET Framework starting with the .NET Framework 2.0. You can download the .NET Framework 3.5 from the [Microsoft Download Center](http://go.microsoft.com/fwlink/?LinkId=191777).
    
If you use an autogenerated proxy, you'll want to have some familiarity with C# programming.
  
> [!NOTE]
> If you're a .NET Framework developer, we encourage you to use the EWS Managed API rather than autogenerated proxies to develop against EWS. The EWS Managed API object model is easier to use than autogenerated proxy object models. Also, the EWS Managed API implements [Autodiscover](autodiscover-for-exchange.md) and includes client-side logic. 
  
## See also


- [Setting up your Exchange application development environment](setting-up-your-exchange-application-development-environment.md)
    
- [EWS client design overview for Exchange](ews-client-design-overview-for-exchange.md)
    
- [Control access to EWS in Exchange](how-to-control-access-to-ews-in-exchange.md)
    
- [EWS generated object models for Exchange](https://msdn.microsoft.com/en-us/library/jj190899)
    
