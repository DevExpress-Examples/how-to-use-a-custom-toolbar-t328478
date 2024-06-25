<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128658677/21.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T328478)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/MainWindow.xaml))
<!-- default file list end -->
# How to: Use a Custom Toolbar


<p>In this example, we demonstrated how to replace the default ribbon/bar of the PDF Viewer with a custom toolbar. For this, the following approach is used.<br>1. Hide the toolbar/ribbon by setting the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfDocumentViewerDocumentViewerControl_CommandBarStyletopic">CommandBarStyle</a> property to <strong>None</strong>.<br>2. Create a custom toolbar (in this example, we used <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfBarsMainMenuControltopic">MainMenuControl</a>).<br>3. Bind items in the toolbar to PdfViewerControl <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfPdfViewerPdfViewerControlMembersTopicAll">commands</a> such as <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfDocumentViewerDocumentViewerControl_OpenDocumentCommandtopic">OpenDocumentCommand</a> and <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfDocumentViewerDocumentViewerControl_CloseDocumentCommandtopic">CloseDocumentCommand</a>.</p>

<br/>


<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=how-to-use-a-custom-toolbar-t328478&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=how-to-use-a-custom-toolbar-t328478&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
