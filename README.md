Tabs at native JavaScript
=========================
Tabs which uses only JS, HTML and CSS.

How to use it
---------------
1) Your HTML tree must have this structure:

#### HTML-structure

    |body |
          |__wrapperMenuTabClass|
          |                     |__menuTabClass
          |                     |__menuTabClass
          |                     |__menuTabClass
          |__tabContentClass
        
2) You must added style in CSS "hide" and "show", which will show(display:flex) and hide(display:none) your tabs, responsively.

3) In function, in variable you must get from document all needed HTML-structure.
