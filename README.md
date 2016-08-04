# Microsoft Azure

### Hosting a Static Website

One of the most useful things about deployment services is that they allow you
to focus on just your code while the service takes care of the servers and other
aspects of a project that might be of concern.

For this part of the workshop we are going to take a program that you have already
written and use another deployment service to host the website.

** Step One: **

To start you will need to make an Azure account. Luckily for us our Dartmouth
accounts give us access to Azure.

Go to [this link](https://login.microsoftonline.com/common/oauth2/authorize?resource=https%3a%2f%2fmanagement.core.windows.net%2f&response_mode=form_post&response_type=code+id_token&scope=user_impersonation+openid&state=OpenIdConnect.AuthenticationProperties%3dZgWkl5BALa-ym9GOVOmNzmvJU-hJ0YEKSXqcLoYQIwkut27AFt7nYesVttjWgP_Uax41Gd6ga3FjCPF0mIKoBS4vH5p9vZOO8zL8tBEjkE2e_OqgdTbQOFX4K8tI8S0Z-h-ZU2YaFOtO-VdAYhW2izvpvLs6VO9aIQcj8Ef5TNv753vF&nonce=636058836739134229.OTAxZjE2ODEtNGM0OS00Y2FiLWE3YTctMjE1NGRiM2ZhMmYxZmZlNDRjOGEtY2Q2My00ZGVjLTg4YmItMGYwMzQ2OWM2Yjhl&client_id=c44b4083-3bb0-49c1-b47d-974e53cbdf3c&redirect_uri=https%3a%2f%2fportal.azure.com%2fsignin%2findex%2f%3fsignIn%3d1%26cdnIndex%3d4&site_id=501430)
- Use the dartmouth email FXX####@kiewit.dartmouth.edu
- But use your NetID.
- It should take you to the dartmouth sign in page, sign in.

You should now be on the Azure dashboard.
![webpage](./Dash.png)

Now click on App Services->Add
![webpageselect](./Rect.png)

**Now you have to sign up for Azure services. If you select the free trial it will ask you for credit card information but you will not be charged at all**

Once you sign-up, return to the dashboard.

Click new again. Select a name for you app, and a name for a new resource group.
![new](newapp.png)

It will take a minute for your new app to show up in the App Services section, when it does, click on it.

Click settings and scroll down to publishing->Deployment Source.
![publish](publishing.png)

Select Github as the configuration source. If it asks for your permission to connect to your Github account. Select yes.

As the project, select the landing page that you created in Lab 1 and whatever your most updated branch is, for most of you it should be gh-pages.

Then click Ok.

It should take another minute to deploy, then you can click browse and it should take you to your landing page.

# YAY SUCCESS!!!

![](http://i.giphy.com/lnlAifQdenMxW.gif)
