1. install poetry -- https://python-poetry.org/docs/#installation
2. install dependencies with poetry
  ```
  $ poetry install
  ```
3. Create keys.py file for your OpenAI API key (you can generate a new one from https://platform.openai.com/account/api-keys)
  ```
  $ echo "OPENAPI_KEY = 'sk-pasteyouropenaikeyhere'" > keys.py -- replace 'sk-pasteyouropenaikeyhere'
  ```
4. Use a text editor to edit the file 'gssp-shell'. Replace '/path/to/gssp-shell.py' with the absolute path of gssp-shell.py file 
5. Make gssp-shell executable so it can be run from the command line
  ```
  $ chmod +x gssp-shell -- make gssp-shell executable so it can be run from the command line
  ```
6. (optional) Add the path to the gssp-shell root directory to your $PATH to allow gssp-shell to be called from anywhere on the os
7. (optional) Edit the prompts.py file to configure a custom prompt
8. Run gssp-shell (Note: If you did the optional step 5 you can run this from anywhere. Otherwise you must be in the gssp-shell root directory.)
  ```
  $ gssp-shell
  ```