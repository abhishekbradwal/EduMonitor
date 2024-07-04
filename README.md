
## Configuration & Installation


To get started with edumonitor, ensure you have the following dependencies and tools installed:

### Frontend

2. Next.js: edumonitor is built using Next.js, a React framework for server-rendered applications along with webrtc . Install it globally using npm :

   ```
   npm install -g next
   ```

Once you have installed the necessary dependencies, follow these steps to set up the development environment:

1. Clone the edumonitor repository from GitHub:
   ```
   git clone https://github.com/AkhileshJyotishi/edumonitor.git
   ```
2. Navigate to the project directory:
   ```
   cd edumonitor
   ```
3. Install project dependencies:
   ```
   npm install
   ```
4. Create a .env file in the root directory and add all environment variables.
   ```
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=

   CLERK_SECRET_KEY=
   
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in

   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

   NEXT_PUBLIC_BASE_URL=http://localhost:3000

   NEXT_PUBLIC_STREAM_API_KEY=

   STREAM_SECRET_KEY=
   ```
5. Start the development server:
   ```
   npm run dev
   ```
6. Open your browser and navigate to http://localhost:3000 to access edumonitor.

### Backend

1. Download Python version 3.8 and it to your Environmental variables.

2. Set up virtual environment using following command :
    ```
    pip install virualenv
    
    cd backend

    cd QuestionGeneration
    
    python3.8 -m venv <virtual-environment-name>

    ```
3.  ```
       pip install flask

       pip install Flask-Cors

       pip install mediapipe
    ```
4. Run Following Commands 
   ```
    python -m nltk.downloader universal_tagset
      
    python -m spacy download en

    pip install -U pip setuptools wheel

    pip install -U spacy

    python -m spacy download en_core_web_sm
   ```





