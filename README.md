

# DiscussionForumClone

DiscussionForumClone (A Question-Answer Forum) is an extended look at building a modern blog with the Django Framework while leveraging other technologies such as jQuery, Markdown, Bootstrap, HTML and CSS.

##### Project Overview : https://www.youtube.com/watch?v=yidkwVbpd2I
                          
##### Project Link : https://discussion-forum-clone.herokuapp.com/


##### Installation Process : 
**Step - 1** : Open command shell and clone the project repo using the below command.     
                 
               git clone https://github.com/Sush97/DiscussionForumClone.git
   (Or you can just download the repo where in all project files are zipped)
                
**Step - 2** : Enter into the project directory.
                
               cd DiscussionForumClone
                 
**Step - 3** : Install all the requirements necessary for this project using below command
                  
               pip install -r requirements.txt 
               
   Make sure pip is already installed in your machine before you run the above command
                  
   **Note** : _For windows, if you have any permission issues during installation rum the Command Prompt or Windows Power Shell in administrator mode (Start -> (cmd or Windows Power Shell) -> right click -> Run as administrator)_
                 
                 
**Step - 4** : To make project run in your local machine run the below commands step by step
              
              cd src
              python manage.py makemigrations
              python manage.py migrate
              python manage.py collectstatic
              python manage.py runserver
              
   Now you can open http://127.0.0.1:8000/ to view the app 
