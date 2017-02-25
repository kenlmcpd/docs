---
title: "Windows namespaces for UWP apps | Microsoft Docs"
ms.custom: ""
ms.date: "12/14/2016"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: a36c0933-9be3-4208-9ab3-2a4e7d53b451
caps.latest.revision: 4
author: "msatranjr"
ms.author: "misatran"
manager: "markl"
---
# Windows namespaces for UWP apps
The `Windows` namespaces (`Windows.Foundation`, `Windows.UI`, `Windows.UI.Xaml`, `Windows.UI.Xaml.Controls.Primitives`, `Windows.UI.Xaml.Media`, `Windows.UI.Xaml.Media.Animation`, and `Windows.UI.Xaml.Media.Media3D`) contain types for managing the user interface of your application.  
  
 This topic displays the types in the `Windows` namespaces that are included in .NET for UWP apps. Note that .NET for UWP apps do not include all the members of each type. For information about individual types, see the linked topics. The documentation for a type indicates which members are included in .NET for UWP apps.  
  
## Windows.Foundation namespace  
  
|Types supported in .NET for UWP apps|Description|  
|------------------------------------------------------------------------------------------|-----------------|  
|<xref:Windows.Foundation.Point>|Represents an x- and y-coordinate pair in two-dimensional space. Can also represent a logical point for certain property usages.|  
|[Rect](http://msdn.microsoft.com/library/windows/apps/windows.foundation.rect.aspx)|Describes the width, height, and point origin of a rectangle.|  
|[Size](http://msdn.microsoft.com/library/windows/apps/windows.foundation.size.aspx)|Describes the width and height of an object.|  
  
## Windows.UI namespace  
  
|Types supported in the .NET for UWP apps|Description|  
|----------------------------------------------------------------------------------------------|-----------------|  
|[Color](http://msdn.microsoft.com/library/windows/apps/windows.ui.color.aspx)|Describes a color in terms of alpha, red, green, and blue channels.|  
  
## Windows.UI.Xaml namespace  
  
|Types supported in the .NET for UWP apps|Description|  
|----------------------------------------------------------------------------------------------|-----------------|  
|[CornerRadius](http://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.cornerradius.aspx)|Describes the characteristics of a rounded corner, such as can be applied to a Windows.UI.Xaml.Controls.Border.|  
|[Duration](http://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.duration.aspx)|Represents the duration of time that a Windows.UI.Xaml.Media.Animation.Timeline is active.|  
|[DurationType](http://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.durationtype.aspx)|Specifies whether a Duration has a special value of Automatic or Forever, or has valid information in its TimeSpan component.|  
|[GridLength](http://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.gridlength.aspx)|Represents the length of elements that explicitly support Star unit types.|  
|[GridUnitType](http://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.gridunittype.aspx)|Describes the kind of value that a GridLength object is holding.|  
|[Thickness](http://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.thickness.aspx)|Describes the thickness of a frame around a rectangle. Four Double values describe the Left, Top, Right, and Bottom sides of the rectangle, respectively.|  
  
## Windows.UI.Xaml.Controls.Primitives namespace  
  
|Types supported in the .NET for UWP apps|Description|  
|----------------------------------------------------------------------------------------------|-----------------|  
|[GeneratorPosition](http://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.controls.primitives.generatorposition.aspx)|Used to describe the position of an item that is managed by Windows.UI.Xaml.Controls.ItemContainerGenerator.|  
  
## Windows.UI.Xaml.Media namespace  
  
|Types supported in the .NET for UWP apps|Description|  
|----------------------------------------------------------------------------------------------|-----------------|  
|[Matrix](http://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.media.matrix.aspx)|Represents a 3x3 affine transformation matrix used for transformations in two-dimensional space.|  
  
## Windows.UI.Xaml.Media.Animation namespace  
  
|Types supported in the .NET for UWP apps|Description|  
|----------------------------------------------------------------------------------------------|-----------------|  
|[KeyTime](http://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.media.animation.keytime.aspx)|Specifies when a particular key frame should take place during an animation.|  
|[RepeatBehavior](http://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.media.animation.repeatbehavior.aspx)|Describes how a Windows.UI.Xaml.Media.Animation.Timeline repeats its simple duration.|  
|[RepeatBehaviorType](http://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.media.animation.repeatbehaviortype.aspx)|Specifies the repeat mode that a RepeatBehavior raw value represents.|  
  
## Windows.UI.Xaml.Media.Media3D namespace  
  
|Types supported in the .NET for UWP apps|Description|  
|----------------------------------------------------------------------------------------------|-----------------|  
|[Matrix3D](http://msdn.microsoft.com/library/windows/apps/windows.ui.xaml.media.media3d.matrix3d.aspx)|Represents a 4 × 4 matrix that is used for transformations in a three-dimensional (3-D) space.|  
  
## See Also  
 [.NET for Windows apps](../net-uwp/dotnet-for-windows-apps.md)