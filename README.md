To run the app locally

    1. Clone the repository:

git clone

   2. Navigate to the project directory:

cd FriendSpace

   3. Navigate to the backend directory:

cd backend

   4. Create a virtual environment:

    On macOS and Linux:

python3 -m venv venv

    On Windows:

python -m venv venv

   5. Activate the virtual environment:

    On macOS and Linux:

source venv/bin/activate

    On Windows:

venv\Scripts\activate

   6. Install the dependencies:

    On macOS and Linux:

pip3 install -r requirements.txt

    On Windows:

pip install -r requirements.txt

   7. Navigate to the frontend directory:

cd ../frontend

    Install the dependencies:

npm install

   8. Build the frontend:

npm run build

   9. Navigate to the backend directory:

cd ../backend

   10. Run the Flask app:

flask run

Open your browser and go to http://localhost:5000/ to view the app.
