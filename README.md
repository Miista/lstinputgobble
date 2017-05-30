# lstinputgobble

Allows you to specify a number of spaces to gobble from every line in
an `lstinputlisting`.

Why this?
The package `listings` already provide a `gobble` option.

Yes, but this option does not work on `lstinputlisting`s, unfortunately.
The option provided by this package does!

# Usage

Simply include the option when issuing the command.

    \lstinputlisting[widthgobble=2]{some/file.ext}

Sometimes it doesn't work as expected.
This is most likely because `tabsize` has not been set.
Setting it to 1 or 2 should do the trick.
If not, try playing around with it.

# Acknowledgements

All code is by Jonas Nyrup found in [this StackOverflow question](https://tex.stackexchange.com/questions/48903/how-to-extend-the-lstinputlisting-command).
This repo exists so that you can clone it and include the file directly in your preamble.
