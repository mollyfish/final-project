# Comments for the Song Maker team final project

* Only Walter is listed in the author field of the package.json file - you should probably update that!  
* Very nice README, I like the fact that you included your profile photos.
* nice job separating concerns (server vs client, songs vs functional) in your test files - made it much easier to navigate
* Given how much functionality is wrapped up in your client.js file, I would expect a few more tests...
* Speaking of client.js - that's a REALLY long file that should probably be broken up into several smaller pieces (a couple of you mentioned this in your write-ups, too). It looks like you got started on this with your helper.js file?
* Consider more informative error messages in eat_auth.js
* Templates - I see a lot of `<div>`'s...but I also realize that with a layout like you have, it could be very difficult to be truly semantic.  One thing I would suggest is using the `<fieldset>` tag in your forms to group `<input>`'s
* ngDraggable looks **amazing** - I will totally be checking that out later!
* Sass:
  * base.scss should contain styles that apply to base html elements, like `<body>`, `<section>`, etc.  Everything else should be organized into smaller partial files.  With everything in one file like this, it will be next to impossible for a newcomer (or you, two weeks from now) to find any particular style.
  * I would split things up like so:
    * base
    * reset
    * layout
    * buttons (possibly also keys?)
    * fonts
    * colors
    * etc
  * You want to be modular with your scss files so you can chunk your code into easily navigable bits.

### VERY well done!

This was a very ambitious project, and you guys did a great job getting it to the MVP stage for demo day.  There is some refactoring to be done, but I know you plan on working on it further - I look forward to seeing where it goes!  Nice job.  :)