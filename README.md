# M3-W1-P2
This is an exercise with the following tasks below;

 GIT Conflicts
With this exercise you will learn how Git conflicts are generated and how to handle them gracefully in your local machine.

Download and install GitHub Desktop and Login with your GitHub credentials
Create a new repository and add a new index.html file with the following boilerplate code:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
Commit and push your code to GitHub! You will be asked whether to keep your repository as Private. Make sure to deselect that box if you are collaborating with a peer.
If you are collaborating with a peer: make sure to get set your colleague as collaborator in your repository settings.
Also choose who will follow instructions for Dev A and who will follow Dev B's. If you are working on your own, just follow along the instructions for both.
DEV A
Create a header title: My Groceries List
Create a <ul> element with two <li> elements inside: Milk and Eggs
Commit and push to Main. Your colleague will now see that he is able to pull your edits.
Now, from the branch main, create your own branch for the next edits and call it dev-a.
DEV B
Pull the edits in the main branch and, always from the branch main, create a new branch called dev-b.
Now dev-a and dev-b are branches based on the same main branch: however from this point in time they will differ!
Add to the groceries list these elements:
        <li>Cake</li>
        <li>Candy</li>
        <li>Chips</li>
        <li>Candy bar</li>
        <li>Cookie</li>
Style your title with a red color
Style the <li> elements with a aquamarine background color and squared bullet points.
Commit and push to dev-b!
DEV A
Meanwhile, Dev A, on your dev-a branch, add these elements to the groceries list:
        <li>Bread</li>
        <li>Butter</li>
        <li>Coffee</li>
        <li>Tea</li>
Style the title with a blue color
Styles the <li> elements with a yellow background color
Commit and push to your own branch!
Now go back to the main branch and merge it with your dev-a branch.
To do so, from the branches menu select "Choose a branch to merge into main" (it's the button at the very bottom of the menu).


This merge should happen without conflicts!
Commit and push!
DEV B
Switch back to the main branch and Pull the new edits, right after Dev A merge.
Try merging your dev-b branch, selecting "Choose a branch to merge into main".
However, your branch won't be able to be automatically merged. You will be facing some conflicts

 

Click on “Open in Visual Studio Code” to open the file in VSCode
You will face a few highlighted lines of code, similar to the following example:

 

 

“Accept current change” will keep the green code, while Incoming Change will keep the blue code.
You can also “Accept both changes” and all the code will be accepted!
Git doesn't know which code to keep because both branches are diverging from main at the same point in time.
Now it's your turn to “sort it out”. Final expected result in the main branch :
A list of all grocery store elements
Blue colored title
Aquamarine and squared bullet point
 
