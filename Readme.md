<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/HowToAddCustomTotals/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/HowToAddCustomTotals/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/HowToAddCustomTotals/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/HowToAddCustomTotals/MainWindow.xaml.vb))
<!-- default file list end -->
# How to: Add Custom Totals


<p>The following example demonstrates how to add custom totals for a particular pivot grid field.</p>


<h3>Description</h3>

<p>In this example, four different totals are added for the <strong>Category Name</strong> row field: Average, Sum, Min and Max. For this, they should be added to the <strong>PivotGridField.CustomTotals</strong> property and the <strong>PivotGridField.TotalsVisibility</strong> property should be set to <strong>FieldTotalsVisibility.CustomTotals</strong>.</p>

<br/>


