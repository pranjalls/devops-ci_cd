# Task Manager DevOps Project
A Flask-based task manager app with CI/CD using Jenkins and containerized with Docker.
# Commands to push github project
cd <folder_name> <br>
git init <br>
git add . <br>
git commit -m "Initial commit" <br>
git remote add origin https://github.com/your-username/inventory-app.git    # Add remote origin <br>
git branch -M main    # Push initial commit to GitHub main branch
git push -u origin main
git checkout -b feature1   # Create and switch to new branch
echo "echo 'New CI/CD feature added\!'" > feature1.sh
chmod +x feature1.sh
git add feature1.sh
git commit -m "Added feature1 script with CI/CD message"
git push origin feature1


