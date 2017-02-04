#Code review comments

* Use meaningful class names, “fotfot” or “wtxt” are not good names.

* Pay attention to the weights of the fonts you used.

* Do not use “&” sign inside HTML, use “&amp;amp;”
[do-i-really-need-to-encode-as-amp](http://stackoverflow.com/questions/3493405/do-i-really-need-to-encode-as-amp)

* When pushing to GIT, write meaningful commit comments, “strdy night” is a bad example, It doesn’t tell your teammates what changes you have done.

* Page resources should not be inside the “styles” folder.

* Adding section breaks in a CSS file is a good practice. 

* In “.mnu1” the width of 100% is not needed because you are stretching the element using the position: absolute and the left:0 and right:0

* Will there be a difference if you change the display property from “inline-block” to “block” in “.mnu1”?

* Why is there a “clearfix” on the header element and on the first UL under the “.top-nav”?
