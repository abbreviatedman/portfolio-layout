# Portfolio Layout Project

### Introduction

This week, we'll be working extensively to sharpen our layout skills. The basic layouts should be the desktop and mobile layouts pictured below (along with some pop culture grades for the weekend):

![Desktop and Mobile Layouts](https://raw.githubusercontent.com/abbreviatedman/portfolio-layout/master/layouts.jpg)


### How do the contents of these two layouts relate to each other?

* The nav sidebar on the desktop layout should collapse to abbreviated words or icons in the subheader of the mobile layout.
* The login/signup link should be a [generic user profile icon](https://duckduckgo.com/?q=profile+icon&t=canonical&atb=v165-1&ia=images&iax=images) in the mobile layout.
* The main content should be in two or more columns in the desktop, then should collapse to one in the mobile layout.


### What should my content be?

I would recommend you make your portfolio follow this classic layout. If you want to make a copy of the portfolio repo and apply these layouts to that copy, feel free. You could also apply your layouts to new content or some lorem ipsum. The power is yours.


### Stretch goals!

* Make the navbar float with the view in desktop view. In other words, when we scroll down the page, our title bar should get scrolled past, but the navbar would stay on the side, with our links viisble, no matter how far we scroll.
* Make the navbar a hamburger menu for the mobile view (which should float just like in the previous stretch goal). Instead of a menu that takes up horizontal room, it should collapse to a hamburger menu, like so:

    ![hamburger menu](https://i0.wp.com/codemyui.com/wp-content/uploads/2018/04/Pure-CSS-Hamburger-Menu-Slide-In.gif?fit=880%2C440&ssl=1)

    It doesn't, of course, have to be CSS only, as that example is. You can do it through JS if you prefer. Or some combination of the two! Whatever tools you'd like to use for this.
* Make our login/signup link a drop-down menu that tabs between login and signup options. The drop-down should activate on click of the login/signup link and disappear if we click anywhere else.
* Make whether they're logged in or not unlock a feature. One easy example would be be a hidden button for admin page, but you could expand this so that the button leads to an _actual_ admin page. This doesn't require a back-end yet; we don't necessarily need to check the login against anything yet!
* Let's store their logins in a global JS variable (what data type should it be?). Then if they're signing up, we can check if they already have an account by that name, and add them if we don't. If they're logging in, we can actually check their password against what we have!
* Now if you really wanna be fancy, you could make a JSON file for their usernames and password, giving them the ability to have an account even if they reload the page or quit their browser or shut down their computer ever. You'd have to run `json-server` to make this happen, but if you want to get back to using a REST API, this is one way to do it!
* And, of course, if you really want to get fancy, you could now make your portfolio editable if they're logged in, and have it persist. This is quite the stretch goal, as it's basically a whole additional project! Something to do in your week off, maybe?