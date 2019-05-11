# FontAwesome-Icons-Dropdown-Umbraco-Plugin
FontAwesome Icons Dropdown Datatype. Labels are unicode while the values are class name.

### Instructions :

1) Download the package and Install it on your umbraco cms. 

2) Add "Font Awesome Icons" property to your document type.

### Umb 7 Code Sample :
```
<i class="fa @Model.Content.GetPropertyValue("yourAlias")"></i>
```

### Umb 8 Code Sample :
```
<i class="fa @Model.Value("yourAlias")"></i>
```
### Expected Output :
```
<i class="fa fa-heart" aria-hidden="true"></i>
```
 *Assuming you selected the heart icon on the cms

Notes :

This plugin uses font-awesome css and fonts (v4.6.3).

https://fortawesome.github.io/Font-Awesome/cheatsheet/


No copyright infringement intended , if this package violates any law , please reach me at : chrisadi.pascual (gmail) to take anything offline (or if you have any feedback or suggestions).

This Project and the Developer is not connected in anyway with the Font-Awesome Team.

### Shout Outs

5-11-19 : Thanks to Heather Floyd for reminding me to update for Umb8

9-5-18 : Thanks to Mike for the generous donation! It helps a lot!

10-17-16 :  Special thanks to Bjarne Fyrstenborg for correcting the razor sample.

### Like the plugin?

Engrish is not my first language - you are not required to donate stuff, this is for those
who can afford to help. Your kind messages also boosts my morale!

[Any amount is appreciated.](https://paypal.me/chrispascual/)
Money goes to noodle funds <3 

[A String of Noodle (Any noodle is good noodle)](https://paypal.me/chrispascual/1)

[Noodles with Soup](https://paypal.me/chrispascual/5)

[Lots of Noodles](https://paypal.me/chrispascual/10)
