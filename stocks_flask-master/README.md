# inventory_management

**Stock Web app Documentation Manual**

**1. Introduction**
   - This web application is built using Flaskframework, HTML templates and mySQL
   - It allows users to sign up, log in, create products, delete products, and update product details in a virtual store.

**2. Prerequisites**
   - Python, Flask, and MySQL should be installed installed.
   
**3. Installation**
   - Clone the application's code repository.
   - Install the required Python packages:
     ```
     pip install Flask flask-mysql
     ```

     ```

**4. Running the Application**
   - Run the application with the following command:
     ```
     python app.py
     ```
   - Access the web application in your browser at `http://localhost:5000`.

**5. Functionality**
   - **User Authentication**
     - **Sign Up**:
       - Users can create an account by providing a username and password.
     - **Log In**:
       - Existing users can log in with their credentials.

   - **Product Management**
     - **Create Product**:
       - Logged-in users can create new products by providing product details.
     - **Delete Product**:
       - Users can delete products by clicking on the "Delete" button.
     - **Update Product Details**:
       - Users can update product details by clicking on the "Edit" button and making changes.
       - Lastly, users can also track the location of their products

