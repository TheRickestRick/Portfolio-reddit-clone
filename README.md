# Reddit Clone With Server

This project is an elegant reddit clone with a database backend. I love using reddit, and I thought it would be really cool to build a simple version of it.  It contains most of the essential features of the actual reddit, and it helped give me a better understanding of how to create persistent data applications.

# Challenges

-This is the first application I built with AngularJS that also has a backend. I had to become comfortable with State, and the Model View Controller design. 

-I found that I really enjoyed using AngularJS, and I did not find it that complicated to use. I liked the way that the app could be organized with components, and view templates.

-Learning the basics of how to make HTTP calls to my server, and retrieve data that users input was a huge breakthrough for me. It helped me connect the bridge between the front-end user interface, and the back-end database.


# Technologies
<table>
  <tr>
<img src="https://res.cloudinary.com/teepublic/image/private/s--wQc63_dO--/t_Preview/b_rgb:ffffff,c_limit,f_jpg,h_630,q_90,w_630/v1509564403/production/designs/2016815_1.jpg" alt="alt text" width="25%" height="25%">
  </tr>
   <tr>
<img src="https://cdn-images-1.medium.com/max/649/1*NHFLjvPW2Yh5NqlCphMGTg.png" alt="alt text" width="25%" height="25%">
  </tr>
   <tr>
<img src="https://i.cloudup.com/zfY6lL7eFa-3000x3000.png" alt="alt text" width="25%" height="25%">
  </tr>
   <tr>
<img src="https://s3.amazonaws.com/media-p.slid.es/uploads/481907/images/2433061/UI_Shield.png" alt="alt text" width="25%" height="25%">
  </tr>
</table>

## How it works

A user can see all of the current posts, and search by time posted, subject line, and the amount of votes it has. The app makes a call to my server which will retrive all of the posts from the posts table, as well as all of the comments that each post has attached to it. This happens on initiation, and the main index page is then filled with all of the posts that people have made.
<img src="https://github.com/TheRickestRick/Portfolio-reddit-clone/blob/master/Screen%20Shot%202018-07-17%20at%2011.36.04%20AM.png" alt="alt text">

A user can also comment on a post, and see what other people had commented. When the comment is submitted, it is attached to the post id that it was directed at. This way the comment will show up on the post that it was meant to be seen with.
<img src="https://github.com/TheRickestRick/Portfolio-reddit-clone/blob/master/Screen%20Shot%202018-07-17%20at%2011.36.26%20AM.png" alt="alt text">

If you want to create your own post you can select the create new post drop down menu, and fill out each of the inputs. When you have filled out each of the inputs you can then create the post, and add it to the post table in the database. The page will refresh and the new post will be visable for everyone else.
<img src="https://github.com/TheRickestRick/Portfolio-reddit-clone/blob/master/Screen%20Shot%202018-07-17%20at%2011.37.36%20AM.png" alt="alt text">

The new post will then be added to the feed, and all the other users can see it!
<img src="https://github.com/TheRickestRick/Portfolio-reddit-clone/blob/master/Screen%20Shot%202018-07-17%20at%2011.38.24%20AM.png" alt="alt text">


