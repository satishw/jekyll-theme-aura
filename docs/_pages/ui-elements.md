---
layout: page
title:  UI Elements
description: Life is short, and it’s up to you to make it sweet.
date:   2025-01-22 15:01:35 +0300
image:  '/images/vietnam.jpg'
toc: true
---

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

![River]({{ site.baseurl }}/images/forest1.jpg){: width="1200" height="900"}
*Photo by [Peter](https://freepik.com) on [Freepik](https://freepik.com)*

## Quote
> It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. 

## Gallery with 2 images
<div class="gallery-box">
  <div class="gallery">
    <img src="{{ site.baseurl }}/images/horses.jpg" alt="Rio">
    <img src="{{ site.baseurl }}/images/tiger3.jpg" alt="Rio">
  </div>
  <em>Gallery / <a href="https://freepik.com/" target="_blank">freepik</a></em>
</div>

## Gallery with 3 images
<div class="gallery-box">
  <div class="gallery">
    <img src="{{ site.baseurl }}/images/whale.jpg" alt="Rio">
    <img src="{{ site.baseurl }}/images/tiger2.jpg" alt="Rio">
    <img src="{{ site.baseurl }}/images/bear.jpg" alt="Rio">    
  </div>
  <em>Gallery / <a href="https://freepik.com/" target="_blank">freepik</a></em>
</div>

## Gallery with 6 images
<div class="gallery-box">
  <div class="gallery">
    <img src="{{ site.baseurl }}/images/two-elephants.jpg" alt="Rio">
    <img src="{{ site.baseurl }}/images/bear.jpg" alt="Rio">
    <img src="{{ site.baseurl }}/images/caribou.jpg" alt="Rio">
    <img src="{{ site.baseurl }}/images/rhino2.jpg" alt="Rio">
    <img src="{{ site.baseurl }}/images/red-fox.jpg" alt="Rio">  
    <img src="{{ site.baseurl }}/images/raccoon.jpg" alt="Rio">    
  </div>
  <em>Gallery / <a href="https://freepik.com/" target="_blank">freepik</a></em>
</div>

## Lists
### Unordered List
- Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum is simply dummy text of the printing and typesetting industry.
- Lorem Ipsum is simply dummy text of the printing and typesetting industry.
- Lorem Ipsum is simply dummy text of the printing and typesetting industry.
- Lorem Ipsum is simply dummy text of the printing and typesetting industry.

### Ordered List
1. Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum is simply dummy text of the printing and typesetting industry.
2. Lorem Ipsum is simply dummy text of the printing and typesetting industry.
3. Lorem Ipsum is simply dummy text of the printing and typesetting industry.
4. Lorem Ipsum is simply dummy text of the printing and typesetting industry.

## Youtube Video

<p><iframe src="https://www.youtube.com/embed/owK1qxDselE?si=O5Gy5TCUSHv3QGwA" frameborder="0" allowfullscreen></iframe></p>

## Infobox Style

{: .yellow-infobox}
It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.

{: .red-infobox}
It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.

<p class="green-infobox">
It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.
</p>

{: .blue-infobox}
It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.

## Tables

<table>
    <thead>
        <th>Column 1</th>
        <th>Column 2</th>
        <th>Column 3</th>
        <th>Column 4</th>
    </thead>
    <tbody>
        <tr>
            <td>Row 1 Column 1</td>
            <td>Row 1 Column 2</td>
            <td>Row 1 Column 3</td>
            <td>Row 1 Column 4</td>
        </tr>
        <tr>
            <td>Row 2 Column 1</td>
            <td>Row 2 Column 2</td>
            <td>Row 2 Column 3</td>
            <td>Row 2 Column 4</td>
        </tr>
        <tr>
            <td>Row 3 Column 1</td>
            <td>Row 3 Column 2</td>
            <td>Row 3 Column 3</td>
            <td>Row 3 Column 4</td>
        </tr>
        <tr>
            <td>Row 4 Column 1</td>
            <td>Row 4 Column 2</td>
            <td>Row 4 Column 3</td>
            <td>Row 4 Column 4</td>
        </tr>
    </tbody>
</table>

<table>
    <thead>
        <th>Column 1</th>
        <th>Column 2</th>
    </thead>
    <tbody>
        <tr>
            <td>Row 1 Column 1</td>
            <td>Row 1 Column 2</td>
        </tr>
        <tr>
            <td>Row 2 Column 1</td>
            <td>Row 2 Column 2</td>
        </tr>
        <tr>
            <td>Row 3 Column 1</td>
            <td>Row 3 Column 2</td>
        </tr>
        <tr>
            <td>Row 4 Column 1</td>
            <td>Row 4 Column 2</td>
        </tr>
    </tbody>
</table>


## Link
- This is [link](https://github.com) to external site

## Code
### Python

```python
def is_prime(n):
    if n <= 1:
        return False
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False
    return True

number = int(input("Enter a number to check if it's prime: "))
if is_prime(number):
    print(f"{number} is a prime number.")
else:
    print(f"{number} is not a prime number.")
```

### JS

```js
// Toggle visibility of additional content
document.getElementById('toggleButton').addEventListener('click', function() {
  const extraContent = document.getElementById('extraContent');
  if (extraContent.style.display === 'none' || extraContent.style.display === '') {
    extraContent.style.display = 'block';
  } else {
    extraContent.style.display = 'none';
  }
});
```

### HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Web Page</title>
</head>
<body>
    <h1>Welcome to My First Web Page!</h1>
    <p>This is a simple example of an HTML document.</p>
    <a href="https://www.example.com">Click here</a> to visit Example website.
</body>
</html>
```

## FAQ

<details>
  <summary>Why is your website so awesome?</summary>
  <p>It's the magic of caffeine, late-night coding, and a sprinkling of unicorn dust. Seriously, we just try to make sure it’s easy to use and full of fun!</p>
</details>

<details> <summary>What’s your secret to flawless website performance?</summary> <p>We bribe the servers with cookies and promise them a beach vacation if they stay fast!</p> </details>

<details> <summary>How do you manage to keep your code bug-free?</summary> <p>We’ve trained the bugs to stay in their own little corner and occasionally offer them a snack to keep them distracted.</p> </details>

<details> <summary>What do you do when the internet goes down?</summary> <p>We hold a support group for frustrated users and then take turns yelling at the Wi-Fi router. Sometimes, it works... sometimes.</p> </details>
