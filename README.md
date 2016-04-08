OWL : Outliner with Wiki Linking (Electron Edition)
===================================================

Wrapping OWL as a desktop app. using Electron.

What?
-----

See [the Outliner with Wiki Linking](https://github.com/interstar/OWL) repository and [Project ThoughtStorms]() for more information of OWL in general.

This is a quick test to see if I can make a desktop app. from it using Electron.

Seems I can, and it's very nice. :-)


Quick Start
-----------

  1) Make sure you have https://nodejs.org/en/ and https://www.npmjs.com/ installed on your machine.

  2)

    git clone https://github.com/interstar/owl-electron.git owl
    cd owl
    npm install
    ./node_modules/.bin/electron .


OWL will now run as a desktop app.


Instructions
------------

To create a link to a page, just write the name, highlight it and click the "Link" button. The text will become a hyperlink to the page.

If the page doesn't exist yet, it will be automatically created.

Pages are automatically saved whenever you leave them for another page. If you want to force a page, just hit the "back" arrow and the "forward" arrow again.

If you want to change the directory where pages are stored, open up the local_setup.js file and change the line 

    pageStore = new NodeBasedPageStore("./pages");
    
to 

    pageStore = new NodeBasedPageStore(YOUR-PAGE-PATH);


Respect
-------
* [Dave Winer](http://scripting.com/) for getting a decent outliner into the browser (at last) and having the generosity to open-source the core.
* [Ward Cunningham](https://github.com/WardCunningham/) for wiki fact and philosophy.
* Everyone in the awesome Electron, node.js and Chrome(eum) communities, who've made this possible.

