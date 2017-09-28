# GlideSampleApplication
Sample application with implementation of Glide V4

```
GlideApp.with(this)
                .load(path)
                .centerCrop()
                .transition(DrawableTransitionOptions.withCrossFade()) //Optional
                .skipMemoryCache(true)  //No memory cache
                .diskCacheStrategy(DiskCacheStrategy.NONE)   //No disk cache               
                .into(imageView);


```
# RESULT
![device-2017-09-28-202343](https://user-images.githubusercontent.com/6814816/30974442-4d7d996c-a48d-11e7-9af2-0aee7dbe845b.png)



                
                
