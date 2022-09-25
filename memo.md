# url

https://github.com/petersommerhoff/jquery-course/tree/master

# 2.animation

## tips

- animation queue
- happens instant
- animate for custom animation
- chaining / callback
  - callback runs one by one
  - chaining run asynchronously
- some dynamic content have no event
  - use `delegated event` to solve this
    - set event handler to parent element and delegate event handler to child
- stop - to prevent too many event

## methods

- fadeIn
- fadeOut
  - display: none
- fadeTo
  - change opacity
- hide
- show
- slideTop
- slideDown
- animate
  - custom animation

# 3. selectors

- find / children
  - find - non-direct children
  - children - direct children
- parents
  - non-direct parents
- parent
- siblings
- prev
- next

- filter
- first
- last
- eq

# 4. Manipulating the DOM I

- append / appendTo
  - same result
- prepend / prependTo
- before
- after

  - can use callback for complex task

- replaceWith

- remove
- detach
  - to use element later
  - keep element as it is including event, etc.
- empty

- attr
- prop
- val
  - for input value

# 5. Manipulating the DOM II

- css

  - can get multiple values using array
    `props['font-size']`
  - can pass callback function as a value to add logic
    `css('font-size', function(){ /* some logic */ return test; })`

- addClass
- removeClass
- toggleClass
- can pass callback function
  `addClass(function(index){$(this).addClass('class' + index)})`

- `data-mydata`
- data
- removeData

- content
  - not pure html
- html
- pure html

# 6. Event Handling

- $('#btn').click(function(){})
- $('#btn').click
- hover
- mouseenter
- mouseleave

- delegated event
- can pass data

  - use data `function(event){ event.data }`

# 7. Handling Form Events

- keydown

- focus
- blur

- change

- submit

# 8. AJAX

- load
- $.getAjax
