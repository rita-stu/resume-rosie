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


## <a name="bugs">Bugs</a>

1. __/resume.html__: Work History section displays incorrectly ([image](rita-stu.github.io/bugs/WorkHistory.png))
* dates display correctly
* left border (the actual line of timeline) and bullets display correctly
* place of employment (h4) and role (p) not doing what they're told.
* 

<a name="fix">__Fixes__</a>
- __.timeline-item p__: changed padding-left to 1.8em (previously: 0)
- added: __.timeline-item h4__ {font-size: 1.3em; padding: 2em 0 0 1.5em;}
- __.history-heading__  changed bottom-margin to 20px (previously: 50px)
- __.history-heading__  added padding-left: 1em;
- __.history-items__    changed margin-bottom to 20px ()
- __.timeline-item:before__: adjusted padding-top accordingly
- __.timeline-item:after__: adjusted padding-top accordingly


## Testing
This was a tutored project; followed all tutorial instruction. Despite using the exact code as tutorial, initial testing of completed site showed __/resume.html__ incorrectly displayed (see __[Bugs](#bugs)__ above)

* After testing again, the above __[Fixes](#fix)__ corrected the issue.
* Responsive works well on all device sizes (400px to 800px).
* Tested all links to all pages from all pages: all work correctly.
* Not yet proficient using Developer Debugging tools – to be done at a later stage
* CSS validation: 


## Deployment
Initial commit: problem, as with ms1 two days ago, github doesn't update immediately after commits (despite deployment). Two days ago, commits took up to __three hours__ to respond/update which meant changes could not be determined or new issues checked.




