# Movie App

In this project, I developed a movie app using React and Vite. The app retrieves data from the TMDB API and presents it in a card format. Users can search for movies and view movie information such as rating, language, release year on a card. The app also features a trending movies section based on user search queries. To manage this, I integrated Appwrite as a Backend-as-a-Service (BaaS) to store the most-searched movies. Additionally, I implemented debouncing to minimize API calls while users type in the search bar, enhancing performance and efficiency.

## Technologies Used
- React
- Vite
- Appwrite

## Deployment
The app is deployed on Vercel and can be accessed [https://movie-app-react-peach.vercel.app/](https://movie-app-react-peach.vercel.app/).

## Resources Used
[https://youtu.be/dCLhUialKPQ?si=PHzgeWDuoG78AYfq/](https://youtu.be/dCLhUialKPQ?si=PHzgeWDuoG78AYfq/)


## React + Vite Details

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

### Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
