---
description: something about CSS
---

# something about CSS

Font attribute defines font, boldness, size and word style.&#x20;

On computer's screen, `sans-serif` is regarded eaiser to read than `serif` .



## CSS font type

In CSS, there are two types of font series.

* **general font series**:  fonts which has similiar looklike.
* **special font series**: the specific font series.

`font-family` you should use two or more fonts in case the browser didn't support one.

```css
p {
    font-family: "Jetbrains Mono", "Microsoft YaHei", "New Times Roman";
}

```

`font-style` assign italic font's style. this attribute has 3 values.

* normal&#x20;
* italic
* oblique

```css
p.normal {
    font-style: normal;
}
```

`font-size` in webpage design, it's vital to manage the size of fonts. But you must's change font size to make paragraphs looks like headlines or make headlines looks like paragraphs.

> It is advised to change font-size by `em` rather than `px`.
>
> 1 em = 16px.
>
> function is `1px/16 = 1 em.`&#x20;

{% hint style="info" %}
Q: Is there one attribute named **`font-color`** ?&#x20;

A: No, it's named **`color`** .
{% endhint %}



