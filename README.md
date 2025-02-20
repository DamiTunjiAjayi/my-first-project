# Full Command Log for My-First-Project

```bash
# Navigated to the projects folder
cd projects
# Initialized a new Git repository
git init
# Added all files in the current folder
git add .
# Commited the changes with a meaningful message
git commit -m "These are all the files"
# Add the remote repository
git remote add origin https://github.com/DamiTunjiAjayi/my-first-project.git
# Pushed the commits to the remote repository on the 'main' branch
git branch -M main
git push -u origin main
# Clone the repository into projects folder
git clone https://github.com/DamiTunjiAjayi/my-first-project.git
# Created a new file named goals.txt
touch goals.txt
# Opened the goals.txt file using Vim editor
vim goals.txt
# In Vim: I pressed "i" to insert text
1. Master a backend programming language (e.g., Node.js, Python, or Java) to build robust server-side applications.
2. Learn and implement RESTful API design principles to create scalable and efficient web services.
3. Gain expertise in database management by working with both SQL (e.g., PostgreSQL, MySQL) and NoSQL (e.g., MongoDB) systems.
4. Develop skills in deploying and managing backend applications using cloud services and containerization tools (e.g., Docker, Kubernetes).
5. Understand and implement authentication, authorization, and security best practices to protect web applications.
6. Practice writing unit tests and integration tests to ensure code reliability and maintainability in a production environment.
#In Vim: I pressed :wq to save and exit the editor
# Staged the new file
git add goals.txt
# Commit the changes and pushed to GitHub
git commit -m "Created the goals file and added my goals for M4ACE program"
git push -u origin main
