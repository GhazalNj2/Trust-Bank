Trust Bank Website

Trust Bank Website is a comprehensive banking platform developed for Web Programming course at [University Name]. The project demonstrates a modern banking website implementation with features including user authentication, appointment scheduling, and administrative controls. Built using HTML5, CSS3 with Bootstrap, JavaScript, and PHP, the platform provides a secure and user-friendly interface for both customers and bank employees.

The system is built on a Docker-based architecture, ensuring easy deployment and scalability. Key features include secure user registration and authentication, appointment management, membership plans, and an administrative dashboard. The frontend utilizes Bootstrap for responsive design, while the backend is powered by PHP with MySQL database integration. The project implements best practices in web security and user experience design, featuring real-time market updates, financial tips, and a comprehensive banking service information portal.

1. Clone the repository:
   ```bash
   git clone [repository-url]
   ```
2. Configure environment variables:
   - Copy `.env.example` to `.env`
   - Update database credentials and other configuration settings
3. Start Docker containers:
   ```bash
   docker-compose up -d
   ```
4. Access the website:
   - Main website: http://localhost:80
   - phpMyAdmin: http://localhost:8080
   - Default admin credentials:
     - Username: admin
     - Password: admin123 (change immediately after first login)

Ensure Docker and Docker Compose are installed on your system before setup.
