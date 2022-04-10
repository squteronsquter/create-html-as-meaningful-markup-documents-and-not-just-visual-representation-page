# Text in HTML

## Emphasis

```<em>``` - emphasis

<https://html.spec.whatwg.org/#the-em-element>

>Cats are cute animals.

>_Dogs_ are cute animals

The meaning of the sentence is changed because of the emphasis. We stress that dogs are cute!

```<i>``` - used to be visually the same, but semantically not the same, it was just visual italic texts and not text which we wanted to emphasize, put stress on.

## Importance

```<strong>``` - importance, urgency, seriousness

<https://html.spec.whatwg.org/#the-strong-element>
if you want to visually show bold fonts in a word or phrase you can still do in the old way using

```<b>``` - bold element, tag. This however carries no meaning, no importance, no sense of urgency or seriousness.

## Side Comments

```<small>``` - seerves as a side comment, disclaimer, attribution.

<https://html.spec.whatwg.org/#the-small-element>

>A good example of ```<small>``` tag usage is:

```
<dl>
 <dt>Single room
 <dd>199 € <small>breakfast included, VAT not included</small>
 <dt>Double room
 <dd>239 € <small>breakfast included, VAT not included</small>
</dl>
```
To indicate that VAT is not included. It's a comment and a disclaimer at the same time.

## Line breaks

```<br>``` - line break.

<https://html.spec.whatwg.org/#the-br-element>

```br``` elements must be used only for line breaks that are actually part of the content, as in poems or addresses.

>Example:

```
<p>P. Sherman<br>
42 Wallaby Way<br>
Sydney</p>
```
## Using ```<span>``` the right way

```<span>``` - has no meaning, must only be used to add a clas inline to a portion of an element or na attribute eg. lang attribute inside text.

<https://html.spec.whatwg.org/#the-span-element>

The ```span``` element doesn't mean anything on its own, but can be useful when used together with the global attributes, e.g. ```class```, ```lang```, or ```dir```. It represents its children.

> Example:

```
<pre><code class="lang-c"><span class="keyword">for</span> (<span class="ident">j</span> = 0; <span class="ident">j</span> &lt; 256; <span class="ident">j</span>++) {
  <span class="ident">i_t3</span> = (<span class="ident">i_t3</span> & 0x1ffff) | (<span class="ident">j</span> &lt;&lt; 17);
  <span class="ident">i_t6</span> = (((((((<span class="ident">i_t3</span> >> 3) ^ <span class="ident">i_t3</span>) >> 1) ^ <span class="ident">i_t3</span>) >> 8) ^ <span class="ident">i_t3</span>) >> 5) & 0xff;
  <span class="keyword">if</span> (<span class="ident">i_t6</span> == <span class="ident">i_t1</span>)
    <span class="keyword">break</span>;
}</code></pre>
```
