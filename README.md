# jekyll-blog
This is a simple travel blog with jekyll and netlify cms

The layout is made using simple 
### Using markdown and html

To run this app

* git clone repo-name
* you need to install ruby in the system using `sudo apt-get install ruby-full build-essential zlib1g-dev`
* then run the build serve command `bundle exec jekyll serve`


Inorder to check the cms status 

* You need to add `/admin` after the link
* if you are new you need the access to my cms .

### The updates are mostly done in the `layouts` section in the  `default.html` & `home.html` files.
### because the changes if done inside the `_site` folder will automatically get override by the default theme of jekyll ( that's a default nature of jekyll ).

#### The content blog is created inside the `home.html` and rest of the posts and blogs are created using `netlify-cms`
#### About section is seperately managed using `about.markdown`

### To make the blog faster the hardcoded data is to be replaced with data inside the `_data/site.yml` and once that data is dynamically used the speed will be updated automatically and also instead of using image links from external `cdns` the images can be uploaded inside a `static` folder using `netlify-cms`

## The website performance is 98% and can be enhanced further , I checked the performance using 
**`dev-tools/lighthouse`** 

