# Introduction
Hands-on demo (Part 2) project to showcase: 
How to install a library into the local maven repository
How to use a java library from the local .m2 maven repository

THIS IS A DEMO


# API
[TMDB API](https://developers.themoviedb.org/3/getting-started/introduction)

# Requirements
You'll need to go create an account to get an API key ([https://www.themoviedb.org/documentation/api](https://www.themoviedb.org/documentation/api))


# Dependencies

 - MovieAPI library (created in the Part 1 - Hands-on)
 
``` 
<dependency>
	<groupId>gr.unipi</groupId>
	<artifactId>MovieAPI</artifactId>
	<version>0.0.1-SNAPSHOT</version>
</dependency>
```

# Maven Coordinates

To add this library as a dependency add the following maven coordinates into your pom.xml file

    <dependency>
	    <groupId>gr.unipi</groupId>
	    <artifactId>MovieApp</artifactId>
	    <version>0.0.1-SNAPSHOT</version>
	</dependency>
