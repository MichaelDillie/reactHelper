# Steps To Setting Up A React App With A GitHub Repo

These steps will take you though getting a React set up with ```create-react-app```, and adding the app to a GitHub repository.

## Creating an new React App
*In The Terminal Run These Commands* 

1. Run ```create-react-app nameofthereactapp```. Name the app what ever you like.

2. ```cd nameofthereactapp```. cd into the app that was just created.

3. In the root run ```yarn install```. This will get yarn installed so you can run the build and start scripts.

4. Run ```yarn start```. This will open the app in the browser.

**If evrything is done right it should look something like this**

![Image Of App In Browser](https://user-images.githubusercontent.com/11478714/41811487-24eb3bc8-76d6-11e8-8460-969b098a1d3e.png)

**Now that we have created a React App lets "wrap" it in a GitHub Repo**

## Creating a new GitHub repo and adding our app

1. Go to [GitHub](http://github.com).

2. Create a new repository with **NO** README.

![Creating a new repo](https://user-images.githubusercontent.com/11478714/41811567-c09d4934-76d7-11e8-8a0a-7fa0f951cb2a.png)

3. Follow the steps under **…or create a new repository on the command line**.

*Should be the first one*

![Steps to adding files and folders a Repo](https://user-images.githubusercontent.com/11478714/41811589-2356387e-76d8-11e8-8765-5618a0f8ea2a.png)

**Run steps 4 - 5 in the root directory of the React App that we just created**

4. In the terminal run ```git init```.

5. **Skip adding a README**. When we ran ```create-react-app``` it added a README for us.

6. Add all of you files with ```git add .```.

7. Make your first commit to GitHub ```git commit -m "First Commit!"```.

8. Make sure you copy the ```git remote add origin``` part from the steps on GitHub. Paste them into the terminal and run it. This will link everything to your Repo.

9. Last step run ```git push -u origin master```.

**Now if we refresh the page we should see all of the files and folders in our GitHub repository**

![Complete Repository](https://user-images.githubusercontent.com/11478714/41811668-93acc6c8-76d9-11e8-950a-759a8add5a3c.png)

### We now have a GitHub repository with our React App linked

**Happy Hacking!**