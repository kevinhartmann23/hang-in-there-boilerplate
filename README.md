# Hang In There

A boilerplate repo. A motivational boost.

## Contributors
* Kevin Hartmann (https://github.com/kevinhartmann23)
* Luke Mason (https://github.com/LukeMason33)

## Final Product
* Deployed Site (file:///Users/lukemason/turing/module1/projects/hang-in-there-boilerplate/index.html)

## Technology Used
* HTML, CSS, JavaScript

### Main Page

![screenshot of main page showing poster](/readme-imgs/homepage.png)

- When the page loads, you should get a random motivational poster with some truly inspirational stuff on there.
- There are 4 buttons that are clickable on this page:
    * __Show Another Random Poster__ -when this button is clicked, another motivational poster will display on the screen, just in case if the current poster you're looking at isn't motivating enough.
    * __Make Your Own Poster__ -when this button is clicked, you will be redirected to a page where you can input your image, title, and quote in order to get that customizable motivation experience that you are looking for!
    * __Save Poster__ -when this button is clicked, it will save the current poster that is shown in your screen to your own personal motivational poster cache.
    * __Show Saved Posters__ -when this button is clicked, it will take you to all of those incredible posters you saved

### Make Your Own Poster Form
When that "Make Your Own Poster" button is clicked it will bring you to this page:
![screenshot of form](/readme-imgs/form.png)
- Within those text boxes, put whatever your little heart desires that you would like to see get posted onto a poster. Once those boxes are filled to your liking, you can click on that "Show My Poster" button and it will display your poster for you (and whoever is looking at your screen) to see! And if it's poster you wish to keep, make sure to click that "SAve Poster" button!
- But if for some reason you're not feeling making your own poster, just hit that "Nevermind Take Me Back" button to return to the main page to recieve that random poster goodness.

### Saved Posters Page
When that "Show Saved Posters" button is clicked on the main page, it will bring you here:
Saved posters page (once working with extra saved posters):
![screenshot of saved posters page](/readme-imgs/saved.png)
- Here you can view all the posters you clicked that "Save" button on the main page. But instead of them being their large, original selves, they've turned into some fancy little posters.
- We've also added this nifty little feature on here that when you double click on one of the mini posters, it will remove it form your page. You know, just in case if that poster wasn't giving off them good vibes.
- And then once you're all done pondering over your saved posters and want to return back to the main page, you can click that "Back To Main" button and continue on with all the poster goodness!

## Our Struggles
- Organizing our DOM so that our steps all flowed smoothly
-

## Future Additions
- 
_Hint: go check out the HTML and CSS files to see how the form and saved posters sections are being hidden in the first place_

## Iteration 2 - Creating a New Poster

Form being filled out:
![screenshot of form](/readme-imgs/form.png)

Once poster is saved:
![screenshot of result](/readme-imgs/form-result.png)

- On the new poster form view, users should be able to fill out the three input fields and then hit the save button
- When the save button is clicked, several things will happen:
  - Save the submitted data into the respective arrays (image URL into the images array, etc) so that future random posters can use the user-created data
  - Use the values from the inputs to create a new instance of our Poster class
  - Change back to the main poster view (hiding the form view again)
  - Display the newly created poster image, title, and quote in the main view

## Iteration 3 - Saving & Viewing Posters

Saved posters view:
![screenshot of saved posters section](/readme-imgs/saved.png)

- When a user clicks the "Save This Poster" button, the current main poster will be added to the `savedPosters` array.
- If a user clicks the "Save This Poster" more than once on a single poster, it will still only be saved once (no duplicates)
- When a user clicks the "Show Saved Posters" button, we should see the saved posters section
- All the posters in the `savedPosters` array should be displayed in the saved posters grid section

## Iteration 4 - Deleting Saved Posters

- From the saved posters view, if a user double clicks a saved poster, it will be deleted

_Hint: How will you update the data model to achieve this?_

## Optional Extensions - Gettin' fancy

Here's a list of possible extensions to implement - but **ONLY IF** your team has completed all the previous iterations **AND** have cleaned up your code to make it DRYer and more readable.

You are welcome to add your own extensions. Be sure they are thoughtful in terms of UX/UI, and that they do not break any prior functionality.

- Implement data validation and error handling into the form (disable button, provide error messages if data entered is not correct, etc)
- In the main poster view, allow users to click each piece of the poster (image, title, quote) to update just that piece with another random item from the appropriate array
- When a user single clicks a saved poster, create a modal to view it larger
- Allow users to drag and drop saved posters into whatever order they want them to appear


Project spec & rubric can be found [here](https://frontend.turing.io/projects/module-1/hang-in-there.html)
