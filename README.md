<h1 class="gap">0x03. Git</h1>


<h4 class="task">
    0. Create and setup your Git and Github account
      <span class="alert alert-warning mandatory-optional">
        mandatory
      </span>
</h4><p>Git is installed on your iMac provided by Holberton, but if you’re using another computer, you might have to <a href="/rltoken/n2SJyaVuu1tuhVgHSKw5Sg" target="_blank" title="install it">install it</a> yourself.</p><ul>
<li>As a Holberton School student, you are eligible to get a GitHub student developer pack, with some nice goodies. Get you pack here: <a href="/rltoken/dKUO2Nc6zsvQaH-RoDqs1w" target="_blank" title="https://education.github.com/pack">https://education.github.com/pack</a></li>
<li>Configure the basics you need on your local account that will be part of your commits: your name, your email. <a href="/rltoken/WCZwvMlDTWNwo7D2h5RXiw" target="_blank" title="Tips">Tips</a></li>
</ul><p>In Github.com:</p><ul>
<li>Create your first repository (please use the graphical interface)

<ul>
<li>name: <code>my_first_repository</code></li>
<li>description: <code>I'm now a Holberton Student, it's my first repository as a full-stack engineer</code></li>
<li>public</li>
<li>no Readme, .gitignore or license</li>
</ul></li>
</ul><p>In your computer, open a terminal to:</p><ul>
<li>navigate to your home/login directory. <a href="/rltoken/nSl91LBC_er1QmayRs60Rg" target="_blank" title="Tips">Tips</a></li>
<li>create a directory <code>my_first_repository</code>. <a href="/rltoken/qE0DHC3e86f7eZF6mlqFyQ" target="_blank" title="Tips">Tips</a></li>
<li>navigate to this new directory. <a href="/rltoken/AwnQVywazMoVHb1fj85DAw" target="_blank" title="Tips">Tips</a></li>
<li>initialize git and add the remote origin</li>
<li>create a file <code>README.md</code> with Emacs (or other command line editors) and write a small <a href="/rltoken/3ZODVIGFqknARuxa8HXC7A" target="_blank" title="Markdown">Markdown</a> text to present this project. <strong>This file is mandatory in all Holberton School projects</strong></li>
<li>add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin (you will probably need to set your login/password to push to the remote server)</li>
</ul><p>Good job! </p><p>You did your <strong>push</strong> in your <strong>first repository</strong> of your <strong>first task</strong> of your <strong>first Holberton School project</strong>.</p>


<h4 class="task">
    1. Coding fury road
      <span class="alert alert-warning mandatory-optional">
        mandatory
      </span>
</h4><p>For the moment we have an empty project, only the description with the <code>README.md</code>, it’s time to code!</p><ul>
<li>create these directories at the root of your project: <code>bash</code>, <code>c</code>, <code>js</code> </li>
<li>create empty files:

<ul>
<li><code>c/c_is_fun.c</code></li>
<li><code>js/main.js</code></li>
<li><code>js/index.js</code></li>
</ul></li>
<li>create a file <code>bash/holberton</code> with inside these two lines: <code>#!/bin/bash</code> and <code>echo "Holberton"</code></li>
<li>create a file <code>bash/school</code> with inside these two lines: <code>#!/bin/bash</code> and <code>echo "School"</code> </li>
<li>add all these new files to git</li>
<li>commit your changes (message: “I’m starting to code, so cool”) and push to the remote server</li>
</ul>


<h4 class="task">
    2. Collaboration is the base of a company
      <span class="alert alert-warning mandatory-optional">
        mandatory
      </span>
</h4><p>A branch is like a copy of your project. It’s used mainly for:</p><ul>
<li>to not breaking your repository</li>
<li>to add a feature in development</li>
<li>collaboration on the same project with someone else</li>
<li>to not upset your co-worker</li>
</ul><p>The goal of a branch is to isolate your work with the main code of your project or with coworker’s work.</p><p>For your first project, you will create a branch <code>update_script</code> and in this branch you will:</p><ul>
<li>create an empty file <code>bash/98</code></li>
<li>update <code>bash/holberton</code> by replacing <code>echo "Holberton"</code> by <code>echo "Holberton School"</code></li>
<li>update <code>bash/school</code> by replacing <code>echo "School"</code> by <code>echo "The school is open!"</code></li>
<li>add and commit these changes (message: “My personal work”)</li>
<li>push this new branch. <a href="/rltoken/DUQcoJJ7Lowt4sieJqVEdg" target="_blank" title="Tips">Tips</a></li>
</ul><p>Perfect! you did an amazing update in your project and it’s isolated correctly from the <strong>master</strong> branch. </p><p>Ho wait, your manager needs a quick fix in your project and it should be deployed now:</p><ul>
<li>change branch to <code>master</code></li>
<li>update the file <code>bash/holberton</code> by replacing <code>echo "Holberton"</code> by <code>echo "Holberton School is so cool!"</code></li>
<li>delete the directory <code>js</code></li>
<li>commit your changes (message: “Hot fix”) and push to the origin</li>
</ul><p>Ouf, hot fix is done!</p>


<h4 class="task">
    3. Collaboration: be up to date
      <span class="alert alert-warning mandatory-optional">
        mandatory
      </span>
</h4><p>Of course, you can also work on the same branch as your co-workers and it’s better for you to be up to date with their changes.</p><p>For this task, <strong>and only for this task</strong>, please update your file <code>README.md</code> in the master branch from Github.com. It’s the <strong>only time</strong> you are allowed to update and commit from Github interface.</p><p>When it’s done, in your terminal:</p><ul>
<li>get locally all changes of the master branch (your <code>README.md</code> file will be updated)</li>
<li>write in a file <code>up_to_date</code> (at the root of your repository) the git command line used</li>
<li>add this new file <code>up_to_date</code>, commit (message: “How to be up to date in git”) and push to the origin</li>
</ul>


<h4 class="task">
    4. HAAA what did you do???
      <span class="alert alert-info mandatory-optional">
        #advanced
      </span>
</h4><p>Collaboration is cool, but not really when you update the same file at the same line…</p><p>To illustrate that, please merge the branch <code>update_script</code> to <code>master</code>: “Cool, all my changes will be now part of the main branch, ready to be deploy!”</p><p><strong>HHHHHHHAAAAAAAA</strong></p>


<h4 class="task">
    5. Never push too much
      <span class="alert alert-info mandatory-optional">
        #advanced
      </span>
</h4><p>Create a <code>.gitignore</code> file and define a rule to never push <code>~</code> files (generated by Emacs). <a href="/rltoken/0ANsyvhObT_TYAToY8-lbA" target="_blank" title="Tips">Tips</a></p>

