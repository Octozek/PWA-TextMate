# J.A.T.E - Just Another Text Editor

## Description

J.A.T.E is a Progressive Web Application (PWA) text editor that runs in the browser. This single-page application meets PWA criteria and features multiple data persistence techniques, ensuring reliable functionality offline. Built using Webpack, Babel, IndexedDB, and Workbox, this project demonstrates modern web development practices.

## Features

- **IndexedDB**: For storing and retrieving text editor content.
- **Service Worker**: Using Workbox to cache static assets for offline use.
- **Babel**: For transpiling next-gen JavaScript.
- **Webpack**: For bundling JavaScript files.
- **PWA**: Installable as a Progressive Web Application with a manifest file.

## Installation

### Local Development

1. Clone the repository:
```bash
   git clone https://github.com/Octozek/PWA-TextMate.git
   cd PWA-TextMate
```
2. Install server dependencies:

```bash
npm install
```
3.  Install client dependencies:

```bash
cd client
npm install
cd ..
```

4. Build the client:

```bash
npm run build
```

5. Start the server:

```bash
npm run server
```

6. Open your browser and navigate to http://localhost:3000.

## Usage

- Text Editing: Type in the editor, and your content will be automatically saved.
- Offline Use: The application works offline thanks to service worker caching.
- PWA Installation: Click the "Install!" button to install the app as a PWA on your device.

## Deployed Application
[Live Demo](https://pwa-textmate.onrender.com/)

## Screenshots
![Screenshot](img/Screenshot_498.png)

## Technologies Used
- HTML5
- CSS3
- JavaScript (ES6+)
- Webpack
- Babel
- IndexedDB
- Workbox
- Express.js

## Contributing
Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are warmly welcome.

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
Ezekiel Owens - octozek@gmail.com

Project Link: [https://github.com/Octozek/PWA-TextMate](https://github.com/Octozek/PWA-TextMate)