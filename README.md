# Robot Project

## Backend
* Link to the project: [Backend Repository](https://github.com/mhdzaid/Pilot)
* The backend is developed using `Java Spring Boot` with `Java version 17`.

### Architecture Decisions
* **Script Handling**: Implemented using the `Factory Pattern`.
  * **Reason**: This approach was chosen to enhance readability and maintainability of the code.
  * **Advantages**: It increases the flexibility of the code, making it easier to add new script commands and modify existing ones without affecting the entire service layer.

## Frontend
* Link to the project: [Frontend Repository](https://github.com/mhdzaid/PilotUI)
* The frontend is developed using `Angular 15`.

### Architecture Decisions
* **Structure**: The frontend is kept simple with a single component.
  * **API Interaction**: The frontend makes a single `POST` call as specified in the documentation. No `GET` calls are implemented.
  * **Data Handling**: The robot's position is received as a response to the `POST` call.

### Time Taken
* The project was completed in approximately 5 hours.
* A significant portion of the time was devoted to the frontend development due to my relatively lower experience in this area compared to backend development.

### Improvements
* **User Interface**: Given more time, I would enhance the UI by replacing the current circle with an arrow for the robot's position with a more detailed robot icon, including a silhouette indicating the direction.
* **Backend Enhancements**: Specifically for the `Direction Action`, I would consider refactoring the code to make it more abstract. Instead of relying on a `switch` statement with multiple cases, a more abstract approach could be employed to handle direction changes dynamically. However, given the current simplicity of the implementation, the existing approach was deemed sufficient for now.
* **State Managment**: I did consider implementing state managment using `NgRx` but seeing how small the front-end requirements are, I found it a bit overkill, atleast with the current requirements. 

## AI Tools Usage

### Backend
* **Regex**: Utilized AI tools to assist in crafting and validating regular expressions.
* **Error Debugging**: Summarized error logs for quicker debugging and issue resolution.

### Frontend
* **HTML and CSS**: Leveraged AI tools for assistance with HTML and CSS, especially for layout and design adjustments using `flexbox`, `grid`, `padding`, etc.
* **Debugging**: Used AI tools to troubleshoot and resolve errors encountered during development.
* **Design Improvements**: Sought AI suggestions for design enhancements and finding compatible libraries such as `toastr` for notifications.
* **Syntax Assistance**: Consulted AI tools for syntax clarification and best practices due to less experience in frontend development.

I mentioned in my introductory interview that I am more of a backend-heavy developer with less experience in frontend development. Therefore, I have used AI tools to assist with frontend tasks to ensure high-quality and efficient development.

