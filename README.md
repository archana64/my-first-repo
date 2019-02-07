# Assignment 1

## Question 1
* Use unix command **wget** to obtain the wikipedia page. 
* Command **wc -l (filename)** is used to count the total number of lines.
The total number of lines = 3457 

```
wget https://en.wikipedia.org/wiki/Alexander_the_Great
wc -l Alexander_the_Great   
```

![Question1](https://github.com/archana64/my-first-repo/blob/master/Question1.png)

## Question 2

### Steps follwoed to fork the repository and create readme.md file.
* Fork the course repository using the fork icon on the top right corner.
* Create a clone of the repository in a local git repository to create changes
* Use git -remote to make changes remotely
* Create new directory test using command **mkdir** 
* Within new directory create a readme.md file using command **touch**
* Commit changes to the git repository
* Use **git push** to publish changes on gitHub



![Question2a](https://github.com/archana64/my-first-repo/blob/master/Question2_a.png)

![Question2b](https://github.com/archana64/my-first-repo/blob/master/Question2_b.png)

![Question2c](https://github.com/archana64/my-first-repo/blob/master/Question2_c.png)


## Question 3

### Issue pull request

![Question3a](https://github.com/archana64/my-first-repo/blob/master/Question3.a.png)

![Question3b](https://github.com/archana64/my-first-repo/blob/master/Question3.b.png)

### Question 4

### Create new repository
![Question4a](https://github.com/archana64/my-first-repo/blob/master/Question4_a.png)

![Question4b](https://github.com/archana64/my-first-repo/blob/master/Question4_b.png)

![Question4c](https://github.com/archana64/my-first-repo/blob/master/Question4_c.png)

![Question4d](https://github.com/archana64/my-first-repo/blob/master/Question4_d.png)

### Question 5
The lsfile() takes the argument path as input and prints output to a text file outfile.txt

```
#!/bin bash
lsfile(){
ls $1 >> outfile.txt
}
lsfile path # path is the input path to the input directory 
```


