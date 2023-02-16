# Daily Stoic
Welcome to The Daily Stoic project! The Daily Stoic is an add-on for the Museum of Stoicism popup website that generates profound quotes from some of history's greatest stoic thinkers.

## Features
The Daily Stoic includes the following features:

 - **Quote Generation**: The app generates a new quote each time the user clicks the "Generate" button.
 - **Audible Button**: For users who are hearing impaired, the "Speak" button uses a SpeechSynthesisUtterance object to speak the quote aloud.
 - **Copy Button**: The "Copy" button stores the generated quote in the user's clipboard for easy sharing.
 - **Twitter Button**: The "Tweet" button quickly transitions the user to their Twitter profile and populates a tweet containing the quote.

## Technologies Used
The Daily Stoic is built using HTML, CSS, and JavaScript. The CSS features a sleek design with clickable list items that have a nice hover-over effect. The HTML includes three list item buttons with event listeners and their own functions attached. For the quote generation, a simple arrow function called randomQuote() is used with a fetch to an API that receives both the author and text data.

## Future Plans
In the future, I hope to add more features to The Daily Stoic, including:

 - **Customizable Voice**: I plan to change the voice of the SpeechSynthesisUtterance object to something more human.
 - **Daily Notifications**: I hope to create an entire mobile app that has the ability to notify the user daily that a new quote is waiting.
Thank you for checking out The Daily Stoic!



## Technologies

![HTML](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)
![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Google Chrome](https://img.shields.io/badge/Google%20Chrome-4285F4?style=for-the-badge&logo=GoogleChrome&logoColor=white)
## Demo

https://daily-stoic-ac7d1.web.app/


## Screenshots

![stoic1](https://user-images.githubusercontent.com/48900828/219256665-ae14a782-0555-46b0-90b4-9c50ef4d147b.png)
## Acknowledgements

 - [The API used for the quote database](https://github.com/benhoneywill/stoic-quotes)
