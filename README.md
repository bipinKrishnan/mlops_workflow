Simple checklist to follow while doing an ML project end to end:

1. Create a git repo 
2. Create a good structure for the project either by using cookiecutter or by yourself
3. Initialize DVC
4. Create a central yaml file to store all parameters
5. While writing python scripts, use Typer for better user friendliness
6. Create a DVC pipeline for better reproducibility
7. Write tests after completing of each class/script
8. Use MLflow or other methods to track parameters and deploy best performing models automatically 
9. Create github actions for running the tests and continuous deployment
10. Add docstrings
11. Reformat the code with black or any other tool
12. Creatr requirements.txt file with pipreqs or other library of your choice
