##Pacman telegram widget 
A classic pacman arcade game built as a standalone telegram widget. 

##About
Pacman is a classic arcade game where pacman collects dots, avoids ghots and tries to achieve the highest score. 

##Features
1. Classic pacman gameplay 
2. Interactive maze
3. Ghost AI 
4. Multiple lives
5. Game-over screen 

##Technologies 
1. HTML5
2. Javascript 
3. Canvas 2D
4. Telegram widget runtime

##Deployment/Player edition
You don't need node.js or dev tools to play the game.
Play online:
1. Open the published game URL in a supported browser or Telegram Widget environment.
2. Start playing!

Run the downloaded build:
1. Doanload the standalone production file: dist/index.html
2. Open the downloaded index.html file in a browser 
3. Start playing!

##Deployment/Developer edition
Installation & Setup
1. Clone the Repository
git clone https://github.com/rounakserry/pacman.git
cd pacman

2. Install Dependencies
npm install

3. Run the Widget in Development Mode
npm run dev
Open the local development URL displayed in your terminal.

4. Build for Production
npm run build
The production build will be generated at:
dist/index.html

Testing with Telegram Widget Sandbox

The Pac-Man project is developed independently from Telegram Widget Sandbox.
1. Clone Telegram Widget Sandbox

git clone https://github.com/TelegramMessenger/widget-sandbox.git
cd widget-sandbox

2. Install Sandbox Dependencies
corepack pnpm install

3. Start the Sandbox
corepack pnpm dev
Open the local URL displayed in your terminal.

4. Load Pac-Man
Use the Sandbox's documented widget loading procedure to load the Pac-Man widget and test it.
The generated production file is located at:
my-widgets/pacman/dist/index.html