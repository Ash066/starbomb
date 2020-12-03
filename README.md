# Milestone Project 1 - Starbomb
This website is for submission as my first milestone project. 
The goal of this site is to promote the band Starbomb by doing the folloing:
* Provide fans and potential fans an introduction to the band and its members.
* Promote the bands music and video via various channels
* Promote upcoming events and provide the ability to submit a form for booking.
* Promote mechandise sales for the band.

## UX

### Design
Website design was initially planned using the following wireframes which I created:

* [Desktop](assets/wireframes/desktop-wireframes.pdf)
* [Tablet](assets/wireframes/tablet-wireframes.pdf)
* [Mobile](assets/wireframes/mobile-wireframes.pdf)

### User Stories

#### User 1 - Band Member
As a band member I want to be sure that people can be diverted to our music platforms to increase playcount statistics on our music and in turn increase revenue from this avenue.

#### User 2 - Band Member
As a band member I want our fans to have easy access to, not only our planned tour dates but to also have a way to contact us for booking us for events.

#### User 3 - Band Member
As a band member I want to promote our social media channels as this gives us a more instant connection with our fans.

#### User 4 - Site User
As a potential fan, I've heard a song on the radio and want to find more of their music.

#### User 5 - Site User
As a fan in a small country, the band does not tour here but I still want to pick up some merchandise and support the band.

## Features

### Index
The index page features a gallery of band photos displayed in a carousel element and links to external music platforms, and a navigation bar which adapt display based on the screensize of the user primarily throught the use of Bootstrap.
The footer contains social media links which will open in a new tab.

### About
The about page features the same responsive navigation and footer of the index page promoting familiarity of use.
This pages layout is achieved utilising rows and colums.

### Music
The about page features the same responsive navigation and footer of the index page promoting familiarity of use.
This pages layout is achieved utilising rows and columns and embedded videos.

### Events
The about page features the same responsive navigation and footer of the index page promoting familiarity of use.
This pages layout is achieved utilising rows and columns.
This page also contains a form for submitting a contact request. Unfortunatly while this form functions on the surface, the information submitted is not passed anywhere valuable as of this release.

### Merch
The about page features the same responsive navigation and footer of the index page promoting familiarity of use.
This pages layout is achieved utilising rows and columns. Although this page currently functions on the surface for ordering of merchandise this does not have the back end to function available in this release.
As stated below, this is a feature I hope to be able implement completely in the future.

## Features Left to Implement

Currently a non-working merch page is featured on this site, however I hope in the future with further study of javascript I will be able to make this a functioning page.


