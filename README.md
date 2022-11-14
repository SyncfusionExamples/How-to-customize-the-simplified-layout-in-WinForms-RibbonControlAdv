# How to customize the ribbon items within the WinForms RibbonControlAdv in simplified layout?
The RibbonControlAdv allows to customize the Ribbon and Ribbon items through the QAT window, where user can add the Ribbon items to a new [ToolStripTabItem](https://help.syncfusion.com/cr/windowsforms/Syncfusion.Windows.Forms.Tools.ToolStripTabItem.html) or [ToolStripEx](https://help.syncfusion.com/cr/windowsforms/Syncfusion.Windows.Forms.Tools.ToolStripEx.html). The newly added ToolStripTabItem or ToolStripEx will only be visible in the respective layout in which items were added originally. The RibbonControlAdv allows to switch between simplified and normal layouts at runtime using the Ribbon minimize button located in the lower right corner of the Ribbon. To enable this option, set the EnableSimplifiedLayoutMode property to True. By default, its value is False.

# C#
    private Syncfusion.Windows.Forms.Tools.RibbonControlAdv ribbonControlAdv1;

    this.ribbonControlAdv1 = new RibbonControlAdv();
    this.ribbonControlAdv1.LayoutMode = RibbonLayoutMode.Simplified;

    this.Controls.Add(ribbonControlAdv1);

# C#
// Switch between Simplified and Normal layout
    private Syncfusion.Windows.Forms.Tools.RibbonControlAdv ribbonControlAdv1;

    this.ribbonControlAdv1 = new RibbonControlAdv();
    this.ribbonControlAdv1.EnableSimplifiedLayoutMode = true;

    this.Controls.Add(ribbonControlAdv1);

![RibbonControlAdv in simplified layout](Images/Output.png)


