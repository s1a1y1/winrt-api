---
-api-id: M:Windows.UI.Xaml.Controls.ListBox.ScrollIntoView(System.Object)
-api-type: winrt method
---

<!-- Method syntax
public void ScrollIntoView(System.Object item)
-->

# Windows.UI.Xaml.Controls.ListBox.ScrollIntoView

## -description
Causes the object to scroll into view.

## -parameters
### -param item
The object to scroll to.

## -remarks
When the contents of the [ItemsSource](itemscontrol_itemssource.md) collection changes, particularly if many items are added to or removed from the collection, you might need to call [UpdateLayout](../windows.ui.xaml/uielement_updatelayout.md) prior to calling [ScrollIntoView](listbox_scrollintoview.md) for the specified item to scroll into the viewport.

## -examples

## -see-also
