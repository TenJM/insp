## Commands to be used 

### 1  ...................    new command prompt    
 
npm init    ### To quickly initialize a Node.js project with default settings using npm

### 2 ...................

npm install   ### recreate the node_modules folder with all the necessary packages.

npm run build    ### This command will execute the build script defined in your package.json file under the "scripts"
 
### 3

npm run serve     ### to run a development server

### 4  ......................       new command prompt

python -m venv myenv  ### Creates a virtual environment

### 5

myenv\Scripts\activate ### Activates the virtual environment immediately after creation.

### 6 ....................... new command prompt

cd app  ### open directory known as app

### 7 

python app.py ### runs the app.py file

### 8 ..........................     new command prompt

redis-server ### starts the Redis server using the default configuration.

### 9 .........................    new command prompt

myenv\Scripts\activate

### 10

celery -A app.tasks.celery worker --loglevel=info ### starts the celery worker and get ready to do the tasks

### 11 .................... when all done

deactivate ###  Deactivates the virtual environment after done.