# Code Library For Blog

Some different ways of formatting code to show on blog:

#### 1. With syntaxhighlighter:
http://www.craftyfella.com/2010/01/syntax-highlighting-with-blogger-engine.html

<pre>
<code>
1. First, take backup of your blogger template
2. After that open your blogger template (In Edit HTML mode) & copy the all css given in this link before </b:skin> tag
3. Paste the followig code before </head> tag

<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shCore.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushCpp.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushCSharp.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushCss.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushDelphi.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushJava.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushJScript.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushPhp.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushPython.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushRuby.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushSql.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushVb.js' type='text/javascript'></script>
<script src='http://syntaxhighlighter.googlecode.com/svn/trunk/Scripts/shBrushXml.js' type='text/javascript'></script>
4. Paste the following code before </body> tag.

<script language='javascript'>
dp.SyntaxHighlighter.BloggerMode();
dp.SyntaxHighlighter.HighlightAll('code');
</script>
5. Save Blogger Template.
6. Now syntax highlighting is ready to use you can use it with <pre></pre> tag.
</code>
</pre>

<pre name="code">
...Your html-escaped code goes here...
</pre>

<pre name="code" class="php">
    echo "I like PHP";
</pre>

<pre>
<code>
7. You can Escape your code here.
8. Here is list of supported language for <class> attribute.
</code>
</pre>

#### 2. Paste and copy from http://hilite.me/

#### 3. Creating a formatted area:

<pre>
 <pre style="font-family: Andale Mono, Lucida Console, Monaco, fixed, monospace; 
                color: #000000; background-color: #eee;
                font-size: 12px; border: 1px dashed #999999;
                line-height: 14px; padding: 5px; 
                overflow: auto; width: 100%">
       <code style="color:#000000;word-wrap:normal;">

            <<<<<<<YOUR CODE HERE>>>>>>>

       </code>
 </pre>
 
How to use :

Paste this snippet in text editor, paste your code in <<<<<<>>>>>> block.
Copy all and paste to HTML view in blogger(or any other) post editor.
BENEFITS : Simple and easy to use, less configuration, easy to reconfigure, no extra software
</pre>
