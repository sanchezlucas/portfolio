+++
author = "Hugo Authors"
title = "Markdown Syntax Guide"
date = "2019-03-11"
description = "Sample article showcasing basic Markdown syntax and formatting for HTML elements."
tags = [
    "markdown",
    "css",
    "html",
]
categories = [
    "themes",
    "syntax",
]
thumbnail= "images/landscape.jpg"
series = ["Themes Guide"]
aliases = ["migrate-from-jekyl"]
+++

Hugo has `figure` shortcode built-in, so you can easily add figure captions or hyperlink rel attributes to images. Documentations can be found here:

https://gohugo.io/content-management/shortcodes/#figure

This theme has 3 CSS classes made for figure elements:

- `big`: images will break the width limit of main content area.
- `left`: images will float to the left.
- `right`: images will float to the right.

If a figure has no class set, the image will behave just like a normal markdown image: `![]()`.

Here are some examples; please be aware that these styles only take effect when the page width is over 1300px.

{{< figure src="https://via.placeholder.com/1600x800" alt="image" caption="figure-normal (without any classes)" >}}

Pellentesque posuere sem nec nunc varius, id hendrerit arcu consequat. Maecenas commodo, sapien ut gravida porttitor, dolor risus facilisis enim, eget pharetra nibh nisl porttitor sapien. Proin finibus elementum ligula sit amet hendrerit. Praesent et erat sodales ante accumsan pharetra non eu nulla. Sed vehicula consequat lorem, a fermentum ante faucibus quis. Aliquam erat volutpat. In vitae tincidunt dui. Proin sit amet ligula sodales, elementum tortor et, venenatis sem. Maecenas non nisl erat. Curabitur nec velit eros. Ut cursus lacus nisi, non pretium libero euismod et. Fusce luctus in nisi quis sollicitudin. Aenean nec blandit ligula. Duis ac felis lorem. Proin tellus tellus, dictum nec tempus sit amet, venenatis ac felis. Sed in pharetra nulla, non mollis sem.

{{< figure src="https://via.placeholder.com/1600x800" alt="image" caption="figure-big" class="big" >}}

Donec nec tincidunt est. Sed id metus in erat fringilla mattis at id turpis. Aliquam tempor vehicula faucibus. Phasellus consequat aliquam odio. Morbi a ex vitae sapien porta auctor. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec sit amet nulla arcu. Praesent ut tortor purus. Praesent id eros diam. Pellentesque vitae dolor at nibh ultrices accumsan eu id urna. Aliquam finibus interdum orci in varius. Pellentesque a enim condimentum, condimentum felis id, vehicula augue. Vivamus cursus commodo eros nec lacinia.

{{< figure src="https://via.placeholder.com/1600x800" alt="image" caption="figure-medium" class="medium" >}}

In a libero varius, luctus ligula et, bibendum tortor. Sed sit amet dui malesuada, mattis justo id, ultricies enim. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Aliquam sollicitudin cursus feugiat. Vivamus suscipit ipsum eget lobortis sollicitudin. Fusce vehicula neque tellus. Integer eu posuere quam, id laoreet tortor. Mauris sit amet turpis urna. Donec venenatis tempor dolor, nec laoreet orci aliquet et. Sed condimentum elit eu tristique aliquam. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nunc luctus ipsum sit amet nisl maximus pellentesque.

{{< figure src="https://via.placeholder.com/1600x800" alt="image" caption="figure-small" class="small" >}}

Pellentesque posuere sem nec nunc varius, id hendrerit arcu consequat. Maecenas commodo, sapien ut gravida porttitor, dolor risus facilisis enim, eget pharetra nibh nisl porttitor sapien. Proin finibus elementum ligula sit amet hendrerit. Praesent et erat sodales ante accumsan pharetra non eu nulla. Sed vehicula consequat lorem, a fermentum ante faucibus quis. Aliquam erat volutpat. In vitae tincidunt dui. Proin sit amet ligula sodales, elementum tortor et, venenatis sem. Maecenas non nisl erat. Curabitur nec velit eros. Ut cursus lacus nisi, non pretium libero euismod et. Fusce luctus in nisi quis sollicitudin. Aenean nec blandit ligula. Duis ac felis lorem. Proin tellus tellus, dictum nec tempus sit amet, venenatis ac felis. Sed in pharetra nulla, non mollis sem.

