# Module 03 - Exercise 01
> Submitted September 04, 2024

---

# Table of Contents
- [Changes Made](#changes-made)
- [Application Screenshots](#application-screenshots)

---

## Changes Made
> Screenshots are after this list.
- The URL for the *App.xaml.cs* is https://ReqBin.com. However, the website returns an error due to not having cookies enabled resulting in the Offline page appearing even though it shouldn't. Therefore, the https://ReqBin.com was used to showcase the Offline Page instead, wherein when the user retries in the Offline Page, the https://Google.com will be used to showcase the Login Page.
![alt](https://i.imgur.com/ndizmYI.jpeg)

- Changed the routing on the *OnStart()* function found in App.xaml.cs
> Reason: The old code prevented the proper way of navigation using Shell.
![alt](https://i.imgur.com/FfoA8lH.jpeg)

- Added an EmployeeLogin Class (Model) for Login Credentials.
![alt](https://i.imgur.com/FHfxh0W.jpeg)

- Added an EmployeeLoginViewModel to handle the login process and store credentials.
![alt](https://i.imgur.com/q4kpP9L.jpeg)

---

## Application Screenshots

### Offline Page
![](https://i.imgur.com/PuGawtP.jpeg)

### Exit Code
![](https://i.imgur.com/CMzIVsm.jpeg)

### Retry Attempt Successful
![](https://i.imgur.com/csUC8Tz.jpeg)

### Login Page
![](https://i.imgur.com/anCWeGw.jpeg)

### Login Page (Wrong Username)
![](https://i.imgur.com/YjvDv0t.jpeg)

### Login Page (Wrong Password)
![](https://i.imgur.com/42oAQRG.jpeg)

### Employee Page (Shown after Successful Login)
![](https://i.imgur.com/mbfwPQl.jpeg)

### Employee Page (Manager Shown)
![](https://i.imgur.com/MFO5yCB.jpeg)
