<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->




<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/PhamQuangNhut/DaiVietGPT">
    <img src="image/logo.png" alt="Logo" style="border-radius: 10px;">
  </a>

  <h3 align="center">DaiVietGPT</h3>

  <p align="center">
    Web project on historical education implements Lagrge language model (LLM).
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://drive.google.com/file/d/1AccfH5VvhW4y9R9cVQIFBwY4SrirvpW0/view?usp=drive_link">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Ai trong chúng ta cũng đã từng thích thú hào hứng với những câu chuyện do ông bà, cha mẹ kể lại về những trải nghiệm thời chiến. Dường như đây là cách tốt nhất để một người trẻ cảm nhận rõ về sự hào hùng của nhân dân ta trong các câu chuyện lịch sử. Từ ý tưởng đó nhóm 1954 đã phát triển ứng dụng Web sử dụng mô hình ngôn ngữ lớn LLM để nhập vai vào các vĩ nhân anh hùng lịch sử Việt Nam và kể lại các câu chuyện cho người dùng. Từ đó ta có thể cảm thấy yêu thích lịch sử, sự hào hùng của văn hóa dân tộc và yêu nước hơn. Đồng thời dự án cũng tăng tinh thần học hỏi môn sử, tạo ra một phương pháp học mới cho môn học này.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* Python
* Huggingface
* Pytorch
* OpenAI API
* Node.js
* React
* MySQL
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AI -->
## AI
We provide a Python package for setting up the system locally.

### Prerequisites
* Python 3.10

### Installation
To get the AI running, follow these steps:
1. Clone the repo
   ```sh
   git clone https://github.com/PhamQuangNhut/DaiVietGPT.git
   ```
2. Setup Python environment
	 ```sh
	  pip install -r AI/requirements.txt
	```
### Usage
3. Deploy mainly on Colab

   Get your FireBase config.json at https://firebase.google.com/
   
  Enter path to your config file 
   ```js
  firebase_admin.initialize_app(cred, {
      # gs://daivietgpt.appspot.com
      'storageBucket': 'daivietgpt.appspot.com'
  })
   ```

   
   Get a free OpenAI API Key at https://platform.openai.com/

  Enter your OpenAI API key
   ```js
   client = OpenAI(api_key = '...')
   ```

   Get a free Ngrok Key at https://dashboard.ngrok.com/tunnels/authtokens

  Enter your Ngrok key
   ```js
   ngrok.set_auth_token('...')
   ```
   
   run Colab.ipynb

## Software

### Prerequisites
To deploy the software, you need to have the following installed:
* WSL 2 (required if you are using Windows)

### Installation
1. Clone the repo
   ```sh
   git clone https://github.com/PhamQuangNhut/DaiVietGPT.git
   ```
2. Rename ```.env.example``` to ```.env``` and fill in the required information.
3. Build the images and run the container.
    ```sh
    npm install
    npm run
    ```
  For more details, please refer to the [Software Documentation](docs/Software.md).


### Example
Here is an example of the system in action. The system will track the user's pose and provide feedback should there be any errors.
<p align="right">(<a href="#readme-top">back to top</a>)</p>





### Demo
We provided a demo video for the software. Please refer to the [Demo Video](https://drive.google.com/file/d/1AccfH5VvhW4y9R9cVQIFBwY4SrirvpW0/view?usp=drive_link).
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License
Distributed under the **BSD 3-Clause License** License. See [LICENSE](LICENSE) for more information.


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
<!-- ## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p> -->



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->


