# Anti XSS Injection for PHP
Anti Cross Site Scripting (XSS) Injection. A very powerful tool to counteract XSS Injection. It has been proven so far that it is still very reliable for dealing with XSS Injection problems.

<h2>How to use?</h2>
Just add antixss(...) function to any post or get variable.
<br>
<br>
<b>Example in Native PHP:</b><br>
antixss($_GET['yourparameter']);
antixss($_POST['variable']);
<br><br>
<b>Example in Code Igniter:</b><br>
$post = $this->input->post();<br>
antixss($post['yourvariable']);
