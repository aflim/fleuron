---
layout: page
title: Styleguide
description: Guides to structures and style content
---

## Heading
Limit heading to 3 level, `<h1>` tag use for page title/post title
# Heading level 1
## Heading level 2
### Heading level 3

## Paragraph
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance. The first line of Lorem Ipsum, "Lorem ipsum dolor sit amet..", comes from a line in section 1.10.32.

The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and 1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in their exact original form, accompanied by English versions from the 1914 translation by H. Rackham.

## Rule/border
---

## Inline style
- **Bolder text**
- *Italic text*
- ~~Deleted text~~
- <mark>Highlight text</mark>
- Abbreviation like this <abbr>html</abbr>
- <cite>Cite</cite>
- Inline code like this `<code>`

## Unordered list
- Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
- Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
- Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.

- Primary list
  - Secondary list
    - Tertiary list
- Primary list
  - Secondary list
    - Tertiary list

## Ordered list
1. Primary list
2. Primary list
3. Primary list

Tired number list
1. Primary
   1. Secondary primary
      1. Tertiary primary
      2. Tertiary primary
   2. Secondary primary
   3. Secondary primary
2. Secondary
   1. Secondary secondary
   2. Secondary secondary
      1. Tertiary secondary
      2. Tertiary secondary
   3. Secondary secondary
3. Tertiary
4. Fourth
5. Fifth

## Definition list
<dl>
  <dt>HyperText Markup Language (HTML)</dt>
  <dd>The language used to describe and define the content of a Web page</dd>

  <dt>Cascading Style Sheets (CSS)</dt>
  <dd>Used to describe the appearance of Web content</dd>

  <dt>JavaScript (JS)</dt>
  <dd>The programming language used to build advanced Web sites and applications</dd>
</dl>

## Figure
### Blockquote
<figure>
  <blockquote cite="https://www.huxley.net/bnw/four.html">
    <p>Words can be like X-rays, if you use them properly—they’ll go through anything. You read and you’re pierced.</p>
  </blockquote>
  <figcaption>—Aldous Huxley, <cite>Brave New World</cite></figcaption>
</figure>

Someone on internet said:
<figure>
  <blockquote cite="https://datatracker.ietf.org/doc/html/rfc1149">
    <p>
    Avian carriers can provide high delay, low throughput, and low altitude
    service. 
    </p>
    <p>
    The connection topology is limited to a single point-to-point path
    for each carrier, used with standard carriers, but many carriers can be used
    without significant interference with each other, outside early spring.
    This is because of the 3D ether space available to the carriers, in contrast
    to the 1D ether used by IEEE802.3.
    </p>
    <p>
    The carriers have an intrinsic collision
    avoidance system, which increases availability.
    </p>
  </blockquote>
</figure>

### Table
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Upvotes</th>
      <th>Downvotes</th>
    </tr>
  </thead>
  <tfoot>
    <tr>
      <td>Totals</td>
      <td>21</td>
      <td>23</td>
    </tr>
  </tfoot>
  <tbody>
    <tr>
      <td>Alice</td>
      <td>10</td>
      <td>11</td>
    </tr>
    <tr>
      <td>Bob</td>
      <td>4</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Charlie</td>
      <td>7</td>
      <td>9</td>
    </tr>
  </tbody>
</table>

### Image
<figure>
  <img src="https://picsum.photos/500/500" width="500" height="500" alt="placeholder image 500×500">
</figure>

<figure>
  <img src="https://picsum.photos/400/300" width="400" height="300" alt="placeholder image 400×300">
  <figcaption>Placeholder image 400×300</figcaption>
</figure>

### Embedded media
YouTube embedded video
<figure>
  <iframe src="https://www.youtube.com/embed/kdXfrMObAlA" width="720" height="480" frameborder="0" allowfullscreen style="aspect-ratio: 16/9;">
  </iframe>
</figure>

<figure>
  <iframe src="https://www.youtube.com/embed/kdXfrMObAlA" width="720" height="480" frameborder="0" allowfullscreen style="aspect-ratio: 16/9;">
  </iframe>
  <figcaption>With caption</figcaption>
</figure>

### Code snippets
Using `<pre>` tag
<figure>
  <pre>
// Example can be run directly in your JavaScript console

// Create a function that takes two arguments and returns the sum of those arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
  </pre>
</figure>

Using rouge highlighter
{% highlight js %}
// Example can be run directly in your JavaScript console

// Create a function that takes two arguments and returns the sum of those arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
{% endhighlight %}

## Message
<p class="msg">
  Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur
</p>

<p class="msg-info">
  Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur
</p>

<p class="msg-success">
  Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur
</p>

<p class="msg-warning">
  Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur
</p>

<p class="msg-danger">
  Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur
</p>


