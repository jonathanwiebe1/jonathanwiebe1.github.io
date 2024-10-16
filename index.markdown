---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
image: /assets/images/dsc_0225.jpg
---

Hi

![Image]({{ page.image }})

```html
<img src="{{ page.image | relatice-url }}" alt="" height="80px" width="100%" style="object-fit: cover">
```

{% include image1.html %}
