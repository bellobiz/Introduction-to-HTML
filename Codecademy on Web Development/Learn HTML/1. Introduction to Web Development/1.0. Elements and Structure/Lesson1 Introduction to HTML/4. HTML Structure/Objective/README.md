<a href="http://ssqt.co/mQfpbL0"><span>INTRODUCTION TO HTML</span></a>
<h2><a href="https://www.codecademy.com/paths/web-development/tracks/learn-html-web-dev-path/modules/learn-html-elements/lessons/intro-to-html/exercises/structure-html">HTML Structure</a></h2>
<em>HTML is organized as a collection of family tree relationships</em>. As you saw in the last exercise, we placed <code><b>&lt;p&gt;</b></code> tags within <code><b>&lt;body&gt;</b></code> tags. When an element is contained inside another element, it is considered the child of that element. The <strong>child element</strong> is said to be nested inside of the parent element.<br>
<br>
<img src="https://cdn-images-1.medium.com/max/800/1*Xlw1ULC03dj6pyJEV9HITg.png" alt="child element tag, p in parent tag, body"><br>

In the example above, the <code><b>&lt;p&gt;</b></code> element is nested inside the <code><b>&lt;body&gt;</b></code> element. The <code><b>&lt;p&gt;</b></code> element is considered a child of the <code><b>&lt;body&gt;</b></code> element, and the <code><b>&lt;body&gt;</b></code> element is considered the parent. You can also see that we’ve added two spaces of indentation (using the space bar) for better readability.<br>

Since there can be multiple levels of nesting, this analogy can be extended to grandchildren, great-grandchildren, and beyond. The relationship between elements and their ancestor and descendent elements is known as hierarchy.<br>
<br>
Let’s consider a more complicated example that uses some new tags:<br>

<img src="https://cdn-images-1.medium.com/max/800/1*wdN2Lh_ksBMUwQQxjyRBaw.png" alt="HTML hierarchy"><br>

In this example, the <code><b>&lt;body&gt;</b></code> element is the parent of the <div> element. Both the <code><b>&lt;h1&gt;</b></code> and <code><b>&lt;p&gt;</b></code> elements are children of the <code><b>&lt;div&gt;</b></code> element. Because the <code><b>&lt;h1&gt;</b></code> and <code><b>&lt;p&gt;</b></code> elements are at the same level, they are considered siblings and are both grandchildren of the <body> element.<br>

Understanding HTML hierarchy is important because child elements can inherit behavior and styling from their parent element. You’ll learn more about webpage hierarchy when you start digging into CSS.
<br>
<h6>Instructions</h6>
1.
Add the paragraph below as a child of the div element.<br>
<br>
<img src="https://cdn-images-1.medium.com/max/800/1*PTbnB7zttjMogJVDs1y45A.png" alt="Add the paragraph below as a child of the div element.">
