# grabage-collection-website

## Project Objective

- Enable GTF (Green Task Force) members to sign up and log in to the system.
- Registered GTF members can upload taken pictures of thrown away garbage, give some feedback and set the location of the incident.
- CMC (Colombo Municipal Council) dedicated green captain should be able to view all the reported incidents, and approve or reject them with priortizing incidents based on the information.
- Garbage collection staff should be able to view the approved incidents with a summary on a map along with importance level.
- General users who isnt registered to the system should be able to see the garbage collection spots on a map, and the news articles posted by the CMC.

## Functional Requirements

- 4 user roles
  - GTF Members
  - Green Captain
  - Collecting staff
  - Web Master (Admin)
- All the user roles should be able to login to the system.
- All the logged in users should be able to log out from the system.
- Non registered users should be able to view Garbage collection spots on the map and the news articles.

### Web Master Functional Requirements

- Should be able to create account for the captains and collecting staff.
- Should be able to post articles and add garbage collection spots to the system.

### Green Captain Functional Requirements

- Should be able to see the reported incidents as a list on the map.
- Should be able to select an individual incident to view all the incident details including images and other details.
- Should be able to approve or reject selected incident.
- Should be able to set flag based on the importance of the selected incident.

### GTF Members Functional Requirements

- Should be able to signup for the system.
- Should be able to report incident by inputing data including incident location, details and images.
- Should be able to delete/update his own reported incidents.

### Collecting Staff Functional Requirements

- Should be able to view the accepted incidents on the map with importance of the selected incident and details.

## Non-Functional Requirements

- Password should be encrypted.
- System should be autheticate every user before posting or modifying the incident
- System should be reliable and available for 24/7 with minimal downtime or errors.
- System should be able handle a large number of users and scalable without having to worry about the performance.
- System should be user friendly and compatible with different browsers and devices.
- System should allow users to reset their password
