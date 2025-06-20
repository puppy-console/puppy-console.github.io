---
title: Installation
layout: doc_page
style: docs
---

{% capture git_install_text %}

---

**1.** Navigate to your project directory.

```bash
cd path/to/your_project
```

**2.** Clone the github directory.

```bash
git clone {{site.project-github}} addons/{{site.project-name}}
```

---

{%
    include admonition.html
    preset="warn"
    content="You may need to restart the editor after cloning your files."
%}

---

**3.** Enable the plugin:

```none
Project > Project Settings > Plugins > puppy-console > Enabled
```

---

{%
    include admonition.html
    preset="success"
    content="That's it! You should be good to go."
%}


{% endcapture %}


<!-- MAIN CONTENT -->

<details>
    <summary>
        Installing through <a href="https://git-scm.com/"><strong>Git</strong></a>:
    </summary>
    {{ git_install_text | markdownify }}
</details>

<details>
    <summary>
    Installing through <a href="https://godotengine.org/asset-library/asset"><strong>the Asset Library</strong></a>:
    </summary>
    <hr>
    {% 
        include admonition.html 
        preset="info"
        content="This option is unavailable at this time, apologies for the incovenience!"
    %}
</details>

---
