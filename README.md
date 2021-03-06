# An Adjustable Semantic Differential Array question for LimeSurvey version 3.x
**A semantic differential array question in which you can move the position of the last answer column.**

This may be useful if:
- You want to have a "No Answer" item outside of the semantic differential layout in a mandatory question.
- You want to place a column before the semantic differential layout.

![Image Adjustable Semantic Diff Array 2](/Adjustable-Semantic-Diff-Array/survey/questions/answer/arrays/array/assets/images/asda_2.png)

**Implementation:**

1) Extract the download and upload the **Adjustable-Semantic-Diff-Array** folder to */pathToLimeSurvey/upload/themes/question/*.

2) Create an Array type question, click Save. 

3) Implement [the semantic differential feature](https://manual.limesurvey.org/Question_type_-_Array#Short_description) by placing a pipe character between the left/right sub-question labels.  
![Image Adjustable Semantic Diff Array 3](/Adjustable-Semantic-Diff-Array/survey/questions/answer/arrays/array/assets/images/asda_3.png)

4) Set the question setting "Question theme" to "Adjustable Semantic Differential Array", click Save.  
![Image Adjustable Semantic Diff Array 4](/Adjustable-Semantic-Diff-Array/survey/questions/answer/arrays/array/assets/images/asda_4.png)

5) Adjust the "Column position" setting in the "Custom options" question attributes. The last answer column will be moved to this position.  
![Image Adjustable Semantic Diff Array 5](/Adjustable-Semantic-Diff-Array/survey/questions/answer/arrays/array/assets/images/asda_5.png)

**Notes:**

1) The styles for the theme can be modified in */pathToLimeSurvey/upload/themes/question/Adjustable-Semantic-Diff-Array/survey/questions/answer/arrays/array/assets/css/asda.css*.

4) Demo survey in */Adjustable-Semantic-Diff-Array/survey/questions/answer/arrays/array/assets/demo/*.
    
    
*Custom themes are given without any warranty, implied or otherwise.*
