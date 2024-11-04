# What ?
This is a Python script that writes Git commits into whatever 52x7 image pattern you give it.

# How to use 
1. Run `git init`
2. Use Paint or photoshop to draw a design into a 52x7 image, template provided in `template.png`
3. Update `main.py` to take the image path as an argument
4. Run `pip install -r requirements.txt` 
5. Run `python3 main.py` to format image to commit history (52x7) matrix
6. Add `git remote add <your_remote_link>` or Update `git remote set-url <your_remote_link>`
7. Push `gut push --set-upstream origin master` to public repository
