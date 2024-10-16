# Simple UI Design of a Blog App in Kotlin

Source code: [https://github.com/joshhh980/kotlin_blog](https://github.com/joshhh980/kotlin_blog)

It has actually been a while since I built native apps because I've doing a lot react native and expo. Even though there are a couple of new techs have popped in, I still stuck with Linear Layout since I'm familiar with that

![ Simple UI Kotlin Blog App ](https://github.com/joshhh980/kotlin_ui_design_blog_app/blob/master/image7.png?raw=true)

The initial page of the blog app is a custom activity that serves as a welcome page and uses intent to navigate to the MainActivity

![ Simple UI Kotlin Blog App ](https://github.com/joshhh980/kotlin_ui_design_blog_app/blob/master/image4.png?raw=true)

For the MainActivity, the theme has been set to NoActionBar so that a Linear Layout that consists of an ImageView and a ShapeableImageView can be used in place of that.

![ Simple UI Kotlin Blog App Navigation Bar ](https://github.com/joshhh980/kotlin_ui_design_blog_app/blob/master/image1.png?raw=true)

The blog posts are rendered via a RecyclerView that is bound to a custom RecyclerViewAdapter which uses an inner ViewHolder class for custom layout for posts

![ Simple UI Kotlin Blog App ](https://github.com/joshhh980/kotlin_ui_design_blog_app/blob/master/image5.png?raw=true)

