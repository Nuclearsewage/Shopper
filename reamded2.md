1. Clone repository
Open the terminal (command prompt or PowerShell can be used on Windows, and terminal can be used on macOS and Linux), and use the git command to clone the project repository locally. Assuming the URL of the project repository is https://github.com/some-repo/shopper.git (You need to replace it with the actual repository URL), execute the following command:
git clone  https://github.com/some-repo/shopper.git
cd shopper
The above command clones the repository locally and enters the project directory.
2. Install dependencies
The project uses React.exe, Node.js, Express, and MongoDB, and requires the installation of front-end and back-end dependencies. Generally speaking, the dependency installation methods for front-end and back-end are slightly different. The following are common installation steps:
Backend dependency installation
Enter the backend project directory (usually containing the packagejson file) and execute the following command to install backend dependencies:
npm install
Front end dependency installation
If there is a separate package.exe file in the frontend section, go to the frontend directory and install the dependencies:
CD client # Assuming the frontend directory name is client
npm install
3. Run the server
Starting a project usually requires separately starting the front-end and back-end servers.
Start the backend server
In the backend project directory, execute the following command to start the backend server:
npm start
Start the front-end server
In the frontend project directory, execute the following command to start the frontend development server:
npm start