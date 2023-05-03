Download Link: https://assignmentchef.com/product/solved-cs2211a-assignment-1
<br>
<h1>QUESTION 1 (12 marks)</h1>

On gaul, change your working directory to <strong>/bin/</strong>

Use only the <em>ls</em> Unix command to display the following <strong><em><u>file names</u></em></strong> in the <strong>/bin/</strong> directory:

<ul>

 <li>(2 marks) whose names that are of length exactly 17 characters</li>

 <li>(2 marks) whose names that have a <strong>z</strong> as the second letter (c) (2 marks) whose names that end with <strong>i</strong> or <strong>j</strong></li>

 <li>(3 marks) whose names that begin with an uppercase letter (<u>do <strong><em>not</em></strong> display any of the directory contents, if any—you</u> <u>may want to read the <em>ls</em> man pages to know how to do so</u>)</li>

 <li>(3 marks) whose names that begin with an uppercase letter other than <strong>D</strong>, or<strong> M</strong> (<u>do <strong><em>not</em></strong> display any of the directory</u> <u>contents, if any—you may want to read the <em>ls</em> man pages to know how to do so</u>)</li>

</ul>




You must include in your report the <strong><em><u>Unix command that you used in each part</u></em></strong> and the <strong><em><u>results that you got</u></em></strong> when executing the command (i.e., the list of required file names).

<strong> </strong>

<h1>QUESTION 2 (12 marks)</h1>

On gaul, accomplish the following tasks using one or two Unix commands:

(a) (2 marks) <em><u>Go to</u></em> your home directory and <em><u>create</u></em> a directory called <strong>public_html </strong>under your home directory (b) (2 marks) Display the permissions of <strong>public_html</strong>

<ul>

 <li>(1 mark) change your working directory to <strong>public_html</strong></li>

 <li>(1 mark) using <strong>touch</strong> command, create a text file called<strong> abc </strong>under the<strong> public_html </strong>directory</li>

 <li>(1 mark) change your working directory one level up (f) (1 mark) change the <strong>public_html</strong> permission to 300</li>

</ul>

(g) (4 marks) Why <strong><em><u>can</u></em></strong> you see information about <strong>abc </strong>when executing<strong> ls public_html/abc</strong> but <strong><em><u>can not</u></em></strong> you see such information when executing <strong>ls public_html</strong>? Fully explain the reason.




You must include in your report <strong><em><u>all Unix commands that you used in each part</u></em></strong> and the <strong><em><u>results that you got</u></em></strong>, if any, when executing the command

<strong> </strong>

<h1>QUESTION 3 (12 marks)</h1>

On gaul, accomplish the following tasks using one or two Unix commands:

<ul>

 <li>(2 marks) Display a list of all hidden files in your home directory (do <strong><em>not</em></strong> display any of the hidden directory contents—<u>you may want to read the <em>ls</em> man pages to know how to do so</u>) <strong><em>sorted in reverse lexicographical (alphabetical) order</em></strong> of file names that <strong>end with letters <em>rc</em></strong> —<u>you may want to read the <em>sort</em> man pages to know how to</u> <u>do so</u>.</li>

 <li>(1 mark) Use the <strong>finger</strong> command to find yourself on <strong>obelix (finger userID) </strong>and show what you will get (long format).</li>

 <li>(1 mark) Create and edit a text file in your home directory called <strong>.plan</strong> outlining some of your plans.</li>

 <li>(1 mark) Change the permissions of <strong>.plan</strong> to make it readable to everyone.</li>

 <li>(1 mark) Use the <strong>finger</strong> command again to find yourself on <strong>obelix</strong> and show what you will get.</li>

 <li>(1 mark) Change the permissions of <strong>.plan</strong> file to 600</li>

 <li>(1 mark) Use the <strong>finger</strong> command for one more time to find yourself on <strong>obelix</strong> and show what you will get.</li>

 <li>(4 marks) Did you see a different between the (b), (e) and (g) outputs? Explain</li>

</ul>




You must include in your report <strong><em><u>all Unix commands that you used in each part</u></em></strong> and the <strong><em><u>results that you got, if any,</u></em></strong> when executing the commands.

<strong> </strong>

<h1>QUESTION 4 (20 marks)</h1>

On gaul, accomplish the following tasks using Unix commands:

