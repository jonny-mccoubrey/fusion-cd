## Fusion-CD

### Set-up
1. Install Git on your local environment
2. Clone this git repository:  
   **git clone https://github.com/jonny-mccoubrey/fusion-cd.git**
3. Create your own custom branch:  
   **git checkout -b <your_branch_name>**
4. Apply your environment specific changes
5. Add modified files to Git to be checked out:  
   **git add <file_name>**
6. Commit files to your branch:  
   **git commit -m '<your_commit_message>**
   

### Updating to latest release
1. Ensure all of your environment specific changes are committed to your branch
2. Merge latest **main** branch changes into your branch:  
   **git pull origin main**
3. Review merge conflicts
4. Commit changes to your branch
5. Deploy changes to environment
