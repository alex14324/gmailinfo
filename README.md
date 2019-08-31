# gmailinfo
Installation

Clone repository
git clone https://gitlab.com/kennbroorg/iKy.git

Install Backend

Redis
You must install Redis
wget http://download.redis.io/redis-stable.tar.gz
tar xvzf redis-stable.tar.gz
cd redis-stable
make
sudo make install
And turn on the server in a terminal
redis-server

Python stuff and Celery
You must install the libraries inside requirements.txt
pip install -r requirements.txt
And turn on Celery in another terminal, within the directory backend
./celery.sh
Finally, again, in another terminal turn on backend app from directory backend
python app.py

Install Frontend

Node
First of all, install nodejs.

Dependencias
Inside the directory frontend install the dependencies
npm install

Turn on Frontend Server
Finally, to run frontend server, execute:
npm start

Browser
Open the browser in this url

Config API Keys
Once the application is loaded in the browser, you should go to the Api Keys option and load the values of the APIs that are needed.

Fullcontact: Generate the APIs from here

Twitter: Generate the APIs from here

Linkedin: Only the user and password of your account must be loaded


Disclaimer
Anyone who contributes or contributed to the project, including me, is not responsible for the use of the tool (Neither the legal use nor the illegal use, nor the "other" use).
Keep in mind that this software was initially written for a joke, then for educational purposes (to educate ourselves), and now the goal is to collaborate with the community making quality free software, and while the quality is not excellent (sometimes not even good) we strive to pursue excellence.
Consider that all the information collected is free and available online, the tool only tries to discover, collect and display it.
Many times the tool cannot even achieve its goal of discovery and collection. Please load the necessary APIs before remembering my mother.
If even with the APIs it doesn't show "nice" things that you expect to see, try other e-mails before you remember my mother.
If you still do not see the "nice" things you expect to see, you can create an issue, contact us by e-mail or by any of the RRSS, but keep in mind that my mother is neither the creator nor Contribute to the project.
We do not refund your money if you are not satisfied.
I hope you enjoy using the tool as much as we enjoy doing it. The effort was and is enormous (Time, knowledge, coding, tests, reviews, etc.) but we would do it again.
Do not use the tool if you cannot read the instructions and / or this disclaimer clearly.
By the way, for those who insist on remembering my mother, she died many years ago but I love her as if she were right here.
