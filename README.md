# Twitter-Clone
## Explanation : 
> This code creates a Twitter clone using JavaScript, HTML, and CSS. 
The code contains an HTML form with a textarea for the user to enter their tweet. 
The form is submitted using JavaScript and the entered tweet is displayed in a container on the page.

> The JavaScript code uses event listeners to listen for the form submit event. 
When the form is submitted, the textarea's value is stored in a variable, 
the textarea is cleared, and a new div element is created to represent the tweet. 
The tweet element is given a class of tweet and several child elements are added to it, including an avatar icon, the tweet text, a like button, and a likes count.

>The avatar icon is selected randomly from an array of avatar URLs and added to the tweet as an img element. 
The like button is created as a button element and has an event listener that increments the likes
count and updates the text of the like button and the likes count whenever it is clicked.

>The CSS code styles the tweet class to display the elements within it as a flex container with vertically aligned items.
The avatar is given a width and height of 50 pixels and a border radius of 25 pixels to make it circular. 
The like button is given a color of #1DA1F2 and the likes count is given a font weight of bold and a color of #657786. The new .likes-icon class is added to style the circle icon for the likes count, making it display as a blue circle with white text.

## Results : 
<img width="1429" alt="Screen Shot 2023-01-30 at 8 45 01 PM" src="https://user-images.githubusercontent.com/110359866/215580853-852eed2e-f44c-49c5-8b5e-3e085aa5fa72.png">

![code](https://user-images.githubusercontent.com/110359866/216446366-b38dba97-57c0-4f46-b160-e785666cec94.png)

Peace!
