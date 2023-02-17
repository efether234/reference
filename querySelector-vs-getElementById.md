# querySelector() vs getElementById()

## querySelector()

- Used to select by any css selector.
- Can be id or class

`document.querySelector("#foo").innerHTML = "Hello, World!";`

## getElementById()

- Can only use id
- More restrictive than querySelector()

`document.getElementById("foo").innerHTML = "Hello, World!";`
