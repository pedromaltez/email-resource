# Targeting Specific Mail Clients

Use the snippet described to target specific mail clients.


### Gmail

```css
u ~ div .foo {}
```

### Outlook App for iOS

```css
body[data-outlook-cycle] .foo {}
```

### Outlook Webmail

```css
[class="x_foo"] {}
```

### Outlook Webmail Dark Mode

```css
[data-ogsc] .darkmode .foo {}
```

### Outlook Webmail Light Mode

```css
[data-ogsc] .lightmode .foo {}
```

### Mozilla Thunderbird

```css
.moz-text-html .foo {}
```

### Yahoo Mail

```css
@media screen yahoo {
  .foo {}
}
```
