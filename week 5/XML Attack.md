<h1> XXE Pentesting</h1>  

<p><pre><h2>1. XXE XML Entity Injection</h3>
<h4>1. Testing Viewable Injection</h4> 
      1. Search for api end points and change Content-Type to 
      <b>application/xml</b> 
        or 
      <b>text/xml</b> 
      and see if it is accepting xml.
      2. check if we can use internal entities.
      3. Check if we can use external entities using system keyword.
      4. inject into viewable parameter.
   
   
<h4>2. Testing Unviewable Injection</h4> 
      1. Search for api end points and change Content-Type to 
      <b>application/xml</b> 
        or 
      <b>text/xml</b> 
      and see if it is accepting xml.
      2. check if we can use internal entities.
      3. Check if we can use external entities using system keyword.
      4. send data to our out band server.</pre></p> 
    
<pre><h2>2. Simple Way to test XXE.</h3></pre>  
    
<pre><h2>3. Learn more indepth about xxe by labs on web-security by portswigger xxe exercise.</h3></pre>  