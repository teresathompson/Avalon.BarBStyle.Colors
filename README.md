

# Avalon.BarBStyle.Colors NuGet Package

![cute-girl-doll-ai-generatedsmall](https://github.com/teresathompson/Avalon.BarBStyle.Colors/assets/13683620/2624221a-87e9-450f-9416-af46de07943d)


## Description

Introducing the Barbie Color Theme: the chicest, sassiest, and most fabulous color theme in the digital universe. Inspired by the iconic Barbie doll, this theme is the ultimate way to infuse your apps with a heavy dose of pink power, and a sprinkle of glitter (virtual glitter, of course).

## Installation

You can install this NuGet package using the NuGet Package Manager Console:

```bash
Install-Package Avalon.BarBStyle.Colors
```

## Usage

Once you've installed the BarBStyle NuGet package, you can apply the theme to your application by following these steps:

1. Reference the package in your App.xaml file :

```<Application.Resources>
        <ResourceDictionary>
            <ResourceDictionary.MergedDictionaries>
                <XamlControlsResources xmlns="using:Microsoft.UI.Xaml.Controls" />
                <!-- Other merged dictionaries here -->
                <ResourceDictionary Source="ms-appx:///Avalon.BarBStyle.Colors/BarBTheme/BarBResourceDictionary.xaml"/>
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

![BarbAccent](https://github.com/teresathompson/Avalon.BarBStyle.Colors/assets/13683620/b0674212-5f64-435a-b14c-680acd892c8d)


## Contributing

Contributions to this Pink Theme NuGet package are welcome. If you have any suggestions, bug reports, or feature requests, please [create an issue](https://github.com/teresathompson/Avalon.BarBStyle.Colors/issues).

## License

This BarBStyle NuGet package is licensed under the [MIT License](LICENSE).



