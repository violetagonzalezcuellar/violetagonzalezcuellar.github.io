---
layout: post
title:  "Chuleta markdown"
date:   2014-08-29 14:34:25
categories: jekyll update
tags: featured
image: /assets/article_images/2014-08-29-welcome-to-jekyll/desktop.jpg
---

Resaltar texto es muy sencillo. Existen varias opctiones:

{% highlight html %}
`resaltado`
*cursiva*
**negrita**
_subrayado_
{% endhighlight %}

También puedes incorporar videos de Youtube directamente en tu blog. Para ello le tienes que dar a compartir en youtube, pinchar en insertar y copiar el código que tiene un formato como este:

{% highlight html %}
<iframe width="560" height="315" src="//www.youtube.com/embed/a_426RiwST8" frameborder="0" allowfullscreen></iframe>
{% endhighlight %}

Después tienes que manipular un poco el código para que se vea bien en youtube. Elimina `allowfullscreen`e introduce un espacio entre `><`

{% highlight html %}
<iframe width="560" height="315" src="//www.youtube.com/embed/a_426RiwST8" frameborder="0" > </iframe>
{% endhighlight %}

