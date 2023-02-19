# Project 8

## Original Output Image

![Original Output Image](./original%20output%20image.png)

![Task 1 Image](./ass8.1-before.png)

## Task 1: Achieve the following Output using JavaScript DOM Manipulation

![Task 1 Image](./ass8.1-after.png)

## JavaScript Code:

```js
const newClass = document.querySelector(".new");
const hr = document.createElement("hr");
const h2 = document.createElement("h2");

h2.className = "new-head";
h2.innerText = "This is my custom heading";
newClass.style.overflow = "scroll";
newClass.append(hr);
newClass.append(h2);
```

---

![Task 2 Image](./ass8.2-before.png)

## Task2: Achieve the following Output using JavaScript DOM Manipulation

![Task 2 Image](./ass8.2-after.png)

## JavaScript Code:

```js
const body = document.body;

body.style.backgroundImage = "none";
```

---

![Task 3 Image](./ass8.3-before.png)

## Task3: Achieve the following Output using JavaScript DOM Manipulation

![Task 3 Image](./ass8.3-after.png)

## JavaScript Code:

```js
const btn = document.querySelector(".navbar-toggler");
const navbarToggler = document.getElementById("navbarTogglerDemo01");
let flag = true;

btn.addEventListener("click", (e) => {
  if (flag) {
    navbarToggler.style.display = "block";
    flag = false;
  } else {
    navbarToggler.style.display = "none";
    flag = true;
  }
});
```
