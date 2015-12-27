# HamburgerMenu
Windows 10 styled, customizable Hamburger Menu control for WPF

# Getting Started

## Install
From nuget:
```
Install-Package HamburgerMenu 
```

## Use
Add library reference in xaml:
```
xmlns:HamburgerMenu="clr-namespace:HamburgerMenu;assembly=HamburgerMenu"
```

Create a Hamburger Menu control and set Background Color, Menu Icon Color, Selection Indicator Color and Menu Item Foreground Color:
```
<HamburgerMenu:HamburgerMenu Background="Blue" MenuIconColor="White" SelectionIndicatorColor="White" MenuItemForeground="White" HorizontalAlignment="Left">
</HamburgerMenu:HamburgerMenu>
```

Add Menu Items and set their Icon and Text:
```
<HamburgerMenu:HamburgerMenu Background="Blue" MenuIconColor="White" SelectionIndicatorColor="White" MenuItemForeground="White" HorizontalAlignment="Left">
      <HamburgerMenu:HamburgerMenuItem Icon="Assets/home.png" Text="Home" SelectionCommand="{Binding ElementName=this_}"/>
      <HamburgerMenu:HamburgerMenuItem Icon="Assets/search.png" Text="Search"/>
      <HamburgerMenu:HamburgerMenuItem Icon="Assets/favorite.png" Text="Likes"/>
      <HamburgerMenu:HamburgerMenuItem Icon="Assets/list.png" Text="Lists"/>
      <HamburgerMenu:HamburgerMenuItem Icon="Assets/person.png" Text="Profile"/>
</HamburgerMenu:HamburgerMenu>
```
