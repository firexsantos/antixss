# antixss
Anti Cross Site Scripting (XSS) Injection

<h2>How to use?</h2>
Just add antixss(...) function to any post or get variable.
<br>
<br>
<b>Example in Native PHP:</b><br>
antixss($_GET['yourparameter']);
antixss($_POST['variable']);
<br><br>
<b>Example in Code Igniter:</b><br>
$post = $this->input->post();
antixss($post['yourvariable']);
