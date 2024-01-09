# <a id="LoginForm_LoginForm"></a> Class LoginForm

Namespace: [LoginForm](LoginForm.md)  
Assembly: LoginForm.dll  

Control de usuario que representa un formulario de inicio de sesión con funcionalidades para obtener datos de usuario, mostrar errores y gestionar la visibilidad.

```csharp
public class LoginForm : UserControl, IAnimatable, IFrameworkInputElement, IInputElement, ISupportInitialize, IQueryAmbient, IAddChild
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[DispatcherObject](https://learn.microsoft.com/dotnet/api/system.windows.threading.dispatcherobject) ← 
[DependencyObject](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject) ← 
[Visual](https://learn.microsoft.com/dotnet/api/system.windows.media.visual) ← 
[UIElement](https://learn.microsoft.com/dotnet/api/system.windows.uielement) ← 
[FrameworkElement](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement) ← 
[Control](https://learn.microsoft.com/dotnet/api/system.windows.controls.control) ← 
[ContentControl](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol) ← 
[UserControl](https://learn.microsoft.com/dotnet/api/system.windows.controls.usercontrol) ← 
[LoginForm](LoginForm.LoginForm.md)

#### Implements

[IAnimatable](https://learn.microsoft.com/dotnet/api/system.windows.media.animation.ianimatable), 
[IFrameworkInputElement](https://learn.microsoft.com/dotnet/api/system.windows.iframeworkinputelement), 
[IInputElement](https://learn.microsoft.com/dotnet/api/system.windows.iinputelement), 
[ISupportInitialize](https://learn.microsoft.com/dotnet/api/system.componentmodel.isupportinitialize), 
[IQueryAmbient](https://learn.microsoft.com/dotnet/api/system.windows.markup.iqueryambient), 
[IAddChild](https://learn.microsoft.com/dotnet/api/system.windows.markup.iaddchild)

#### Inherited Members

[UserControl.OnCreateAutomationPeer\(\)](https://learn.microsoft.com/dotnet/api/system.windows.controls.usercontrol.oncreateautomationpeer), 
[ContentControl.ContentProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol.contentproperty), 
[ContentControl.HasContentProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol.hascontentproperty), 
[ContentControl.ContentTemplateProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol.contenttemplateproperty), 
[ContentControl.ContentTemplateSelectorProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol.contenttemplateselectorproperty), 
[ContentControl.ContentStringFormatProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol.contentstringformatproperty), 
[ContentControl.AddChild\(object\)](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol.addchild), 
[ContentControl.AddText\(string\)](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol.addtext), 
[ContentControl.OnContentChanged\(object, object\)](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol.oncontentchanged), 
[ContentControl.OnContentTemplateChanged\(DataTemplate, DataTemplate\)](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol.oncontenttemplatechanged), 
[ContentControl.OnContentTemplateSelectorChanged\(DataTemplateSelector, DataTemplateSelector\)](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol.oncontenttemplateselectorchanged), 
[ContentControl.OnContentStringFormatChanged\(string, string\)](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol.oncontentstringformatchanged), 
[ContentControl.LogicalChildren](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol.logicalchildren), 
[ContentControl.Content](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol.content), 
[ContentControl.HasContent](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol.hascontent), 
[ContentControl.ContentTemplate](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol.contenttemplate), 
[ContentControl.ContentTemplateSelector](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol.contenttemplateselector), 
[ContentControl.ContentStringFormat](https://learn.microsoft.com/dotnet/api/system.windows.controls.contentcontrol.contentstringformat), 
[Control.BorderBrushProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.borderbrushproperty), 
[Control.BorderThicknessProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.borderthicknessproperty), 
[Control.BackgroundProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.backgroundproperty), 
[Control.ForegroundProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.foregroundproperty), 
[Control.FontFamilyProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.fontfamilyproperty), 
[Control.FontSizeProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.fontsizeproperty), 
[Control.FontStretchProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.fontstretchproperty), 
[Control.FontStyleProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.fontstyleproperty), 
[Control.FontWeightProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.fontweightproperty), 
[Control.HorizontalContentAlignmentProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.horizontalcontentalignmentproperty), 
[Control.VerticalContentAlignmentProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.verticalcontentalignmentproperty), 
[Control.TabIndexProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.tabindexproperty), 
[Control.IsTabStopProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.istabstopproperty), 
[Control.PaddingProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.paddingproperty), 
[Control.TemplateProperty](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.templateproperty), 
[Control.PreviewMouseDoubleClickEvent](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.previewmousedoubleclickevent), 
[Control.MouseDoubleClickEvent](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.mousedoubleclickevent), 
[Control.OnTemplateChanged\(ControlTemplate, ControlTemplate\)](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.ontemplatechanged), 
[Control.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.tostring), 
[Control.OnPreviewMouseDoubleClick\(MouseButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.onpreviewmousedoubleclick), 
[Control.OnMouseDoubleClick\(MouseButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.onmousedoubleclick), 
[Control.MeasureOverride\(Size\)](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.measureoverride), 
[Control.ArrangeOverride\(Size\)](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.arrangeoverride), 
[Control.BorderBrush](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.borderbrush), 
[Control.BorderThickness](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.borderthickness), 
[Control.Background](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.background), 
[Control.Foreground](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.foreground), 
[Control.FontFamily](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.fontfamily), 
[Control.FontSize](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.fontsize), 
[Control.FontStretch](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.fontstretch), 
[Control.FontStyle](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.fontstyle), 
[Control.FontWeight](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.fontweight), 
[Control.HorizontalContentAlignment](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.horizontalcontentalignment), 
[Control.VerticalContentAlignment](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.verticalcontentalignment), 
[Control.TabIndex](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.tabindex), 
[Control.IsTabStop](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.istabstop), 
[Control.Padding](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.padding), 
[Control.Template](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.template), 
[Control.HandlesScrolling](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.handlesscrolling), 
[Control.PreviewMouseDoubleClick](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.previewmousedoubleclick), 
[Control.MouseDoubleClick](https://learn.microsoft.com/dotnet/api/system.windows.controls.control.mousedoubleclick), 
[FrameworkElement.StyleProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.styleproperty), 
[FrameworkElement.OverridesDefaultStyleProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.overridesdefaultstyleproperty), 
[FrameworkElement.UseLayoutRoundingProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.uselayoutroundingproperty), 
[FrameworkElement.DefaultStyleKeyProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.defaultstylekeyproperty), 
[FrameworkElement.DataContextProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.datacontextproperty), 
[FrameworkElement.BindingGroupProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.bindinggroupproperty), 
[FrameworkElement.LanguageProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.languageproperty), 
[FrameworkElement.NameProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.nameproperty), 
[FrameworkElement.TagProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.tagproperty), 
[FrameworkElement.InputScopeProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.inputscopeproperty), 
[FrameworkElement.RequestBringIntoViewEvent](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.requestbringintoviewevent), 
[FrameworkElement.SizeChangedEvent](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.sizechangedevent), 
[FrameworkElement.ActualWidthProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.actualwidthproperty), 
[FrameworkElement.ActualHeightProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.actualheightproperty), 
[FrameworkElement.LayoutTransformProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.layouttransformproperty), 
[FrameworkElement.WidthProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.widthproperty), 
[FrameworkElement.MinWidthProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.minwidthproperty), 
[FrameworkElement.MaxWidthProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.maxwidthproperty), 
[FrameworkElement.HeightProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.heightproperty), 
[FrameworkElement.MinHeightProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.minheightproperty), 
[FrameworkElement.MaxHeightProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.maxheightproperty), 
[FrameworkElement.FlowDirectionProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.flowdirectionproperty), 
[FrameworkElement.MarginProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.marginproperty), 
[FrameworkElement.HorizontalAlignmentProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.horizontalalignmentproperty), 
[FrameworkElement.VerticalAlignmentProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.verticalalignmentproperty), 
[FrameworkElement.FocusVisualStyleProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.focusvisualstyleproperty), 
[FrameworkElement.CursorProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.cursorproperty), 
[FrameworkElement.ForceCursorProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.forcecursorproperty), 
[FrameworkElement.LoadedEvent](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.loadedevent), 
[FrameworkElement.UnloadedEvent](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.unloadedevent), 
[FrameworkElement.ToolTipProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.tooltipproperty), 
[FrameworkElement.ContextMenuProperty](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.contextmenuproperty), 
[FrameworkElement.ToolTipOpeningEvent](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.tooltipopeningevent), 
[FrameworkElement.ToolTipClosingEvent](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.tooltipclosingevent), 
[FrameworkElement.ContextMenuOpeningEvent](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.contextmenuopeningevent), 
[FrameworkElement.ContextMenuClosingEvent](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.contextmenuclosingevent), 
[FrameworkElement.OnStyleChanged\(Style, Style\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.onstylechanged), 
[FrameworkElement.ParentLayoutInvalidated\(UIElement\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.parentlayoutinvalidated), 
[FrameworkElement.ApplyTemplate\(\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.applytemplate), 
[FrameworkElement.OnApplyTemplate\(\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.onapplytemplate), 
[FrameworkElement.BeginStoryboard\(Storyboard\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.beginstoryboard\#system\-windows\-frameworkelement\-beginstoryboard\(system\-windows\-media\-animation\-storyboard\)), 
[FrameworkElement.BeginStoryboard\(Storyboard, HandoffBehavior\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.beginstoryboard\#system\-windows\-frameworkelement\-beginstoryboard\(system\-windows\-media\-animation\-storyboard\-system\-windows\-media\-animation\-handoffbehavior\)), 
[FrameworkElement.BeginStoryboard\(Storyboard, HandoffBehavior, bool\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.beginstoryboard\#system\-windows\-frameworkelement\-beginstoryboard\(system\-windows\-media\-animation\-storyboard\-system\-windows\-media\-animation\-handoffbehavior\-system\-boolean\)), 
[FrameworkElement.GetVisualChild\(int\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.getvisualchild), 
[FrameworkElement.GetTemplateChild\(string\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.gettemplatechild), 
[FrameworkElement.FindResource\(object\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.findresource), 
[FrameworkElement.TryFindResource\(object\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.tryfindresource), 
[FrameworkElement.SetResourceReference\(DependencyProperty, object\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.setresourcereference), 
[FrameworkElement.OnPropertyChanged\(DependencyPropertyChangedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.onpropertychanged), 
[FrameworkElement.OnVisualParentChanged\(DependencyObject\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.onvisualparentchanged), 
[FrameworkElement.GetBindingExpression\(DependencyProperty\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.getbindingexpression), 
[FrameworkElement.SetBinding\(DependencyProperty, BindingBase\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.setbinding\#system\-windows\-frameworkelement\-setbinding\(system\-windows\-dependencyproperty\-system\-windows\-data\-bindingbase\)), 
[FrameworkElement.SetBinding\(DependencyProperty, string\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.setbinding\#system\-windows\-frameworkelement\-setbinding\(system\-windows\-dependencyproperty\-system\-string\)), 
[FrameworkElement.GetUIParentCore\(\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.getuiparentcore), 
[FrameworkElement.BringIntoView\(\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.bringintoview\#system\-windows\-frameworkelement\-bringintoview), 
[FrameworkElement.BringIntoView\(Rect\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.bringintoview\#system\-windows\-frameworkelement\-bringintoview\(system\-windows\-rect\)), 
[FrameworkElement.GetFlowDirection\(DependencyObject\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.getflowdirection), 
[FrameworkElement.SetFlowDirection\(DependencyObject, FlowDirection\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.setflowdirection), 
[FrameworkElement.MeasureCore\(Size\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.measurecore), 
[FrameworkElement.ArrangeCore\(Rect\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.arrangecore), 
[FrameworkElement.OnRenderSizeChanged\(SizeChangedInfo\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.onrendersizechanged), 
[FrameworkElement.GetLayoutClip\(Size\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.getlayoutclip), 
[FrameworkElement.MeasureOverride\(Size\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.measureoverride), 
[FrameworkElement.ArrangeOverride\(Size\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.arrangeoverride), 
[FrameworkElement.MoveFocus\(TraversalRequest\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.movefocus), 
[FrameworkElement.PredictFocus\(FocusNavigationDirection\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.predictfocus), 
[FrameworkElement.OnGotFocus\(RoutedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.ongotfocus), 
[FrameworkElement.BeginInit\(\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.begininit), 
[FrameworkElement.EndInit\(\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.endinit), 
[FrameworkElement.OnInitialized\(EventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.oninitialized), 
[FrameworkElement.OnToolTipOpening\(ToolTipEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.ontooltipopening), 
[FrameworkElement.OnToolTipClosing\(ToolTipEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.ontooltipclosing), 
[FrameworkElement.OnContextMenuOpening\(ContextMenuEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.oncontextmenuopening), 
[FrameworkElement.OnContextMenuClosing\(ContextMenuEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.oncontextmenuclosing), 
[FrameworkElement.RegisterName\(string, object\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.registername), 
[FrameworkElement.UnregisterName\(string\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.unregistername), 
[FrameworkElement.FindName\(string\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.findname), 
[FrameworkElement.UpdateDefaultStyle\(\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.updatedefaultstyle), 
[FrameworkElement.AddLogicalChild\(object\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.addlogicalchild), 
[FrameworkElement.RemoveLogicalChild\(object\)](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.removelogicalchild), 
[FrameworkElement.Style](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.style), 
[FrameworkElement.OverridesDefaultStyle](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.overridesdefaultstyle), 
[FrameworkElement.UseLayoutRounding](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.uselayoutrounding), 
[FrameworkElement.DefaultStyleKey](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.defaultstylekey), 
[FrameworkElement.Triggers](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.triggers), 
[FrameworkElement.TemplatedParent](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.templatedparent), 
[FrameworkElement.VisualChildrenCount](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.visualchildrencount), 
[FrameworkElement.Resources](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.resources), 
[FrameworkElement.InheritanceBehavior](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.inheritancebehavior), 
[FrameworkElement.DataContext](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.datacontext), 
[FrameworkElement.BindingGroup](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.bindinggroup), 
[FrameworkElement.Language](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.language), 
[FrameworkElement.Name](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.name), 
[FrameworkElement.Tag](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.tag), 
[FrameworkElement.InputScope](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.inputscope), 
[FrameworkElement.ActualWidth](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.actualwidth), 
[FrameworkElement.ActualHeight](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.actualheight), 
[FrameworkElement.LayoutTransform](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.layouttransform), 
[FrameworkElement.Width](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.width), 
[FrameworkElement.MinWidth](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.minwidth), 
[FrameworkElement.MaxWidth](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.maxwidth), 
[FrameworkElement.Height](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.height), 
[FrameworkElement.MinHeight](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.minheight), 
[FrameworkElement.MaxHeight](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.maxheight), 
[FrameworkElement.FlowDirection](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.flowdirection), 
[FrameworkElement.Margin](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.margin), 
[FrameworkElement.HorizontalAlignment](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.horizontalalignment), 
[FrameworkElement.VerticalAlignment](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.verticalalignment), 
[FrameworkElement.FocusVisualStyle](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.focusvisualstyle), 
[FrameworkElement.Cursor](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.cursor), 
[FrameworkElement.ForceCursor](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.forcecursor), 
[FrameworkElement.IsInitialized](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.isinitialized), 
[FrameworkElement.IsLoaded](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.isloaded), 
[FrameworkElement.ToolTip](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.tooltip), 
[FrameworkElement.ContextMenu](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.contextmenu), 
[FrameworkElement.Parent](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.parent), 
[FrameworkElement.LogicalChildren](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.logicalchildren), 
[FrameworkElement.TargetUpdated](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.targetupdated), 
[FrameworkElement.SourceUpdated](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.sourceupdated), 
[FrameworkElement.DataContextChanged](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.datacontextchanged), 
[FrameworkElement.RequestBringIntoView](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.requestbringintoview), 
[FrameworkElement.SizeChanged](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.sizechanged), 
[FrameworkElement.Initialized](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.initialized), 
[FrameworkElement.Loaded](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.loaded), 
[FrameworkElement.Unloaded](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.unloaded), 
[FrameworkElement.ToolTipOpening](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.tooltipopening), 
[FrameworkElement.ToolTipClosing](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.tooltipclosing), 
[FrameworkElement.ContextMenuOpening](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.contextmenuopening), 
[FrameworkElement.ContextMenuClosing](https://learn.microsoft.com/dotnet/api/system.windows.frameworkelement.contextmenuclosing), 
[UIElement.PreviewMouseDownEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewmousedownevent), 
[UIElement.MouseDownEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mousedownevent), 
[UIElement.PreviewMouseUpEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewmouseupevent), 
[UIElement.MouseUpEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mouseupevent), 
[UIElement.PreviewMouseLeftButtonDownEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewmouseleftbuttondownevent), 
[UIElement.MouseLeftButtonDownEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mouseleftbuttondownevent), 
[UIElement.PreviewMouseLeftButtonUpEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewmouseleftbuttonupevent), 
[UIElement.MouseLeftButtonUpEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mouseleftbuttonupevent), 
[UIElement.PreviewMouseRightButtonDownEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewmouserightbuttondownevent), 
[UIElement.MouseRightButtonDownEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mouserightbuttondownevent), 
[UIElement.PreviewMouseRightButtonUpEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewmouserightbuttonupevent), 
[UIElement.MouseRightButtonUpEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mouserightbuttonupevent), 
[UIElement.PreviewMouseMoveEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewmousemoveevent), 
[UIElement.MouseMoveEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mousemoveevent), 
[UIElement.PreviewMouseWheelEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewmousewheelevent), 
[UIElement.MouseWheelEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mousewheelevent), 
[UIElement.MouseEnterEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mouseenterevent), 
[UIElement.MouseLeaveEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mouseleaveevent), 
[UIElement.GotMouseCaptureEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.gotmousecaptureevent), 
[UIElement.LostMouseCaptureEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.lostmousecaptureevent), 
[UIElement.QueryCursorEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.querycursorevent), 
[UIElement.PreviewStylusDownEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylusdownevent), 
[UIElement.StylusDownEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusdownevent), 
[UIElement.PreviewStylusUpEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylusupevent), 
[UIElement.StylusUpEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusupevent), 
[UIElement.PreviewStylusMoveEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylusmoveevent), 
[UIElement.StylusMoveEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusmoveevent), 
[UIElement.PreviewStylusInAirMoveEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylusinairmoveevent), 
[UIElement.StylusInAirMoveEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusinairmoveevent), 
[UIElement.StylusEnterEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusenterevent), 
[UIElement.StylusLeaveEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusleaveevent), 
[UIElement.PreviewStylusInRangeEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylusinrangeevent), 
[UIElement.StylusInRangeEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusinrangeevent), 
[UIElement.PreviewStylusOutOfRangeEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylusoutofrangeevent), 
[UIElement.StylusOutOfRangeEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusoutofrangeevent), 
[UIElement.PreviewStylusSystemGestureEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylussystemgestureevent), 
[UIElement.StylusSystemGestureEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylussystemgestureevent), 
[UIElement.GotStylusCaptureEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.gotstyluscaptureevent), 
[UIElement.LostStylusCaptureEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.loststyluscaptureevent), 
[UIElement.StylusButtonDownEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusbuttondownevent), 
[UIElement.StylusButtonUpEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusbuttonupevent), 
[UIElement.PreviewStylusButtonDownEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylusbuttondownevent), 
[UIElement.PreviewStylusButtonUpEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylusbuttonupevent), 
[UIElement.PreviewKeyDownEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewkeydownevent), 
[UIElement.KeyDownEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.keydownevent), 
[UIElement.PreviewKeyUpEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewkeyupevent), 
[UIElement.KeyUpEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.keyupevent), 
[UIElement.PreviewGotKeyboardFocusEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewgotkeyboardfocusevent), 
[UIElement.GotKeyboardFocusEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.gotkeyboardfocusevent), 
[UIElement.PreviewLostKeyboardFocusEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewlostkeyboardfocusevent), 
[UIElement.LostKeyboardFocusEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.lostkeyboardfocusevent), 
[UIElement.PreviewTextInputEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewtextinputevent), 
[UIElement.TextInputEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.textinputevent), 
[UIElement.PreviewQueryContinueDragEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewquerycontinuedragevent), 
[UIElement.QueryContinueDragEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.querycontinuedragevent), 
[UIElement.PreviewGiveFeedbackEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewgivefeedbackevent), 
[UIElement.GiveFeedbackEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.givefeedbackevent), 
[UIElement.PreviewDragEnterEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewdragenterevent), 
[UIElement.DragEnterEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.dragenterevent), 
[UIElement.PreviewDragOverEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewdragoverevent), 
[UIElement.DragOverEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.dragoverevent), 
[UIElement.PreviewDragLeaveEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewdragleaveevent), 
[UIElement.DragLeaveEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.dragleaveevent), 
[UIElement.PreviewDropEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewdropevent), 
[UIElement.DropEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.dropevent), 
[UIElement.PreviewTouchDownEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewtouchdownevent), 
[UIElement.TouchDownEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.touchdownevent), 
[UIElement.PreviewTouchMoveEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewtouchmoveevent), 
[UIElement.TouchMoveEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.touchmoveevent), 
[UIElement.PreviewTouchUpEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewtouchupevent), 
[UIElement.TouchUpEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.touchupevent), 
[UIElement.GotTouchCaptureEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.gottouchcaptureevent), 
[UIElement.LostTouchCaptureEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.losttouchcaptureevent), 
[UIElement.TouchEnterEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.touchenterevent), 
[UIElement.TouchLeaveEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.touchleaveevent), 
[UIElement.IsMouseDirectlyOverProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ismousedirectlyoverproperty), 
[UIElement.IsMouseOverProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ismouseoverproperty), 
[UIElement.IsStylusOverProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isstylusoverproperty), 
[UIElement.IsKeyboardFocusWithinProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.iskeyboardfocuswithinproperty), 
[UIElement.IsMouseCapturedProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ismousecapturedproperty), 
[UIElement.IsMouseCaptureWithinProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ismousecapturewithinproperty), 
[UIElement.IsStylusDirectlyOverProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isstylusdirectlyoverproperty), 
[UIElement.IsStylusCapturedProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isstyluscapturedproperty), 
[UIElement.IsStylusCaptureWithinProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isstyluscapturewithinproperty), 
[UIElement.IsKeyboardFocusedProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.iskeyboardfocusedproperty), 
[UIElement.AreAnyTouchesDirectlyOverProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.areanytouchesdirectlyoverproperty), 
[UIElement.AreAnyTouchesOverProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.areanytouchesoverproperty), 
[UIElement.AreAnyTouchesCapturedProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.areanytouchescapturedproperty), 
[UIElement.AreAnyTouchesCapturedWithinProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.areanytouchescapturedwithinproperty), 
[UIElement.AllowDropProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.allowdropproperty), 
[UIElement.RenderTransformProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.rendertransformproperty), 
[UIElement.RenderTransformOriginProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.rendertransformoriginproperty), 
[UIElement.OpacityProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.opacityproperty), 
[UIElement.OpacityMaskProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.opacitymaskproperty), 
[UIElement.BitmapEffectProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.bitmapeffectproperty), 
[UIElement.EffectProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.effectproperty), 
[UIElement.BitmapEffectInputProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.bitmapeffectinputproperty), 
[UIElement.CacheModeProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.cachemodeproperty), 
[UIElement.UidProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.uidproperty), 
[UIElement.VisibilityProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.visibilityproperty), 
[UIElement.ClipToBoundsProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.cliptoboundsproperty), 
[UIElement.ClipProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.clipproperty), 
[UIElement.SnapsToDevicePixelsProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.snapstodevicepixelsproperty), 
[UIElement.GotFocusEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.gotfocusevent), 
[UIElement.LostFocusEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.lostfocusevent), 
[UIElement.IsFocusedProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isfocusedproperty), 
[UIElement.IsEnabledProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isenabledproperty), 
[UIElement.IsHitTestVisibleProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ishittestvisibleproperty), 
[UIElement.IsVisibleProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isvisibleproperty), 
[UIElement.FocusableProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.focusableproperty), 
[UIElement.IsManipulationEnabledProperty](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ismanipulationenabledproperty), 
[UIElement.ManipulationStartingEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.manipulationstartingevent), 
[UIElement.ManipulationStartedEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.manipulationstartedevent), 
[UIElement.ManipulationDeltaEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.manipulationdeltaevent), 
[UIElement.ManipulationInertiaStartingEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.manipulationinertiastartingevent), 
[UIElement.ManipulationBoundaryFeedbackEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.manipulationboundaryfeedbackevent), 
[UIElement.ManipulationCompletedEvent](https://learn.microsoft.com/dotnet/api/system.windows.uielement.manipulationcompletedevent), 
[UIElement.ApplyAnimationClock\(DependencyProperty, AnimationClock\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.applyanimationclock\#system\-windows\-uielement\-applyanimationclock\(system\-windows\-dependencyproperty\-system\-windows\-media\-animation\-animationclock\)), 
[UIElement.ApplyAnimationClock\(DependencyProperty, AnimationClock, HandoffBehavior\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.applyanimationclock\#system\-windows\-uielement\-applyanimationclock\(system\-windows\-dependencyproperty\-system\-windows\-media\-animation\-animationclock\-system\-windows\-media\-animation\-handoffbehavior\)), 
[UIElement.BeginAnimation\(DependencyProperty, AnimationTimeline\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.beginanimation\#system\-windows\-uielement\-beginanimation\(system\-windows\-dependencyproperty\-system\-windows\-media\-animation\-animationtimeline\)), 
[UIElement.BeginAnimation\(DependencyProperty, AnimationTimeline, HandoffBehavior\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.beginanimation\#system\-windows\-uielement\-beginanimation\(system\-windows\-dependencyproperty\-system\-windows\-media\-animation\-animationtimeline\-system\-windows\-media\-animation\-handoffbehavior\)), 
[UIElement.GetAnimationBaseValue\(DependencyProperty\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.getanimationbasevalue), 
[UIElement.RaiseEvent\(RoutedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.raiseevent), 
[UIElement.AddHandler\(RoutedEvent, Delegate\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.addhandler\#system\-windows\-uielement\-addhandler\(system\-windows\-routedevent\-system\-delegate\)), 
[UIElement.AddHandler\(RoutedEvent, Delegate, bool\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.addhandler\#system\-windows\-uielement\-addhandler\(system\-windows\-routedevent\-system\-delegate\-system\-boolean\)), 
[UIElement.RemoveHandler\(RoutedEvent, Delegate\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.removehandler), 
[UIElement.AddToEventRoute\(EventRoute, RoutedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.addtoeventroute), 
[UIElement.OnPreviewMouseDown\(MouseButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewmousedown), 
[UIElement.OnMouseDown\(MouseButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onmousedown), 
[UIElement.OnPreviewMouseUp\(MouseButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewmouseup), 
[UIElement.OnMouseUp\(MouseButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onmouseup), 
[UIElement.OnPreviewMouseLeftButtonDown\(MouseButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewmouseleftbuttondown), 
[UIElement.OnMouseLeftButtonDown\(MouseButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onmouseleftbuttondown), 
[UIElement.OnPreviewMouseLeftButtonUp\(MouseButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewmouseleftbuttonup), 
[UIElement.OnMouseLeftButtonUp\(MouseButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onmouseleftbuttonup), 
[UIElement.OnPreviewMouseRightButtonDown\(MouseButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewmouserightbuttondown), 
[UIElement.OnMouseRightButtonDown\(MouseButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onmouserightbuttondown), 
[UIElement.OnPreviewMouseRightButtonUp\(MouseButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewmouserightbuttonup), 
[UIElement.OnMouseRightButtonUp\(MouseButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onmouserightbuttonup), 
[UIElement.OnPreviewMouseMove\(MouseEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewmousemove), 
[UIElement.OnMouseMove\(MouseEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onmousemove), 
[UIElement.OnPreviewMouseWheel\(MouseWheelEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewmousewheel), 
[UIElement.OnMouseWheel\(MouseWheelEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onmousewheel), 
[UIElement.OnMouseEnter\(MouseEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onmouseenter), 
[UIElement.OnMouseLeave\(MouseEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onmouseleave), 
[UIElement.OnGotMouseCapture\(MouseEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ongotmousecapture), 
[UIElement.OnLostMouseCapture\(MouseEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onlostmousecapture), 
[UIElement.OnQueryCursor\(QueryCursorEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onquerycursor), 
[UIElement.OnPreviewStylusDown\(StylusDownEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewstylusdown), 
[UIElement.OnStylusDown\(StylusDownEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onstylusdown), 
[UIElement.OnPreviewStylusUp\(StylusEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewstylusup), 
[UIElement.OnStylusUp\(StylusEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onstylusup), 
[UIElement.OnPreviewStylusMove\(StylusEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewstylusmove), 
[UIElement.OnStylusMove\(StylusEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onstylusmove), 
[UIElement.OnPreviewStylusInAirMove\(StylusEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewstylusinairmove), 
[UIElement.OnStylusInAirMove\(StylusEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onstylusinairmove), 
[UIElement.OnStylusEnter\(StylusEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onstylusenter), 
[UIElement.OnStylusLeave\(StylusEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onstylusleave), 
[UIElement.OnPreviewStylusInRange\(StylusEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewstylusinrange), 
[UIElement.OnStylusInRange\(StylusEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onstylusinrange), 
[UIElement.OnPreviewStylusOutOfRange\(StylusEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewstylusoutofrange), 
[UIElement.OnStylusOutOfRange\(StylusEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onstylusoutofrange), 
[UIElement.OnPreviewStylusSystemGesture\(StylusSystemGestureEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewstylussystemgesture), 
[UIElement.OnStylusSystemGesture\(StylusSystemGestureEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onstylussystemgesture), 
[UIElement.OnGotStylusCapture\(StylusEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ongotstyluscapture), 
[UIElement.OnLostStylusCapture\(StylusEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onloststyluscapture), 
[UIElement.OnStylusButtonDown\(StylusButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onstylusbuttondown), 
[UIElement.OnStylusButtonUp\(StylusButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onstylusbuttonup), 
[UIElement.OnPreviewStylusButtonDown\(StylusButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewstylusbuttondown), 
[UIElement.OnPreviewStylusButtonUp\(StylusButtonEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewstylusbuttonup), 
[UIElement.OnPreviewKeyDown\(KeyEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewkeydown), 
[UIElement.OnKeyDown\(KeyEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onkeydown), 
[UIElement.OnPreviewKeyUp\(KeyEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewkeyup), 
[UIElement.OnKeyUp\(KeyEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onkeyup), 
[UIElement.OnPreviewGotKeyboardFocus\(KeyboardFocusChangedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewgotkeyboardfocus), 
[UIElement.OnGotKeyboardFocus\(KeyboardFocusChangedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ongotkeyboardfocus), 
[UIElement.OnPreviewLostKeyboardFocus\(KeyboardFocusChangedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewlostkeyboardfocus), 
[UIElement.OnLostKeyboardFocus\(KeyboardFocusChangedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onlostkeyboardfocus), 
[UIElement.OnPreviewTextInput\(TextCompositionEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewtextinput), 
[UIElement.OnTextInput\(TextCompositionEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ontextinput), 
[UIElement.OnPreviewQueryContinueDrag\(QueryContinueDragEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewquerycontinuedrag), 
[UIElement.OnQueryContinueDrag\(QueryContinueDragEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onquerycontinuedrag), 
[UIElement.OnPreviewGiveFeedback\(GiveFeedbackEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewgivefeedback), 
[UIElement.OnGiveFeedback\(GiveFeedbackEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ongivefeedback), 
[UIElement.OnPreviewDragEnter\(DragEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewdragenter), 
[UIElement.OnDragEnter\(DragEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ondragenter), 
[UIElement.OnPreviewDragOver\(DragEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewdragover), 
[UIElement.OnDragOver\(DragEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ondragover), 
[UIElement.OnPreviewDragLeave\(DragEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewdragleave), 
[UIElement.OnDragLeave\(DragEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ondragleave), 
[UIElement.OnPreviewDrop\(DragEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewdrop), 
[UIElement.OnDrop\(DragEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ondrop), 
[UIElement.OnPreviewTouchDown\(TouchEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewtouchdown), 
[UIElement.OnTouchDown\(TouchEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ontouchdown), 
[UIElement.OnPreviewTouchMove\(TouchEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewtouchmove), 
[UIElement.OnTouchMove\(TouchEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ontouchmove), 
[UIElement.OnPreviewTouchUp\(TouchEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onpreviewtouchup), 
[UIElement.OnTouchUp\(TouchEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ontouchup), 
[UIElement.OnGotTouchCapture\(TouchEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ongottouchcapture), 
[UIElement.OnLostTouchCapture\(TouchEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onlosttouchcapture), 
[UIElement.OnTouchEnter\(TouchEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ontouchenter), 
[UIElement.OnTouchLeave\(TouchEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ontouchleave), 
[UIElement.OnIsMouseDirectlyOverChanged\(DependencyPropertyChangedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onismousedirectlyoverchanged), 
[UIElement.OnIsKeyboardFocusWithinChanged\(DependencyPropertyChangedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.oniskeyboardfocuswithinchanged), 
[UIElement.OnIsMouseCapturedChanged\(DependencyPropertyChangedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onismousecapturedchanged), 
[UIElement.OnIsMouseCaptureWithinChanged\(DependencyPropertyChangedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onismousecapturewithinchanged), 
[UIElement.OnIsStylusDirectlyOverChanged\(DependencyPropertyChangedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onisstylusdirectlyoverchanged), 
[UIElement.OnIsStylusCapturedChanged\(DependencyPropertyChangedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onisstyluscapturedchanged), 
[UIElement.OnIsStylusCaptureWithinChanged\(DependencyPropertyChangedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onisstyluscapturewithinchanged), 
[UIElement.OnIsKeyboardFocusedChanged\(DependencyPropertyChangedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.oniskeyboardfocusedchanged), 
[UIElement.InvalidateMeasure\(\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.invalidatemeasure), 
[UIElement.InvalidateArrange\(\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.invalidatearrange), 
[UIElement.InvalidateVisual\(\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.invalidatevisual), 
[UIElement.OnChildDesiredSizeChanged\(UIElement\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onchilddesiredsizechanged), 
[UIElement.Measure\(Size\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.measure), 
[UIElement.Arrange\(Rect\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.arrange), 
[UIElement.OnRender\(DrawingContext\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onrender), 
[UIElement.OnRenderSizeChanged\(SizeChangedInfo\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onrendersizechanged), 
[UIElement.MeasureCore\(Size\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.measurecore), 
[UIElement.ArrangeCore\(Rect\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.arrangecore), 
[UIElement.OnVisualParentChanged\(DependencyObject\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onvisualparentchanged), 
[UIElement.GetUIParentCore\(\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.getuiparentcore), 
[UIElement.UpdateLayout\(\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.updatelayout), 
[UIElement.TranslatePoint\(Point, UIElement\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.translatepoint), 
[UIElement.InputHitTest\(Point\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.inputhittest), 
[UIElement.CaptureMouse\(\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.capturemouse), 
[UIElement.ReleaseMouseCapture\(\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.releasemousecapture), 
[UIElement.CaptureStylus\(\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.capturestylus), 
[UIElement.ReleaseStylusCapture\(\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.releasestyluscapture), 
[UIElement.Focus\(\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.focus), 
[UIElement.MoveFocus\(TraversalRequest\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.movefocus), 
[UIElement.PredictFocus\(FocusNavigationDirection\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.predictfocus), 
[UIElement.OnAccessKey\(AccessKeyEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onaccesskey), 
[UIElement.HitTestCore\(PointHitTestParameters\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.hittestcore\#system\-windows\-uielement\-hittestcore\(system\-windows\-media\-pointhittestparameters\)), 
[UIElement.HitTestCore\(GeometryHitTestParameters\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.hittestcore\#system\-windows\-uielement\-hittestcore\(system\-windows\-media\-geometryhittestparameters\)), 
[UIElement.GetLayoutClip\(Size\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.getlayoutclip), 
[UIElement.OnGotFocus\(RoutedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ongotfocus), 
[UIElement.OnLostFocus\(RoutedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onlostfocus), 
[UIElement.OnCreateAutomationPeer\(\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.oncreateautomationpeer), 
[UIElement.OnManipulationStarting\(ManipulationStartingEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onmanipulationstarting), 
[UIElement.OnManipulationStarted\(ManipulationStartedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onmanipulationstarted), 
[UIElement.OnManipulationDelta\(ManipulationDeltaEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onmanipulationdelta), 
[UIElement.OnManipulationInertiaStarting\(ManipulationInertiaStartingEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onmanipulationinertiastarting), 
[UIElement.OnManipulationBoundaryFeedback\(ManipulationBoundaryFeedbackEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onmanipulationboundaryfeedback), 
[UIElement.OnManipulationCompleted\(ManipulationCompletedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.onmanipulationcompleted), 
[UIElement.CaptureTouch\(TouchDevice\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.capturetouch), 
[UIElement.ReleaseTouchCapture\(TouchDevice\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.releasetouchcapture), 
[UIElement.ReleaseAllTouchCaptures\(\)](https://learn.microsoft.com/dotnet/api/system.windows.uielement.releasealltouchcaptures), 
[UIElement.HasAnimatedProperties](https://learn.microsoft.com/dotnet/api/system.windows.uielement.hasanimatedproperties), 
[UIElement.InputBindings](https://learn.microsoft.com/dotnet/api/system.windows.uielement.inputbindings), 
[UIElement.CommandBindings](https://learn.microsoft.com/dotnet/api/system.windows.uielement.commandbindings), 
[UIElement.AllowDrop](https://learn.microsoft.com/dotnet/api/system.windows.uielement.allowdrop), 
[UIElement.StylusPlugIns](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusplugins), 
[UIElement.DesiredSize](https://learn.microsoft.com/dotnet/api/system.windows.uielement.desiredsize), 
[UIElement.IsMeasureValid](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ismeasurevalid), 
[UIElement.IsArrangeValid](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isarrangevalid), 
[UIElement.RenderSize](https://learn.microsoft.com/dotnet/api/system.windows.uielement.rendersize), 
[UIElement.RenderTransform](https://learn.microsoft.com/dotnet/api/system.windows.uielement.rendertransform), 
[UIElement.RenderTransformOrigin](https://learn.microsoft.com/dotnet/api/system.windows.uielement.rendertransformorigin), 
[UIElement.IsMouseDirectlyOver](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ismousedirectlyover), 
[UIElement.IsMouseOver](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ismouseover), 
[UIElement.IsStylusOver](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isstylusover), 
[UIElement.IsKeyboardFocusWithin](https://learn.microsoft.com/dotnet/api/system.windows.uielement.iskeyboardfocuswithin), 
[UIElement.IsMouseCaptured](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ismousecaptured), 
[UIElement.IsMouseCaptureWithin](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ismousecapturewithin), 
[UIElement.IsStylusDirectlyOver](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isstylusdirectlyover), 
[UIElement.IsStylusCaptured](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isstyluscaptured), 
[UIElement.IsStylusCaptureWithin](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isstyluscapturewithin), 
[UIElement.IsKeyboardFocused](https://learn.microsoft.com/dotnet/api/system.windows.uielement.iskeyboardfocused), 
[UIElement.IsInputMethodEnabled](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isinputmethodenabled), 
[UIElement.Opacity](https://learn.microsoft.com/dotnet/api/system.windows.uielement.opacity), 
[UIElement.OpacityMask](https://learn.microsoft.com/dotnet/api/system.windows.uielement.opacitymask), 
[UIElement.BitmapEffect](https://learn.microsoft.com/dotnet/api/system.windows.uielement.bitmapeffect), 
[UIElement.Effect](https://learn.microsoft.com/dotnet/api/system.windows.uielement.effect), 
[UIElement.BitmapEffectInput](https://learn.microsoft.com/dotnet/api/system.windows.uielement.bitmapeffectinput), 
[UIElement.CacheMode](https://learn.microsoft.com/dotnet/api/system.windows.uielement.cachemode), 
[UIElement.Uid](https://learn.microsoft.com/dotnet/api/system.windows.uielement.uid), 
[UIElement.Visibility](https://learn.microsoft.com/dotnet/api/system.windows.uielement.visibility), 
[UIElement.ClipToBounds](https://learn.microsoft.com/dotnet/api/system.windows.uielement.cliptobounds), 
[UIElement.Clip](https://learn.microsoft.com/dotnet/api/system.windows.uielement.clip), 
[UIElement.SnapsToDevicePixels](https://learn.microsoft.com/dotnet/api/system.windows.uielement.snapstodevicepixels), 
[UIElement.HasEffectiveKeyboardFocus](https://learn.microsoft.com/dotnet/api/system.windows.uielement.haseffectivekeyboardfocus), 
[UIElement.IsFocused](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isfocused), 
[UIElement.IsEnabled](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isenabled), 
[UIElement.IsEnabledCore](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isenabledcore), 
[UIElement.IsHitTestVisible](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ishittestvisible), 
[UIElement.IsVisible](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isvisible), 
[UIElement.Focusable](https://learn.microsoft.com/dotnet/api/system.windows.uielement.focusable), 
[UIElement.PersistId](https://learn.microsoft.com/dotnet/api/system.windows.uielement.persistid), 
[UIElement.IsManipulationEnabled](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ismanipulationenabled), 
[UIElement.AreAnyTouchesOver](https://learn.microsoft.com/dotnet/api/system.windows.uielement.areanytouchesover), 
[UIElement.AreAnyTouchesDirectlyOver](https://learn.microsoft.com/dotnet/api/system.windows.uielement.areanytouchesdirectlyover), 
[UIElement.AreAnyTouchesCapturedWithin](https://learn.microsoft.com/dotnet/api/system.windows.uielement.areanytouchescapturedwithin), 
[UIElement.AreAnyTouchesCaptured](https://learn.microsoft.com/dotnet/api/system.windows.uielement.areanytouchescaptured), 
[UIElement.TouchesCaptured](https://learn.microsoft.com/dotnet/api/system.windows.uielement.touchescaptured), 
[UIElement.TouchesCapturedWithin](https://learn.microsoft.com/dotnet/api/system.windows.uielement.touchescapturedwithin), 
[UIElement.TouchesOver](https://learn.microsoft.com/dotnet/api/system.windows.uielement.touchesover), 
[UIElement.TouchesDirectlyOver](https://learn.microsoft.com/dotnet/api/system.windows.uielement.touchesdirectlyover), 
[UIElement.PreviewMouseDown](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewmousedown), 
[UIElement.MouseDown](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mousedown), 
[UIElement.PreviewMouseUp](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewmouseup), 
[UIElement.MouseUp](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mouseup), 
[UIElement.PreviewMouseLeftButtonDown](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewmouseleftbuttondown), 
[UIElement.MouseLeftButtonDown](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mouseleftbuttondown), 
[UIElement.PreviewMouseLeftButtonUp](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewmouseleftbuttonup), 
[UIElement.MouseLeftButtonUp](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mouseleftbuttonup), 
[UIElement.PreviewMouseRightButtonDown](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewmouserightbuttondown), 
[UIElement.MouseRightButtonDown](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mouserightbuttondown), 
[UIElement.PreviewMouseRightButtonUp](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewmouserightbuttonup), 
[UIElement.MouseRightButtonUp](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mouserightbuttonup), 
[UIElement.PreviewMouseMove](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewmousemove), 
[UIElement.MouseMove](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mousemove), 
[UIElement.PreviewMouseWheel](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewmousewheel), 
[UIElement.MouseWheel](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mousewheel), 
[UIElement.MouseEnter](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mouseenter), 
[UIElement.MouseLeave](https://learn.microsoft.com/dotnet/api/system.windows.uielement.mouseleave), 
[UIElement.GotMouseCapture](https://learn.microsoft.com/dotnet/api/system.windows.uielement.gotmousecapture), 
[UIElement.LostMouseCapture](https://learn.microsoft.com/dotnet/api/system.windows.uielement.lostmousecapture), 
[UIElement.QueryCursor](https://learn.microsoft.com/dotnet/api/system.windows.uielement.querycursor), 
[UIElement.PreviewStylusDown](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylusdown), 
[UIElement.StylusDown](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusdown), 
[UIElement.PreviewStylusUp](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylusup), 
[UIElement.StylusUp](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusup), 
[UIElement.PreviewStylusMove](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylusmove), 
[UIElement.StylusMove](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusmove), 
[UIElement.PreviewStylusInAirMove](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylusinairmove), 
[UIElement.StylusInAirMove](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusinairmove), 
[UIElement.StylusEnter](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusenter), 
[UIElement.StylusLeave](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusleave), 
[UIElement.PreviewStylusInRange](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylusinrange), 
[UIElement.StylusInRange](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusinrange), 
[UIElement.PreviewStylusOutOfRange](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylusoutofrange), 
[UIElement.StylusOutOfRange](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusoutofrange), 
[UIElement.PreviewStylusSystemGesture](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylussystemgesture), 
[UIElement.StylusSystemGesture](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylussystemgesture), 
[UIElement.GotStylusCapture](https://learn.microsoft.com/dotnet/api/system.windows.uielement.gotstyluscapture), 
[UIElement.LostStylusCapture](https://learn.microsoft.com/dotnet/api/system.windows.uielement.loststyluscapture), 
[UIElement.StylusButtonDown](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusbuttondown), 
[UIElement.StylusButtonUp](https://learn.microsoft.com/dotnet/api/system.windows.uielement.stylusbuttonup), 
[UIElement.PreviewStylusButtonDown](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylusbuttondown), 
[UIElement.PreviewStylusButtonUp](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewstylusbuttonup), 
[UIElement.PreviewKeyDown](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewkeydown), 
[UIElement.KeyDown](https://learn.microsoft.com/dotnet/api/system.windows.uielement.keydown), 
[UIElement.PreviewKeyUp](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewkeyup), 
[UIElement.KeyUp](https://learn.microsoft.com/dotnet/api/system.windows.uielement.keyup), 
[UIElement.PreviewGotKeyboardFocus](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewgotkeyboardfocus), 
[UIElement.GotKeyboardFocus](https://learn.microsoft.com/dotnet/api/system.windows.uielement.gotkeyboardfocus), 
[UIElement.PreviewLostKeyboardFocus](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewlostkeyboardfocus), 
[UIElement.LostKeyboardFocus](https://learn.microsoft.com/dotnet/api/system.windows.uielement.lostkeyboardfocus), 
[UIElement.PreviewTextInput](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewtextinput), 
[UIElement.TextInput](https://learn.microsoft.com/dotnet/api/system.windows.uielement.textinput), 
[UIElement.PreviewQueryContinueDrag](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewquerycontinuedrag), 
[UIElement.QueryContinueDrag](https://learn.microsoft.com/dotnet/api/system.windows.uielement.querycontinuedrag), 
[UIElement.PreviewGiveFeedback](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewgivefeedback), 
[UIElement.GiveFeedback](https://learn.microsoft.com/dotnet/api/system.windows.uielement.givefeedback), 
[UIElement.PreviewDragEnter](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewdragenter), 
[UIElement.DragEnter](https://learn.microsoft.com/dotnet/api/system.windows.uielement.dragenter), 
[UIElement.PreviewDragOver](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewdragover), 
[UIElement.DragOver](https://learn.microsoft.com/dotnet/api/system.windows.uielement.dragover), 
[UIElement.PreviewDragLeave](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewdragleave), 
[UIElement.DragLeave](https://learn.microsoft.com/dotnet/api/system.windows.uielement.dragleave), 
[UIElement.PreviewDrop](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewdrop), 
[UIElement.Drop](https://learn.microsoft.com/dotnet/api/system.windows.uielement.drop), 
[UIElement.PreviewTouchDown](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewtouchdown), 
[UIElement.TouchDown](https://learn.microsoft.com/dotnet/api/system.windows.uielement.touchdown), 
[UIElement.PreviewTouchMove](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewtouchmove), 
[UIElement.TouchMove](https://learn.microsoft.com/dotnet/api/system.windows.uielement.touchmove), 
[UIElement.PreviewTouchUp](https://learn.microsoft.com/dotnet/api/system.windows.uielement.previewtouchup), 
[UIElement.TouchUp](https://learn.microsoft.com/dotnet/api/system.windows.uielement.touchup), 
[UIElement.GotTouchCapture](https://learn.microsoft.com/dotnet/api/system.windows.uielement.gottouchcapture), 
[UIElement.LostTouchCapture](https://learn.microsoft.com/dotnet/api/system.windows.uielement.losttouchcapture), 
[UIElement.TouchEnter](https://learn.microsoft.com/dotnet/api/system.windows.uielement.touchenter), 
[UIElement.TouchLeave](https://learn.microsoft.com/dotnet/api/system.windows.uielement.touchleave), 
[UIElement.IsMouseDirectlyOverChanged](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ismousedirectlyoverchanged), 
[UIElement.IsKeyboardFocusWithinChanged](https://learn.microsoft.com/dotnet/api/system.windows.uielement.iskeyboardfocuswithinchanged), 
[UIElement.IsMouseCapturedChanged](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ismousecapturedchanged), 
[UIElement.IsMouseCaptureWithinChanged](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ismousecapturewithinchanged), 
[UIElement.IsStylusDirectlyOverChanged](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isstylusdirectlyoverchanged), 
[UIElement.IsStylusCapturedChanged](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isstyluscapturedchanged), 
[UIElement.IsStylusCaptureWithinChanged](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isstyluscapturewithinchanged), 
[UIElement.IsKeyboardFocusedChanged](https://learn.microsoft.com/dotnet/api/system.windows.uielement.iskeyboardfocusedchanged), 
[UIElement.LayoutUpdated](https://learn.microsoft.com/dotnet/api/system.windows.uielement.layoutupdated), 
[UIElement.GotFocus](https://learn.microsoft.com/dotnet/api/system.windows.uielement.gotfocus), 
[UIElement.LostFocus](https://learn.microsoft.com/dotnet/api/system.windows.uielement.lostfocus), 
[UIElement.IsEnabledChanged](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isenabledchanged), 
[UIElement.IsHitTestVisibleChanged](https://learn.microsoft.com/dotnet/api/system.windows.uielement.ishittestvisiblechanged), 
[UIElement.IsVisibleChanged](https://learn.microsoft.com/dotnet/api/system.windows.uielement.isvisiblechanged), 
[UIElement.FocusableChanged](https://learn.microsoft.com/dotnet/api/system.windows.uielement.focusablechanged), 
[UIElement.ManipulationStarting](https://learn.microsoft.com/dotnet/api/system.windows.uielement.manipulationstarting), 
[UIElement.ManipulationStarted](https://learn.microsoft.com/dotnet/api/system.windows.uielement.manipulationstarted), 
[UIElement.ManipulationDelta](https://learn.microsoft.com/dotnet/api/system.windows.uielement.manipulationdelta), 
[UIElement.ManipulationInertiaStarting](https://learn.microsoft.com/dotnet/api/system.windows.uielement.manipulationinertiastarting), 
[UIElement.ManipulationBoundaryFeedback](https://learn.microsoft.com/dotnet/api/system.windows.uielement.manipulationboundaryfeedback), 
[UIElement.ManipulationCompleted](https://learn.microsoft.com/dotnet/api/system.windows.uielement.manipulationcompleted), 
[Visual.HitTestCore\(PointHitTestParameters\)](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.hittestcore\#system\-windows\-media\-visual\-hittestcore\(system\-windows\-media\-pointhittestparameters\)), 
[Visual.HitTestCore\(GeometryHitTestParameters\)](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.hittestcore\#system\-windows\-media\-visual\-hittestcore\(system\-windows\-media\-geometryhittestparameters\)), 
[Visual.GetVisualChild\(int\)](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.getvisualchild), 
[Visual.AddVisualChild\(Visual\)](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.addvisualchild), 
[Visual.RemoveVisualChild\(Visual\)](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.removevisualchild), 
[Visual.OnVisualParentChanged\(DependencyObject\)](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.onvisualparentchanged), 
[Visual.OnVisualChildrenChanged\(DependencyObject, DependencyObject\)](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.onvisualchildrenchanged), 
[Visual.OnDpiChanged\(DpiScale, DpiScale\)](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.ondpichanged), 
[Visual.IsAncestorOf\(DependencyObject\)](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.isancestorof), 
[Visual.IsDescendantOf\(DependencyObject\)](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.isdescendantof), 
[Visual.FindCommonVisualAncestor\(DependencyObject\)](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.findcommonvisualancestor), 
[Visual.TransformToAncestor\(Visual\)](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.transformtoancestor\#system\-windows\-media\-visual\-transformtoancestor\(system\-windows\-media\-visual\)), 
[Visual.TransformToAncestor\(Visual3D\)](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.transformtoancestor\#system\-windows\-media\-visual\-transformtoancestor\(system\-windows\-media\-media3d\-visual3d\)), 
[Visual.TransformToDescendant\(Visual\)](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.transformtodescendant), 
[Visual.TransformToVisual\(Visual\)](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.transformtovisual), 
[Visual.PointToScreen\(Point\)](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.pointtoscreen), 
[Visual.PointFromScreen\(Point\)](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.pointfromscreen), 
[Visual.VisualChildrenCount](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualchildrencount), 
[Visual.VisualParent](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualparent), 
[Visual.VisualTransform](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualtransform), 
[Visual.VisualEffect](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualeffect), 
[Visual.VisualBitmapEffect](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualbitmapeffect), 
[Visual.VisualBitmapEffectInput](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualbitmapeffectinput), 
[Visual.VisualCacheMode](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualcachemode), 
[Visual.VisualScrollableAreaClip](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualscrollableareaclip), 
[Visual.VisualClip](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualclip), 
[Visual.VisualOffset](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualoffset), 
[Visual.VisualOpacity](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualopacity), 
[Visual.VisualEdgeMode](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualedgemode), 
[Visual.VisualBitmapScalingMode](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualbitmapscalingmode), 
[Visual.VisualClearTypeHint](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualcleartypehint), 
[Visual.VisualTextRenderingMode](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualtextrenderingmode), 
[Visual.VisualTextHintingMode](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualtexthintingmode), 
[Visual.VisualOpacityMask](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualopacitymask), 
[Visual.VisualXSnappingGuidelines](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualxsnappingguidelines), 
[Visual.VisualYSnappingGuidelines](https://learn.microsoft.com/dotnet/api/system.windows.media.visual.visualysnappingguidelines), 
[DependencyObject.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject.equals), 
[DependencyObject.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject.gethashcode), 
[DependencyObject.GetValue\(DependencyProperty\)](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject.getvalue), 
[DependencyObject.SetValue\(DependencyProperty, object\)](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject.setvalue\#system\-windows\-dependencyobject\-setvalue\(system\-windows\-dependencyproperty\-system\-object\)), 
[DependencyObject.SetCurrentValue\(DependencyProperty, object\)](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject.setcurrentvalue), 
[DependencyObject.SetValue\(DependencyPropertyKey, object\)](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject.setvalue\#system\-windows\-dependencyobject\-setvalue\(system\-windows\-dependencypropertykey\-system\-object\)), 
[DependencyObject.ClearValue\(DependencyProperty\)](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject.clearvalue\#system\-windows\-dependencyobject\-clearvalue\(system\-windows\-dependencyproperty\)), 
[DependencyObject.ClearValue\(DependencyPropertyKey\)](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject.clearvalue\#system\-windows\-dependencyobject\-clearvalue\(system\-windows\-dependencypropertykey\)), 
[DependencyObject.CoerceValue\(DependencyProperty\)](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject.coercevalue), 
[DependencyObject.InvalidateProperty\(DependencyProperty\)](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject.invalidateproperty), 
[DependencyObject.OnPropertyChanged\(DependencyPropertyChangedEventArgs\)](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject.onpropertychanged), 
[DependencyObject.ShouldSerializeProperty\(DependencyProperty\)](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject.shouldserializeproperty), 
[DependencyObject.ReadLocalValue\(DependencyProperty\)](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject.readlocalvalue), 
[DependencyObject.GetLocalValueEnumerator\(\)](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject.getlocalvalueenumerator), 
[DependencyObject.DependencyObjectType](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject.dependencyobjecttype), 
[DependencyObject.IsSealed](https://learn.microsoft.com/dotnet/api/system.windows.dependencyobject.issealed), 
[DispatcherObject.Dispatcher](https://learn.microsoft.com/dotnet/api/system.windows.threading.dispatcherobject.dispatcher), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

## Remarks

Proporciona métodos para obtener el nombre de usuario y la contraseña, mostrar errores, ocultar y mostrar el formulario, así como para vincular un evento clic al botón de inicio de sesión.

## Constructors

### <a id="LoginForm_LoginForm__ctor"></a> LoginForm\(\)

Constructor de la clase LoginForm.

```csharp
public LoginForm()
```

#### Remarks

Inicializa una nueva instancia del formulario de inicio de sesión, estableciendo la fuente de la imagen del logotipo.

## Fields

### <a id="LoginForm_LoginForm_LogoIconSourceProperty"></a> LogoIconSourceProperty

Propiedad de dependencia para la fuente de la imagen del ícono del logotipo.

```csharp
public static readonly DependencyProperty LogoIconSourceProperty
```

#### Field Value

 [DependencyProperty](https://learn.microsoft.com/dotnet/api/system.windows.dependencyproperty)

#### Remarks

Define una propiedad de dependencia para la fuente de la imagen del ícono del logotipo en el formulario de inicio de sesión.

## Properties

### <a id="LoginForm_LoginForm_LogoIconSource"></a> LogoIconSource

Fuente de la imagen del ícono del logotipo.

```csharp
public ImageSource LogoIconSource { get; set; }
```

#### Property Value

 [ImageSource](https://learn.microsoft.com/dotnet/api/system.windows.media.imagesource)

#### Remarks

Propiedad que representa la fuente de la imagen del ícono del logotipo en el formulario de inicio de sesión.

## Methods

### <a id="LoginForm_LoginForm_BindHandler_System_Windows_RoutedEventHandler_"></a> BindHandler\(RoutedEventHandler\)

Vincula un controlador de eventos al botón de inicio de sesión.

```csharp
public void BindHandler(RoutedEventHandler func)
```

#### Parameters

`func` [RoutedEventHandler](https://learn.microsoft.com/dotnet/api/system.windows.routedeventhandler)

Controlador de eventos a vincular.

#### Remarks

Método que establece un controlador de eventos para el clic del botón de inicio de sesión.

### <a id="LoginForm_LoginForm_GetPassword"></a> GetPassword\(\)

Obtiene la contraseña ingresada en el formulario.

```csharp
public string GetPassword()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

