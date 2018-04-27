# JPics
JPics - Image loading library.
 -- Easy to integrate with other android projects/apps.
 -- Enable cache configurably by users' need
 -- The same image may be requested by multiple sources simultaneously (even before it has loaded), and if one of
    the sources cancels the load, it will not affect the remaining requests.
 -- An image load can be cancelled by users' need.
 
How to integrate into your project?
- Jsut copy and paste the jpics folder and make sure you changed the package name with your package.

Example: 
 JPics.with( context ).setUrl( Url ).into( imageView ); - done!
