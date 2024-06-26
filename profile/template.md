<br/>
<div align="center">
<a href="https://github.com/ShaanCoding/makeread.me">
<img src="images/logo.png" alt="Logo" width="80" height="80">
</a>
<h3 align="center">makeread.me</h3>
<p align="center">
An awesome ReadMe Generator to Jumpstart your Projects!
<br/>
<br/>
<a href="https://github.com/ShaanCoding/makeread.me/wiki"><strong>Explore the docs »</strong></a>
<br/>
<br/>
<a href="https://www.makeread.me/">View Demo .</a>  
<a href="https://github.com/ShaanCoding/makeread.me/issues/new?labels=bug&amp;template=bug_report.md">Report Bug .</a>
<a href="https://github.com/ShaanCoding/makeread.me/issues/new?labels=enhancement&amp;&template=feature_request.md">Request Feature</a>
</p>
</div>

![Contributors](https://img.shields.io/github/contributors/ShaanCoding/makeread.me?color=dark-green) ![Issues](https://img.shields.io/github/issues/ShaanCoding/makeread.me) ![License](https://img.shields.io/github/license/ShaanCoding/makeread.me)

## Table of Contents

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [What is PAPO?](#what-is-papo)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [For MacOS users: Use Homebrew](#for-macos-users-use-homebrew)
    - [`node.js & npm`](#nodejs--npm)
    - [`react`](#react)
    - [`next.js`](#nextjs)
    - [`python`](#python)
    - [`fastapi`](#fastapi)
  - [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

## About The Project

<img src="./img/demo.gif" alt="Screenshot" style="width: 100%;">

### What is PAPO?

The nature of the problem at hand revolves around the client's manual and time-consuming drug procurement processes, characterized by the need for constant evaluation of alternatives based on price, quantity, and packaging. Additionally, the criticality of specific drugs necessitates a precise and timely restocking strategy. Our final deliverable aims to address these challenges comprehensively through an AI-driven procurement solution. 

This solution comprises a three-tiered technical approach: continuous stock monitoring and replenishment based on live feed analysis, intelligent recommendations for alternative drug replacements drawn from the pharmacy's database, and the development of a user-friendly interface based on client feedback. The proposed model offers innovative features such as dynamic stock monitoring, intelligent alternative recommendations prioritized by cost, dosage preference, and packaging, and a user-centric interface tailored to streamline the buyer's decision-making process. This solution is poised to significantly optimize the client's drug procurement workflow, ensuring efficiency, accuracy, and responsiveness to critical drug restocking requirements.

### Built With

This project was built with the following technologies:

**Front End:**
- [Next.js](https://nextjs.org/)
- [React](https://react.dev/)
- [React Hook Form](https://react-hook-form.com/)

**Back End**
- [Python]()
- [FastAPI]()

**Server Side**
- [AWS]()
  - EC2
  - RDS
  - S3
  - Route53


## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This project requires `node.js & npm`, `react`, `next.js`, `python`, and `fastapi`, to be installed in your system. If you don&#39;t have it installed, you can follow these steps:

### For MacOS users: Use Homebrew

    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"        



#### `node.js & npm`

- **Recommended Method: Using Homebrew** ***(for MacOS users)*** | Others OS can download it from [here](https://nodejs.org/en/download/).
- Install Yarn globally using npm (Node Package Manager). Open your terminal and run:

  ```sh
  brew install node
  ```

    This command will install both **Node.js** and **npm** on your system.

- Verify that Node and npm has been installed on your machine by running the following command in your terminal:

  ```sh
  node --version
  npm --version
  ```

  If  has been installed correctly, your terminal should display the version of Node and npm installed on your machine.

#### `react`

- Install React using the [official documentation](https://react.dev/learn/installation)

#### `next.js`

- Install Next.js using the [official documentation](https://nextjs.org/docs/getting-started/installation)

#### `python`

- Install python using homebrew:

    ```sh
    brew install python
    ```

#### `fastapi`

- Open your terminal and run:
    
    ```sh
    pip install "fastapi[all]"
    ```

### Installation

Please follow the following steps for successful installation:

1. **Clone the Repository:** Get started by cloning the repository to your local machine.

   ```
   https://github.com/ShaanCoding/makeread.me
   ```

2. **Install Frontend Packages:** Navigate to the &quot;/frontend&quot; directory and install the required yarn packages by executing the following command in your terminal:

   ```sh
   yarn install
   ```

3. **Install Backend Packages:** Similarly, navigate to the &quot;/backend&quot; directory and install the required yarn packages by executing the following command in your terminal:

   ```sh
   yarn install
   ```

4. **Set Up Environment:**

   - In the &quot;/backend&quot; directory, copy the content of &quot;.env.example&quot; file and create a new file named &quot;.env&quot;. Adjust the environment variables according to your requirements or you can leave them as it is.

   - Navigate to &quot;frontend/api/generated/readMeGenerator.ts&quot; and set the BASE parameter to your backend API route. For instance, if you are running backend on your local server at port 8080, you should set:

     ```javascript
     BASE: "http://localhost:8080/api";
     ```

5. **Run the Backend:** Navigate to &quot;/backend&quot; directory and type the following command in your terminal to run your backend server:

   ```sh
   yarn dev
   ```

6. **Run the Frontend:** Finally, navigate to &quot;/frontend&quot; directory and type the following command in your terminal to run your frontend server:

   ```sh
   yarn dev
   ```

   Now, your application should be successfully up and running!

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag &quot;enhancement&quot;.
Don&#39;t forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m &#39;Add some AmazingFeature&#39;`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

    MIT License
    
    Copyright (c) 2024 PAPO
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.

## Contact

If you have any questions or suggestions, feel free to reach out to us:

- Raise an issue on the repository: [GitHub Repository](https://github.com/ShaanCoding/makeread.me)
- Connect with us on Twitter: [@ShaanCoding](https://twitter.com/ShaanCoding)

## Acknowledgments

A special thanks to the following for their contributions, support and inspiration:

- [makeread.me](https://github.com/ShaanCoding/makeread.me)
- [Othneil Drew](https://github.com/othneildrew/Best-README-Template)