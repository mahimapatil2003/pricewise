# Technologies and Frameworks

- Next.js: A React framework for building web applications. It is used for both the frontend and the backend of the application.
- Tailwind CSS: A utility-first CSS framework for rapidly building custom designs. It is used for styling the application.
- TypeScript: A statically typed superset of JavaScript. It is used for writing the code.
- Mongoose: An Object Data Modeling (ODM) library for MongoDB and Node.js. It is used for defining the product schema and interacting with the MongoDB database.
- Nodemailer: A module for Node.js applications to allow easy email sending. It is used for sending email notifications to users.
- Axios: A promise-based HTTP client for the browser and Node.js. It is used for making HTTP requests to scrape product details from Amazon.
- Cheerio: A fast, flexible, and lean implementation of core jQuery designed specifically for the server. It is used for parsing the HTML response from the Amazon product page.
- React Responsive Carousel: A lightweight carousel component for React. It is used for displaying a carousel of images on the home page.
- Google Fonts: A library of free licensed font families. It is used for defining the font styles in the application.
# Installation

Follow these steps to install and run the project:

1. **Clone the repository**

   Open your terminal and run the following command to clone the repository:

   ```bash
   git clone https://github.com/adrianhajdin/pricewise.git
   ```

2. **Navigate to the project directory**

   ```bash
   cd pricewise
   ```

3. **Install Node.js**

   The project requires Node.js to run. If you don't have it installed, you can download it from [here](https://nodejs.org/en/download/).

4. **Install the required packages**

   The project requires several packages to be installed. Run the following command to install them:

   ```bash
   npm i
   ```

5. **Install the required fonts**

   The project requires the "font-inter" and "font-spaceGrotesk" fonts to be available. You can download them from [Google Fonts](https://fonts.google.com/).

6. **Set up the environment variables**

   The project requires the MONGODB_URI environment variable to be defined. You can do this in a `.env` file in the root of your project:

   ```bash
   MONGODB_URI=your_mongodb_uri
   ```

7. **Start the server**

   Run the following command to start the server:

   ```bash
   npm run start
   ```

Now, you should be able to access the project at `http://localhost:3000`.

Please note that the project requires the "m.media-amazon.com" domain to be accessible for image handling. If you are unable to access this domain, you may encounter issues with image loading.
