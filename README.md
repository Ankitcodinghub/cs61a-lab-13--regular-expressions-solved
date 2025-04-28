# cs61a-lab-13--regular-expressions-solved
**TO GET THIS SOLUTION VISIT:** [CS61A Lab 13- Regular Expressions Solved](https://www.ankitcodinghub.com/product/cs61a-lab-13-regular-expressions-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119682&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS61A  Lab 13- Regular Expressions Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
Starter Files

Download lab13.zip. Inside the archive, you will find starter files for the questions in this lab, along with a copy of the Ok autograder.

Topics

Consult this section if you need a refresher on the material for this lab. It’s okay to skip directly to the questions and refer back here should you get stuck.

Regular Expressions

Regular expressions are a way to describe sets of strings that meet certain criteria, and are incredibly useful for pattern matching.

The simplest regular expression is one that matches a sequence of characters, like aardvark to match any “aardvark” substrings in a string.

However, you typically want to look for more interesting patterns. We recommend using an online tool like regexr.com or regex101.com for trying out patterns, since you’ll get instant feedback on the match results.

Character classes

A character class makes it possible to search for any one of a set of characters. You can specify the set or use pre-defined sets.

Class Description

`[abc]` Matches a, b, or c

`[a-z]` Matches any character between a and z

`[^A-Z]` Matches any character that is not between A and Z.

`w` Matches any “word” character. Equivalent to `[A-Za-z0-9_]`.

`d` Matches any digit. Equivalent to `[0-9]`.

`[0-9]` Matches a single digit in the range 0 – 9. Equivalent to `d`.

`s` Matches any whitespace character (spaces, tabs, line breaks).

`.` Matches any character besides new line.

Character classes can be combined, like in [a-zA-Z0-9].

Combining patterns

There are multiple ways to combine patterns together in regular expressions.

Combo Description

`AB` A match for A followed immediately by one for B. Example: `x[.,]y` matches “x.y” or “x,y”.

`A|B` Matches either A or B. Example: `d+|Inf` matches either a sequence containing 1 or more digits **or** “Inf”.

A pattern can be followed by one of these quantifiers to specify how many instances of the pattern can occur.

Symbol Description

`*` 0 or more occurrences of the preceding pattern. Example: `[a-z]*` matches any sequence of lower-case letters or the empty string.

`+` 1 or more occurrences of the preceding pattern. Example: `d+` matches any non-empty sequence of digits.

`?` 0 or 1 occurrences of the preceding pattern. Example: `[-+]?` matches an optional sign.

Matches the specified quantity of the preceding pattern. `{1,3}` will match from 1 to 3 instances. `{3}` will match exactly 3 instances.

`{1,3}`

`{3,}` will match 3 or more instances. Example: `d{5,6}` matches either 5 or 6 digit numbers.

Groups

Parentheses are used similarly as in arithmetic expressions, to create groups. For example, (Mahna)+ matches strings with 1 or more “Mahna”, like “MahnaMahna”. Without the parentheses, Mahna+ would match strings with “Mahn” followed by 1 or more “a” characters, like “Mahnaaaa”.

Anchors

^: Matches the beginning of a string. Example: ^(I|You) matches I or You at the start of a string.

$: Normally matches the empty string at the end of a string or just before a newline at the end of a string. Example:

(.edu|.org|.com)$ matches .edu, .org, or .com at the end of a string.

: Matches a “word boundary”, the beginning or end of a word. Example: s matches s characters at the end of words.

Special characters

The following special characters are used above to denote types of patterns:

( ) [ ] { } + * ? | $ ^ .

That means if you actually want to match one of those characters, you have to escape it using a backslash. For example, (1+3) matches “(1 + 3)”.

Using regular expressions in Python

Many programming languages have built-in functions for matching strings to regular expressions. We’ll use the Python re module in 61A, but you can also use similar functionality in SQL, JavaScript, Excel, shell scripting, etc.

The search method searches for a pattern anywhere in a string:

py re.search(r”(Mahna)+”, “Mahna Mahna Ba Dee Bedebe”)

That method returns back a match object, which is considered truth-y in Python and can be inspected to find the matching strings. If no match is found, returns None.

For more details, please consult the re module documentation or the re tutorial.

Questions

Regular Expressions

Q1: What Would RegEx Match?

For each of the following regular expressions, suggest a string that would be fully matched.

Use Ok to test your knowledge by choosing the best answer for each of the following questions:

python3 ok -q wwrm -u

A hexadecimal color code begins with # and is followed by exactly six hexadecimal numbers, which can be the digits 0-9 or letters af.

“`py Q: #[a-f0-9]{6} Choose the number of the correct choice: 0) A hexadecimal color code with 3 letters and 3 numbers 1) A hexadecimal color code that starts with letters and ends with numbers, like #gg1234 2) Any 6-digit hexadecimal color code, like #fdb515 3) Any hexadecimal color code with 0-6 digits

Q: (fizz(buzz|)|buzz) Choose the number of the correct choice: 0) Only fizzbuzz or buzz 1) Only fizzbuzzbuzz 2) Only fizz 3) Only fizzbuzz, fizz, and buzz 4) Only fizzbuzz

Q: [-+]?d*.?d+ Choose the number of the correct choice: 0) Only signed numbers like +1000, -1.5 1) Only signed or unsigned integers like +1000, -33 2) Signed or unsigned numbers like +1000, -1.5, .051 3) Only unsigned numbers like 0.051

Q: [1-9]+[05]+ Choose the number of the correct choice: 0) Any positive number 1) Numbers that are both greater than 5 and divisible by 5 like 10, 25, 800 2) Numbers that are divisible by 5 but do not have the digits 0 and 5 adjacent to each other as the last 2 digits 3) Numbers that are divisible by 5 like 5, 20, 6325 “`

Q2: Scientific Name

Returns whether the input string name follows the correct format for a scientific name. A scientific name’s format is as follows: starts with a capital letter, followed by a period (.) or a series of lowercase letters, followed by a space, followed by a series of lowercase letters. Refer to the doctests for examples of valid and invalid strings.

“`py import re

def scientific_name(name): “”” Returns True for strings that are in the correct notation for scientific names; i.e. contains a capital letter followed by a period or lowercase letters, followed by a space, followed by more lowercase letters. Returns False for invalid strings.

&gt;&gt;&gt; scientific_name(“T. rex”)

True

&gt;&gt;&gt; scientific_name(“t. rex”)

False

&gt;&gt;&gt; scientific_name(“tyrannosurus rex”)

False

&gt;&gt;&gt; scientific_name(“t rex”)

False

&gt;&gt;&gt; scientific_name(“Falco peregrinus”)

True

&gt;&gt;&gt; scientific_name(“F peregrinus”)

False

&gt;&gt;&gt; scientific_name(“Annie the F. peregrinus”)

False

&gt;&gt;&gt; scientific_name(“I want a pet T. rex right now”)

False “”” return bool(re.search(__________, name))

“`

Use Ok to test your code:

py python3 ok -q scientific_name

Q3: Calculator Ops

Write a regular expression that parses strings written in the 61A Calculator language and returns True if any expression has exactly two numeric operands. Returns False otherwise.

“`py import re

def calculator_ops(calc_str): “”” Returns True if an expression from the Calculator language that has two numeric operands exists in calc_str, False otherwise.

&gt;&gt;&gt; calculator_ops(“(* 2 4)”)

True

&gt;&gt;&gt; calculator_ops(“(+ (* 3 (+ (* 2 4) (+ 3 5))) (+ (- 10 7) 6))”) True

&gt;&gt;&gt; calculator_ops(“(* 2)”)

False

&gt;&gt;&gt; calculator_ops(“(/ 8 4 2)”)

False

&gt;&gt;&gt; calculator_ops(“(- 8 3)”)

True

&gt;&gt;&gt; calculator_ops(“+ 3 23”)

False “”” return bool(re.search(__________, calc_str))

“`

Use Ok to test your code:

py python3 ok -q calculator_ops

Q4: Roman Numerals

Return True if any string of letters that resemble a Roman numeral exists in text and aren’t part of another word. A Roman numeral is made up of the letters I, V, X, L, C, D, M and is at least one letter long.

For the purposes of this problem, don’t worry about whether or not a Roman numeral is valid. For example, “VIIIII” is not a Roman numeral, but it is fine if your regex matches it.

“`py import re

def roman_numerals(text): “”” Returns True if any string of letters that could be a Roman numeral (made up of the letters I, V, X, L, C, D, M) is found. Returns False otherwise.

&gt;&gt;&gt; roman_numerals(“Sir Richard IIV, can you tell Richard VI that Richard IV is on the phone?”) True

&gt;&gt;&gt; roman_numerals(“My TODOs: I. Groceries II. Learn how to count in Roman IV. Profit”) True

&gt;&gt;&gt; roman_numerals(“I. Act 1 II. Act 2 III. Act 3 IV. Act 4 V. Act 5”)

True

&gt;&gt;&gt; roman_numerals(“Let’s play Civ VII”)

True

&gt;&gt;&gt; roman_numerals(“i love vi so much more than emacs.”)

False

&gt;&gt;&gt; roman_numerals(“she loves ALL editors equally.”)

False “”” return bool(re.search(__________, text))

“`

Use Ok to test your code:

py python3 ok -q roman_numerals

Submit

Make sure to submit this assignment by running:

py python3 ok –submit
