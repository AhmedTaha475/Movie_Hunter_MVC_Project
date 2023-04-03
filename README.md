# Movie_Hunter

# **Project Parts**
This project has been divided into five parts, each with its own set of tasks and responsibilities.

1. Project Structure
The project structure was created by Ahmed and Heba. It includes the following:

Setting up program.cs services and middlewares to work with the project
Configuring appsettings.json file for connection string, Facebook, Google, and Stripe
Partitioning the project into Areas:
AdminDashboard
Identity
Payment
User: interaction of user with movies and series
Movies and Series area
2. Database
The database was created as a group effort. It includes the following:

Creating a database schema, models, and context
Implementing the Repository Pattern in C# interfaces and classes
3. Identity System
The identity system was created by Ahmed, Heba, and Mohamed Abdelfattah. It includes the following:

Scaffolded identity system created
Register system with normal user
External logins with Google and Facebook
Creating Roles ("Admin," "Normal Users")
Admin account applied without register:
ID: admin@moviehunter.com
Password: Admin@movie123
Normally any normal or external user is assigned to the Normaluser role
Ability to edit user profile and delete the account
4. Admin Dashboard
The admin dashboard was created by Asmaa. It is only accessed by users with the Admin role and includes the following:

Creating a dashboard to CRUD movies, series, and episodes
Assigning users to a role
Removing users from a role
CRUD on Role
Using the AdminDashboard Template
Using custom data annotations
Using Routing and Routing Constraints
5. Movie Website Features
The movie website features were created by Hesham, Maha, and Mohamed Abdel fattah. They include the following:

Only authenticated users can watch movies and use the full system features
Users can choose among three plans (Basic, Premium, Pro) and use Stripe API to mimic payment
Showing all movies and all series and every episode available for that series
Users can add a specific amount of movies based on their plan:
Basic: 2 movies
Premium: 6 movies
Pro: Unlimited movies
No plan: No favorite movies
If a user tries to add more than the given amount for their plan, they will be redirected to a custom handler Exception page
Showing favorite movies and series for each user and also recommending movies based on their favorite category
Users can add movies and series to their watchlist
Watching movies and series episodes and the ability to download them if authenticated
News page
Handling 404 errors and unauthorized errors with custom pages
6. Website Deployment
The website was deployed on IIS.
