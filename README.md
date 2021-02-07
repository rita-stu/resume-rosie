# Learning BootStrap ([v4.3](https://getbootstrap.com/docs/4.3/getting-started/introduction/))

## Goal: [Rosie's resume](rita-stu.github.io/resume-rosie/index.html)
Create resume-style website incorporating Bootstrap features.

The website should contain a home (index) page, a resumé page, a contact page and a download page (for downloadable CV in pdf format).

## Objective
The objective is to use Bootstrap features to improve responsive functionality of the whole site, while making it more aesthetically pleasing.

__The following features are incorporated__:
- __contact form__ on [contact page](https://rita-stu.github.io/resume-rosie/contact.html)
- sweep-to-bottom (main navigation menu) on all pages
- container-fluid on all pages
- fa icons on all pages
- progress bar work history section of ([resume page](https://rita-stu.github.io/resume-rosie/resume.html))


## Technologies Used

1. HTML
2. CSS
3. [Bootstrap](https://getbootstrap.com/docs/4.3/getting-started/introduction/) version 4.3
4. [FontAwesome](https://fontawesome.com/) icons


## Bugs

<a name="bugs">1.</a> __[resume page](https://rita-stu.github.io/resume-rosie/resume.html)__: Work History section displays incorrectly ([image](rita-stu.github.io/bugs/WorkHistory.png))
* dates display correctly
* left border (the actual line of timeline) and bullets display correctly
* place of employment (h4) and role (p) not doing what they're supposed to do.

2. __[CSS Validation Service](https://jigsaw.w3.org/css-validator/)__ result: 3 errors
   1. button background-color invalid (e84610) – missing: #
   2. unnecessary script
   3. -webkit-transform: "unknown vendor extension"

3. __[W3C Markup Validation Service](https://validator.w3.org/)__ result: Document checking completed. No errors or warnings to show.

__<a name="fix">Fixes__</a>
- __.timeline-item p__: changed padding-left to 1.8em (previously: 0)
- added: __.timeline-item h4__ {font-size: 1.3em; padding: 2em 0 0 1.5em;}
- __.history-heading__  changed bottom-margin to 20px (previously: 50px)
- __.history-heading__  added padding-left: 1em;
- __.history-items__    changed margin-bottom to 20px ()
- __.timeline-item:before__: adjusted padding-top accordingly
- __.timeline-item:after__: adjusted padding-top accordingly


## Testing
Initial testing of completed __resume.html__: History section displayed incorrectly (see __[Bugs](#bugs)__ section above)

* After testing again, the above __[Fixes](#fix)__ corrected the issue.
* Responsive works well on all device sizes (400px to 800px).
* Tested all links to all pages from all pages: all work correctly.
* Not yet proficient using Developer Debugging tools – to be done at a later stage
* CSS validation: fixed two of three issues
  1. corrected button bg-color
  2. removed unwanted script
  3. left -webkit-transform; in style.css. Not sure yet why/how page is affected (sweep-over nav links no longer work).
  * Ran validator again. Result: Congratulations! No Error Found.
* HTML Validation: Document checking completed. No errors or warnings to show.



## Deployment
__Initial commit__: problem, as with ms1 two days ago, github doesn't update immediately after commits (despite deployment). Two days ago, commits took up to __three hours__ to respond/update which meant changes could not be determined or new issues checked.

(24 hours later and this current version had not committed.)




