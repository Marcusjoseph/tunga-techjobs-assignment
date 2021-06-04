# Emmet Exercises

### Write the one-line Emmet commands to produce the following HTML

1. `<h1></h1>` 
``` html
h1
```
2.   `<div>`

       `<p>`

        `<section>`

     `<h1>Nice!</h1>`

        `</section>`

      `</p>`

     `</div>`
```html
div>p>section>h1{Nice}*1
```

3. `<ul>outside`

    `<li>inside</li>`
    `<li>inside</li>`
    `<li>inside</li>`
    `<li>inside</li>`
`</ul>`
```html
ul>outside>li{inside}*4
```

4. `<p>sibling 1</p>`

`<div>sibling 2</div>`

`<p>parent`

 `<div>child`

`<div>grandchild</div>`

`</div>`

`</p>`
```html
p{sibling 1}+div{sibline 2}+p{perent}>div{child}>div{grandchiled}*1
```
