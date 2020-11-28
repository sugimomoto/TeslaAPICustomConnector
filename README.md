# What is this?

This is Tesla API Custom Connector for Microsoft PowerApps/PowerAutomate/LogicApps.

This connector can get a lot of your Tesla data and request each commands.

# How to use

Usage is simple. This connector is pulished at Github so you can import at "Import OpenAPI from URL" on the custom connector page.

![image](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sugimomoto/20201128/20201128094021.png)

Enter any name and paste the URL below, Then click "import" button.

```url
https://raw.githubusercontent.com/sugimomoto/TeslaAPICustomConnector/main/TeslaAPICustomConnector.json
```

![image](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sugimomoto/20201128/20201128094029.png)

After that, you can set the icon you like.

![image](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sugimomoto/20201128/20201128094036.png)

Security and Definition information are no need change. You can register by clicking "Create Connector".

![image](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sugimomoto/20201128/20201128094051.png)

# Test method

The authentication method is to specify the Access Token in the Authorization header.

Therefore, You should get Access Token manually by referring to the following articke.

[Tesla API Postman Collection](https://github.com/sugimomoto/TeslaAPIPostmanCollection)

After getting, open "New Connection"

![image](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sugimomoto/20201128/20201128094105.png)

Specify the acquired Access Token in the API key item including "Bearer".

If your Access Token is "qts-12345", Enter "Bearer qts-12345".

![image](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sugimomoto/20201128/20201128094113.png)

After that, You can execute any actions. 

![image](https://cdn-ak.f.st-hatena.com/images/fotolife/s/sugimomoto/20201128/20201128094121.png)
