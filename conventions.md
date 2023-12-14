PEP 8 is the official style guide for Python code. Here are some of the most common conventions outlined in PEP 8 alongside of of our own variations:

    Indentation:
        Use 4 spaces per indentation level.

    Maximum Line Length:
        Limit all lines to a maximum of 120 characters for code and 100 for docstrings.
        For long lines, break lines using parentheses, brackets, or backslashes.

    Imports:
        Imports should usually be on separate lines and should be grouped in the following order:
            Standard library imports.
            Related third-party imports.
            Local application/library specific imports.
        Import should be grouped in sections, with a blank line between each section.

    Whitespace in Expressions and Statements:
        Avoid extraneous whitespace in the following situations:
            Immediately inside parentheses, brackets, or braces
            Immediately before a comma, semicolon, or colon.
            Immediately before the open parenthesis that starts the argument list of a function call.

    Comments:
        Comments should be complete sentences and should be used sparingly.
        Comments should be used for explanations of code when necessary.

    Naming Conventions:
        Function and variable names should be lowercase, with words separated by underscores.
        Constants should be in all capital letters with underscores separating words.
        Class names should follow the CapWords (or CamelCase) convention.

    Function and Method Arguments:
        Avoid using mutable objects as default values for function or method arguments.

    Wildcards in Import Statements:
        Avoid using wildcard imports (from module import *), except for a few specific cases.

    Whitespace Around Operators:
        Avoid extraneous whitespace around the following:
            The assignment operator (=) when used to indicate a keyword argument or a default parameter value.
            Augmented assignment operators (+=, -=, etc.).


For any other scenario that's not covered by this, please pick a convention, note it here, tell the team and stick with it 😊😊.
