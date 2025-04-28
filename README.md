# cmpt135-assignment-1--echo-solved
**TO GET THIS SOLUTION VISIT:** [CMPT135 Assignment 1- Echo Solved](https://www.ankitcodinghub.com/product/cmpt135-assignment-1-echo-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120363&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPT135  Assignment 1- Echo Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (2 votes)    </div>
    </div>
For this assignment, please download the file myecho.cpp and put all your code into that file.

Part 1

Question 1

Write a function called quote(s) that returns a copy of the string s surrounded by double quotes. If s already starts and ends with double quotes, then return an unchanged copy.

For example, this:

cpp cout &lt;&lt; quote(“hello”) &lt;&lt; ” ” &lt;&lt; quote(“goodbye”) &lt;&lt; ” ” &lt;&lt; quote(“”Aloha!””) &lt;&lt; ” ” &lt;&lt; quote(“toodles””) &lt;&lt; ” ” &lt;&lt; quote(“””) &lt;&lt; ” ” &lt;&lt; quote(“”) &lt;&lt; ” “;

Should print this:

“hello” “goodbye” “Aloha!” “toodles”” “”” “”

In addition to implementing quote, also write a function called test_quote() that automatically tests your quote function. Use assert or ifstatements to do the testing, and test the above examples, as well as a few other examples that you make up. Be thorough — your function should work for all valid inputs, not just the ones in the examples.

cpp void quote_test() { cout &lt;&lt; “testing quote … “; assert(quote(“a” ) == “”a”” ); assert(quote(“ab” ) == “”ab”” ); assert(quote(“”a”” ) == “”a”” ); assert(quote(“”ab”” ) == “”ab”” ); assert(quote(“a”b” )

== “”a”b””); assert(quote(“”a” ) == “””a”” ); assert(quote(“a”” ) == “”a””” ); assert(quote(“” ) ==

“””” ); assert(quote(“”” ) == “”””” ); cout &lt;&lt; “all tests passed “; } Question 2

When dealing with vectors of strings, it’s convenient to print them with the &lt;&lt; operator. For example:

cpp vector&lt;string&gt; v = {“art”, “booth”, “C”}; cout &lt;&lt; v &lt;&lt; ” “; // prints: {“art”, “booth”, “C”} To make that work we must overload operator&lt;&lt; like this:

“`cpp string to_string(const vector&amp; v) { // // … you write the body … // } ostream&amp; operator&lt;&lt;(ostream&amp; out, const vector&amp; v) { return out &lt;&lt; to_string(v); } “`

Implement the to_string(v) function so that operator&lt;&lt; works correctly. to_string(v) takes a vector&lt;string&gt; as input and returns a nicely formatted string as in the examples. The output of to_string should be the same format as C++ string vectors, so you could cut-andpaste the output directly into a C++ program.

Here are some more examples:

cpp cout &lt;&lt; vector&lt;string&gt;{} &lt;&lt; ” ” &lt;&lt; vector&lt;string&gt;{“a”} &lt;&lt; ” ” &lt;&lt; vector&lt;string&gt;{“a”, “b”} &lt;&lt; ” ” &lt;&lt; vector&lt;string&gt;{“a”, “b”, “c”} &lt;&lt; ” “;

This prints:

{} {“a”} {“a”, “b”} {“a”, “b”, “c”}

In addition to implementing to_string, also write a function called test_to_string() that automatically tests your to_string function. Use assert or if-statements to do the testing, and test the above examples, as well as a few other examples that you make up. Be thorough — your function should work for all valid inputs, not just the ones in the examples.

Part 2

The echo command is a standard shell command that prints the arguments passed to it. For example, here is the Fish shell echo command:

“`bash â¯ echo Welcome to Linux! Welcome to Linux! â¯ echo -s Welcome to Linux! WelcometoLinux!

â¯ echo Welcome to Linux! -s Welcome to Linux! -s “`

The -s flag prints the arguments without a space between them. As the example shows, it must be first to have any effect.

In the following questions, your task to implement a customized version of the echo utility. It works similarly, but not identically, to the Linux echo.

Each question asks you to add a new feature, and you can do this is all in the same program.

Case matters in the input strings, e.g. -s and -S are treated as different strings, and so -S would be an invalid flag.

A flag, like -s, is only treated as a flag if it is the first string passed to your myecho. Otherwise, if it’s not the first string, it’s treated like a regular word and printed normally.

Question 3

Implement myecho so that when passed 0 or more strings, each separated by at least once space, those strings are printed on the screen with exactly one space between them. For example:

“`bash

./myecho Welcome to Linux! Welcome to Linux!

â¯ ./myecho Welcome to Linux! Welcome to Linux!

â¯ ./myecho

“`

The sample output uses the Fish shell, and we recommend you use that. Otherwise, you might get slightly different-looking output.

Question 4

To the version of ./myecho you wrote in the previous question, add support for a -h flag that prints the help message given below and exits (ignoring any strings that come after the -h).

The help message should look like this:

“`bash â¯ ./myecho -h Usage: ./myecho [-runtests|-(hrs)] [string …] -runtests: run the tests over-rides single-character flags -h: print this help message over-rides other single-character flags -r: print the strings in reverse order -s: no space between arguments -q: quote the printed results rs, -sr: no space between arguments, in reverse order

Repeated single-character flags are allowed (and are ignored). Unknown flags cause an error.

Examples: â¯ ./myecho -q “” â¯ ./myecho x y z x y z â¯ ./myecho -q x y z “x y z” â¯ ./myecho -sr x y z zyx â¯ ./myecho -h “` Please use this particular help message. The other options listed in it will be implemented in the following questions.

Question 5

To the version of ./myecho you wrote in the previous question, add support for a -runtests flag that calls the test_quote() and test_to_string() functions. Any strings after -runtests are ignored.

The tests should print their results, as shown in the examples.

For example:

“`bash â¯ ./myecho -runtests running quote tests … all passed running to_string tests … all passed â¯ ./myecho -runtests one two three running quote tests … all passed running to_string tests … all passed â¯ ./myecho one two -runtests three one two -runtests three â¯ ./myecho -runtests -h one two three running quote tests … all passed running to_string tests … all passed â¯ ./myecho -h -runtests a b … prints the help message … “`

As these examples show, -h and -runtests only have their special meaning if they appear as the first string passed to myecho. If they appear later, they are treated as regular strings.

Question 6

To the version of ./myecho you wrote in the previous question, add support for the -q flag that prints a ” character (double quote) at the begin and end of the printed result. For example:

“`bash â¯ ./myecho -q “” â¯ ./myecho x y z x y z â¯ ./myecho -q x y z “x y z”

./myecho -qh z y z … prints the help message … “`

Notice that in the quoted strings there is no space after the last string.

Question 7

To the version of ./myecho you wrote in the previous question, add support for the -s flag that prints the strings without a space between them. For example:

“`bash â¯ ./myecho -s Welcome to Linux! WelcometoLinux! â¯ ./myecho -s Welcome to Linux! WelcometoLinux!

â¯ ./myecho -qs Welcome to Linux! “WelcometoLinux!”

./myecho -s

./myecho -sq “” “`

Note that -s is treated as a regular string if it is not the first string:

“`bash

./myecho Welcome to -s Linux! Welcome to -s Linux! “`

Question 8

To the version of ./myecho you wrote in the previous question, add support for the -r flag that prints the strings in reverse order. For example:

“`bash â¯ ./myecho -r Welcome to Linux! Linux! to Welcome

./myecho -r Welcome to Linux! Linux! to Welcome

./myecho -r Welcome to Linux! Linux! to Welcome

./myecho Welcome to -r Linux! Welcome to -r Linux!

./myecho -r

“`

Note that -r is treated as a regular string if it is not the first string.

Question 9

To the version of ./myecho you wrote in the previous question, add support for multiple single-character flags. For example:

“`bash

./myecho -sr a b c cba

./myecho -rqs a b c “cba”

./myecho -sh Welcome to Linux! … help message printed…

./myecho -hq Welcome to Linux! … help message printed… “`

Note that the help message is not printed in quotes because of the -q flag. The -h flag takes precedence over all other flags, and so the -q flag is ignored.

The order of multiple single-character flags does not matter. Repeated single-character flags are allowed, but ignored. For example:

“`bash

./myecho -qssq Welcome to Linux! “WelcometoLinux!”

./myecho -hhshs Welcome to Linux! … help message printed … “`

If -h is one of the flags, it always takes precedence (and any other flags/strings are ignored).

If -runtests is the first string, then the tests are run and any following flags/strings are ignored. For example:

bash â¯ ./myecho -runtests -s Welcome to Linux! running quote tests … all passed running to_string tests … all passed

Mixing -runtests with other single-character flags is not allowed and should cause an “invalid flag” error, e.g.: “`bash â¯ ./myecho -hruntests Error, invalid flag: u

… help message printed …

â¯ ./myecho -runtestsh Error, invalid flag: u … help message printed … “`

Also, if an invalid flag is passed, then print an error message, followed by the help message, and then immediately exit:

“`bash â¯ ./myecho -S Welcome to Linux! Error, unknown flag: -S … help message printed… â¯ ./myecho -qQs Welcome to Linux! Error, unknown flag: -Q … help message printed… “`

Hints

Working with a vector&lt;string&gt; is easier than working with a C-style array of strings, and so a good first step is to convert the argc command-line inputs into a vector&lt;string&gt;.

You are not required to use quote and &lt;&lt; in the implementation of myecho, but they can be useful for printing when debugging.

The logic for handling flags can get tricky, so make it as simple as possible, even if you need to sacrifice some efficiency. For this assignment, code that is easy to test and easy to read is more important than squeezing out every last drop of performance (you can improve the performance later).

The file test.sh contains a script that you can run like this:

“`bash

./test.sh … lots of output … “`

Sample correct output is in the file test.out. You can use this to help test your program. For instance in BASH (the default shell on Ubuntu) you can type this command to compare the output of your program with the correct “`bash

./test.sh &gt; out.txt diff out.txt test.out … no output means your program produced the correct output … “`

Marking Scheme

It compiles on Ubuntu Linux using the standard course makefile, e.g.:

bash $ make myecho g++ -std=c++17 -Wall -Wextra -Werror -Wfatal-errors -Wno-sign-compare -Wnon-virtual-dtor -g myecho.cpp -o myecho

If your program fails to compile, your mark for this assignment will be 0.

It has no memory leaks, according to valgrind, e.g.:

“`console $ valgrind ./myecho one two three

// … lots of output … “`

A program is considered to have no memory leaks if:

In the LEAK SUMMARY, definitely lost, indirectly lost, and possibly lost are all 0.

ERROR SUMMARY reports 0 errors.

It is usually okay if still reachable reports a non-zero number of bytes.

If valgrind reports any errors for your program, your mark for the assignment will be 0.

It includes the large comment section with student info, statement of originality, and notes to the marker, completely and correctly filled out. If your submitted file does not have this, then we will assume your work is not original, and your mark for the assignment will be 0.

All code is sensibly and consistently indented, and all lines are 100 characters in length, or less.

Whitespace is used to group related pieces of a code to make it easier for humans to read. All whitespace should have a purpose.

Variable and function names are self-descriptive.

Appropriate features of C++ are used, as discussed in class and in the notes. Note If you use a feature that we haven’t discussed in class, you must explain it in a comment, even if you think it’s obvious.

Comments are used when needed to explain chunks of code whose purpose is not obvious from the code itself. There should be no commented-out code from previous versions.

No unnecessary work is done.

No unnecessary memory is used. Source code correctness

Deductions

-1 mark (at least) if your file does not have the correct name

Submitting Your Assignment

Please submit your assignment on Canvas when it is done. Submit just your myecho.cpp file. Do not zip it, and do not submit any other files.
