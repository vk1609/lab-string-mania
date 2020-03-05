![Image description](https://i1.faceprep.in/ProGrad/face-logo-resized.png)

# ProGrad Lab | String Mania

## A Quick Introduction



## What should you do
```
Fork this repo
Clone this repo
Practice Java basics - operators, conditions, loops, class and object
```

## How To Submit
```
Upon completion, run the following commands:

git add .
git commit -m "ProGrad ID"
git push origin master

And finally, create a pull request so your ProGrad Mentor (PM) can review your work.
```

## Instructions

1. ***Do not modify the entire code.***
2. ***Edit the code as per the instructions.***
3. ***Go to Java Resources -> src folder.***
4. ***You will have 3 packages src/controller, src/utility.***
5. ***Once the progressions are completed, follow the instructions to run the application and test your code.***

## Testing
1. ***Right click on your project and then run as - Junit.***
 
## Run the Project
1. ***Right click on the project.***
2. ***Go to Run as -> Run on server.***
3. ***You can check the output in eclipse browser or in your browser.***

## Input Format
1. ***There are three stages***
2. ***In stage - 1, there is one input which is a String.***
3. ***In stage - 2, there are two String inputs.***
4. ***In stage - 3, there are two String inputs.***


## Output Format
1 ***Based on the function selected, it can be a string, integer or boolean value.***


## Progression - 1 
1. ***Create a class called StringBasic inside the utility package.***
2. ***

## Progression - 2
1. ***Create an Abstract class BasicEligibility in the utility package***
2. ***Create an abstract method - abstract boolean basicEligibilityCheck (User user)***

## Progression - 3
1. ***Create an interface EligibilityInterface in the utility package***
2. ***Create a method in interface - boolean checkUser (User user)***
3. ***Create a method in interface - boolean checkQuizAnswer (String points)***

## Progression - 4
1. ***Create a class called EligibilityCheck which extends the abstract class BasicEligibility and implements EligibilityInterface***
2. ***Implement the method basicEligibilityCheck (User user)***
3. ***The basicEligibilityCheck method should in turn invoke 2 methods checkUser(User user) ana checkQuizAnswers(String points)***
4. ***Return true if the candidate is eligible for space journey, return false otherwise.***

## Progression - 5
1. ***checkUser(User user) method is used to check whether the user is eligible for space journey or not.***
2. ***A person is eligible if his (18 <= age <= 35, (155 <=height<=170 ) , (55<= weight <= 90) and Country == ProGrad.***
3. ***Return true if the person is eligible and return false otherwise.***

## Progression - 6
1. ***checkQuiz(String points) method is used to check whether the candidate has cleared the assessment or not.***
2. ***A candidate clears the test only if he scores more than 80.***
3. ***Return true if he scores more than 80 else false.***
4. ***Convert the String to an Integer.***

## Progression - 7
1. ***Create an object for the User class and pass the input arguments to the contructor.***
2. ***Create an object for the EligibilityCheck class in EligibilityViewController.***
3. ***Call the basicEligibilityCheck(user) method with the object created.***
4. ***Store the return value in a boolean variable spaceEligible.***
5. ***Create an object for the EligibilityCheck class in Eligibility.***
3. ***Call the checkQuizAnswers(String points) method with the object created.***
4. ***Store the return value in a boolean variable spaceEligible.***


Happy Coding ProGrad ❤️
