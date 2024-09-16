# 🍲 WEB APPLICATIONS PROJECT - [COOKINGTOK]

We have developed a **fully functional web page** where users can **share their recipes**! 🧑‍🍳 This project was built using **Python**, **SQL**, **HTML**, **CSS**, and even **JavaScript**. Feel free to check it out!

---

## 🧑‍💻 AUTHORS:
- **Francisco José Landa Ortega** - NIA: 100483174
- **Teresa Gener López** - NIA: 100472787
- **Diego Hernández Suárez** - NIA: 100472809

---

## ⚙️ SETUP INSTRUCTIONS:
No additional packages are required. Simply follow these steps to get started:

```bash
python3 -m venv venv
. venv/bin/activate
flask --debug --app=cooking run

pip install -U pip
pip install Flask python-dateutil
pip install flask-sqlalchemy mysqlclient
pip install flask-bcrypt
pip install flask-login

## Database Details:

Username: 24_webapp_028
Password: WgdPsWC3
Database name: 24_webapp_028c

## 💡 ADDITIONAL FUNCTIONALITIES:

📌 **Bookmark Feature**: A bookmark icon next to the recipe title changes depending on whether the recipe is bookmarked.
📋 **Recipe Status**: Differentiates between complete (with ingredients and steps) and incomplete recipes. The main page displays only complete recipes, while incomplete recipes can be accessed from the Create Recipe and My Profile views.
🖼️ **User Profile Features**: Displays user-specific data like their recipes, incomplete recipes, bookmarks, and uploaded images (if the user is authenticated).
↔️ **Drag-and-Drop for Steps**: JavaScript functionality allows users to drag and reorder recipe steps. Add/remove buttons for ingredients and steps are also available via JavaScript.
🔍 **Interactive Interface**: Hovering over elements (like a recipe) will increase their size to enhance user interaction.
💬 **Comment Section**: Users can leave multiple comments but are limited to one rating per recipe. The average rating is plotted and displayed below the recipe title.
🔎 **Search Functionality**: Search recipes by ingredients. While typing, the app will suggest existing ingredients from the database (e.g., typing "chee" will suggest "cheese").
🏠 **Home Navigation**: Clicking the CookingTok logo in the header always redirects the user to the main view.
📝 **Incomplete Recipe Handling**: Users can resume incomplete recipes they’ve started, continuing from the page where they add steps and ingredients.
🎨 **Aesthetic Design**: The webpage uses warm tones with a hint of grey to create a visually appealing experience.

🔐 ##USER ACCOUNTS ALREADY REGISTERED:

Email: curro@gmail.com | User: Curro123 | Password: Hola
Email: diego@gmail.com | User: Dieguito_guay | Password: minecraft
Email: teresa@gmail.com | User: Teresita_03cooker | Password: 1234
Email: maria@gmail.com | User: merylop7 | Password: 0000
