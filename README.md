# EpiEssentials.Public
Documentation and issue tracking for EpiEssentials, a collection of plugins for Episerver.

## EpiEssential.CategoryHide

Hide the category edit field.

To use, install the package in your project.

[NuGet package](https://www.nuget.org/packages/EpiEssentials.CategoryHide/)

## EpiEssential.CategoryToSettingsTab

Move the category edit field to the Settings tab.

To use, install the package in your project.

[NuGet package](https://www.nuget.org/packages/EpiEssentials.CategoryToSettingsTab/)

## EpiEssentials.ContentAreaMaxItems

Limit how many items can go into a content area.

To use, put the attribute on your property:

    [ContentAreaMaxItems(1)]

[NuGet package](https://www.nuget.org/packages/EpiEssentials.ContentAreaMaxItems/)

## EpiEssentials.EditorDescriptors

More options for input fields in the episerver editor.

To use, put the attribute on your property:

     [UIHint(EpiEssentials.Web.UIHint.Long)]

[NuGet package](https://www.nuget.org/packages/EpiEssentials.EditorDescriptors/)

## EpiEssentials.EditorPropertyDescriptions

Show property descriptions in the Episerver editor.

To use, install the package in your project.

[NuGet package](https://www.nuget.org/packages/EpiEssentials.EditorPropertyDescriptions/)

## EpiEssentials.EnumProperties

Render an enum field as a dropdown in the editor.

To use, put the attribute on your property:

    [EditorDescriptor(EditorDescriptorType = typeof(EnumEditorDescriptor<YourEnum>))]

[NuGet package](https://www.nuget.org/packages/EpiEssentials.EnumProperties/)

## EpiEssentials.Instances

Find instances of Page and Block types in Episerver.

[NuGet package](https://www.nuget.org/packages/EpiEssentials.Instances/)

## EpiEssentials.LoginImages

Set your own background images and logo on the episerver login screen.

To use, set these appsettings:

    <add key="Episerver.Login.Logo" value="/Content/logo.svg" />
    <add key="Episerver.Login.Background1" value="/Content/background1.png" />
    <add key="Episerver.Login.Background2" value="/Content/background2.png" />
    <add key="Episerver.Login.Background3" value="/Content/background3.png" />

To use only one background image, set all three values to the same image.

[NuGet package](https://www.nuget.org/packages/EpiEssentials.LoginImages/)

## EpiEssentials.Nostalgia

Make the new Episerver UI look a bit more like the old one.

[NuGet package](https://www.nuget.org/packages/EpiEssentials.Nostalgia/)

## EpiEssentials.Orphans

Find and remove orphaned models and properties.

[NuGet package](https://www.nuget.org/packages/EpiEssentials.Orphans/)

