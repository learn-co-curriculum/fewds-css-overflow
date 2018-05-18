# Overflow

In CSS, there's an overflow property that allows the overflow of content to be controlled. Overflow can be set to `visible`, `hidden`, `scroll`, or `auto`. When the overflow is set to `visible`, you will be able to see content overflow outside of the fixed-size container, whereas when you set overflow to `hidden` the content will get truncated or chopped at the edge of the parent container. 

You can can also set overflow to `scroll` which will insert scroll bars into the element. Setting the overflow to `auto` will detect if the content is larger than the parent element, and will only create scroll bars if necessary. 

<iframe width="100%" height="300" src="//jsfiddle.net/flatiron_school/sFfw5/embedded/html,css,result/" allowpaymentrequest allowfullscreen="allowfullscreen" frameborder="0"></iframe>

The first element in the example is set with overflow to hidden, and the text is getting chopped off inside of the element. On the next one the overflow is set to scroll, so you can see a small scroll bar that will allow the content inside of the element to be scrolled. Lastly, wthere's an element with an overflow set to visible. You can see the overflowing content popping outside of the element. 

*Note: It's important that you always have a fixed height set on that element in order to use the overflow property.*
