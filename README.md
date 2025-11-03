# FontAwesome-Icons-Dropdown-Umbraco-Plugin
FontAwesome Icons Dropdown Datatype. The labels display as Unicode characters, while the values store the class names.

### Instructions :

1) Install the package on your Umbraco CMS by downloading it manually or via NuGet: `dotnet add package FontAwesomeIconsDropdown`
2) Add the **"Font Awesome Icons"** property to your document type.

### Umbraco 7 Example :
```csharp
<i class="fa @Model.Content.GetPropertyValue("yourAlias")"></i>
```

### Umbraco 8 Example :
```csharp
<i class="fa @Model.Value("yourAlias")"></i>
```

### Expected Output :
```html
<i class="fa fa-heart" aria-hidden="true"></i>
```
*Example uses the heart icon.*

---

**Notes :**

This plugin uses Font Awesome CSS and fonts (v4.6.3).  
https://fortawesome.github.io/Font-Awesome/cheatsheet/

No copyright infringement intended.  
If this package violates any rights or you have feedback or suggestions, please raise an issue in this repo so I can take appropriate action.

**This project and its developer are not affiliated in any way with the Font Awesome team.**
---

### Acknowledgements

- **5-11-19:** Thanks to *Heather F.* for reminding me to update for Umbraco 8.  
- **9-5-18:** Thanks to *Mike B.* for the generous donation—it really helps!  
- **10-17-16:** Special thanks to *Bjarne F.* for correcting the Razor sample.

---

### Like the plugin?

English isn’t my first language. You don’t have to donate—this is only for those who want to help support development.  
Your kind messages also keep me motivated!

[Support the project on PayPal](https://paypal.me/chrispascual?currency_code=USD) — any amount is appreciated.  
All donations go toward development (and noodles ❤️).
