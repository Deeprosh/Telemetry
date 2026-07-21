# Architecture of the project  
- From internet, anyone can access this project.  
- Using LoadGenerator, it will balance the load of the requests from the user,QA will test the project using LoadGenerator.
- To access the application from mobile it uses reactnative app and through HTTPD mobile users can access this from mobile.
- Along with these we do have front end proxy which acts as a reverse proxy that is popularly used in real-time application.
Reverse proxy is to verify and handle the custom login before forwarding actual traffic to your application(front or web).
- Front end is the user interface that we see on the home page.From here, we can connect to differenet services like product catalogue, cart service, checkout service.
- From checkout service(As you add the product to the cart), we have shipping service, it will ask us to fill the addresss.
- Quota service is to let know the avaible stock or quota.  
- Email service is get a notification for the order which we made.
- Currency service is used to select the currency based on your location.  
- Payment service is used to buy the product once everything has been ok.
- Recommendation service is used to get recommendations about the products based on what we search till then.
- Fraud detection service is used to provide MFA or more secutity.
- Flag d or feature d is used to enable or disbale some settings according to the customer location.
- Ad service is used to run the ads on this project based on the customer context.  
- Each service is written/developed in different lanaguages.  
