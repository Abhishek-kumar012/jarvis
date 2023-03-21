# jarvis
Introduction 👨‍💻
It is a voice assistant which can be used to interact with your computer and also you have been seeing it in Iron man movies, but this JARVIS is not that much advanced as shown in movies.

Built with: Python

Cool functionalities of JARVIS ):

It can access your mobile camera

I have wrote code which you can use JARVIS in the following ways :

It can tell count of Covid-19 cases for each state in India

It can do Screen Recording with voice recording stuff.

It can also do voice recording



It can access your web camera

It can find the location of a phone number
It can read pdf's

It can work as a telephone dictionary(Add contacts, search contacts)

It can generate qr codes for Links/anyText.

It can check/find your Internet speed

It can tell your IP address

It can tell the latest news

It can check the system condition

It can send gmails

It can send whatsapp messages to Individual & group chats

It can play youtube songs

It can download youtube songs

It can download instagram profiles

It can find/tell your current location where ever you are

It can take screenshots with a custom filename

It can tell current time

It can tell current day

It can tell random progrmamming jokes

It can also tell your schedule for each day

It can be silent for a certain number of time if we mention how much time we want it to be silent

It can search in wikipedia and tell about it in 5 lines

It can tell procedure/instructions how to make something.

It can search for information in browser which we want

It can control system volumes

It can control system power activities(Eg: shutdown, restart, sleep)

It can play music file in a particular directory where the songs are present

It can open your social media and open-source accounts

It can open your college meeting accounts

It can open your OTT platforms accounts

It can open your all google apps

It can open presentation tools like canva, google slide

It can open shopping websites

It can open all the URL links

It can open/close all the pc applications(NOTE: give correct path based on your OS)

It can sleep until you say wake up

Finally It can interact with you and you can also add more commands if you want😎

NOTE: Before running the code you must make sure you have all the modules installed in your python version(NOTE: python version can be >=3.6).

These are the following modules used in JARVIS📚 :
SpeechRecognisation | PyAudio | pyttsx3 | pywhatkit | datetime | wikipedia | pyjokes | cv2 | cv2 tools | requests | smtplib | psutil | random | instaloader | PyAutoGUI | PyPDF2 | bs4 | PyQt5 | pywikihow | speed test | pytube | numpy | urllib | covid | phonenumbers | folium | opencage | pillow | Pywave | win32api | mscvrt

API keys 🔑
To run this project you should need some API key's for reading news, for finding phone number location. Register for your API key by clicking the following

NewsAPI : used for fetching news
Open cage : to locate a place in maps
Note : supported OS : Windows, working on the making the JARVIS for Linux, but it many take some time.

Installation 💻
You need to first fork this repository and clone the repository to your local system

git clone https://github.com/<your-github-username>/J.A.R.V.I.S.git

Make sure to install all the required python modules mentioned above or you can simply install them by

pip install -r requirements.txt

Note: For any errors while installing the python modules refer ERRORS.md because I got some errors while installing and using them.

Add the correct system paths in JARVIS.py to open the system applications

Add your gmail id and password to send emails(line:797,798)

Make sure you have registerd in NewsAPI and replace the apiKey="yourapikey" with your API key and in Open cage and replace the API_key = "api" with your API key(PhoneNumber.py(lineNo: 13))

For using mobile camera you need to first install an app in mobile called IP Webcam after installing go to START SERVER it will open your mobile camara at the bottom of the screen you can see IPv4 there you can find the IP address and replace _IP_Webcam_IP_address_ with the IP address in JARVIS.py MobileCamera function.

Add the correct system paths to gifs or for background images in GUI.py and jarvis.py. If you got any elements missing(RED SCREEN) refer ERRORS.md file.

Finally run the python JARVIS.py file
