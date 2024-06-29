# MyChat

## Description 
A Group video calling application using the Agora Web SDK with a Django backend.

##  How to use this source code

#### 1 - Clone repo
```
git clone https://github.com/dtechshoemaker/chat-app
```

#### 2 - Install requirements
```
cd mychat
pip install -r requirements.txt
```

#### 3 - Update Agora credentals


###### views.py
```
def getToken(request):
    appId = "YOUR APP ID"
    appCertificate = "YOUR APPS CERTIFICATE"
    ......
```

###### streams.js
```
....
const APP_ID = 'YOUR APP ID'
....
```


#### 4 - Start server
```
python manage.py runserver
```


