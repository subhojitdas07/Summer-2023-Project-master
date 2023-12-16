# Summer 2023 Project

## Tech Stack Used

- ReactJS
- MongoDB
- Django

## Application Workflow

- Open-source application for managing medium-scale enterprises.
- The user can alter the functionalities on an as-per-need basis (template).
- Given entries, the app processes the data to create numerical projections and presents graphs/charts.
- Using large data-intensive APIs to perform complex statistics and data analysis and inference.

### Dashboard

<img src="./Dashboard.png">

- Structured to be relatively easy to set up (for non-technical folks).

- Scalable for a variety of operations (small-scale to medium-scale institutions).

- Customizable for specific needs of the user.

- Incorporates the following 4 subsystems:

  - Account Management (Component AM)

    > The AM component will be for employee management with respect to the designation, promotions, and access rights. Sample (which can be customized later):

    - Administrators/Owners have all the permissions to handle the application and access all four subsystems.
    - Organizers/Managers have permission to handle SR, PA, and PF, with minimal handling of the application.
    - Mentors/Senior Staff have permission to handle SR and PA, with no control over application modifications.
    - Workers/Junior Staff have access to SR only.

  - Sales/Transactions Register (Component SR)
    > The SR component will be for managing routine transactions with customers, along with inventory management of products/services.
  - Predictive Analytics/Trends (Component PA)
    > The PA component will be for predicting and displaying inferences from past activities to create monetary projections along with employee performance statistics.
  - Payroll System & Financial Ledger (Component PF)
    > The PF components will be for handling the salaries and incentives for employees, along with non-routine transactions like acquisitions, mergers, and other corporate options.

