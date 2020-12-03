# Python Chatbot
Hello, and welcome to Python Chatbot! This program was created by Kapilesh Pennichetty and Sanjay Balasubramanian. Through user interaction, it can do the following:

- Retrieve the summary of a Wikipedia article
- Find the weather of any location, automatically by finding the user's location using their external IP address*, or manually by prompting the user to enter a city
- Play an Interactive Story, where the user decides how the character responds to different scenarios

*Please note that if you are going to use the automatic IP address function, you must run it on a local machine for accurate results. This is because the program needs your IP address to accurately find your location, and then it uses your location to retrieve the weather. Also, please disable your VPN or Internet Proxy for accurate results.

Also, please note that you will need to have Python 3.7 or newer to run this program. You can install Python for your operating system here: https://www.python.org/

To operate the chatbot, you must first install these dependencies for the chatbot to be functional:

- Wikipedia API

  - For Windows users:
    - Open the command prompt and type:
    ```shell
    pip install wikipedia-api
    ```
  - For POSIX (including macOS and Linux) users:
    - Open the terminal and type:
    ```shell
    $ python3 -m pip install wikipedia-api
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
    $ python3 -m pip install pyowm
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
    $ python3 -m pip install ipstack
    ```
    
Then, download this repository, and run the "main.py" file to start interacting with the chatbot!

Thank you for using Python Chatbot! We hope you enjoy using it!

# Sources
**Special thanks to Mr. Bailey Hulsey for his contributions and for sharing his knowledge of computer science to noobs like us!**

- Wikipedia API and Documentation: https://github.com/martin-majlis/Wikipedia-API
- Wikipedia: https://wikipedia.org
- OpenWeatherMap Raw API and Documentation: https://openweathermap.org/current
- OpenWeatherMap Python Library and Documentation: https://github.com/csparpa/pyowm
- ipstack Raw API and Documentation: https://ipstack.com/documentation
- ipstack Python Library and Documentation: https://github.com/nathan-fiscaletti/ipstackgeo-py
