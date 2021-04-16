# pythonstylesf

My (SF) own coding style for Python, to help me collaborate with past-me and future-me.

# Preamble

Adapted for my own situation, such as the devices I usually use, the screen size, the Python version I need to use
(can be as old as 3.4 for some reasons), and my not-so-good memory. If it is good for me, it is good.

# General Principles

Simple and (generally) consistent.

# Naming

## Case

Use **lowercase letters**. Use uppercase letters when it is really, really natural (to me) to use the uppercase letters.
Should (nearly) never use CamelCase.

```
a = 1
b = [1, 2, 3]
```

## Underscore

Use underscore only to separate words. Do not use dot (`.`) and do not use hyphen (`-`), unless it is really, really natural to do so.

```
this_is_a_long_name = dict([["a", 1], ["b", 2]])
```

## Length

Long names are OK with me. It is more important to know quickly what a variable is then to type less.

# Strings

Use double quotes, unless there are double quotes in the string.

```
a = "Hello"
b = '"Hello"'
```

# Identation

Use four spaces (usually). I use two spaces if it can improve readability.

```
if a is None:
    print("a is None")
```

# Align in a readable way

That is ... align in anyway I want.

```
def hello_world(
      arg_1,
      arg_2a, arg_2b,
      arg_3
      ):
    print(arg_2b)
```

# Line Length

70 for code. I sometimes work on a small screen. For comments, 70 if possible but it is not a must.

# Whitespace

Always add at least one whitespace before and and one whitespace after an operator, including `=`.

```
3 + 2
5 * 4
a = 10
```

For me, it is OK to add more whitespaces to align elements. It is easier for me to detect typo errors that lead to inconsistent alignment.

```
a     = 1
b     = 2
candd = 3
```
