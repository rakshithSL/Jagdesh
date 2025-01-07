git init                          # Initialize repository (if not done already)
git checkout -b staging           # Create and switch to the staging branch
git remote add origin <url>       # Add remote repository if not linked
git push origin staging           # Push the staging branch to GitHub
git add .                         # Stage all changes
git commit -m "Your message"      # Commit your changes
git push origin staging
