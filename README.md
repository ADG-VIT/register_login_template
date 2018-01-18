# register_login_template
To get started go to this url:
https://console.firebase.google.com<br />
<br />
Then click on add project<br />
![](images/12.jpg)<br />
<br />
Then enter the details like name of your project and choose country region<br />
![](images/5_5.jpg)<br />
<br />
After that go through the instructions for installing pods<br />
![](images/6.jpg)<br />
<br />
Download the google-info.plist and add it to your xcode project<br />
![](images/7.jpg)<br />
<br />
Next add your bundle id which is located in your xcode project remaining two fields are optional<br />
![](images/8.jpg)<br />
<br />
Your Podfile should look like this :<br />
![](images/9.jpg)<br />
<br />
After installing the pods open the "your_project_name.xcworkspace" file,this is what you're going to be working on<br />
<br />
Go to the AppDelegate file and add the following code<br />
![](images/11.jpg)<br />
<br />
After creating the app and registering few users, the authentication page in your console will look like this<br/>
![](images/2.jpg)<br />
<br />
While typing the password in the textfield,to hide it do this:<br />
![](images/4.jpg)<br />
<br />
Your password textfield will look like this<br />
![](images/5.jpg)<br />
<br />
Do it for both the registration view controller and the login view controller <br />
