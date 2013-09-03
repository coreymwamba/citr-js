citr-js
=======

The *cite* attribute is not presented to the reader by many browsers, even though it can hold important information. 

**citr.js** is JavaScript that exposes this information along with the title attribute in \<blockquote\> and \<q\> elements 
to create meaningful references. 

citr.js is made available under the GNU Affero General Public Licence.

usage
=====
In your HTML

+ create \<blockquote\> or \<q\> elements with *title* and/or *cite* attributes. For the *title*, write the reference in the format you want;
+ with \<q\> elements, trigger indirect quoting (no quotation marks) by setting the *class* to "indirect";
+ choose the type of reference by setting the *class* to either "marginalia" or "harvard" for \<q\>, or "footnote" for \<blockquote\> and \<q\> elements; and then
+ place citr.js in a \<script\> element at the end of the \<body\>.

citr.js will then marry up the URL in the *cite* attribute with the *title*; and optionally create a list of references. For examples and wider discussion, please head to [JavaScript Rendering of References for Quotations and Paraphrases](http://www.coreymwamba.co.uk/testbed/js-cite-quotes/).