La contraseña ingresada.

#### Remarks

Método que devuelve la contraseña escrita en el campo correspondiente del formulario de inicio de sesión.

### <a id="LoginForm_LoginForm_GetUsername"></a> GetUsername\(\)

Obtiene el nombre de usuario ingresado en el formulario.

```csharp
public string GetUsername()
```

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

El nombre de usuario ingresado.

#### Remarks

Método que devuelve el nombre de usuario escrito en el campo correspondiente del formulario de inicio de sesión.

### <a id="LoginForm_LoginForm_Hide"></a> Hide\(\)

Oculta el formulario de inicio de sesión.

```csharp
public void Hide()
```

#### Remarks

Método que establece la visibilidad del formulario como oculta.

### <a id="LoginForm_LoginForm_Show"></a> Show\(\)

Muestra el formulario de inicio de sesión.

```csharp
public void Show()
```

#### Remarks

Método que establece la visibilidad del formulario como visible.

### <a id="LoginForm_LoginForm_ShowError_System_String_"></a> ShowError\(string\)

Muestra un mensaje de error en el formulario.

```csharp
public void ShowError(string str)
```

#### Parameters

`str` [string](https://learn.microsoft.com/dotnet/api/system.string)

Mensaje de error a mostrar.

#### Remarks

Método que establece el contenido del mensaje de error en el formulario de inicio de sesión.

