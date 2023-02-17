# Creating and deleting DOM elements

## Create DOM elements

1. Get parent element from document
    ```
    const main = document.querySelector("#main");
    ```

2. Create new child element and append to parent element
    ```
    const newChild = document.createElement("p");
    const newChild.textContent = "Hello, World!";
    main.append(newChild);
    ```
