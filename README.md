Ansible LAMP Stack Deployment
Automate the deployment and configuration of a LAMP stack (Linux, Apache, MySQL, PHP) on multiple servers using Ansible, following best practices for structure, modularity, and maintainability.

🧱 Project Structure 
_ This project follows Ansible best practices:
_ Roles are used to separate concerns (e.g., apache, mysql, php, firewall).
_ Blocks are used for logically grouped tasks and to implement error handling.
_ Includes/imports ensure playbooks are modular and easy to manage.
_ Error handling is implemented using block, rescue, and always sections.
_ Handlers notify and restart services such as Apache when configurations change.
