# IngrediGenie

IngrediGenie is a web-based application designed to combat food waste by generating creative recipes from ingredients you already have in your pantry. Built as a solo hackathon project, IngrediGenie empowers users to turn what might otherwise be wasted food into delicious meals, making sustainable cooking both easy and inspiring.

## **Features**

  - **AI-Powered Recipe Generation**: Generates unique recipes by leveraging the **OpenAI API** based on user-provided ingredients.
  - **Dynamic User Interface**: Asynchronously updates the web page with the generated recipe without a full page reload.
  - **Responsive Design**: A clean, modern interface that works seamlessly on both desktop and mobile devices.
  - **Smooth Animations**: Utilizes the **Intersection Observer API** for scroll-based fade-in animations, providing an elegant user experience.
  - **Intuitive Layout**: Features a simple two-page flow, guiding users from the home page to the recipe generation tool effortlessly.

## **Technologies**

  - **Back-end**:
      - **Python**: The core programming language.
      - **Flask**: A micro-framework used to build the back-end application.
  - **Front-end**:
      - **HTML5**: For structuring the content.
      - **CSS3**: For styling, with a custom stylesheet.
      - **JavaScript**: To handle front-end logic, API calls, and animations.
  - **API**:
      - **OpenAI API**: Used for AI-driven recipe generation.

## **Live Demo**

Experience IngrediGenie for yourself by visiting the live demo:

[**IngrediGenie**](https://ingredigenie.pythonanywhere.com/)

## **Usage**

1.  Navigate to the home page of the live demo and click **"Get Started"** to go to the recipe generation page.
2.  In the text area, list the ingredients you have available (e.g., "chicken, broccoli, pasta, garlic").
3.  Click the **"Get Recipe Ideas\!"** button.
4.  The application will call the OpenAI API and display a unique recipe card on the page.

## **Project Structure**

```
/ingredigenie
├── static/
│   ├── favicon.ico
│   ├── styles.css
│   └── (other static assets)
├── templates/
│   ├── get_started.html
│   └── home.html
├── app.py
└── README.md
```

  - **`app.py`**: The main Flask application file.
  - **`templates/`**: Contains the HTML files for the website.
  - **`static/`**: Stores static assets like stylesheets and images.

## **License**

This project is licensed under the MIT License.
