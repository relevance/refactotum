!SLIDE 
# Git #
## Rob Sanheim ##

!SLIDE bullets

## Learning Git

* Just jump in
* SVN -> Git is not hard

!SLIDE commandline

    $ svn checkout svn://foo.googlecode.com/svn/trunk foo
    # make your changes
    $ svn commit -m "my first commit"

    is equivalent to:

    $ git clone git@github.com:pjhyett/foo.git
    # make your changes
    $ git commit -a -m "my first commit"
    $ git push


!SLIDE bullets

Free Resources abound:

* [Definitive practical guide](http://stackoverflow.com/questions/315911/git-for-beginners-the-definitive-practical-guide)
* [Git Community Book](http://book.git-scm.com/)
* [Git SVN Crash course](https://git.wiki.kernel.org/index.php/GitSvnCrashCourse)
* [Scott Chacon's Pro Git](http://progit.org/book/)

!SLIDE bullets

## Guidelines

!SLIDE bullets

* work in small bits
// if it takes longer then a sentence, you waited too long to check in
* when in doubt, create a topic branch
* ABC --> always be committing
* always be pushing

