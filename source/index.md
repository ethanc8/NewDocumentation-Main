``````{div} landing-title
:style: "padding: 0.1rem 0.5rem 0.6rem 0; background-image: linear-gradient(315deg, #438ff9 0%, #1572f4 74%); clip-path: polygon(0px 0px, 100% 0%, 100% 100%, 0% calc(100% - 1.5rem)); -webkit-clip-path: polygon(0px 0px, 100% 0%, 100% 100%, 0% calc(100% - 1.5rem));"

`````{grid}
:reverse:
:gutter: 2 3 3 3
:margin: 4 4 1 2

````{grid-item}
:columns: 12 4 4 4

<!-- ```{image} ./_static/logo_square.svg
:width: 200px
:class: sd-m-auto sd-animate-grow50-rot20
``` -->
````

````{grid-item}
:columns: 12 8 8 8
:child-align: justify
:class: sd-text-white sd-fs-3

A set of cross-platform Cocoa-compatible frameworks to easily build amazing apps and web services.

```{button-ref} about/index
:ref-type: doc
:outline:
:color: white
:class: sd-px-4 sd-fs-5
Learn more
```

````
`````

``````

```{toctree}
---
hidden: true
---

about/index
install/index
objc/index
app/index
port/index
reference/index
```

::::{grid} 1 2 2 3
:margin: 4 4 0 0
:gutter: 1

:::{grid-item-card} {octicon}`download` Install GNUstep
:link: install/index
:link-type: doc

Install GNUstep on your system.
:::

:::{grid-item-card} {octicon}`paintbrush` Customize
:link: customize/index
:link-type: doc

Customize GNUstep to suit your needs and desired look.
:::

:::{grid-item-card} {octicon}`terminal` Learn Objective-C
:link: objc/index
:link-type: doc

Learn Objective-C, the preferred programming language for GNUstep. Build simple command-line tools.
:::

:::{grid-item-card} {octicon}`rocket` Build Apps
:link: app/index
:link-type: doc

Build example apps to learn the GNUstep framework
:::

:::{grid-item-card} {octicon}`squirrel` Port Apps
:link: port/index
:link-type: doc

Bring your Mac apps to other platforms.
:::

:::{grid-item-card} {octicon}`book` Reference Documentation
:link: reference/index
:link-type: doc

Dive further with API documentation and other frameworks.
:::

::::