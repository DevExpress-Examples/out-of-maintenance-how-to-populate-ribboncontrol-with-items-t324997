<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128655662/21.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T324997)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/MainWindow.xaml))
<!-- default file list end -->
# How to: Populate RibbonControl with Items


The RibbonControl supports all bar item types from the DXBars Suite. Additionally, the DXRibbon Suite includes items that can be used only in RibbonControl - <a href="https://documentation.devexpress.com/WPF/clsDevExpressXpfRibbonBarButtonGrouptopic.aspx">BarButtonGroup</a> and <a href="https://documentation.devexpress.com/WPF/clsDevExpressXpfRibbonRibbonGalleryBarItemtopic.aspx">RibbonGalleryBarItem</a>. To obtain a complete list of supported items, refer to <a href="https://documentation.devexpress.com/#WPF/CustomDocument6646">The List of Bar Items and Links</a>.<br><br>As MS Ribbon, RibbonControl can display items in different areas:<br>1. <a href="https://documentation.devexpress.com/#WPF/CustomDocument7956">Page Group</a>;<br>2. <a href="https://documentation.devexpress.com/#WPF/CustomDocument7957">Quick Access Toolbar</a>;<br>3. <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfRibbonRibbonControl_PageHeaderItemstopic">Page Header</a>.<br><br>The appearance of items added to a <a href="https://documentation.devexpress.com/#WPF/CustomDocument7956">Page Group</a> is controlled by the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfBarsBarItem_RibbonStyletopic">RibbonStyle</a> property instead of <a href="https://documentation.devexpress.com/#wpf/DevExpressXpfBarsBarItem_BarItemDisplayModetopic">BarItemDisplayMode</a> and <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfBarsBarItem_GlyphSizetopic">GlyphSize</a>, which work for items in bars.<br><br><strong>See also:</strong><br><a href="https://documentation.devexpress.com/#WPF/CustomDocument8183">How to arrange ribbon items in two rows similar to MS Office</a><br><a href="https://documentation.devexpress.com/#WPF/CustomDocument8187">How to define an in-ribbon gallery</a>

<br/>


