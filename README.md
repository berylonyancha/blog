# Blog

## Description

A personal blogging website where you can create and share your opinions and other users can read and comment on them.

## Created by Beryl Onyancha 

## BDD

| Behaviour      | Input                     | Output                                                    |
| -------------- | ------------------------- | --------------------------------------------------------- |
| Registration   | email ,username ,password | Submit User creates an account and receives welcome email |
| New_blog       | blog title and content    | blog displays in index                                                      |
| Edit blog      | submit edit blog          | blog updated                                              |
| Delete blog    | click delete              | Blog deleted                                              |
| Delete Comment | click delete              | comment dleted                                            |

## Setup and installations

#### Prerequisites

1. [Python3.6](https://www.python.org/downloads/)

2. [virtualenv](https://virtualenv.pypa.io/en/stable/installation/)
3. [Pip](https://pip.pypa.io/en/stable/installing/)

#### Technologies used

   - Python 3.6
   - HTML
   - Bootstrap 4
   - Heroku
   - Postgresql
   - Flask

#### Clone the Repo and rename it to suit your needs.

```bash
git clone https://github.com/berylonyancha/blog```

#### Initialize git and add the remote repository

```bash
git init```

```bash
git remote add origin <your-repository-url>```

#### Create and activate the virtual environment

```bash
python3.6 -m virtualenv virtual```

```bash
source virtual/bin/activate```

#### Setting up environment variables

Create a `.env` file and paste paste the following filling where appropriate:

```SECRET_KEY='<Secret_key>'
export MAIL_USERNAME=<Your Email Address>
export MAIL_PASSWORD=<Your Email Password>
DEBUG=True```

#### Install dependancies

Install dependancies that will create an environment for the app to run
`pip install -r requirements.txt`

#### Run chmod a+x start.py

```bash
chmod a+x start.py```

#### Run the app

```bash
./start.sh```

#### Access the application through localhost:5000

Open [localhost:5000](http://127.0.0.1:5000/)

## Support and contact details
Feel free to buy me a cup of coffee. Contact me at [Beryl Onyancha](berylonyancha@gmail.com)

### License

[MIT](https://github.com/berylonyancha/blog/blob/master/LICENSE)

Copyright (c)2019 **Beryl Onyancha**