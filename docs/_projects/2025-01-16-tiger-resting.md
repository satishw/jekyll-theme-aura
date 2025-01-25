---
date: 2025-01-16 05:20:35 +0300
title: Tiger
subtitle: Wildlife
image: '/images/tiger2.jpg'
---

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.

## Photo
![River]({{ site.baseurl }}/images/forest1.jpg){: width="1200" height="900"}
*Photo by [Peter](https://freepik.com) on [Freepik](https://freepik.com)*

It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. 

> It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. 

Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. 

{: .red-infobox}
It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English.

## Python Code
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

## Image Gallery
<div class="gallery-box">
  <div class="gallery">
    <img src="{{ site.baseurl }}/images/whale.jpg" alt="Rio">
    <img src="{{ site.baseurl }}/images/tiger2.jpg" alt="Rio">
  </div>
  <em>Gallery / <a href="https://freepik.com/" target="_blank">freepik</a></em>
</div>

## FAQ
<details>
  <summary>Why is your website so awesome?</summary>
  <p>It's the magic of caffeine, late-night coding, and a sprinkling of unicorn dust. Seriously, we just try to make sure it’s easy to use and full of fun!</p>
</details>

<details> <summary>How do you ensure such great design consistency?</summary> <p>We’ve got a secret army of design ninjas who move swiftly through the pixels, making sure everything aligns perfectly. 🥷🖥️</p> </details>
