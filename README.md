# django-chat-app
Basic Asynchronous Chat App based on Django Channels

## Installation and Setup

1. Install Dependencies

```
pip install -r requirements.txt
```

2. Run Migrations on local

```
python manage.py migrate
```
3. Run Server
```
python manage.py runserver
```
## Usage
* Open your web browser at localhost:8000/chat/
* Enter random lobby name.   
* Open another tab with same lobby name.   
* Start sending messages from 1 tab it should reflect in another tab as well.    
