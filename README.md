# weather-test



Installations :

install java 
install plugin "geckodriver" for browser to open  
and change the path in java file webHelper






Run Highlights:

Run file "RunFeature"

tags are used to restrict test case execution.



Improvements

Better report generations 
group all Given , when , then , And functions in one java file
group all the reusable functional in one java file , so that functions can be reused. 
if we use Java 8 , string validations will be much easier
group all the global variable in common properties eg : Sleep , Url ( so it is easier to change the URl depending of the environment tested )
can test for multiple browsers
can put the the paths in the common.proprties 



testing coverage 
Can cover more edge cases - but no enough time to coverage 


Req Not clear: 
Daily forecast should summarise the 3 hour data:  - not sure what are the calculation used in the application but for rounding down have to use -  Math.floor
