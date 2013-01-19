jQuery Single Page Plugin
===================
Single Page - A jquery plugin for creating single page web sites.


Installation
-------
    <script type="text/javascript" charset="utf-8" src="jquery.js"></script>
    <script type="text/javascript" charset="utf-8" src="jquery.singlepage.min.js"></script>

Usage
-----
Html Code:

    <div id="mainWrap"></div>

JavaScript:

    $('#mainWrap').SinglePage({
        pages : [{'hash':'about', 'url':'about.html'}],
        defaultPage : null
    });


Testing
-------

To run the tests:

    $ rake

To add tests see the `Commands` section earlier in this
README.