<ul>

 <li>(2 mark) <em><u>Go to</u></em> your home directory and <em><u>create</u></em> a directory called <strong>Working-Area</strong> under your home directory</li>

 <li>(2 marks) under <strong>Working-Area </strong>directory, <em>create</em> a sub-directory called <strong>Dir1</strong> and a text file called <strong>File1</strong></li>

 <li>(2 marks) under <strong>Dir1</strong>, <em>create</em> two directories called <strong>Dir3</strong> and <strong>Dir4</strong></li>

 <li>(2 marks) under <strong>Dir3,</strong> <em>create</em> a text file called <strong>File3</strong></li>

 <li>(2 marks) under <strong>Dir4</strong>, <em>create</em> three text files called <strong>File4</strong>, <strong>File5</strong> and <strong>File6</strong></li>

 <li>(2 marks) under <strong>Working-Area </strong>directory, <em>create</em> <strong>Dir2</strong>, a symbolic link that points to <strong>Dir1/Dir4 </strong>directory</li>

</ul>




<em>Set</em> the permissions of:

<ul>

 <li>(2 marks) <strong>Working-Area</strong> to give all permissions to the owner user, and none to others and group users</li>

 <li>(2 marks) <strong>Dir3</strong> to give all permissions to the owner user, while read and execute to group users, and none to others</li>

 <li>(2 marks) <strong>File3</strong> to give read and execute permission to others and group users, as well as all permissions to the owner</li>

 <li>(2 marks) <strong>File5</strong> to give execute permission alone to others and group users, as well as read and execute permission to the owner user</li>

</ul>




<strong>You must include in your report </strong><em><u>all Unix commands that you used</u></em>.

<strong> </strong>

<strong><u>QUESTION 5 (16 marks)</u></strong><em> to be performed on gaul </em>

(a) (2 marks) <em><u>Go to</u></em> your home directory and <em><u>create</u></em> a text file called <strong>letter.txt</strong>. Write at least 12 lines in this file, where each line will have just a number from the list {01, 02, 03, …  , 11, 12} in this order. (b) (2 marks) Display the content of <strong>letter.txt.</strong>

<ul>

 <li>(2 marks) What does the command <strong>tail -3 ~/letter.txt</strong> do and what does the command <strong>tail +3 ~/letter.txt</strong> do?</li>

 <li>(2 marks) What does the command <strong>head -3 ~/letter.txt</strong> do and what does the command <strong>head +3 ~/letter.txt</strong> do?</li>

 <li>(2 marks) What does the command <strong>who | tee ~/letter2.txt | wc -l </strong>do?</li>

 <li>(2 marks) Give the Unix command that shows the calendar for <em>November, 1955</em> (g) <em>(</em>2 marks<em>)</em> Explain the difference between <strong>cat &lt;</strong> <strong>txt</strong> and <strong>cat</strong> <strong>letter.txt</strong>.</li>

</ul>

(h) (2 marks) What does <strong>echo cat</strong> command do and what does <strong>cat</strong> <strong>echo </strong>command do?




You must include in your report <strong><em><u>all Unix commands that you used in each part</u></em></strong> and the <strong><em><u>results that you got, if any,</u></em></strong> when executing the commands.




<strong><u>QUESTION 6 (9 marks)</u></strong><em> to be performed on gaul </em>

<ul>

 <li>(3 marks) Assume that you are in your home directory and there is a directory called <strong>courses/</strong> under your home directory. Give <em>one</em> Unix command that copy all the files and directories under the <strong>courses/</strong> directory to your home directory. <strong><em>Explain whatever copying options to be used, if any. </em></strong></li>

 <li>(3 marks) Give <em>one</em> Unix command to accomplish the same task as in (a), assuming that your current working directory is not your home directory</li>

 <li>(3 marks) Give <em>one</em> Unix command that will change the permission of all files and directories under <strong>courses/ </strong>to only allow the owner to read/write/execute, but not anyone else</li>

</ul>




<strong><u>QUESTION 7 (19 marks)</u></strong><em> to be performed on gaul </em>

(a) (3 marks) Briefly explain (with examples) the Unix <em>absolute pathname</em> and <em>relative pathname</em>. (b) (1 mark) What is the <strong>./</strong> directory?

(c) (1 mark) What is the <strong>../ </strong>directory? (d) (1 mark) What is the <strong>~/</strong> directory?

<ul>

 <li><strong>(</strong>3 marks) The Unix command <strong>rmdir abc_dir</strong> fails with the message saying that the directory is not empty. On running <strong>ls abc_dir</strong>, no files are displayed. Why did the <strong>rmdir </strong>command said it is not empty?</li>

 <li>(3 marks) The Unix command <strong>cp file1 backup/file1.bak</strong> did not work even though all files exist. Name three possible reasons for such failure.</li>

 <li>(3 marks) Run the <strong>tty</strong> Unix command, and note the device name of your terminal. Now, use this device name (say, <strong>/dev/pts/6</strong>) in the Unix command <strong>cp ~/.login /dev/pts/6</strong>. What do you observe? Explain.</li>

 <li>(4 marks) If <strong>umask</strong> shows the value (i) <strong>000</strong>, (ii) <strong>002</strong>, what implication does it have from the security view point?</li>

</ul>