# Assignment 1
Submitted by: Archana Balan
JHED Id: abalan2

## Question 1
* Use unix command **wget** to obtain the wikipedia page. 
* Command **wc -l (filename)** is used to count the total number of lines.
The total number of lines = 3457 

```
wget https://en.wikipedia.org/wiki/Alexander_the_Great
wc -l Alexander_the_Great   
```
##### Question1.png
![Question1](https://github.com/archana64/my-first-repo/blob/master/Question1.png)

## Question 2

### Steps follwoed to fork the repository and create readme.md file.
* Fork the course repository using the fork icon on the top right corner.
* Create a clone of the repository in a local git repository to create changes
* Use git -remote to make changes remotely in the local repository
* Create new directory test using command **mkdir** 
* Within new directory create a readme.md file using command **touch**
* Commit changes to the git repository
* Use **git push** to publish changes on gitHub


##### Question2.a.png
![Question2a](https://github.com/archana64/my-first-repo/blob/master/Question2_a.png)

##### Question2.b.png
![Question2b](https://github.com/archana64/my-first-repo/blob/master/Question2_b.png)

##### Question2.c.png
![Question2c](https://github.com/archana64/my-first-repo/blob/master/Question2_c.png)


## Question 3

### Issue pull request
Issued a pull request in the course repository for the changes made in Question 2

##### Question3.a.png
![Question3a](https://github.com/archana64/my-first-repo/blob/master/Question3.a.png)

##### Question3.b.png
![Question3b](https://github.com/archana64/my-first-repo/blob/master/Question3.b.png)

## Question 4

### Create new repository
* Create a new repository called ds4bmeTest
* Clone the repository to access it in the local system
* Create a new readme.md file in the local clone of the repository 
* Add and commit the changes in the local repository
* Push the changes back to the GitHub server
* A readme.md file is created in the ds4bmeTest repository in GitHub

##### Question4.a.png
![Question4a](https://github.com/archana64/my-first-repo/blob/master/Question4_a.png)

##### Question4.b.png
![Question4b](https://github.com/archana64/my-first-repo/blob/master/Question4_b.png)

##### Question4.c.png
![Question4c](https://github.com/archana64/my-first-repo/blob/master/Question4_c.png)

##### Question4.d.png
![Question4d](https://github.com/archana64/my-first-repo/blob/master/Question4_d.png)

## Question 5
* Create an html file called index.html
* Serve the page by changing the settings for Github pages 
* The link for the web page: https://archana64.github.io/my-first-repo/index.html

##### Question5.a.png
![Question5a](https://github.com/archana64/my-first-repo/blob/master/Question5_a.png)

##### Question5.b.png
![Question5b](https://github.com/archana64/my-first-repo/blob/master/Question5_b.png)


## Question 6
* The lsfile() takes the argument path as input and prints output to a text file outfile.txt

```
#!/bin bash
lsfile(){
ls $1 > outfile.txt
}
```
To run script: lsfile **path** # path is the input path to the input directory 

## Question 7
* The recursive_dcm() function takes in an input directory and outputs all .dcm files to out_dcm.txt file in the current working directory.

```
#!/bin bash
recursive_dcm(){
ls-R $1 > tmp.txt
grep ".dcm" tmp.txt > out_dcm.txt
rm tmp.txt
}
```
To run script: recursive_dcm **input directory** 

