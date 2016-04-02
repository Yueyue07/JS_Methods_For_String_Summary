# JS_Methods_For_String_Summary
Here is the summary of String Methods in JavaScript with the purpose for your quick reference.

<table>
  <tbody>
    <tr>
      <th>Num</th>
      <th align="center">Methods</th>
      <th align="center">Examples</th>
      <th align="center">Links(Mozilla)</th>
    </tr>
    <tr>
      <td>1</td>
      <td align="center">.fromCharCode()</td>
      <td align="left">
        <code>
          String.fromCharCode(65, 66, 67);  // "ABC"
        </code>
      </td>
      <td>
       <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/fromCharCode">Link</a>
      </td>
    </tr>
    <tr>
      <td>2</td>
      <td align="center">.charAt()</td>
      <td align="left">
        <code>
          var anyString = 'AB';
          console.log(anyString.charAt(0)); //'A'
          console.log(anyString.charAt(1)); //'B' 
        </code>
      </td>
      <td>
       <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/charAt">Link</a>
      </td>
    </tr> 
    <tr>
      <td>3</td>
      <td align="center">.charCodeAt()</td>
      <td align="left">
        <code>
          'ABC'.charCodeAt(0); // returns 65
        </code>
      </td>
      <td>
       <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/charCodeAt">Link</a>
      </td>
    </tr>  
    <tr>
      <td>4</td>
      <td align="center">.concat()</td>
      <td align="left">
        <code>
          var hello = 'Hello, ';
          console.log(hello.concat('Kevin', ' have a nice day.'));
          /* Hello, Kevin have a nice day. */
        </code>
      </td>
      <td>
       <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/concat">Link</a>
      </td>
    </tr>
    <tr>
      <td>5</td>
      <td align="center">.endsWidth()</td>
      <td align="left">
        <code>
          var str = 'To be, or not to be, that is the question.';
          
          console.log(str.endsWith('question.')); // true
          console.log(str.endsWith('to be'));     // false
          console.log(str.endsWith('to be', 19)); // true
        </code>
      </td>
      <td>
       <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/endsWidth">Link</a>
      </td>
    </tr> 
    <tr>
      <td>6</td>
      <td align="center">
        .includes()
        <br>
        <strong>str.includes(searchString[, position])</strong>
      </td>
      <td align="left">
        <code>
          'Blue Whale'.includes('blue'); // returns false
        </code>
      </td>
      <td>
       <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/includes">Link</a>
      </td>
    </tr>    
  </tbody>
</table>  
