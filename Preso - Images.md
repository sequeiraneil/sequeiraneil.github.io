---
theme: league
bg: "#D4A373"
padding: 5px
---
# Working with Images <!-- .slide bg="#E9EDC9"= -->

---

## Single Image

---

Image Dimensions: 960 x 720px

Source: [Pixabay](https://pixabay.com/photos/fly-insect-green-bottle-fly-8461020/)

![](https://cdn.pixabay.com/photo/2023/12/21/01/20/fly-8461020_960_720.jpg)

---

## The problem

Image is too big for the slide, so bottom is cropped.

---

## Option 1:

## Resize the image within markdown

---

Resized to ?px x ?px

syntax: `![|360](pic_source.jpg)`

<split left="1" right="2" gap="1">
![|360](https://cdn.pixabay.com/photo/2023/12/21/01/20/fly-8461020_960_720.jpg)
![|480](https://cdn.pixabay.com/photo/2023/12/21/01/20/fly-8461020_960_720.jpg)
</split>

---


## Option 2:

## Use as a background image


---

syntax:

` <!-- s lide bg="pic_source.jpg" -->`


<!-- slide bg="https://cdn.pixabay.com/photo/2023/12/21/01/20/fly-8461020_960_720.jpg" -->


---

<!-- slide bg="https://cdn.pixabay.com/photo/2023/12/21/01/20/fly-8461020_960_720.jpg" data-background-opacity="0.5" -->

`data-background-opacity` <br>to make the text jump out


but you might lose the sharpness of the picture 

(set at 0.5 here) <!-- element style="font-size:18px" -->


---

## `data-background-size`
options are `cover` or `contain`

---

<!-- slide bg="https://cdn.pixabay.com/photo/2023/12/21/01/20/fly-8461020_960_720.jpg" data-background-size="contain" -->

`data-background-size="contain"` <!-- element frag="1" -->

---

<!-- slide bg="https://cdn.pixabay.com/photo/2023/12/21/01/20/fly-8461020_960_720.jpg" data-background-size="cover" -->

`data-background-size="cover"` <!-- element frag="1" -->

