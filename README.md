

# BarBStyle.Colors.Theme NuGet Package

<a href="https://imgur.com/HO23zQj"><img src="https://i.imgur.com/HO23zQj.jpg" title="source: imgur.com" /></a>


## Description

Introducing the BarB Color Theme: the chicest, sassiest, and most fabulous color theme in the digital universe. Inspired by the iconic Barbie doll, this theme is the ultimate way to infuse your apps with a heavy dose of pink power, and a sprinkle of glitter (virtual glitter, of course).

## Installation

You can install this NuGet package using the NuGet Package Manager Console:

```bash
Install-Package BarBStyle.Colors.Theme
```

## Usage

Once you've installed the BarBStyle NuGet package, you can apply the theme to your application by following these steps:

1. Reference the package in your App.xaml file :

```<Application.Resources>
        <ResourceDictionary>
            <ResourceDictionary.MergedDictionaries>
                <XamlControlsResources xmlns="using:Microsoft.UI.Xaml.Controls" />
                <!-- Other merged dictionaries here -->
                <ResourceDictionary Source="ms-appx:///BarBStyle.Colors.Theme/BarBTheme/BarBResourceDictionary.xaml"/>
            </ResourceDictionary.MergedDictionaries>
            <!-- Other app resources here -->
        </ResourceDictionary>
    </Application.Resources>
```

  2. Run your application and marvel at the pinkness!

## Features

- **Stunning Pink Color Palette**: The colors were selected and carefully tested to have the perfect balance of vibrancy and contrast, while still being easy on the eyes.
- **14 shades of Pink**: The theme includes 14 shades of pink. You don't need to apply the style locally to each control.


## Example

``` <Button Style="{StaticResource AccentButtonStyle}">Click Me</Button>```

<a href="https://imgur.com/JLxPjaN"><img src="https://i.imgur.com/JLxPjaN.png" title="source: imgur.com" /></a>


## Contributing

Contributions to this Pink Theme NuGet package are welcome. If you have any suggestions, bug reports, or feature requests, please [create an issue](https://github.com/teresathompson/Avalon.BarBStyle.Colors/issues).

## License

This BarBStyle NuGet package is licensed under the [MIT License](LICENSE).



