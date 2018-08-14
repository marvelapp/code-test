# Marvel code test
The task is to create a simple image zoom app with React.

It should take around 2-3 hours so please don't spend excessive amounts of time on it.

This [prototype](https://marvelapp.com/1gcfd93/) shows how the app might work.

Don't worry about styling, we're more interested in correct functionality and the quality of the code.

You can reference our GraphQL documentation [here](https://marvelapp.com/developers/documentation/)

You can get up and running using our developer key [here](https://marvelapp.com/oauth/devtoken) once you've logged the user you have been given for the test.


## Specification
* it should use the Marvel GraphQL to retrieve the project named "Code Test" and it's images. We will provide you with an account and login containing the project and it's images
* it should centre each individual image in the viewport
* it should initially render the image at the zoom level that fits the image, by width, to the viewport, or 100% of the image if the whole image width fits
* it should allow zooming in and out in 5% increments of the image
* it should zoom in to a maximum of 100% of the image
* it should zoom out to a minimum of 50% of the image
* it should allow selection of any of the 3 sample images provided

## Sample images
https://marvelapp.com/static/assets/images/onboarding/iphone6/Onboarding-invite.png
https://marvelapp.com/static/assets/images/onboarding/web/Main-page.png
https://marvelapp.com/static/assets/images/onboarding/ipad/Onboarding-location.png

## Implementation
The only stipulation is that you build the app in React (or a compatible library if you've been using, say, preact or inferno). Beyond that, you are free to use any library (except anything that already implements an image zoom component!).

You can write tests for the app but it's not a requirement.

To submit your solution either send us a link to a code repo or send us a zip file. Please provide simple instructions on how to run your app.
