So, first off, we're presented with a "super secure portal". I'd expect to find some plaintext key or partial key, which is the password, with a few tweaks. Or maybe a cookie password?

Okay, let's of course inspect it, check the javascript...and it's pretty clear we can see parts of the flag visible here:

<img width="602" height="533" alt="image" src="https://github.com/user-attachments/assets/f05f0bc6-ccfc-490e-b254-04f5e588adf4" />

So, let's count the splits, from 0 to 8, combine the strings, and get our result! Easy victory!
