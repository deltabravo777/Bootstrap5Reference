# Bootstrap5Reference
A cheat sheet of bootstrap5 items

- Setup (for now):
- add "using BootstrapDemo.Models;" to Error.cshtml.g.cs, if there is a build error saying that a namespace could not be found
- import the following dependencies: bootstrap, bootstrap-icons, font-awesome, javascript.util, jquery, jquery-validation, jquery-validation-unobstrusive, popper.js, respond.js, respnsive, responsive-nav-js, twitter-bootstrap. I am trying to upload the libraries though the file count is too high so I may get around this another day
- Alternatively you can look at the Bootstrap reference guide which is great to do, though there are a few things that may not work right away. Bootstrap 5 does require a careful reading of the notes on top, and the ordering of the stylesheets also matters for things such as Popper. You can just copy _Layout.cshtml as that does allow Popper to work. It took me a while to find a workable way to get Popper to work
