# Shuffle-Array
Here's an explanation of the program step by step:
We start by defining a class called ShuffleArray.
In the main method, we create an array of Integer objects named intArray containing integers from 1 to 7.
We then convert the intArray into a List of Integer using Arrays.asList(intArray). This allows us to use the convenient shuffle method provided by the Collections class.
Next, we use Collections.shuffle(intList) to shuffle the elements within the intList. This randomizes the order of elements in the list.
To update the original array with the shuffled values, we use intList.toArray(intArray). This method copies the elements from the shuffled list back into the original array intArray.
Finally, we print the shuffled array using Arrays.toString(intArray).