## Tecnologies Used
* All wireframes were created using the [balsamiq](https://balsamiq.com/) wireframes software.
* [Bootstrap](https://getbootstrap.com/) was utilised along with user created css stylesheets in the design and function of these pages.
* Javascript elements taken from the [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/javascript/) website.
* iframe used to embed with the help of [W3Schools](https://www.w3schools.com/html/html_youtube.asp).
* [cdnjs](https://cdnjs.com/) used to insure proper links used.


## Testing

### Validating

* style.css validated by [Jigsaw-MarkUpValidationService](https://jigsaw.w3.org/css-validator/)
* index.html validated by [MarkUpValidationService](https://validator.w3.org/)
* about.html validated by [MarkUpValidationService](https://validator.w3.org/)
* music.html validated by [MarkUpValidationService](https://validator.w3.org/)
* events.html validated by [MarkUpValidationService](https://validator.w3.org/)
* merch.html validated by [MarkUpValidationService](https://validator.w3.org/)

### Website display response 

Website display response was tested for funtionality on destop, tablet and mobile resolutions using chrome developer tools.
Verified no conflicting html and css. Response elements achieved using Bootstrap and Media Query CSS.

### Footer response issues
Original iterations contained a fixed navbar for the footer, however due to issues of covering content and difficulty maintaining a cohesive look on all display seizes. 
This element was changed to an unorder list with a background matching the top navigation bar to achieve a better look and feel of site while maintaining functionality.

### Music link response issues
During the development of the site the music platform links were moved from the music page to the landing page as this would most likely be the main reason why fans visit the site and as providing traffic to these platforms was beneficial to the band for promotion of their music play count and sales.
As they were now on the landing page additional styling was required which did not respond as intended when tested on a differnet screen size. Media Query elements were added to the CSS file to target the buttons to ensure correct display on all devices. 

### Event page testing

When testing the funtionality of the event page using a screen reader, it was established that the tour poster portraying the information was ineffective for anyone accessing this site using this tecnology.
To make this information more accessable the tour poster image element was removed and the information was conveyed using text. This also allows the possibility of adding hyperlinks to the individual dates for buying tickets from respective venue sites.

### Form empty fields
When filling out the form within the event page, there was nothing to stop an empty field from being submitted. The required modifier was added to the name, email and event details, fields to ensure the submitted request was complete.

### Merch element spacing unclear
When using the grid spacing with bootstrap for the layout of this page, at all device sizes, was not providing an intuitive experience for the user.
To conteract this the elements within the columns were assigned float values to make sections clearer and button labels were renamed to be more explanitory.

## Deployment

Deployment process adapted from official [Github](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/creating-a-github-pages-site) documentation.

The following steps were taken to deploy this site:

1. Created a repository via my Github profile by selecting the 'New Repository' option from the dropdown menu in the upper-right corner of the page.
2. From the owner dropdown menu selector, I chose my username and gave the repository the name 'Starbomb'.
3. Visibility was set to public as this is a requirement to deploy this page via Github Pages.
4. I selected Initialize this repository with a README so that it would be possible to immediately clone the repository to my pc.
5. I then selected create repository.
6. Using the [Gitpod](https://www.gitpod.io/) development environment I created the required css and html pages. I also uploaded the required media within this environment.
7. Upon completion of these files I opened my github profile and selected the repositories tab.
8. Within the repositories tab I selected the starbomb repository. 
9. I accessed the settings using the settings tab on the navigation bar of this repository.
10. Scroll down to the Github Pages section of the settings.
11. Within the Github Pages section, under the source heading, I selected the master branch and the root folder.
12. Saved the selected options.

## Credits

### Content
* About information of band members in about.html sourced on [official band site.](https://starbomb.com/about/)
* Band information in about.html sourced on [Wikipedia](https://en.wikipedia.org/wiki/Starbomb)

### Media

* All icons used for this site were sourced at [FontAwesome](https://fontawesome.com/)

#### The following images were used in creation of this site:
* starbomb-logo-1: https://www.gamegrin.com/assets/Uploads/_resampled/croppedimage640200-starbomb-banner.jpg
* starbomb-logo-2: https://external-preview.redd.it/SwpAumQ2cM20EbekQjxTERwRDHfUrq16Hx4uC5tt9G8.png?auto=webp&s=5c9535877e10a2c57d43fbf5d2166af50787cf15
* starbomb-tour-1 : https://mir-s3-cdn-cf.behance.net/project_modules/2800_opt_1/d9565f30041931.56108f2c8212e.jpg
* starbomb-band1: https://www.gamegrin.com/assets/Uploads/_resampled/resizedimage640339-starbomb-Player2.jpg
* starbomb-band-2 : https://img.discogs.com/cPd9iTl5D7kZnmSblvHe_RrMQVs=/551x551/smart/filters:strip_icc():format(jpeg):mode_rgb():quality(90)/discogs-images/A-3598628-1522535645-2583.jpeg.jpg
* starbomb-band-3 : https://zdnet3.cbsistatic.com/hub/i/r/2015/05/08/695822ab-51c6-4ef2-a7ed-cc627b09cab4/resize/770xauto/7e730a2bda08dc4ffd6742311a94a17e/b4lle8kiiaiauph-png-large.png
* starbomb-band-4 : https://d11mgq5hlnsdgo.cloudfront.net/7c9f3e96-10e9-440a-a4b3-3a0528e4a1fe.jpg
* starbomb-band-5 : https://pbs.twimg.com/profile_images/1112884232534122496/HPHT4RLw.png
* starbomb-band-6 : https://images.genius.com/bce7a7802a76e3737717475104525737.1000x563x1.png
* members-arin:https://static.wikia.nocookie.net/roosterteeth/images/f/fb/Arin_Hanson.png/revision/latest?cb=20160116040010
* members-dan: https://upload.wikimedia.org/wikipedia/commons/thumb/e/ef/Dan_Avidan_at_the_Hammersmith_Apollo_in_London_-_October_2017.jpg/1200px-Dan_Avidan_at_the_Hammersmith_Apollo_in_London_-_October_2017.jpg
* members-brian:https://media2.fdncms.com/sacurrent/imager/u/original/14468153/screen_shot_2018-08-09_at_1.42.25_pm.png
* starbomb-merch-1 : https://s9.limitedrun.com/images/1426800/StarbombBlackMetalTee_Proof_Front.png
* starbomb-merch-2 : https://s9.limitedrun.com/images/1426799/Old_Logo_Tee.png
* starbomb-merch-3 : https://s9.limitedrun.com/images/1426798/StarbombGangTee_Proof_Front.png
* starbomb-merch-4 : https://s9.limitedrun.com/images/1456695/BombLogoTee__1_.png
* starbomb-merch-5 : https://s9.limitedrun.com/images/1456698/BombLogoHoodie.png
* starbomb-merch-6 : https://s9.limitedrun.com/images/1456700/Starbomb_LogoHat_Mock02__1_.png

#### Videos
All videos were sourced from the [Egoraptor](https://www.youtube.com/user/egoraptor) youtube channel.

* Rap Battle: Ryu vs. Ken ANIMATED MUSIC VIDEO by Spazkidin3D - Starbomb : https://youtu.be/reVaJhAVEsE
* The NEW Pokerap!! - ANIMATED MUSIC VIDEO by grind3h – Starbomb https://youtu.be/zCbl-12QV2c
* Video 3: Overwatch RAP Music Video - Starbomb animated by Knights of the Light Table -https://youtu.be/bbkU_PCimWY

### Acknoledgements

#### This project and site could not have been completed without the support of the following people:

* Arin Hanson, Brian Wecht, and Dan Avidan whose music inspired this project and help create happiness in the darkest of times.
* Roman Grubic, my in class co-ordinator whom provided support on a daily basis.
* Excellence Ilesanmi, my mentor whom provided industry perspective and support via the mentor sessions.
* Code institute, for providing this opportunity to take part in this course and for the learning supports provided.
* Oisin Gargan whom provided emotional support and supressed the bootstrap enduced murderous rage.
* The Patdown podcast with Ms.Pat, which made the time spent on this project even more enjoyable.
