# Guide to Using Laravel 10 with Breeze and Vue

# Prerequisites

Before you begin, ensure you have the following installed:

- PHP
- Composer
- Node.js and npm

# Steps to Use the Project

1. **Clone the Repository:**
   - Clone the project repository from GitHub:
     ```bash
     git clone <repository_url>
     ```
2. **Install Dependencies:**

   - Navigate into the project directory:
     ```bash
     cd <project_directory>
     ```
   - Install PHP dependencies:
     ```bash
     composer install
     ```
   - Install Node.js dependencies:
     ```bash
     npm install
     ```

3. **Set Up Environment:**

   - Create a copy of the `.env.example` file and rename it to `.env`.
   - Generate an application key:
     ```bash
     php artisan key:generate
     ```

4. **Run Migrations:**

   - Execute database migrations:
     ```bash
     php artisan migrate
     ```

5. **Start Development Server:**

   - Launch the development server:
     ```bash
     php artisan serve
     ```

6. **Compile Assets:**

   - Compile frontend assets:
     ```bash
     npm run dev
     ```

7. **Access the Application:**
   - Open your web browser and go to `http://localhost:8000`.
