# GifTok Project

Hello to [BigDevSoon](https://bigdevsoon.me/) 👋

Build a GIF exploration platform for mobile and desktop layouts.

## How to start

1. Start the project in our [app](https://app.bigdevsoon.me/projects/giftok) to get a feel for it.
2. Review the requirements listed below in this README.
3. Go through the design assets on the [project's page](https://app.bigdevsoon.me/projects/giftok) to understand the project more.
4. Clone this repository or use [GitHub Codespaces](https://github.com/features/codespaces) to set up the project environment.
5. Choose your preferred technology stack and overwrite repository files as needed to set up your project structure. We included a few files and the `assets` folder for convenience, extracted from the design.
6. Begin coding, either using the Freerun mode to work on each card individually or the Speedrun mode to work at your own pace. Be sure to follow the guidelines outlined below.
7. Have a strong desire to learn and improve your skills as a Big Developer. 🚀

## Requirements

- [ ] Research and explore the [Giphy API's](https://developers.giphy.com/docs/api/endpoint/#trending) trending endpoint, which can return a maximum of 25 GIFs at once and has an offset limit of up to 5000 GIFs. Study [The GIF Object](https://developers.giphy.com/docs/api/schema/#gif-object) and store the API key securely as an environment variable.
- [ ] Implement the mobile version of GifTok, starting with displaying a single GIF from the trending endpoint.
- [ ] Enable loading more GIFs by utilizing parameters such as limit and offset, allowing users to swipe to view the next GIF.
- [ ] Implement swipe functionality to enable users to navigate back to the previous GIF, ensuring it stops at the first GIF when reaching the beginning.
- [ ] Load more GIFs as the user approaches the end to provide a seamless transition, allowing for infinite scrolling until no more GIFs are available (which is unlikely to occur with 5000 possible GIFs).
- [ ] Display the user's avatar URL, username, and GIF title in the bottom-left corner of the GIF.
- [ ] Implement skeleton loading animations while new GIFs are being loaded to enhance the user experience during fast swiping.
- [ ] Develop the desktop version of GifTok, either utilizing the [Giphy Grid](https://github.com/Giphy/giphy-js/blob/master/packages/react-components/README.md#grid) component or a custom implementation, displaying skeleton loaders as GIFs load, and providing an animated loader when scrolling for more GIFs. Show user details and GIF titles on hover, similar to the mobile version.
- [ ] Handle edge cases such as no more GIFs to load, error handling, and other potential scenarios that may arise.

## Guidelines

1. Aim for pixel-perfect implementation of the design. Use tools like [PixelParallel](https://chrome.google.com/webstore/detail/pixelparallel-by-htmlburg/iffnoibnepbcloaaagchjonfplimpkob?hl=en) or other techniques to ensure accuracy.
2. Write clean and efficient code. Use extensions like [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) and [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) for formatting and errors, and consider using [GitHub Copilot](https://github.com/features/copilot) and [VSCode](https://code.visualstudio.com/) as your code editor.
3. Follow a [GitHub flow](https://docs.github.com/en/get-started/quickstart/github-flow). Keep your commits small and descriptive, organize your work into separate branches, and use pull requests for code reviews.

Remember, the cleaner and more accurate your code is, the faster you can finish and the better you'll feel about your work.
So let's make it happen! 💡

## Submitting project

Once you've completed the project and unlocked the Submit step in our app, it's time to deploy your project to [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/), or [GitHub Pages](https://pages.github.com/) (if you haven't done so already). Keep in mind that we've added a `<bds />` tag to the `index.html` file, and we'll check for it when you submit your Project URL. So don't forget to include it! You'll also need to provide the project title and the primary frontend technology used. Good luck!

## We're in Beta and getting better every day!

Hey there, Big Developer! We wanted to take a moment to thank you for participating in our project and helping us improve our platform. We're always looking for ways to make our app better, so if you have any feedback or suggestions, please feel free to let us know.

Happy coding! 🚀
