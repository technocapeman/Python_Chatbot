# Python Chatbot
Hello, and welcome to Python Chatbot! This program was made by Kapilesh Pennichetty and Sanjay Balasubramanian. Through user interaction, it can do the following:

- Store and return the user's name using global variable "name".
- Retrieve the weather of a location automatically using an IP address or manually with a user input*
- Retrieve the introduction to a Wikipedia article
- Play an interactive story, where you decide how the character reacts to different scenarios

*Please note that if you are going to use the automatic IP address function, you must run it on a local machine for accurate results. This is because the program needs your IP address to accurately find your location, and then it uses your location to retrieve the weather. Also, please disable your VPN or Internet Proxy for accurate results.

Also, please note that you will need to have Python 3.7 or newer with pip to run this program.

To operate the chatbot, you must first install these dependencies for the chatbot to be functional:

- Wikipedia API

  - For Windows users:
    - Open the command prompt and type:
    ```shell
    pip3 install wikipedia-api
    ```
  - For POSIX (including macOS and Linux) users:
    - Open the terminal and type:
    ```shell
    $ python -m pip install wikipedia-api
    ```
  
- PyOWM

  - For Windows users:
    - Open the command prompt and type:
    ```shell
    pip install pyowm
    ```
  - For POSIX (including macOS and Linux) users:
    - Open the terminal and type:
    ```shell
    $ python -m pip install pyowm
    ```
  
- IPStack for Python (Geo Location Library)

  - For Windows users:
    - Open the command prompt and type:
    ```shell
    pip install ipstack
    ```
  - For POSIX (including macOS and Linux) users:
    - Open the terminal and type:
    ```shell
    $ python -m pip install pyowm
    ```
    
Then, download this repository, and run the "main.py" file to start interacting with the chatbot!

Please note that the program is currently in a beta stage, and that there may be issues with the program. Please feel free to send us feedback on our program.

Thank you for using Python Chatbot! We hope you enjoy using it!

# Sources
**Special thanks to Mr. Bailey Hulsey for his contributions and for sharing his knowledge of computer science to noobs like us!**

- Wikipedia API and Documentation: https://github.com/martin-majlis/Wikipedia-API
- Wikipedia: https://wikipedia.org
- OpenWeatherMap Raw API and Documentation: https://openweathermap.org/current
- OpenWeatherMap Python Library and Documentation: https://github.com/csparpa/pyowm
- ipstack Raw API and Documentation: https://ipstack.com/documentation
- ipstack Python Library and Documentation: https://github.com/nathan-fiscaletti/ipstackgeo-py
