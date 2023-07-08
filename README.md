## Dad Joke Generator

This project is a simple Dad Joke Generator that retrieves random dad jokes from an API and displays them on the webpage. Each time the user clicks the "Tell me a Joke" button, a new joke is fetched and shown.

### Usage
To use the Dad Joke Generator, open the `index.html` file in a web browser of your choice. The webpage will display the heading "Dad Joke Generator" along with a joke and a button labeled "Tell me a Joke". Clicking the button will retrieve a new joke and display it on the page.

### Features
- Random Jokes: The Dad Joke Generator fetches random dad jokes from an API to provide a variety of jokes for entertainment.
- Interactive Button: The "Tell me a Joke" button triggers the fetching of a new joke when clicked, updating the joke displayed on the webpage.
- Stylish Design: The webpage has a responsive design with a centered container and a visually appealing layout.

### Technologies Used
- HTML
- CSS
- JavaScript

### How It Works
1. When the webpage loads, the initial joke is displayed on the page.
2. Clicking the "Tell me a Joke" button triggers the `getJoke` function.
3. The `getJoke` function sends a GET request to the Dad Joke API using the provided API key.
4. The response from the API is received, and the joke is extracted from the data.
5. The joke is displayed on the webpage, replacing the previous joke.
6. The button text is updated to "Tell me another joke!" to indicate that a new joke can be fetched.

### Future Enhancements
- Error Handling: Implement error handling to display a message if there is an issue retrieving jokes from the API.
- Joke Categories: Add the ability to select specific joke categories or themes, allowing users to customize their joke preferences.
- Share Jokes: Include options for users to share jokes on social media platforms or copy them to the clipboard.

Feel free to explore the code and make modifications according to your requirements or to further enhance the project.

### Hosted Project
The Dad Joke Generator is hosted on GitHub Pages. You can access it [here](https://utkarshkrishna2004.github.io/Dad-Joke-Generator/).

Thank you!
