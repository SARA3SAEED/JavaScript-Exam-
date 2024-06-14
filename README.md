# JavaScript Exam 1

**JavaScript Bootcamp First Exam**

If you want to become a skilled programmer, you must be a great researcher. Therefore, you are only allowed to use Google as a resource.

## Task 1: Create a New User Registration Page

1. **User Registration Page Requirements:**
    - **Username:**
        - Must be more than three characters.
    - **User ID:**
        - Must contain at least one uppercase letter.
    - **Email:**
        - Must contain an "@" symbol.
    - **Password:**
        - Must be more than four digits.
    - The user should not be able to proceed if any information is missing or incorrect.
    - After successfully filling in the details, the user should be redirected to the login page.

## Task 2: Create a Login Page

1. **Login Page Requirements:**
    - **User ID:**
        - Must verify that the User ID exists in the database.
    - **Password:**
        - Must verify that it matches the password used during the new user registration.

## Task 3: Create a New Page to Display User Information

1. **New Page Requirements:**
    - Display the username with an appropriate design.
    - Provide two options:
        - Prayer Times
        - Weather

## Task 4: Implement Prayer Times and Weather Features

1. **Prayer Times:**
    - Use the API: [Prayer Times API](https://aladhan.com/prayer-times-api#GetCalendarByCitys)
    - Extract the following data:
        - Hijri date
        - Gregorian date
        - Day
        - Prayer times
    - Include buttons to toggle between displaying the Hijri and Gregorian dates.

2. **Weather:**
    - Use the API: [OpenWeather API](https://api.openweathermap.org/data/2.5/weather?q=London&appid=yourkey)
    - Display the following data for the city of Riyadh:
        - City name
        - Temperature
        - Humidity
        - Longitude
        - Latitude

## Bonus: Search Feature

- Implement a search field to look up weather information for a specific city.

**Note:** The website should be responsive and compatible with all screen sizes.


## Demo Live: [here](https://sara3saeed.github.io/JavaScript-Exam-/)
