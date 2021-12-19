React is a free and open-source front-end JavaScript library for building user interfaces or UI components. It is maintained by Facebook and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications. However, React is only concerned with state management and rendering that state to the DOM, so creating React applications usually requires the use of additional libraries for routing, as well as certain client-side functionality.
 
0.1 Why React.js is faster
The virtual DOM doesn’t regenerate the entire page. Developers can optimize the update process and create standalone virtual representations with an updated fragment. It’ll then be reconciled with the actual DOM, but only an edited portion of the codebase will be processed on the server. 
Instead of rolling out and processing new pages for each interaction, you can implement small changes.
An important note:
Virtual DOM makes the performance faster, not because the processing itself is done in less time. The reason is the amount of changed information – rather than wasting time on updating the entire page, you can dissect it into small elements and interactions.
 
1 React prerequisites
HTML, CSS, JavaScript.
ES6 understanding will make you comfortable with ReactJs.
 
React Js Environment up
Install Node and NPM
Install vs code editor 
Download vs code with this link
install the CRA app
npx create-react-app file-name  




1.1 What is a node and, How Node and NPM will be installed?
Node Package Manager (NPM) is a command-line tool that installs, updates, or uninstalls Node.js packages in your application. It is also an online repository for open-source Node.js packages. The node community around the world creates useful modules and publishes them as packages in this repository.
Official website: https://www.npmjs.com

1.2 How to install Node and NPM on Ubuntu.

curl -fsSL https://deb.nodesource.com/setup_14.x | sudo -E bash -










sudo apt-get install -y nodejs






NPM is included with Node.js installation. After you install Node.js, verify NPM installation by writing the following command in the terminal or command prompt.

C:\> npm -v
2.11.3





If you have an older version of NPM then you can update it to the latest version using the following command.
C:\> npm install npm -g



Labeling Key





Label Name
Extracted Text


Download vs code with this link


npx create-react-app file-name  








