![alt text](image.png)# Version-Control-System (GitHub)

# Authentication Setup

Use the following steps to set up SSH based authentication:

1. Create a ssh key on your system's terminal using following command   
ssh-keygen -t ed25519 -C "your_email@example.com"

Press enter for all inputs and it will create two files in ~/.ssh folder - id_ed25519 and id_ed25519 pub

2. Copy the contents of id_ed25519.pub file.

3. In your Github Account settings (https://github.com/settings/profile), click on "SSH and GPG Keys". (Make sure you are logged in using beingzero id).

4. On the SSH and GPG Keys page (https://github.com/settings/keys), click on "New SSH key. Give an easy to understand title and paste the contents of the "id_ed25519.pub" file in the Key section. Click "Add SSH Key".

5. You are ready to work with beingzero github repositories.

NOTE: 
1. For Windows users go to services by searching in the search bar.
2. Next search openSSH Authentication Agent.
3. Right click on it and select Automatic from startup type.
4. After that once again right click on openSSH Authentication Agent & start.

# Contributing to Existing Projects

1. Fork the repo with your Github account.

2. Clone the forked repo in your local system.

3. Create a new branch for each new feature/bug and make commits in the branch

4. The new branch should be based on the main branch

5. Push the new branch to your forked repo.

6. Create a new PR from Github Ul to the main branch of the project

NOTE : 
Never send direct commits to your fork's main branch or to the project repository.
