
# Application requirements
The application should allow job posters (Clients) to be able to post their requirements easily. And, the Job seekers (Freelancers) will be able to then look for jobs and apply for them. As MVP we should aim at creating a minimum set of features to go live. This will allow the
community to see something in real life and then we can continue to keep adding features and improving the existing features as well. The idea is to grow slowly but steadily. No great product was built in one day, neither did launch with all features in one shot. **They all evolved.**.

### Modules
 1. Job posting 
 2.  Job search 
 3. User profile 
 4. Search

## Entities 

### User 
This is the core entity of the application. There will be three primary roles in the application (Client, Freelancer, Admin). Both Client and Freelancer are users. They can have both a Client and Freelancer role as well. Basically, I can be a client for someone and Freelancer for someone as well. The application should allow me to do so. 

### User’s profile 
User’s profile is what will be visible as bio for every user. This should be something like a LinkedIn profile for a user. Based on this a Client will be able to decide whether to work with a particular Freelancer or not. 

### Jobs
 This is how a work will be posted on to the application. A user with a Client role should be able to create a new Job (I am not calling it a project right now because we may later look at allowing someone to divide the work inside a well as well. Like outsource the front end to someone and back end to someone).
 
###  Applications
 Every job will have multiple applications. Freelancers can apply for a job and the respective job poster will be able to see the applications along with the applicants and their profile. (We may later on, allow some additional fields in a Freelancer’s profile to be only visible to a client when the Freelancer has applied for a job for that client.
