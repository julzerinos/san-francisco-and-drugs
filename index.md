---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<br/>

> 🎵 If you're going to San Francisco, be sure to wear some flowers in your hair 🎵

<br/>

{% include_relative _content/introduction.md %}

---

{% include_relative _content/history.md %}

---

{% include_relative _content/trend.md %}

---

{% include_relative _content/district.md %}

---

{% include_relative _content/summary.md %}

---
Add new section as separate markdown with `{{ '{' }}% include_relative _content/section_name.md %}`