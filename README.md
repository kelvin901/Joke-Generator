# phase-1-Independent Project
# Joke Generator

This project is a simple web application that generates random jokes using the JokeAPI from https://sv443.net/jokeapi/v2/. The application is built using JavaScript, HTML, and CSS, and utilizes the `fetch` function to retrieve data from the API. The application also includes a `db.json` file which serves as a local database for storing favorite jokes.

## Author

Kelvin Nyoike

## Technologies Used

- HTML
- CSS
- JavaScript
- JokeAPI
- db.json

## Installation

To run the application locally, follow these steps:

1. Clone the repository or download the ZIP file.
2. Navigate to the root directory of the project.
3. Open `index.html` in your preferred web browser.

## Usage

To generate a random joke, click the "Generate Joke" button. To save a joke to your favorites list, click the "Favorite" button. To view your favorite jokes, click the "View Favorites" button.

## Credits

This project was built using the JokeAPI from https://sv443.net/jokeapi/v2/.

## License

This project is licensed under the MIT License.
## Checklist/Outline

Create Basic HTML Structure - COMPLETE
Fill it in with Divs/Forms/Title/etc - COMPLETE
Little CSS - COMPLETE
Fetch JavaScript Data and Render On Page (randomly) - COMPLETE (for two liners)
Add Buttons to Render New Joke - COMPLETE (for two liners)
Add Function to Hide Punch Line for Two Liners - COMPLETE
Reveal Punchline Button/Hover/whatever - COMPLETE
Add Upvote/DownVote Buttons - COMPLETE
Add Bookmark Button - COMPLETE
Add Joke Submission Form - COMPLETE (for two liners)
    -Name
    -Setup
    -Punchline
        -Note: Either the Setup or the Punchline will need to be optional in case of one liner joke
    -Category
Joke Request Form - COMPLETE
    -Dropdown Selections for Categories
    -Or a Checklist
    -?






Maybe a Dark/Light Mode Toggle Event Listener?

Add Font Awesome Icons for Buttons, etc - COMPLETE

For Reference:  These Functions have been consolidated into one function, "postJoke"
// const postBookmarkedJoke = (bookmarkedJokePost) => {
//     fetch(LOCAL_URL + "bookmarkedJoke", {
//         method: "POST",
//         headers: {
//             "Content-Type": "application/json",
//         },
//         body: JSON.stringify(bookmarkedJokePost),
//     })
//     .then((response) => response.json())
//     .then((bookmarkedJokePost) => {
//         console.log("Success:", bookmarkedJokePost);
//     })
//     .catch((error) => console.error(error))
// }

// const postUserJoke = (userJokePost) => {
//     fetch(LOCAL_URL + "userJoke", {
//         method: "POST",
//         headers: {
//             "Content-Type": "application/json",
//         },
//         body: JSON.stringify(userJokePost),
//     })
//     .then((response) => response.json())
//     .then((userJokePost) => {
//         console.log("Success:", userJokePost);
//     })
//     .catch((error) => console.error(error))
// }
