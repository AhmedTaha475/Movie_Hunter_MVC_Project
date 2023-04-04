**Movie Hunter Documentation**
 		

**Project Parts:**

1. **Project Structure**  
1. **Data base** 
1. **Identity System** 
1. **Admin dashboard**
1. **Movie Website**

**Part Details :** 

1. **Project Structure**: 
   1. **Set up for program.cs services and middle wares to work with the project**
   1. **Add the configuration for appsettings.json file for connection string ,facebook , google , stripe** 
   1. **Project is  partitioned into Areas :**
      1. **AdminDashBoard**
      1. **Identity**
      1. **Payment**
      1. **User: interaction of user with movies and series**
      1. **Movies and Series area**

1. **Database**: 
      **Created Database schema , Models and Context** 
   1. **Created Reposatory Pattern in C# Interfaces and classes** 



1. **Identity System** :
   1. **Scaffolded identity system created**
   1. **Register System with normal user** 
   1. **External logins with google and facebook** 
   1. **Created Roles (“Admin,Normal users”)**
   1. **Admin Account Applied Without Register :
      ID:admin@moviehunter.com	
      Password:Admin@movie123**  
   1. **Normaly any normal or external user is assigned to Normaluser role** 
   1. **Ability to Edit user profile and delete the account**

1. **Admin Dashboard:
   Only  accessed to Admin Role** 
   1. **Created dashboard to CRUD movies , series and episodes** 
   1. **Assign user to Role**
   1. **Remove user from Role**
   1. **CRUD on  Role**
   1. **AdminDashboard Template Was Used**
   1. **Custom Data annotation were used**
   1. **Using Routing and Routing Constraints**
**

1. **Movie Website Features:
   ` `(Only Authenticated user can watch movies and user full system Features)**
   1. **User Can choose among 3 plans (Basic,Premium,Pro) and Use Stripe API to mimic Payment** 
   1. **Show all movies and all series and every episode available of that series** 
   1. **User can add  specific amount of movies based on his Plan** 
      Basic : 2 movies
      Premium : 6 movies
      Pro : Unlimited Movies
      No Plan : No Favorite movies

      **If user tries to add more than the given amount for his plan he will be redirected to custom handler Exception page**
   1. **Show Favorite Movies and series for Each user and also recommened Movies based on his Favorite Category**
   1. **User can add movies and series to his watch list**
   1. **Watch Movies and Series Episodes and the ability to Download them if Authenticated**
   1. **News Page** 
   1. **Handling 404 Errors and unauthorized Errors with custom pages**
**
1. **Web site Deployed on IIS**


