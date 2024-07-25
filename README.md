# Feedback System   <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/112846526/347160330-a015a6e5-290d-4e11-a28c-3f9b0d59d818.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240725%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240725T060500Z&X-Amz-Expires=300&X-Amz-Signature=90b8903b176e86d1853a4862d7f77e6e5bf17a2fe93c0547eccc31d7b2f6110f&X-Amz-SignedHeaders=host&actor_id=112846526&key_id=0&repo_id=740856953" alt="image" width="50"/>



## Overview

The Feedback System project is designed to facilitate the collection and management of feedback within an educational institution. The project has three primary sections: Admin, Teacher, and Student.

## Tech Stack  <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/112846526/347160897-e7da1ab5-4360-46a0-bf45-74aaa349de1a.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240725%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240725T060526Z&X-Amz-Expires=300&X-Amz-Signature=1867b1f53de45f4b4730fd64fc387822f42aff2a510028b4b31d828d4594696b&X-Amz-SignedHeaders=host&actor_id=112846526&key_id=0&repo_id=740856953" alt="image" width="50"/>


- **Frontend:** HTML, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Server:** XAMPP

## Sections

### 1. Student Section  <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/112846526/347161090-ba465c73-bd69-4294-b784-bfb507cd9586.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240725%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240725T060548Z&X-Amz-Expires=300&X-Amz-Signature=109fd6f86bc2121fd458a88961f7c5a85259e5bb29366f53e4e976326f28440b&X-Amz-SignedHeaders=host&actor_id=112846526&key_id=0&repo_id=740856953" alt="image" width="50"/>


Students can:
- Set up and manage their profile.
- Provide feedback on subjects and class outcomes for the teachers who teach them.

### 2. Teacher Section  <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/112846526/347161264-38e82f67-201a-4d03-b4e0-a37cd84b6295.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240725%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240725T060608Z&X-Amz-Expires=300&X-Amz-Signature=f14d18ab1fc9c9ec143b6a701c4019da04dc0782a8e1f840405db7349235c1b6&X-Amz-SignedHeaders=host&actor_id=112846526&key_id=0&repo_id=740856953" alt="image" width="50"/>


Teachers can:
- Manage their profile.
- View their class allotments.
- Update or add course outcomes.
- Add students to their courses.
- View which students have provided feedback and which have not.
- Sort and print a list of students who have not given feedback.

### 3. Admin Section  <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/112846526/347161425-c693ae2e-9869-4ac8-95dd-fd5e2105ae00.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240725%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240725T060627Z&X-Amz-Expires=300&X-Amz-Signature=1d48bb336e93a92dba0cf6eeba7038175c943f0674951142cfe60acb03fff77b&X-Amz-SignedHeaders=host&actor_id=112846526&key_id=0&repo_id=740856953" alt="image" width="50"/>


Admins have all the functionalities of teachers plus additional capabilities:
- Add and manage teachers.
- View all feedback given.
- Generate processed reports of the feedback.

## Getting Started<img src="https://github-production-user-asset-6210df.s3.amazonaws.com/112846526/347161601-19c5d9ca-f0cf-41a2-aefd-9fb989c6137b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240725%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240725T060644Z&X-Amz-Expires=300&X-Amz-Signature=57ae7af0a59187bd719fc9de5aec01ed7a923ed0641fb7fd1a238ebe30b9e47d&X-Amz-SignedHeaders=host&actor_id=112846526&key_id=0&repo_id=740856953" alt="image" width="50"/>


### Prerequisites

Ensure you have the following installed on your local development environment:
- [XAMPP](https://www.apachefriends.org/index.html)
- MySQL (comes with XAMPP)

### Installation

1. Clone the repository in htdocs:
   ```sh
   git clone <repository_url>
   ```


2. Navigate to the project directory:
   ```sh
   cd feedback-system
    ```

3. Set up the database:
   - Open XAMPP Control Panel and start Apache and MySQL.
   - Open phpMyAdmin by visiting [http://localhost/phpmyadmin/](http://localhost/phpmyadmin/).
   - Create a database named `feedback_system`.
   - Import the provided SQL file to set up the tables.

### Running the Project <img src="https://github-production-user-asset-6210df.s3.amazonaws.com/112846526/347161820-3b00fcd4-59af-4b3a-bf88-4d1182322eb9.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240725%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240725T060713Z&X-Amz-Expires=300&X-Amz-Signature=5fe07f4384d5571d3b737c40fd7bf6b9260b76ddf19c107989bccfe7acde814d&X-Amz-SignedHeaders=host&actor_id=112846526&key_id=0&repo_id=740856953" alt="image" width="50"/>


- Start your web server and ensure it's serving the project directory.
- Open your web browser and navigate to [http://localhost/feedback-system](http://localhost/feedback-system) (or the appropriate URL based on your server configuration).

    
