To start the development of DTM, please follow this step by step process, its assumed that you already have python3 installed.
#### Step 1:Fork the threat-mirror to your personal repo
#### Step 2:Clone the forked repo to your device
  * $ git clone  https://github.com/**yourgitrepo**/threat-mirror.git
#### Step 3:Navigate to the project Directory(DTM)
  * $ cd threat-mirror/DTM
#### Step 4: Create a virtual environment:
  * $ virtualenv venv
#### Step 5: Activate the virtual environment:
  * $ source venv/bin/activate
#### Step 6: Install the requirements:
  * $ pip3 install -r requirements.txt
#### Step 7: Verify the installed packages:
  * $ pip3 freeze
#### Step 8: Start the server:
  * $ cd DTM_project
  * $ python3 manage.py runserver
#### Step 8: Chck the server is accesable via web:
	* http://127.0.0.1:8000/
** Note:This manual is tested on mac, commands might vary depending on your device but steps would essentially remain similar.
## You now have the Django environment setup, use editor of your preference and start building the pages. 
