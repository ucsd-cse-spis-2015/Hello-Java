# Hello-Java
Hello World in Java

Create the file Hello.java using a text editor such as:
* gedit (available on ACMS linux machines from "Accessories" menu, last item.
* vim (see [Resources for learning vim](#Learning-Vim), below
* emacs (see [Resources for learning emacs](#Learning-Emacs), below

To compile on your ACMS account, use `javac Hello.java`, like this:

```
[spis15t7@ieng6-240]:Hello-Java:507$ javac Hello.java
[spis15t7@ieng6-240]:Hello-Java:508$ 
```

To run on your ACMS account, use `java Hello`, like this:

```
[spis15t7@ieng6-240]:Hello-Java:504$ java Hello 
Hello SPIS
[spis15t7@ieng6-240]:Hello-Java:505$ 
```

Note that when you RUN a program in Java:
* you specify the command `java` which invokes the Java Virtual Machine, and
* you follow `java` with the name of the `class` that contains the `main` method.


More preciesly, the command `java` is followed by the name of the class that contains the `public static void main(String [] args) { ... }` method).    

When we say the name of that class, we mean, the name that follows the keyword `class`, as in `class Hello { ... }`.  You do NOT use the name of a file, so `java Hello.class` is incorrect.

# <a name="Learning-Java"></a>Learning Java

Here are some resources for learning some Java on your own, either before you get to CSE 8A/11 or in addition to what you learn in CSE 8A/11:

Books: 

* <em>Head First Java, 2nd Edition</em>.   By: Kathy Sierra; Bert Bates. Publisher: O'Reilly Media, Inc. Pub. Date: February 9, 2005. Print ISBN-13: 978-0-596-00920-5
 * Read it online for free (from UCSD network connections): http://proquest.safaribooksonline.com/book/programming/java/0596009208 (From off campus, see [How to VPN, below](#How-to-VPN)
 * Buy from [Amazon](http://www.amazon.com/Head-First-Java-Kathy-Sierra/dp/0596009208), price as of 08/26/2015 is $27.44

# <a name="Learning-Vim"></a>Learning Vim

Websites: 
* A website that teaches you vim: http://www.openvim.com/
* An adventure game that teaches you vim: http://vim-adventures.com/

Books:
* <em>vi and Vim Editors Pocket Reference</em>, 2nd Edition By: Arnold Robbins Publisher: O'Reilly Media, Inc. Pub. Date: January 27, 2011 Print ISBN-13: 978-1-4493-9217-8
 * Read it online for free (from on the UCSD Campus, but only 30 simultaneous users): http://proquest.safaribooksonline.com/book/programming/vi/9781449303082
 * To read it for free from off campus, see [How to VPN](#vpn-access), below.
 * [Buy it from Amazon](http://www.amazon.com/Editors-Reference-Support-editing-Paperback/dp/B00DWYQ2OO) $9.99 as of 08/26/2015



# <a name="Learning-Emacs"></a>Learning Emacs

* This handout is great (here it is at various sizes): http://www.cs.ucsb.edu/~pconrad/images/emacsPoster/
* This site has a great collection of links to more resources: http://batsov.com/articles/2011/11/30/the-ultimate-collection-of-emacs-resources/

# <a name="How-to-VPN">How to VPN

Or, Reading books in the Safari O'Reilly library from off campus, with your UCSD login.

Above, are various URLs for books in the Safari O'Reilly library. You can read these for free from on campus, (provided no more than 30 users in the entire UC system are accessing the library.)

If you are off campus, though, you either won't be able to see the full content, OR, you might be asked to create  a personal account which requires a credit card.   You probably don't want to have to pay for this access, since the University of California already paid for it, and its included in your tuition. 

The solution is a VPN or Proxy connection. VPN stands for "Virtual Private Network".  It is a way of making it "appear" that you are on the UCSD network, when you are in fact, connected to some other network.

A true VPN to the UCSD network requires you to [install software on your computer](http://blink.ucsd.edu/technology/network/connections/off-campus/VPN/).    An easier way is to use a proxy server&mdash;that does NOT require you to install anything.  You just use an intermediate web site.  Here's how:

* Navigate to: https://vpn-2.ucsd.edu/ and login with your UCSD username and password 
* Paste the URL for the bookabove into the box that looks like this, and click "browse" ![/images/VPN.url.bar.png](/images/VPN.url.bar.png)
