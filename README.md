<h2 style="text-align: center;">Stage 1/4: A needle in the hay</h2>

<h2 style="text-align: center;">Description</h2>

<p>Ever see a huge 2000+ page book full of various organizations and people, written with a small font and with multiple columns on each page? If you’re unprepared, it's an impossible task to find the information you need. In fact, even computers can struggle with the task of searching among millions of entries from the start of the directory to its end.</p>

<p>Various algorithms can perform tasks differently; some are slower than others. In this project, you will implement several algorithms and compare the time efficiency among them using a big dataset.</p>

<p>Then you need to download the file <a target="_blank" href="https://stepik.org/media/attachments/lesson/197761/directory.txt" rel="nofollow noopener noreferrer">directory.txt</a>. This file contains over a million people’s phone numbers in multiple cities.</p>

<p>In this stage, you should implement the simplest search and find numbers for the people listed in the file <a target="_blank" href="https://stepik.org/media/attachments/lesson/197761/find.txt" rel="nofollow noopener noreferrer">find.txt</a>.</p>

<p>Note how long it takes you to do this by a linear search so you can compare results with other search methods.</p>

<p>To measure time difference you can use <code class="java">System.currentTimeMillis()</code>.</p>

<p>Also notice, that you don't need to read the file "directory.txt" again after each query. You should load all  lines into memory and measure only the search process.</p>

<p><div class="alert alert-warning">Please, do not keep the downloaded files inside your project directory because the server can reject large files and you will see the message <strong>"Failed to post submission to the Hyperskill"</strong>.</div></p>

<h2 style="text-align: center;">Example</h2>

<p>Below is an example of how should look your output:</p>

<pre><code class="java">Start searching...
Found 500 / 500 entries. Time taken: 1 min. 56 sec. 328 ms.</code></pre>