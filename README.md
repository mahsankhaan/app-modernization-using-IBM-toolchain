# app-modernization-using-toolchain
Mordernize application using IBM toolchain

## Follow below steps:

### Step 1 : Sign-up for IBM Cloud Platform

[http://ibm.biz/becomecloudnative](http://ibm.biz/becomecloudnative)

![GitHub Logo](images/1.png)


### Step 2 : Login into your IBM account and search for "CloudFoundry"

![GitHub Logo](images/2.png)


### Step 3 : Then select "Public Application" and click Create

![GitHub Logo](images/3.png)


### Step 4 : Let's setup your cloud foundry 

1. Select region "Dallas" and account type "lite".

![GitHub Logo](images/4.png)

2. Select runtime "PHP" 
3. App name: "Cloudnative-xyz" (Please use different names)
4. Once everything is done click "Create"

![GitHub Logo](images/5.png)


### Step 5 : Check if your application is up

Click "Visit App URL" and a new tab will open then you can see your app running.

![GitHub Logo](images/6.png)


### Step 6 : It's time to enable toolchain in our application

1. Select "Overview"
2. In Continuous delivery section "Select Enable" button.

![GitHub Logo](images/7.png)

3. Now you will see Continuous Delivery Toolchain page.

![GitHub Logo](images/8.png)

4. In Git repos section insert Source repository URL:

[https://github.com/mahsankhaan/app-modernization-using-toolchain.git](https://github.com/mahsankhaan/app-modernization-using-toolchain.git)

![GitHub Logo](images/9.png)

5. In Delivery Pipeline section , click "new" to generate API

6. Once everything is done press "Create" button

![GitHub Logo](images/10.png)


7. Now your toolchain is created and select "Delivery Pipeline"

![GitHub Logo](images/11.png)

8. In "Delivery Pipeline" start your build stage
9. Wait until the your "Build stage" becomes green
10. After that your "Delpoy stage" will run automatically 


![GitHub Logo](images/12.png)

11. Once both the stages run successfully you will able to see it in green.

![GitHub Logo](images/13.png)



### Step 7 : Finally your application is up and running

1. Get back to your main page by selectung your app name on top

![GitHub Logo](images/14.png)


2. Click visit URL and see your app running

![GitHub Logo](images/15.png)
