# KOR.Theme.ColorAndIcons
Custom Colors and Icons for WPF Projects

## App.xaml
Add as resource dictionary and ready to use

```xaml
<Application.Resources>
    <ResourceDictionary>
        <ResourceDictionary.MergedDictionaries>
            <!-- Colors -->
            <ResourceDictionary Source="pack://application:,,,/KOR.Theme.ColorAndIcons;component/Colors.xaml"/>
            <!-- Icons -->
            <ResourceDictionary Source="pack://application:,,,/KOR.Theme.ColorAndIcons;component/Icons.xaml"/>
        </ResourceDictionary.MergedDictionaries>
    </ResourceDictionary>
</Application.Resources>
```

## Colors

```xaml
... Bakcground="{StaticResource BlueGrey200}" ...
```

## Icons

```xaml
<Path Height="20" Width="30" Stretch="Uniform"
      Data="{Binding Source={StaticResource Console}, Path=Data}"
      Fill="{StaticResource BlueGrey200}"/>
```