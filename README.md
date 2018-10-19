# Casper2 👻
grav theme

![Casper2 Theme](thumbnail.jpg)

## Instructions


You can change **logo** in **Themes » Casper 2**
There you can also change social icons by writing only your id after site name.  
You can also change favicon there, and **tagline** text.

As you can see this theme uses images on header of every post.
If you don't have image set and ready, you can select placeholder image from unsplash
that will show as background instead. That's what **Default Card Background Image** is for.  
You can find examples on how to set desired unsplash image or set of images that will change
upon reload on https://source.unsplash.com/

...

## Important note:

Create page of type : blog and go to Advanced.
under `body-classes` write `home-template`

While you're there, in blog page - go to Content tab - upload your own **Primary Image** - and hit Save, of course.

Blog page should be blank - without any text.

Under blog page you can create as many posts with page template `item` as you want. 
This is how you populate your blog.

- One more thing -

In this theme you can create a page of type : archive.
Page with that type shall list all your posts written so far.  


## Details

This Grav theme is port of a MIT theme for ghost.

### GPM Installation (Preferred)

The simplest way to install this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm) through your system's Terminal (also called the command line).  From the root of your Grav install type:

    bin/gpm install casper

This will install the Gateway theme into your `/user/themes` directory within Grav. Its files can be found under `/your/site/grav/user/themes/casper`.

### Manual Installation

To install this theme, just download the zip version of this repository and unzip it under `/your/site/grav/user/themes`. Then, rename the folder to `casper`.

You should now have all the theme files under

    /your/site/grav/user/themes/casper
    
If you want to set Casper2 as the default theme, you can do so by following these steps:

* Navigate to `/your/site/grav/user/config`.
* Open the **system.yaml** file.
* Change the `theme:` setting to `theme: casper`.
* Save your changes.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in Terminal and typing `bin/grav clear-cache`.

### GPM Update (Preferred)

The simplest way to update this theme is via the [Grav Package Manager (GPM)](http://learn.getgrav.org/advanced/grav-gpm). You can do this with this by navigating to the root directory of your Grav install using your system's Terminal (also called command line) and typing the following:

    bin/gpm update casper

This command will check your Grav install to see if your Gateway theme is due for an update. If a newer release is found, you will be asked whether or not you wish to update. To continue, type `y` and hit enter. The theme will automatically update and clear Grav's cache.

### Manual Update

Manually updating theme is pretty simple. Here is what you will need to do to get this done:

* Delete the `your/site/user/themes/clean-blog` directory.
* Download the new version of theme from this repository.
* Unzip the zip file in `your/site/user/themes` and rename the resulting folder to `casper2`.
* Clear the Grav cache. The simplest way to do this is by going to the root Grav directory in terminal and typing `bin/grav clear-cache`.

## Thank You

Grav has fantastic team, people that are very helpful and people that I probably bored to death, 
or at least quite a lot to achieve what I want. 
In [Slack's chat room](https://getgrav.slack.com/messages) I bugged always helpful `@andrewscofield`
`@ricardo`, and `@olevik`.

Words cannot express how thankful I am to all of you. I'm the one to blame if anything is wrong, 😅
but you guys helped to get most of the things right. So kudos to you. 

And at last, but not least - Thank You if you're using this theme. 🙂
