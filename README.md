# Fullstack Coding challenge

This is a Scribe Fullstack developer challenge.

# Intructions

- Please use your preferred development enviornment, programming language and tools.
- A candidate should submit their test results on a public git repository.
- Once you finish, please share the git repository URL with us so we can review your work.

# Challenge - Imgur feed viewer and search

Write a simple web application that reads data from Imgur's API and displays the images on the page to the user.
Please check the Imgur API documentation from the following URL:

- [Imgur](https://apidocs.imgur.com/)
- [Public feed](https://api.imgur.com/3/gallery/hot/viral/0.json)

## Details

- Write a web application that on page load, the applications should load the public feed images in either a list or grid view but without pagination(!), please make sure the apps' responsiveness is acceptable :)
- The user should be able to enter a keyword in a search box and click on a search button and the app should return images with the relevant tags.
- Use any other third party library of your choice if needed.
- You can use any UI library to make your application look good.

## Advanced details

- Please use a backend server, don't call Imgur api directly from the client.
- The Imgur public feed only return 50~ images, you can use register an app to work with their api and build a fetch larger set.
- It's OK to save imgur responses in a DB to avoid API rate limits.
- We value scalable solutions, a well-done gallery should be a able to support over 5K images+ (note that you probably won't need 5000 </img> elements in your DOM)
- Feel free to amaze us with a spactacular feature you think could make your gallery stand out (but feel free not to)
- High performant CSS is a plus! (not pretty, high performant, watch out for unnessesary layout calls)

## Important guidelines

- Don't overkill! it's _OK_ to leave TODOs and comments, we know your time is valuable 🕒
- Make sure we can easily run your code on our machines, deploying your solution to a cloud is appritiated ☁️
- Show us how you tested your code, TDD is cool but not a must, a pinch of tests should be enough ✨
- UI Design is not important(!!) we just know you can make images load blazing fast (Great UX) and look appealing.

## Super bonus

- Images can be large and load slow, espacially when the browser tries to load and render a lot of them.
- UX is important, and since we want to support 5K+ images in our gallery we want "the feel" of a fast smooth scrolling at all times.
- Hint: Add the prominent color of images in addition to the image url in your API, we'd love to see your design approach for this system.
- In the browser, the gallery can now show a colored box until the browser loads your images.

FYI: for inspiration check out:
[Google Image Search](https://www.google.com/search?q=rick+and+morty)
