Below are the step-by-step instructions using the command line interface (CLI) to create a new GitHub repository named 'new-project' with a development branch:

1. Create a new repository:
curl -u 'your_username' https://api.github.com/user/repos -d '{"name":"new-project"}'

2. Clone the Repository:
git clone https://github.com/your_username/new-project.git

3. Navigate into the cloned repository:
cd new-project

4. Create a branch:
git checkout -b development

5. Make some change in a file, add it to Git, make commit
git add file.txt && git commit -m "my commit"

6. Push the development branch to GitHub:
git push origin development
