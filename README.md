**How to install from GitHub**

1. Click the "Download Source" button.
2. Unzip the download
3. Rename the folder to SelectStuff.tmbundle
4. Double-click
5. TextMate handles the rest!

---

Select Stuff
============

Balance Jr
----------
*Created by [Thomas Aylott](http://subtlegradient.com/ "Howdy")*

Select the most obvious thing. Try it.

* Balance Jr Back &mdash; **HOME**
* Balance Jr Forward &mdash; **END**

Select Folding Group
--------------------
*Created by [Thomas Aylott](http://subtlegradient.com/ "Howdy")*

Select the current folding group. Undoable.  
&#x2318;Z moves your cursor back to its previous location.

* Select Folding Group &mdash; **&#x2303;F1**

Select Balanced Tags
--------------------
*Created by [Hans-Jörg Bibiko](http://www.bibiko.de/ "Homepage - Hans-Jörg Bibiko")*

Select the current HTML / XML tag or its contents.  
Repeatable. Keep running the command to select the next parent tag.

* Select Balanced (HT|X)ML Tags &mdash; **&#x21E7;&#x2318;B**
* Select Content of Balanced (HT|X)ML Tags &mdash; **&#x2325;&#x21E7;&#x2318;B**

To make this work you'll have to install **HTML::Parser** for Perl. Run this from the terminal:

	sudo -H cpan -i HTML::Parser