{{< figure src="https://via.placeholder.com/1600x800" alt="image" caption="figure-tiny" class="tiny" >}}

Suspendisse fringilla malesuada massa, in malesuada orci lacinia a. Praesent dapibus faucibus nisl, id volutpat elit bibendum eu. Nulla vitae laoreet nibh, eu hendrerit lacus. Donec lacinia auctor ligula, vel interdum ipsum malesuada vitae. Donec placerat a justo eu gravida. Aenean ultricies imperdiet convallis. Pellentesque accumsan non ex sed euismod. Proin bibendum lectus nec enim faucibus feugiat. Donec hendrerit nisi viverra ornare luctus. Nullam non viverra nisl. Nam vel tellus et tortor elementum volutpat sit amet et erat. Aliquam a libero quis libero porta consectetur. Etiam aliquam felis vel nulla mattis finibus. Mauris laoreet lacus arcu, sed rhoncus odio condimentum sed. Aenean in dui rutrum elit faucibus faucibus nec fringilla augue. Fusce non ornare mauris.

{{< figure src="https://via.placeholder.com/400x280" alt="image" caption="figure-left" class="left" >}}

In a libero varius, luctus ligula et, bibendum tortor. Sed sit amet dui malesuada, mattis justo id, ultricies enim. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Aliquam sollicitudin cursus feugiat. Vivamus suscipit ipsum eget lobortis sollicitudin. Fusce vehicula neque tellus. Integer eu posuere quam, id laoreet tortor. Mauris sit amet turpis urna. Donec venenatis tempor dolor, nec laoreet orci aliquet et. Sed condimentum elit eu tristique aliquam. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nunc luctus ipsum sit amet nisl maximus pellentesque.

{{< figure src="https://via.placeholder.com/400x280" alt="image" caption="figure-right" class="right" >}}

Pellentesque eu consequat nunc. Vivamus eu eros ut nulla dapibus molestie in id tortor. Cras viverra ligula erat, tincidunt hendrerit diam blandit nec. Cras id urna vel dolor dictum mattis. Vestibulum congue erat ac eros molestie accumsan. Maecenas lorem nibh, maximus vel justo eget, facilisis egestas lectus. Mauris eu est ut odio blandit consequat id feugiat eros. Fusce id suscipit mi, et lacinia lectus. Mauris a arcu placerat dolor iaculis feugiat nec non mi. Ut porttitor elit tortor, eget tempus velit mollis eu. Aliquam sem nulla, dictum cursus mauris ac, semper ullamcorper leo.

Donec nec tincidunt est. Sed id metus in erat fringilla mattis at id turpis. Aliquam tempor vehicula faucibus. Phasellus consequat aliquam odio. Morbi a ex vitae sapien porta auctor. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec sit amet nulla arcu. Praesent ut tortor purus. Praesent id eros diam. Pellentesque vitae dolor at nibh ultrices accumsan eu id urna. Aliquam finibus interdum orci in varius. Pellentesque a enim condimentum, condimentum felis id, vehicula augue. Vivamus cursus commodo eros nec lacinia.





-----



Thumbnails can be enabled easily by setting the `thumbnail` parameter in the frontmatter to an image such as `"images/landscape.jpg"`.

Make sure to copy the image the `static/images/` directory.

If put together, it will look like this (that's in fact this post's frontmatter):

```md
+++
author = "Hugo Authors"
title = "Guide to Thumbnails in Hugo"
date = "2019-03-04"
description = "Guide to Thumbnails in Hugo"
tags = [
    "thumbnail",
]
thumbnail= "images/landscape.jpg"
+++
```

-------


This article offers a sample of basic Markdown syntax that can be used in Hugo content files, also it shows whether basic HTML elements are decorated with CSS in a Hugo theme.

<!--more-->

## Headings

The following HTML `<h1>`—`<h6>` elements represent six levels of section headings. `<h1>` is the highest section level while `<h6>` is the lowest.

# H1

## H2

### H3

#### H4

##### H5

###### H6

## Paragraph

