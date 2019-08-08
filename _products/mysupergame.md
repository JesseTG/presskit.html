---
# This is your product or game page. It should focus on ONLY one product. This
# is not a replacement for your product’s website, but a quick way for the press
# to know it faster.
#
# Name this file anything you want, but put it in /_data/products.

### General Information ########################################################
################################################################################

title: My Super Game
website: https://pizzaburger.studio/mysupergame

# You can also add an URL to a request page for this product.
# A button will be displayed on the page.

press-copy-request: http://pizzaburger.studio/mysupergame/request

# If you have one or many publishers for this product, you can add them here.
# The based-in and website fields are optional.

partners:
  - type: Publisher
    title: Pixelnest Studio
    website: https://pixelnest.io
    based-in: Rennes, France
  - type: Distributor
    title: Pizza Oven LLC

# Add as many dates, platforms and prices as needed.

release-dates:
  - 04 Feb, 2016
  - 10 Oct, 2016

# Put all the platforms your product is available on.
# The link field is optional.

platforms:
  - name: PC / Mac
    link: http://itch.io
  - name: Steam
    link: http://steampowered.com
  - name: Inc New Store (TBA)

# Show the price of your product.
# Try to be exhaustive, it will be helpful for a reviewer.

prices:
  - currency: EUR
    value: 20
  - currency: USD
    value: 20
  - currency: GBP
    value: 16
  - currency: JPY
    value: 2300

### Relations ##################################################################
################################################################################

# You can specify relations between products using the relations field.
# Then, on this page product, you will see a new line in the factsheet.
# In the related product page, a new value will also be added.

# You can have as many relations as you want. You can use it to show DLCs,
# expansions, sequels, prequels, etc.

relations:
  - type: DLC
    product: "My Super Game: Ultimate Edition"

### Description & History ######################################################
################################################################################


# Describe your product here. Be brief.

description: Here goes a quick description of your product or game. Be concise and explain in very few words the concept or the gameplay and why it's really cool and why everyone should use or play it.

# Tell the story of your product with the histories field.

history: "Add some storytelling here. Not the scenario of your game, but rather some backgrounds behind the creation process: why are you making this game? Most projects starts with a cool story."

### Features ###################################################################
################################################################################

# Show the most important features of your product.
# Focus on what is really important and is a key aspect of it.

features:
  - List some "Key Sellings Points" to grab player's attention.
  - Don't be too generic ("pixel art graphics!"), don't be too pretentious ("most incredible game experience!").
  - Also, people like numbers, so you can add some (450 weapons, hundreds of levels, dozens of hours of playtime!).
  - Need ideas? Maybe explain some game modes?
  - It would be a nice place to say something about multiplayer, if you have some.
  - Have you translated your game? (You probably should btw.)


### Trailers ###################################################################
################################################################################

# Add your videos. Trailer, teaser, snippets? Let’s roll!
# You can use YouTube and/or Vimeo. Only one is needed, and only one is recommended.

# Don’t put the full link: just the ID is necessary.
# If you want to provide a link to download the video, add the download field.

trailers:
  - name: Release Trailer
    youtube: EtXajayBLzw
  - name: "Gameplay Video #2"
    youtube: EPNK1j3TMjU
    download: https://example.com/presskit.mp4
  - name: Early Access Trailer
    youtube: EtyQMcc19xY
    vimeo: 108650530
  - name: "Short gameplay preview: Burger vs Pizza"
    download: https://example.com/presskit.mp4

### Widgets ####################################################################
################################################################################

# Add your widgets to your product here.
# If the product is not a game or an app, you won’t probably need that.
# We only need the ID of the product on the store.
# This section is optional, and you can use as many widgets (or none) as you want.

# Warning: widgets import many scripts and assets. This may have a penalty on
# your page size and responsiveness.

widgets:
  appstore: 950812012
  playstore: com.noodlecake.altosadventure
  steam: 347160
  humble: steredenn/7SDLfk23hw
  itch: 27992
  bandcamp: 1135613467

### Awards, quotes & links #####################################################
################################################################################

# You got awards for this product? Great! Put them here. Optional.

awards:
  - description: Game of the year without a doubt
    info: Saint-Père-Marc-En-Poulet (France), 04 February, 2016
  - description: Best soundtrack
    info: A great game festival (World), 01 October, 2015
  - description: Best MYGAMENGINE game
    info: Deep into the woods (Forest), 31 March, 2014

# Quotes are used to show the appreciation of your users.

# Show something important, something nice, or something funny, for example.
# Optional.

quotes:
  - description: This is my favorite game of all time.
    name: Mum
    website: At home
    link: http://at.home
  - description: A very serious quote you're very proud of by someone you respect.
    name: Master
    website: Master's website
    link: http://mast.er
  - description: 10/10 would play it again and again.
    name: A friendly anonymous Steam reviewer
    website: Steam review
    link: http://steam.review

# Need to link to a resource? A small product? An RSS feed? An OST?
# A press release? Put those here, in the additionals field. Optional.

additionals:
  - title: Original Soundtrack (OST)
    description: Composed by an awesome musician. Listen for free, download for $3 at
    link: http://zandernoriega.bandcamp.com/album/steredenn-original-soundtrack
  - title: Release announcement
    description: Announcement are exciting, so we usually make blog posts or news about it on
    link: http://pixelnest.io/journal

### About ######################################################################
################################################################################

# An "About Your Company" section is automatically generated from the content of
# the company page. This field is completely optional. If you don’t want this
# section, just delete it.

# But sometimes, you want to add a description for a partner. This is this the
# place to do it.

# For example, if you have a publisher, you can speak a bit more about it here.
# Most of the time, you should link that to the tag above, if you want to
# explain a partner a bit more. But you could use this section for other purpose.

# The tag is optional.

abouts:
  - title: Pixelnest Studio
    description: Pixelnest Studio is a small French studio which creates games, websites and apps. They made Steredenn, a roguelike-shmup in big pixels. They are also behind presskit.html, which you are probably using if you are reading this.</description>
    link: https://pixelnest.io
  - title: Pizza Oven LLC
    description: This is a fake company to illustrate the fact that you can have multiple about tags in your product page

# Team & Contacts ##############################################################
################################################################################

# This is for the product team.

# Add yourself, of course, but also your collaborators, freelancers and/or
# partners for example.

# The role field can be anything you want. But we recommend to, at least, put
# the company name for the founders/employees. This will distinguish this person
# from the external collaborators.

# The website field is optional.

credits:
  - person: Krokmou
    role: Bot Leader, Game Designer, Pixelnest Studio
  - person: Hiccup
    role: Developer, Pixelnest Studio
  - person: Astrid
    website: http://www.astridsupergame.com
    role: Musician, Freelancer

# Add more contact information.

# Add links to your product social accounts, as well as mail specific to this
# product. And the website.

# For each item, use either the mail or the link field.

contacts:
  - name: Inquiries
    mail: mysupergame@pizzaburger.studio
  - name: Twitter
    link: https://twitter.com/pizzaburgerstudio
  - name: Facebook
    link: https://facebook.com/pizzaburgerstudio
  - name: Web
    link: http://mysupergame.pizzaburger.studio


image-dir: assets/images/mysupergame

# All done!
---
