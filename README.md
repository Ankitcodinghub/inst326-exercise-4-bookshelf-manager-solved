# inst326-exercise-4-bookshelf-manager-solved
**TO GET THIS SOLUTION VISIT:** [INST326 Exercise 4-BookShelf Manager Solved](https://www.ankitcodinghub.com/product/inst326-exercise-4-bookshelf-manager-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93575&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;INST326 Exercise 4-BookShelf Manager Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
# Instructions

For this homework assignment, you will read in multiple works of literature to create an index of the words used in each work (in the form of a dictionary) and a popularity index. We will assume that each one of these works exist as text files in a folder within the same directory as your python script named data. We will also assume that your script is named bookshelf.py.

Your script should contain two classes, Book and BookShelf, and at least one function (remove_punctuation, main and parse_args) that exist outside of any class. At the end of the script should be an if __name__ == “__main__”: statement. Specifications for each of these required program elements are given below. You may write additional classes, methods, and/or functions if you wish.

# remove_punctuation()

**Functionality**

– This function takes a string and returns a string containing only the lower cased alphabetical characters. If the item being passed in is not a string a TypeError should be raised.

**Parameters**

– word: the input string that contains a word. This word may contain non-alphabetical characters such as numbers or punctuation marks.

**Returns**

– A lowercase string containing only the lowercased alphabetical characters from the input string with all of the non alphabetical characters stripped away. If the string did not contain any alphabetical characters (the string is empty), the function will return None.

# Book class

**Functionality**

– This class stores the text data for a single book

**Attributes**

– words: a list of all of the individual words in the book. The elements in this list do not have to be unique.

**Methods**

– __init__()

– Parameters

– Self

– Path – The path to the file that we are going to read.

– Functionality

– The init method should open the file specified by the path for reading and set the words to attribute to a list containing all of the words in the file split on the spaces. You should also use the remove_punctuations() function within a list comprehension to remove all of the non-alphabetical characters from each element in the list and set the resulting list to the words attribute. While you are at it, you should also remove any elements of the list that were determined to be None by remove_punctuations(). The resulting words attribute should be a list of string elements where each element contains only lowercase alphabetical characters.

– unique_words()

– Parameters

– Self

– Functionality

– This method should return a set created from the words attribute (which should be a list).

# BookShelf class

**Functionality**

– This class stores the index for words in books as they are provided.

**Attributes**

– index: a dictionary representing an index of the words of a book where the keys are the unique words found in a series of books, and the values are lists containing string elements that represent the name of the book in which that word is found.

– popularity_index: a dictionary based on the index attribute which is itself an index where the keys are integers that represent how many books a word is found in and the values are the words that correspond to this count. For example: if the words “tree” and “car” are found in two different books, and the word “lantern” is found in one book the dictionary might look like so: {2:[“tree”, car], 1:[“lantern”]}.

&gt; NOTE: This attribute will start off empty and will not be created until find_popularity() is invoked later.

**Methods**

– __init__()

– Parameters

– Self

– Functionality

– Sets the index attribute to an empty dictionary (to be populated later). The format of this index will be the following: {word: a list containing names of books that use that word}.

– Sets the popularity_index attribute to an empty dictionary (to be populated later).

– add_books()

– Parameters

– Self

– text

– Functionality

– This method will create a book object from the text name that is being passed in. It should invoke the unique_words() method in order to return the unique words in that work. It should save this returned value so that it can add the words from this text and index those words in the index attribute. It should only add to the index, it should not delete or remove anything from the index attribute.

&gt; NOTE: It is completely fine if the name of the text being indexed is the path to the file itself.

– find_popularity()

– Parameters

– Self

– Functionality

– This method should reset the popularity_index attribute. It should then populate the popularity_index by iterating over the items of the index attribute so that the popularity_index becomes an index where the keys are integers that represent how many books a word is found in and the values are the words that correspond to this count. For example: if the words “tree” and “car” are found in two books, and the word “lantern” is found in one book the dictionary might look like {2:[“tree”, car], 1:[“lantern”]}.

&gt; NOTE: This attribute will start off empty and will not be created until find_popularity() is invoked later.

# main()

**Functionality**

– This function will create an instance of bookshelf. Use each path in the library list (the list that is passed in) to invoke the add_books method on that bookshelf instance. Then invoke the find_popularity() method of the instance of bookshelf that you created.

**Parameters**

– Library: A list of strings where the strings are paths to text files which are books on your machine.

**Returns**

– As a tuple, return the index attribute of your bookshelf, length of the index of your bookshelf and the popularity_index attribute of your bookshelf.

# parse_args()

**Functionality**

– This function will create an instance of an ArgumentParser object and assign one argument to it named books. This argument should be of type str. This argument should be flagged so that it accepts any number of command line arguments (but at least one) and create a list of these arguments. This can be done with the nargs keyword argument of the parse_args method of ArgumentParser. For more information on this keyword argument please take a look at the argpase documentation on nargs.

**Parameters**

– args_list: A list of command line arguments. Can be of any length.

**Returns**

– The ArgumentParser object which was created.

# if __name__ == “__main__”:

– The if __name__ == “__main__”: statement should create a list of strings which are the paths to the text files that you will be indexing (the text files contained in “data”).

– The list is going to come from the returned value of the argparse function (specifically, from the books attribute of this object). You may find that you will need to manipulate the contents of this returned list in some way. You should call the main function and pass in this list as an argument.

&gt; NOTE: For testing purposes, you may print the returned values of the main() function call. The final version of your script dos not need to. You can instead, simply call the

main().

# Running your program

– Your program is designed to run from the terminal. To run it, open a terminal and ensure you are in the directory where your script is saved.

– The program takes at least one command-line argument: the name of the text files (which are books) that you want to process using your script. Below are some examples of how to use the program. The examples assume you are using a Unix based OS (macOS, Linux) and your program is called bookshelf.py. If you are using Windows, replace python3 with python.

– Your script won’t produce an output unless you print the returned value of the main() function. You may choose to print the values for testing purposes but the final version of your script should not print anything. Keep in mind, should you pass in all the books provided as arguments, the length of the bookshelf index created should be 33065. Should you pass in only don_quixote.txt the length of the bookshelf index created should be 16848.

&gt; NOTE: python3 bookshelf.py don_quixote.txt

&nbsp;

&nbsp;

&nbsp;
