# Steps
Step 1: New Project Setup

Step 2: Create Basic Python File with vim

    def add(a, b):
        return a + b
    
    
    if __name__ == "__main__":
        print("Addition result:", add(2, 3))
Step 3: GitHub Setup

    git remote add origin https://github.com/your-username/simple-math-app.git
    git add .
    git commit -m "Initial commit with add function"
    git push -u origin main
    
Step 4: Create Feature Branch

    git checkout -b feature-subtraction

Step 5: Add Subtraction Function Using vim
    
    def add(a, b):
        return a + b
    
    
    def subtract(a, b):
        return a - b
    
    
    if __name__ == "__main__":
        print("Addition result:", add(2, 3))
        print("Subtraction result:", subtract(5, 2))

Step 6: Commit & Push Feature Branch

    git add calculator.py
    git commit -m "Added subtract function"
    git push -u origin feature-subtraction

Step 7: Raise Pull Request

    Open GitHub
    
    Click Compare & pull request
    
    Title: Add subtract function
    
    Description: This PR introduces a new subtract function to the calculator app.
    
    Submit PR

  