Xerum, quo qui aut unt expliquam qui dolut labo. Aque venitatiusda cum, voluptionse latur sitiae dolessi aut parist aut dollo enim qui voluptate ma dolestendit peritin re plis aut quas inctum laceat est volestemque commosa as cus endigna tectur, offic to cor sequas etum rerum idem sintibus eiur? Quianimin porecus evelectur, cum que nis nust voloribus ratem aut omnimi, sitatur? Quiatem. Nam, omnis sum am facea corem alique molestrunt et eos evelece arcillit ut aut eos eos nus, sin conecerem erum fuga. Ri oditatquam, ad quibus unda veliamenimin cusam et facea ipsamus es exerum sitate dolores editium rerore eost, temped molorro ratiae volorro te reribus dolorer sperchicium faceata tiustia prat.

Itatur? Quiatae cullecum rem ent aut odis in re eossequodi nonsequ idebis ne sapicia is sinveli squiatum, core et que aut hariosam ex eat.

## Blockquotes

The blockquote element represents content that is quoted from another source, optionally with a citation which must be within a `footer` or `cite` element, and optionally with in-line changes such as annotations and abbreviations.

#### Blockquote without attribution

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **Note** that you can use _Markdown syntax_ within a blockquote.

#### Blockquote with attribution

> Don't communicate by sharing memory, share memory by communicating.<br>
> — <cite>Rob Pike[^1]</cite>

[^1]: The above quote is excerpted from Rob Pike's [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015.

## Tables

Tables aren't part of the core Markdown spec, but Hugo supports supports them out-of-the-box.

| Name  | Age |
| ----- | --- |
| Bob   | 27  |
| Alice | 23  |

#### Inline Markdown within tables

| Italics   | Bold     | Code   |
| --------- | -------- | ------ |
| _italics_ | **bold** | `code` |

## Code Blocks

#### Code block with backticks

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Example HTML5 Document</title>
  </head>
  <body>
    <p>Test</p>
  </body>
