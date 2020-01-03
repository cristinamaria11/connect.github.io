We decided to implement some basic features of the application such as the login/signup and the pages of the users. If a profile is created at the moment, the algorithm that is supposed to recommend the profiles is not in place yet, but a possible buyer can see how the app is supposed to be working.

# Login

The login page is basic, it requires you to complete the username and passwords, just like any other similar page. It also displays some error messages, depending on the case. The motivation behind implementing this functionality is obvious, you can't say an app is any good without having any kind of security, no matter how basic this is at first.
<div id='soloImg'>
    <img src="/connect.github.io/images/MVP/login.png" alt="Loginexample" height="400" width="230">
    <img src="/connect.github.io/images/MVP/login-error.png" alt="LoginexampleError" height="400" width="230">
<div>

# Creating a profile

After logging in to the application, a user has to choose whether he/she is looking for a job or for a possible employee. This is shown in the following screenshot. The app being meant for 2 different types of users, without this implementation, the app wouldn't make too much sense.

<div id="soloImg">
  <img src="/connect.github.io/images/MVP/choose-profile-type.png" alt="chooseusertype" height="400" width="230">
</div>


The actual modal where you can create a new job offer or a candidate profile is based on having to complete some mandatory fields, depending on the relevance for each category. Screenshots for these cases are shown below:
<img src="/connect.github.io/images/Register.png" alt="register" >
<img src="/connect.github.io/images/Register company.png" alt="registercompany" >

As a recruiter you can also add different job offers and the modal that will be shown to you when doing this action is the one below:
<div id="soloImg">
  <img src="/connect.github.io/images/Create job type.png" alt="createjobtype" >
</div>


<div style="display:inline; float:left">
<input type="button" class="button" value="<< Milestone 6" onclick="window.location.href='milestone6.html'" />
</div>
