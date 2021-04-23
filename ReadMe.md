Sagar Sanghvi

1131629

Mobile Computing 

Final Project

**Chefyumm**

Chefyumm is basically a simple blogging application where the user can blog about new recipes and find other new recipes for different kinds of cruises. The application is an initiative of discovering various types of food dishes and how to make them. 

Food is something which is essential for human life across the globe. And the most interesting part is that people have different food items that they eat in their daily life. Getting this diverse variety of cooking and enjoying delicious food together in one place is the major goal of this application.

**Configuration instructions:**

`    `Node.Js: 14.X.X,

`    `Mysql Server:  5.X,

`    `AWS Elastic beanstalk,

`    `Android Device: version 6.0 and up

**Installation instructions:**

1. first install npm packages using `npm install` command
1. update database environment variables in .env
1. check the API and database connection is working fine
1. host the api on the aws elastic beanstalk or any server. example- heroku
1. update API link in android application (API link is in Style.dart file)
1. after that build the app and check the network permission is given. 

**Operating instructions:**

`    `First add new blogs using web panel on Api itself. example- https://API/blog/manage

`    `after adding blogs, the blog will appear on application.

**Manifest**

`    `-bin

`        `controllers:

`            `blog.js

`        `custom:

`            `error.js

`            `errors.js

`            `functions.js

`        `models:

`            `blog.js

`        `routes:

`            `blog.js

`    `-public:

`        `axios.js

`        `cover.css

`    `-uploads:

`        `blog:

`            `.gitkeep

`    `-views:

`        `index.ejs

`    `.env

`    `.gitignore

`    `.npmrc

`    `package-lock.json

`    `package.json

`    `app.js

`    `connection.js

`    `README.md

**Copyright information:**

Are not available yet but can be worked on later.

**Contact information:**

Email: ssanghv1@lakeheadu.ca

` `Phone: +1 8077079705   

**Bug list:**

The Api is hosted on free hosting, the Api server will hardreset after some time,

it will delete the images on the disk and the images will be unavailable. (this bug will be fixed if we use storage service of AWS)



**Troubleshooting tips:** 

` `Delete all the blogs by clicking the DeleteAllBlog button on web panel and again add the blogs.

**Credits and acknowledgements:**

Credits to websites providing recipes 

flutter for the application.

Html css for backend.








**Project Logo:**






**Demo screenshots/gifs:**



**Tables of contents:**

Access to internet for adding the blog on the website.

Download the available apk for accessing the application.

Add/ Find new recipes and enjoy your food.

**Concise project description:**

The project consists of developing an android application which is functional with its code.

The application which was build is a food blogging application where the user can read blogs of recipes of various kinds of food. The process of making the dish is described and it also mentions the required ingredients for making that food item.

Using the application is very simple and is freely open for everyone. One can add recipes of their favourite dish on the website for which the link is provided with the application as well.

Once the person adds their recipe to the website, it is available as a blog on the application. 

The application will receive notification if any new recipe is added. 
Once people start adding their recipes others can learn about new dishes and how to cook them.

Link for the Chefyummm website:

http://chefyumm-env.eba-sfjrfiec.ap-south-1.elasticbeanstalk.com/blog/manage

**Features List:**

- -Backend is independent of frontend the API functionality can be easily changed in future as required.
- -Optimized Android App for most of the android device.
- -Web panel for add and delete blogs.
- -Blogs images are compressed by api and converted to .webp format for fast loading of images.

**Links to further reading:**

- The application can further be updated with new features.
- We can add Gps feature to locate nearby restaurants.
- A section of distinguished cruises can be added so that access to a particular cruise becomes easy.
- Adding Blogs can be done directly from the application itself. 
- Short Video logs can be added for food items that can be instantly made.

**Changed Log:**

`    `-Version 1.0 (2020) initial log:

`        `Features:

`            `\* Web panel added for add and delete blogs.

`            `\* API image compression added.

`            `\* Allowed to serve static files from the api.