</html>
```

#### Code block indented with four spaces

    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="utf-8" />
        <title>Example HTML5 Document</title>
      </head>
      <body>
        <p>Test</p>
      </body>
    </html>

#### Code block with Hugo's internal highlight shortcode

{{< highlight html >}}

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Example HTML5 Document</title>
  </head>
  <body>
    <p>Test</p>
  </body>
</html>
{{< /highlight >}}

## List Types

#### Ordered List

1. First item
2. Second item
3. Third item

#### Unordered List

- List item
- Another item
- And another item

#### Nested list

- Fruit
  - Apple
  - Orange
  - Banana
- Dairy
  - Milk
  - Cheese

## Other Elements — abbr, sub, sup, kbd, mark

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.



-----


The notice shortcode supports three different types of disclaimers. These are as following:

## Info Notice

```
{{%/* notice info */%}}
Lorem Impsum..
{{%/* /notice */%}}
```

{{< notice info >}}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
{{< /notice >}}

## Update Notice

```
{{%/* notice update */%}}
Lorem Impsum..
{{%/* /notice */%}}
```

{{< notice update >}}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
{{< /notice >}}

## Warning Notice

```
{{%/* notice warning */%}}
Lorem Impsum..
{{%/* /notice */%}}
```

{{< notice warning >}}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
{{< /notice >}}



----


Lorem est tota propiore conpellat pectoribus de pectora summo. <!--more-->Redit teque digerit hominumque toris verebor lumina non cervice subde tollit usus habet Arctonque, furores quas nec ferunt. Quoque montibus nunc caluere tempus inhospita parcite confusaque translucet patri vestro qui optatis lumine cognoscere flos nubis! Fronde ipsamque patulos Dryopen deorum.

1. Exierant elisi ambit vivere dedere
2. Duce pollice
3. Eris modo
4. Spargitque ferrea quos palude

Rursus nulli murmur; hastile inridet ut ab gravi sententia! Nomine potitus silentia flumen, sustinet placuit petis in dilapsa erat sunt. Atria tractus malis.

1. Comas hunc haec pietate fetum procerum dixit
2. Post torum vates letum Tiresia
3. Flumen querellas
4. Arcanaque montibus omnes
5. Quidem et

# Vagus elidunt

<svg class="canon" xmlns="http://www.w3.org/2000/svg" overflow="visible" viewBox="0 0 496 373" height="373" width="496"><g fill="none"><path stroke="#000" stroke-width=".75" d="M.599 372.348L495.263 1.206M.312.633l494.95 370.853M.312 372.633L247.643.92M248.502.92l246.76 370.566M330.828 123.869V1.134M330.396 1.134L165.104 124.515"></path><path stroke="#ED1C24" stroke-width=".75" d="M275.73 41.616h166.224v249.05H275.73zM54.478 41.616h166.225v249.052H54.478z"></path><path stroke="#000" stroke-width=".75" d="M.479.375h495v372h-495zM247.979.875v372"></path><ellipse cx="498.729" cy="177.625" rx=".75" ry="1.25"></ellipse><ellipse cx="247.229" cy="377.375" rx=".75" ry="1.25"></ellipse></g></svg>

[The Van de Graaf Canon](https://en.wikipedia.org/wiki/Canons_of_page_construction#Van_de_Graaf_canon)

## Mane refeci capiebant unda mulcebat

Victa caducifer, malo vulnere contra dicere aurato, ludit regale, voca! Retorsit colit est profanae esse virescere furit nec; iaculi matertera et visa est, viribus. Divesque creatis, tecta novat collumque vulnus est, parvas. **Faces illo pepulere** tempus adest. Tendit flamma, ab opes virum sustinet, sidus sequendo urbis.

Iubar proles corpore raptos vero auctor imperium; sed et huic: manus caeli Lelegas tu lux. Verbis obstitit intus oblectamina fixis linguisque ausus sperare Echionides cornuaque tenent clausit possit. Omnia putatur. Praeteritae refert ausus; ferebant e primus lora nutat, vici quae mea ipse. Et iter nil spectatae vulnus haerentia iuste et exercebat, sui et.

Eurytus Hector, materna ipsumque ut Politen, nec, nate, ignari, vernum cohaesit sequitur. Vel **mitis temploque** vocatus, inque alis, _oculos nomen_ non silvis corpore coniunx ne displicet illa. Crescunt non unus, vidit visa quantum inmiti flumina mortis facto sic: undique a alios vincula sunt iactata abdita! Suspenderat ego fuit tendit: luna, ante urbem Propoetides **parte**.

{{< css.inline >}}

<style>
.canon { background: white; width: 100%; height: auto; }
</style>

{{< /css.inline >}}



-----


REDIRECT


<!--+++
author = "Hugo Authors"
title = "Redirect"
date = "2021-06-20"
description = "Usage of redirectUrl"
tags = [
    "redirect", "redirectUrl",
]
redirectUrl="https://gohugo.io"
+++

Forwarding to [gohugo](https://gohugo.io) using `redirectUrl`

{{% loading %}}-->




------




Hugo ships with several [Built-in Shortcodes](https://gohugo.io/content-management/shortcodes/#use-hugos-built-in-shortcodes) for rich content, along with a [Privacy Config](https://gohugo.io/about/hugo-and-gdpr/) and a set of Simple Shortcodes that enable static and no-JS versions of various social media embeds.

## <!--more-->

## YouTube Privacy Enhanced Shortcode

{{< youtube ZJthWmvUzzc >}}

<br>

---

## Twitter Simple Shortcode

{{< twitter_simple 1085870671291310081 >}}

<br>

---

## Vimeo Simple Shortcode

{{< vimeo_simple 48912912 >}}



-------



<!-----
author: Hugo Authors
title: Series Part 1
date: 2021-08-14
description: A brief guide to how to setup series part 1
series:
  - series-setup
----->

In this first part of the series we'll show you how to create a series

<!--more-->

As a first step we need to add series as a taxonomy. We can do this by editing the `config.toml`.
Note: We always need to define the existing taxonomies as well.

```toml
[taxonomies]
    category = "categories"
    series = "series"
    tag = "tags"
```

Now we have the series enabled, the next thing we need to do is add the series name in the FrontMatter.
For our example we'll use this post and the next part.

As you can see we've set the series to `series-setup`. We also do the same in the next parts of the series.
This end results should be a Front Matter that looks similar to this:

```md
---
author: Hugo Authors
title: Series Part 1
date: 2021-08-14
description: A brief guide to how to setup series part 1
series:
  - series-setup
---
```

Each individual post will now also show the other posts in the series under the `Posts in this Series` heading.


<!-----
author: Hugo Authors
title: Series Part 2
date: 2021-08-15
description: A brief guide to how to setup series part 2
series:
  - series-setup
----->

In this second part of the series we'll show you where to find the full series

<!--more-->

When you created a series, you'll probably want to link to the full set of blogposts.
In this example we used `series-setup` as our series name.

This means we can now go to [http://localhost:1313/series/series-setup/](http://localhost:1313/series/series-setup/) to see all the blog posts of this serie.
