# zenAPI

# What is API?
Are you learning programming and wondering what an API is? An API is an Application Programming Interface that allows different software or systems to communicate with one another. This is 2 files of simple API made with python and Flask. It will take you 5 minutes to type the code or to think a new one.

## How to test it?

Download the **Postman app**, then start debugging the API from Visual Studio Code. If you don't know how Click on "Terminal" that is on the top of you screen then click "New terminal". Type "py main.py" or "py main2.py" it depens on what is the name of the file (hope you understand it). Now open the **Postman** app click on the plus that you are seeing in the left top of your screen and it will make a new API request. Now go to Visual Studio Code and copy the link in the terminal that is after "Running on ..." it should be under the red text. Now paste it in the line after "GET" in the app. After your link add: /create-user . Now click on the GET button and chose POST. Under this line is a category Body (that we need). Click on Body, raw then on the blue text that is "Text" and chose "JSON". On the white paragraph under this type this:
```json

{
    "username": "YourName"
}

```

Now if you see the same on the other white paragraph that means this is working succesfully.
So thats a good tool that you can use to test out your APIs as you continue to do more development.

## Authors

- [@mitrashkov](https://github.com/mitrashkov)

## Support

For support, email hypexdevelopers@gmail.com or join our Discord channel.



## Feedback

If you have any feedback, please reach out to us at hypexdevelopers@gmail.com

![ZenAPI](https://github.com/mitrashkov/zenAPI/assets/140254231/63065a29-5d45-4f72-849c-8c24610d57c8)
