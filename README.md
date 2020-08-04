# thesis-code
In The Project, I have used FER 2013 Dataset which contains 35,887 images.

Step 1.
We first need to connect the dataset to the code.(In my project I have dataset as well as code uploaded on the drive)
  
  1.1 When we run the linking code(connect the dataset to the code) it will show you the link("Go to this URL in a browser: https://accounts.google.com/o/oauth2/auth?client_id=947318989803-6bn6qk8qdgf4n4g3pfee6491hc0brc4i.apps.googleusercontent.com&redirect_uri=urn%3aietf%3awg%3aoauth%3a2.0%3aoob&response_type=code&scope=email%20https%3a%2f%2fwww.googleapis.com%2fauth%2fdocs.test%20https%3a%2f%2fwww.googleapis.com%2fauth%2fdrive%20https%3a%2f%2fwww.googleapis.com%2fauth%2fdrive.photos.readonly%20https%3a%2f%2fwww.googleapis.com%2fauth%2fpeopleapi.readonly").
  
  1.2 Click the link and provide access to your drive(dataset is there).It will give a code.
  
  1.3 Copy the code and paste in the last blank(Enter your authorization code:
··········).
  
  1.4 It will connect the code with dataset(" Mounted at /content/drive ").
  
Step 2.
  Use the dataset by giving the path of dataset(" /content/drive/My Drive/face_recognisation/ ").
  
Step 3.
 Divide the dataset into different sets(training set, testing set, validation set) depends upon model.
 
Step4. Create architecture of CNN model and set some parameter values.

Step 5. Run the Code and It will give you the results and graphs.
