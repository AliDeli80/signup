# Signup Page with React and JSON Server  

Welcome to the Signup Page project! This application allows users to sign up using their email addresses. It checks if the entered email already exists in the database, and if it does, it displays an error message.

## Features  

- **Email Validation**: Checks if the email is already in use.  
- **User-Friendly Interface**: Simple and interactive signup form.  
- **Fast Response Time**: Uses JSON Server for quick responses.

- ## Technologies Used  

- **React**: For building the user interface.  
- **JSON Server**: For simulating a RESTful API for user data.

- ## Getting Started  

### Prerequisites  

Make sure you have the following installed:  

- [Node.js](https://nodejs.org/) (including npm)  

### Installation  

1. Clone the repository:  

```bash  
git clone https://github.com/AliDeli80/signup.git
```
2. Navigate to the project directory:

```bash  
cd signup
```
3. Install the required dependencies:

```bash  
npm install  
```
4. Start JSON Server:

In a separate terminal, run:

```bash  
npx json-server --watch db.json
```
This will create a mock REST API based on the `db.json` file included in the project.

5. Run the React application:

```bash  
npm start
```   
Your application should now be running on http://localhost:3000.

How to Use
1. Enter your email address in the signup form.
2. If the email exists, an error message will be displayed.
3. If the email is new, the signup will proceed successfully.

for example if you use `test@test.com` email thet exist in the json server database it will give you an error.

## Contributing

Contributions are welcome! If you have suggestions for improvements or find bugs, please open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
