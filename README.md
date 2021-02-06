# Material.Icons.Avalonia
Avalonia control for display material icons from [Material.Icons](https://github.com/SKProCH/Material.Icons).  
Icons list can be found on the [materialdesignicons.com](https://materialdesignicons.com/) or in the demo application.

### Getting started
Install [Material.Icons.Avalonia nuget package](https://www.nuget.org/packages/Material.Icons.Avalonia/):
```
dotnet add package Material.Icons.Avalonia
```
Include styles in `App.xaml`
```
<Application ...>
  <Application.Styles>
    ...
    <StyleInclude Source="avares://Material.Icons.Avalonia/App.xaml"></StyleInclude>
  </Application.Styles>
</Application>
```
### Using
Use `MaterialIcon` control:
```
<avalonia:MaterialIcon Kind="Abacus"></avalonia:MaterialIcon>
```
The `Foreground` property controls the color of the icon.
