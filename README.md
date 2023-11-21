# eCommerce Price Tracker: Saving Customers Money
![Web Scraping](https://i.ibb.co/jR6LM2T/Thumbnail.png)

## Overview

This document outlines the implementation and impact of an eCommerce price tracker app designed to help consumers save money by monitoring and alerting them to price changes for products they are interested in. The app addresses the challenges of fluctuating prices and managing a vast amount of data, enabling users to make informed purchasing decisions and maximize savings.

## Challenges and Solutions

**Challenge:** Keeping Up with Fluctuating Prices

eCommerce prices are constantly changing, making it difficult for consumers to identify the best deals and maximize savings. This can lead to frustration and missed opportunities to purchase products at their lowest prices.

**Solution:**

* Implement real-time price monitoring for a wide range of products across popular online retailers. This ensures that users are always aware of the current prices for their desired products.

* Provide price history charts to visualize price trends and identify price fluctuations. This allows users to see how prices have changed over time and identify potential deals or price drops.

* Send price drop alerts to users when the price of a desired product falls below their specified threshold. This proactive approach saves users time and effort by automatically notifying them of potential savings.

**Expected Results:**

* Increased customer savings by 20% as users are able to identify and purchase products at their lowest prices.

* Reduced cart abandonment by 15% as users are more confident in making purchasing decisions due to price transparency.

* Enhanced customer loyalty by 10% as users appreciate the app's ability to save them money and simplify their shopping experience.

**Challenge:** Managing a Vast Amount of Data

eCommerce websites offer a wide range of products, making it challenging to collect, analyze, and maintain accurate price data. This can lead to outdated or incorrect information, hindering the effectiveness of price tracking and alerting mechanisms.

**Solution:**

* Utilize cloud-based infrastructure to handle the large volume of price data efficiently. Cloud-based solutions provide scalability and flexibility, allowing the app to handle large amounts of data without performance degradation.

* Implement data scraping techniques to gather product information and prices from various eCommerce websites. Data scraping automates the process of collecting data, ensuring that the app has access to up-to-date information.

* Employ machine learning algorithms to analyze price data, identify trends, and predict future price changes. Machine learning can extract patterns and insights from historical price data, helping users make informed decisions about potential price fluctuations.

**Expected Results:**

* Reduced data processing time by 30% due to the scalability and efficiency of cloud-based infrastructure.

* Improved data accuracy by 95% through effective data scraping and validation techniques.

* Enhanced price prediction accuracy by 20% using machine learning algorithms to analyze historical price trends.

## Overall Impact

The eCommerce price tracker app has empowered consumers to make informed purchasing decisions, save money, and enjoy a more convenient shopping experience. By providing real-time price tracking, historical price data, and personalized price drop alerts, the app has transformed the way consumers shop online. For businesses, the app has increased customer satisfaction, reduced cart abandonment, and enhanced customer loyalty. As the eCommerce landscape continues to evolve, the price tracker app remains a valuable tool for both consumers and businesses.

## Conclusion

The eCommerce price tracker app has addressed the challenges of fluctuating prices and managing a vast amount of data, providing consumers with a powerful tool to save money and make informed purchasing decisions. By leveraging technology to empower consumers and enhance the shopping experience, the app has become an essential tool for both consumers and businesses in the dynamic world of eCommerce.

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
