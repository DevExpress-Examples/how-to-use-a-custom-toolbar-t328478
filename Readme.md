<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/MainWindow.xaml))
<!-- default file list end -->
# How to: Use a Custom Toolbar


<p>In this example, we demonstrated how to replace the default ribbon/bar of the PDF Viewer with a custom toolbar. For this, the following approach is used.<br>1. Hide the toolbar/ribbon by setting the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfDocumentViewerDocumentViewerControl_CommandBarStyletopic">CommandBarStyle</a> property to <strong>None</strong>.<br>2. Create a custom toolbar (in this example, we used <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfBarsMainMenuControltopic">MainMenuControl</a>).<br>3. Bind items in the toolbar to PdfViewerControl <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfPdfViewerPdfViewerControlMembersTopicAll">commands</a> such as <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfDocumentViewerDocumentViewerControl_OpenDocumentCommandtopic">OpenDocumentCommand</a> and <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfDocumentViewerDocumentViewerControl_CloseDocumentCommandtopic">CloseDocumentCommand</a>.</p>

<br/>


