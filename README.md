# Cookie Clicker

We're developing a hot new game called "Cookie Clicker" that is going to blow up the mobile-friendly web-app gaming world!

The game functionality is all set! It counts the number of times the user clicks the cookie image in the middle of the screen. In our first round of user testing, we discovered that when a user refreshes the page, they didn't like that they had to start all over. We have now implemented cookies so they keep their score!

If you'd like a little more context on cookies before diving in, the [w3schools intro](https://www.w3schools.com/js/js_cookies.asp) is a good place to start.

If you'd like to look at pictures of cookies before you start, [unsplash](https://unsplash.com) is a great place for free stock images, and it has [pictures of cookies](https://unsplash.com/search/photos/cookies).

## Base

Start this project with `npm start`

In the second round of user testing, we found that users like to see their name on the screen.

- [ ] The username should display on the screen.
- [ ] When a user clicks the `Edit Username` button, the username display should turn into an input, and the button should turn into a `Save` button.
- [ ] When the user selects the save button, it should turn back into an `Edit Username` button, and the input should turn back into a display of the new name.
- [ ] When the user refreshes the page, they should continue to see their name.

To see all of the cookies for your application. Open the dev tools, then click `Application`. Scroll down to `Storage`, and `Cookies` should be one of the options you can view.

Clear your cookies before starting this assignment by clicking the 🚫symbol in the cookies page dev tool. Doing this regularly will avoid potential cookie conflicts between sites you are developing.

![Cookies Dev Tool](/images/cookies-dev-tool.png)

## Stretch

- [ ] Allow the user to log out by removing the cookie.
- [ ] Every time a user clicks the cookie, change the background of the site to a random image of a cookie. The [unsplash api documentation](https://unsplash.com/documentation) will be helpful here.