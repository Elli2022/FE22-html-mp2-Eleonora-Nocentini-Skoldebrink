# HighStDeliAndMarketImitation

## Project Description

This project is a mini-project aimed at creating a responsive website for a restaurant using Tailwind CSS. The website consists of several pages including a homepage, a menu page, and a reservation page.

## Installation

Follow these steps to install and run the project locally:

1. Clone this repository:
    ```sh
    git clone https://github.com/yourusername/HighStDeliAndMarketImitation.git
    ```

2. Navigate to the project folder:
    ```sh
    cd HighStDeliAndMarketImitation
    ```

3. Install the necessary npm packages:
    ```sh
    npm install
    ```

4. Build the CSS files with Tailwind:
    ```sh
    npm run build
    ```

5. Start a local server to view the website:
    ```sh
    npx http-server ./src
    ```

6. Open your browser and go to `http://127.0.0.1:8080` to view the website.

## File Structure

The project's file structure is as follows:

HighStDeliAndMarketImitation/
│
├── dist/
│ └── output.css
│
├── node_modules/
│
├── src/
│ ├── css/
│ │ └── styles.css
│ ├── html/
│ │ ├── bokabord.html
│ │ └── meny.html
│ ├── images/
│ │ ├── cheeseBurger.jpeg
│ │ ├── highStMarketDeliLogo.png
│ │ ├── highStreetDeli933.jpg
│ │ └── highStreetMarjetAndDeli.jpg
│ └── index.html
│
├── .gitignore
├── package-lock.json
├── package.json
└── tailwind.config.js


## Deployment

This project is configured for easy deployment on Netlify. The following settings are used:

- **Branch to deploy:** `main`
- **Base directory:** (Leave empty)
- **Build command:** `npm run build`
- **Publish directory:** `src`

## Technologies Used

- HTML
- Tailwind CSS

## Tailwind CSS Configuration

The project uses Tailwind CSS to quickly and easily create responsive designs. The Tailwind configuration can be found in `tailwind.config.js`.

## Contact

For questions or support, contact Eleonora Nocentini Skoldebrink via [email](mailto:eleonora.nocentini@gmail.com).
