This is my first official repo on GitHub

Some time ago I programmed a password generator in Python using the secrets module which
is suitable for crypto stuff. To prove it I built this 'test'.

It checks if at some point the generator repeats passwords.

The test consists of 3 main processes:

1) Generating a first password (18 characters long) and fill up a list with millions of passwords.
2) Sorting that list using the Merge Sort algorithm.
3) Searching the first password in the list using the Binary Search algorithm.

As a plus I used the time.time() method to print the time it takes the computer to  perform these processes.