<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Form1.cs) (VB: [Form1.vb](./VB/Form1.vb))
* [PrintableListView.cs](./CS/PrintableListView.cs) (VB: [PrintableListView.vb](./VB/PrintableListView.vb))
<!-- default file list end -->
# How to implement the IPrintable interface


<p>The following example demonstrates how a standard control can be modified to enable its use with <strong>PrintableComponentLink</strong>. To accomplish this, the control should implement the <strong>IPrintable</strong> interface. In this sample, we create a printable descendant of the System.Windows.Forms.ListView control, that implements the <strong>IPrintable</strong> interface.</p>

<br/>


