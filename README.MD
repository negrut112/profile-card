# My-Profile-card

<p>A simple profile-card containig a short intro about me, a nice background and posibilities how to get in contact with me with help of HTML and CSS.</p>

<p>My profile-card link: <a href="https://negrut112.github.io/profile-card/">https://negrut112.github.io/profile-card/</a></p>
<img src="https://i.imgur.com/YKV65fN.png">

## HTML
<p>First thing I did, was to prepare the framework containing: name and proffesion, location, two short paragraphs, contact icons with their links and two images.<br>
Along this, inside the head tags I added external links one for bootstrap library and another for CSS file.</p>
<p>Below you can see the framework:</p>

<pre><code>
&lt;div class=“profile-card”&gt;<br>
&lt;div class=“head”&gt;<br>
&lt;div class=“profile-image”&gt;&lt;img src=&quot;<a href="https://i.imgur.com/YwNQquU.jpg">https://i.imgur.com/YwNQquU.jpg</a>&quot; alt=“My profile picture”&gt;&lt;/div&gt;<br>
&lt;div class=“name-headline”&gt;<br>
&lt;h1&gt;Alin Negrut&lt;/h1&gt;<br>
&lt;h2&gt;Profession:Manufacturing Engineer&lt;/h2&gt;<br>
&lt;span&gt;location: &lt;i class=“fa fa-map-marker”&gt;&lt;/i&gt; Bucharest, România&lt;/span&gt;<br>
&lt;/div&gt;<br>
&lt;/div&gt;<br>
&lt;div class=“content”&gt;<br>
&lt;div class=“about”&gt;<br>
&lt;p&gt;I’m very passionate person about Engineering and Information Technology, due to my decisions to study Engineering – department of Machine Building Technology and lately I’ve just completed an online course named: “CodeBerry Programming School” 2018 - 2019  &lt;/p&gt;<br>
&lt;br&gt;<br>
&lt;p&gt;Right now you can find me on Slack discussing about programming, or if u are interested<br>
in my work you can check on &lt;a href=&quot;<a href="https://github.com/negrut112">https://github.com/negrut112</a>“&gt;GitHub.&lt;/a&gt; &lt;/p&gt;<br>
&lt;/div&gt;<br>
&lt;section class=“section-links”&gt;<br>
&lt;h2&gt;Contact me via:&lt;/h2&gt;<br>
&lt;ul&gt;<br>
&lt;li&gt;&lt;a  href=”<a href="https://www.facebook.com/alin.negrutz">https://www.facebook.com/alin.negrutz</a>&quot;&gt;Facebook &lt;i class=“fa fa-facebook-square”&gt;&lt;/i&gt;&lt;/a&gt;&lt;/li&gt;</p>
&lt;li&gt;&lt;a href=&quot;https://www.linkedin.com/in/alin-negrut-872b79129/&quot;&gt;Linkdin &lt;i class=&quot;fa fa-linkedin&quot;&gt;&lt;/i&gt;&lt;/a&gt;&lt;/li&gt;
        &lt;li&gt;&lt;a href=&quot;&quot;&gt;Google+ &lt;i class=&quot;fa fa-google-plus-square&quot;&gt;&lt;/i&gt;&lt;/a&gt;&lt;/li&gt;
       &lt;/ul&gt;
    &lt;/section&gt;
  &lt;/div&gt;
&lt;/div&gt;
</code></pre>

## CSS

<p>Here I customized the profile image, giving it a circle shape and a transition effect when you put the mouse over it. I styled the body content as well manipulating its elements like item alignment or background properties.</p>

<pre><code>body {<br>
height: 100vh;<br>
display: flex;<br>
align-items:center;<br>
justify-content: center;<br>
background: url(’<a href="https://i.imgur.com/FktX2Kf.jpg">https://i.imgur.com/FktX2Kf.jpg</a>') no-repeat center center fixed;<br>
background-size: cover;<br>
}</p>
<p>img {<br>
width: 116px;<br>
height: 106px;<br>
border-radius: 50%;<br>
padding: 1px;<br>
background-color: #666;<br>
transition: all 0.5s ease-in-out;<br>
}</code></pre>
