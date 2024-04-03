# Tech Stack Advisor

<br/>
<p align="center">
    <a href="https://www.openai.com/" >
        <img alt="OpenAI's GPT-3 Turbo (for AI-powered features) - An autoregressive language model that uses deep learning to produce human-like text" src="https://img.shields.io/static/v1.svg?label=OpenAI&message=GPT-3-turbo&color=brightgreen" /></a>
    <a href="https://nodejs.org/" >
        <img alt="Node.js - A JavaScript runtime built on Chrome's V8 JavaScript engine, used for building fast and scalable network applications" src="https://img.shields.io/static/v1.svg?label=Node.js&message=JavaScript runtime&color=lightyellow" /></a>
    <a href="https://www.npmjs.com/" >
        <img alt="Node Package Manager" src="https://img.shields.io/static/v1.svg?label=npm&message=packages&color=lightblue" /></a>
    <a href="https://reactjs.org/" >
        <img alt="React - A JavaScript library for building user interfaces" src="https://img.shields.io/static/v1.svg?label=React&message=UI library&color=blue" /></a>
    <a href="https://expressjs.com/" >
        <img alt="Express.js - Fast, unopinionated, minimalist web framework for Node.js" src="https://img.shields.io/static/v1.svg?label=Express.js&message=Web framework&color=green" /></a>
    <a href="https://github.com/">
        <img alt="GitHub (for repository hosting and project management) - Provides hosting for software development and version control using Git" src="https://img.shields.io/static/v1.svg?label=GitHub&message=hosting&color=lightgrey" /></a>
    <a href="https://opensource.org/license/mit/">
        <img alt="The MIT License" src="https://img.shields.io/static/v1.svg?label=License&message=MIT&color=lightgreen" /></a>
</p>
<br/>
TechStackAdvisor is your personal AI-powered consultant designed to provide technology stack recommendations for your software projects. Just describe your project needs, and receive insightful, AI-generated advice on the most suitable technologies to use.

## Features

- Receive AI-generated technology stack recommendations based on your project description.
- Full-stack application with a React frontend and an Express backend.
- Leverages OpenAI's GPT-3 Turbo for generating recommendations.

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/naturuplift/TechStackAdvisor.git
```

2. Navigate to the project directory:

```bash
cd TechStackAdvisor
```

3. Install the required dependencies for both client and server:

```bash
cd server && npm install
cd ../client && npm install
```

## OpenAI API Key

To use TechStackAdvisor, you need an OpenAI API key. Sign up at OpenAI, set up billing, and generate an API key under "API Keys" in your account. Store this key securely and privately.

Create an .env file in the server directory to store your API key:

```bash
OPENAI_API_KEY=your_api_key_here
```

This setup ensures your API key remains secure and is not exposed publicly.

## Usage

Build the application presentation from project directory:

```bash
npm run build
```

Start the server:

```bash
cd server
npm start
```
In a new terminal, launch the client:

```bash
cd client
npm run preview
```

Navigate to `http://localhost:3000` in your web browser to start using TechStackAdvisor.

You can enter the project that you are looking to implement:

![image](https://github.com/naturuplift/TechStackAdvisor/assets/23546356/7392e9f0-4d15-45fb-b6ed-dfeeea7073a2)

Then application make use of OpenAI to advise on tech stacks for the project:

![image](https://github.com/naturuplift/TechStackAdvisor/assets/23546356/e0010f77-d7a7-4979-8dbb-b3b43b7f3ecb)

**Note:** Used Google Search Books as a boiler plate for this project and some functions need refactoring. 

## Contributing

Contributions are welcome! Feel free to fork the repository, make changes, and submit pull requests. If you have suggestions or encounter issues, please open an issue in the repository.

## License

This project is licensed under the [MIT License][mit-license]. See the LICENSE file for details.

[mit-license]: <https://github.com/naturuplift/TechStackAdvisor/blob/main/LICENSE>
