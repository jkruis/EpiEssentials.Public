# EpiEssentials.Public
Documentation and issue tracking for EpiEssentials, a collection of plugins for Episerver.

## EpiEssentials.Instances

Find instances of Page and Block types in Episerver.

[NuGet package](https://www.nuget.org/packages/EpiEssentials.Instances/)

## EpiEssentials.Orphans

Find and remove orphaned models and properties.

[NuGet package](https://www.nuget.org/packages/EpiEssentials.Orphans/)

## EpiEssentials.LoginImages

Set your own background images and logo on the episerver login screen.

To use, set these appsettings:

    <add key="Episerver.Login.Logo" value="/Content/logo.svg" />
    <add key="Episerver.Login.Background1" value="/Content/background1.png" />
    <add key="Episerver.Login.Background2" value="/Content/background2.png" />
    <add key="Episerver.Login.Background3" value="/Content/background3.png" />

To use only one background image, set all three values to the same image.

[NuGet package](https://www.nuget.org/packages/EpiEssentials.LoginImages/)

## EpiEssentials.EnumProperties

Render an enum field as a dropdown in the editor.

To use, put the attribute on your property:

    [EditorDescriptor(EditorDescriptorType = typeof(EnumEditorDescriptor<YourEnum>))]

[NuGet package](https://www.nuget.org/packages/EpiEssentials.EnumProperties/)

## EpiEssentials.ContentAreaMaxItems

Limit how many items can go into a content area.

To use, put the attribute on your property:

    [ContentAreaMaxItems(1)]

[NuGet package](https://www.nuget.org/packages/EpiEssentials.ContentAreaMaxItems/)


