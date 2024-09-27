# Restaurant Reviews Challenge - Yelp MVP

## Background & Objectives

The objective of this challenge is to build a Ruby on Rails application featuring two main models: Restaurant and Review. The app allows users to create restaurants and submit anonymous reviews for them. This project demonstrates the use of Ruby on Rails for building a full-stack web application, along with JavaScript for handling dynamic behaviors on the client side.

## Features

* Restaurant Management: Users can create, view, and list restaurants.
* Anonymous Reviews: Users can submit reviews for restaurants without requiring a login, ensuring anonymity.
* CRUD Functionality: Full Create, Read, Update, and Delete operations for restaurants and reviews.
* JavaScript Integration: Front-end enhancements with JavaScript to improve user experience, such as form validation and dynamic content loading.

## Stack
* Ruby on Rails: Backend framework for building the server, handling routing, and managing database interactions.
* JavaScript: Used for enhancing the front-end with dynamic content updates and interactivity.

## Models
* Restaurant: Represents a restaurant with attributes like name, address, and cuisine.
* Review: Represents an anonymous review with attributes like rating, comment, and a reference to the associated restaurant.

## Objectives

* Two-Model App: Implement two models, Restaurant and Review, with a one-to-many relationship. A restaurant can have many reviews, while each review belongs to a specific restaurant.
* Anonymous Reviews: Allow users to submit reviews without the need for authentication.
* Frontend Interaction: Use JavaScript to improve the user experience, such as handling form submissions or dynamically updating content without reloading the page.
* CRUD Functionality: Implement full CRUD operations for both restaurants and reviews.

## How to Run the Project
1. Clone the repository:

```
git clone https://github.com/yourusername/restaurant-reviews-challenge.git
cd restaurant-reviews-challenge
```

2. Install dependencies:

```
bundle install
yarn install
```

3. Set up the database:

```
rails db:create
rails db:migrate
```

4. Run the application:

```
rails server
```

Navigate to http://localhost:3000 to view and interact with the application.

## Future Enhancements

* Pagination: Add pagination for the list of restaurants and reviews for better user navigation.
* Rating System: Implement an average rating for each restaurant based on user reviews.
* Review Moderation: Introduce a feature to flag or moderate inappropriate reviews.
* Improved UI: Use additional JavaScript and CSS libraries to enhance the user interface and experience.

## Contributions

This project is part of my learning journey, and contributions are welcome! If you have suggestions for improvements, feel free to open an issue or submit a pull request.
