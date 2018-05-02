
[![](https://www.jitpack.io/v/GitJonibek/JPics.svg)](https://www.jitpack.io/#GitJonibek/JPics)

# JPics
JPics - Image loading library.
 -- Easy to integrate with other android projects/apps.
 -- Enable cache configurably by users' need
 -- The same image may be requested by multiple sources simultaneously (even before it has loaded), and if one of
    the sources cancels the load, it will not affect the remaining requests.
 -- An image load can be cancelled by users' need.
 
How to integrate into your project?
follow the steps:--------
  allprojects {
   repositories {
    ...
    maven { url 'https://www.jitpack.io' }
   }
  }
  dependencies {
          implementation 'com.github.GitJonibek:JPics:-SNAPSHOT'
  }
  
Example: 
 JPics.with( context ).setUrl( Url ).into( imageView ); - done!

setting the cache configurably:
 JPics.Config.setCacheCapacity(--size of cache--);
