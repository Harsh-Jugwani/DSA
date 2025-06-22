#BackTracking Notes


BackTracking is the type of recursion which helps us to skip the unnecessary operations.

BackTracking is very helpful when there is large no. of choices.

##Psuedo Code for BackTracking

'void solve(...){
      //base condition
      if(isSolved(...) == true)
          save/print
      // mutiple choice
      for(int i = 0; i < s; i++){
          if(isValid(...) == true)//checking for skipping
            solve(...);
      }
 return;
}
'

