---
-api-id: M:Windows.Graphics.Printing.PrintTaskSourceRequestedArgs.SetSource(Windows.Graphics.Printing.IPrintDocumentSource)
-api-type: winrt method
---

<!-- Method syntax
public void SetSource(Windows.Graphics.Printing.IPrintDocumentSource source)
-->

# Windows.Graphics.Printing.PrintTaskSourceRequestedArgs.SetSource

## -description
Informs the print task of the content to be printed.

## -parameters
### -param source
A pointer to the **IPrintDocumentSource** interface.

## -remarks
Content source information for the print task can come from either HTML (via [MSApp.GetHtmlPrintDocumentSource](http://msdn.microsoft.com/library/windows/apps/hh831251.aspx)) or from XAML (via the XAML [PrintDocument.DocumentSource](http://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.printing.printdocument.documentsource.aspx)). Or you can create your own method to provide content source information to the print task. For information about how to create your own method, see the [Direct2D printing sample](http://code.msdn.microsoft.com/windowsapps/Direct2Dapp-printing-sample-9869f99c).

## -examples

## -see-also
[Direct2D printing sample](http://code.msdn.microsoft.com/windowsapps/Direct2Dapp-printing-sample-9869f99c), [IPrintDocumentSource](iprintdocumentsource.md), [MSApp.GetHtmlPrintDocumentSource](http://msdn.microsoft.com/library/windows/apps/hh831251.aspx), [PrintDocument.DocumentSource](http://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.printing.printdocument.documentsource.aspx)