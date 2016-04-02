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
    <tr>
      <td>7</td>
      <td align="center">
        .indexOf()
      </td>
      <td align="left">
        <code>
          'Blue Whale'.indexOf('Blue');     // returns  0
          'Blue Whale'.indexOf('Blute');    // returns -1
          'Blue Whale'.indexOf('Whale', 0); // returns  5
          'Blue Whale'.indexOf('Whale', 5); // returns  5
          'Blue Whale'.indexOf('', 9);      // returns  9
          'Blue Whale'.indexOf('', 10);     // returns 10
          'Blue Whale'.indexOf('', 11);     // returns 10
        </code>
      </td>
      <td>
       <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/index">Link</a>
      </td>
    </tr>  
    <tr>
      <td>8</td>
      <td align="center">
        .lastIndexOf()
      </td>
      <td align="left">
        <code>
          'canal'.lastIndexOf('a');     // returns 3
          'canal'.lastIndexOf('a', 2);  // returns 1
          'canal'.lastIndexOf('a', 0);  // returns -1
          'canal'.lastIndexOf('x');     // returns -1
          'canal'.lastIndexOf('c', -5); // returns 0
          'canal'.lastIndexOf('c', 0);  // returns 0
          'canal'.lastIndexOf('');      // returns 5
          'canal'.lastIndexOf('', 2);   // returns 2
        </code>
      </td>
      <td>
       <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/lastIndexOf">Link</a>
      </td>
    </tr> 
    <tr>
      <td>9</td>
      <td align="center">
        .match()
      </td>
      <td align="left">
        <code>
          var str = 'For more information, see Chapter 3.4.5.1';
          var re = /see (chapter \d+(\.\d)*)/i;
          var found = str.match(re);
          
          console.log(found);
           // logs [ 'see Chapter 3.4.5.1',
           // 'Chapter 3.4.5.1',
           // '.1',
           // index: 22,
           // input: 'For more information, see Chapter 3.4.5.1' ]
        </code>
      </td>
      <td>
       <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match">Link</a>
      </td>
    </tr>
    <tr>
      <td>10</td>
      <td align="center">
        .repeat()
      </td>
      <td align="left">
        <code>
          'abc'.repeat(1);    // 'abc'
          'abc'.repeat(2);    // 'abcabc'
          'abc'.repeat(3.5);  // 'abcabcabc' (count will be converted to integer)
        </code>
      </td>
      <td>
       <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/repeat">Link</a>
      </td>
    </tr>
    <tr>
      <td>11</td>
      <td align="center">
        .replace()
      </td>
      <td align="left">
        <code>
          var str = 'Twas the night before Xmas...';
          var newstr = str.replace(/xmas/i, 'Christmas');
          console.log(newstr);  // Twas the night before Christmas...
        </code>
      </td>
      <td>
       <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/replace">Link</a>
      </td>
    </tr>
    <tr>
      <td>12</td>
      <td align="center">
        .search()
      </td>
      <td align="left">
        <code>
          'ab'.search('a'); //0
          'ab'.search('b'); //1
        </code>
      </td>
      <td>
       <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/search">Link</a>
      </td>
    </tr>
    <tr>
      <td>13</td>
      <td align="center">
        .slice()
      </td>
      <td align="left">
        <code>
          var str1 = 'The morning is upon us.';
          var str2 = str1.slice(4, -2);
          
          console.log(str2); // OUTPUT: morning is upon u
        </code>
      </td>
      <td>
       <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/slice">Link</a>
      </td>
    </tr>
    <tr>
      <td>14</td>
      <td align="center">
        .split()
      </td>
      <td align="left">
        <code>
          var names = 'Harry Trump ;Fred Barney; Helen Rigby ; Bill Abel ;Chris Hand ';
          var re = /\s*;\s*/;
          var nameList = names.split(re);
          console.log(nameList); // ["Harry Trump", "Fred Barney", "Helen Rigby", "Bill Abel", "Chris Hand "]
        </code>
      </td>
      <td>
       <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/split">Link</a>
      </td>
    </tr>
    <tr>
      <td>15</td>
      <td align="center">
        .substr()
      </td>
      <td align="left">
        <code>
          var str = 'abcdefghij';
          
          console.log('(1, 2): '   + str.substr(1, 2));   // '(1, 2): bc'
          console.log('(-3, 2): '  + str.substr(-3, 2));  // '(-3, 2): hi'
          console.log('(-3): '     + str.substr(-3));     // '(-3): hij'
          console.log('(1): '      + str.substr(1));      // '(1): bcdefghij'
          console.log('(-20, 2): ' + str.substr(-20, 2)); // '(-20, 2): ab'
          console.log('(20, 2): '  + str.substr(20, 2));  // '(20, 2): '
        </code>
      </td>
      <td>
       <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/substr">Link</a>
      </td>
    </tr>  
    
  </tbody>
</table>  
