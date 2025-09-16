# Fast React Pizza 🍕

A fast-food style pizza ordering frontend built with React — users can browse the menu, customize pizzas, add them to the cart, and place orders (example project from Jonas Schmedtmann’s course).

## 🚀 Features
- Browse pizza menu with sizes, prices, and descriptions.
- Add pizzas to cart and update quantities,Make order and use your location.
- Calculate total price and view order summary.
- Responsive UI for mobile and desktop.
- Example data loading with React Router loaders / async data fetching.

## 🛠️ Technologies Used
- React (functional components)
- React Router (data loading / routing)
- Redux / Redux Toolkit (state management) — optional depending on your fork
- Tailwind CSS for styling (or plain CSS if you prefer)
- JavaScript (ES6+)

## 📂 How to Run
1. Clone the repository.
2. Run `npm install` to install dependencies.
3. (Optional) If the project uses a mock API, start the mock backend:
   - If `json-server` is included:
     ```bash
     npx json-server --watch db.json --port 4000
     ```
   - Or follow the repo's instructions for any custom backend.
4. Start the development server:
   ```bash
   npm start
