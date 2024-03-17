# Doctor Console
This repository contains the console for the medical staff of the hospital like the doctor, lab technicians and surgeons. This console is primarily for interacting with the patients of the [Patient Console](https://github.com/tech-threee/patient-swiftcare), viewing and managing full patient records/medical history, issuing prescriptions, issuing tests and procedures, creating/recording test/procedure results, viewing assigned appointments and so on



NB: For the first release of this software, the features currently available are
- Viewing employees
- Viewing patient details
- Account authentication and management


## How To Access
The software is hosted using Netlify using [this url](https://doctor-swiftcare.netlify.app)

## How To Use 
1. In order to get access to the application, one would have to login by providing a `Staff ID` and a `pin`
![](/screenshots/login.png)

2. After logging in, the user will see the Dashoard page which is a summary of the statistics of the system.
![](/screenshots/dashboard.png)

3. From there, they can visit the messages page to view in-app messages sent from other users of the application by using the navigation bar on the left hand side

4. The can visit the patients page to view details about the patients of the hospital and view medical records


The long-term goal of the software is to include features to allow the users manafe hospital website content, perform system checks across other consoles, provide technical support to other users and other relevant system support functionalities.


## Stack
This software was built using 
1. [Next.js](https://nextjs.org/)
2. [TailwindCSS](https://tailwindcss.org/)
3. [Shadcn UI](https://ui.shadcn.com/)

## Design System
Because this system is part of a software suite (SwiftCare Connec+), it shares the same design and components as the other consoles of the software suite however, the only different is that the primary color is blue - `#2196F3`
