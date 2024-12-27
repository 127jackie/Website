 # Lists `<li>`
 
 - Lists `<li>`:
      - *use type of list, then nest `<li>`
      - 3 different kinds of lists:
        - Unordered List `<ul>` (ex: grocery list)
        - Ordered List `<ol>` (numbered, ex: to do list)
        - Description List  `<dl>` (key value paris, ex: term & definition)
          - description lists need **terms**, `<dt>`
            - **definition descrpition** (`<dd>`) can be added under terms 
          ```
           <!-- Description List-->
            <h4></h4>
            <dl>
              <dt>dragon</dt>
              <dd>a mythical monster resembling a giant reptile, sometimes shown as having wings. In European tradition the dragon is typically fire-breathing and tends to symbolize chaos or evil, whereas in East Asia it is usually a beneficent symbol of fertility, associated with water and the heavens.</dd>
            </dl>
          ```

      - can create nested lists
        ``` 
          <!-- Unordered List-->
            <h4>Groceries</h4>
            <ul>
                <li>milk</li>
                <li>egges </li>
                <li>bread</li>
                <li>coffee supplies</li>
                <ul>
                    <li>coffee beans</li>
                    <li>sugar</li>
                    <li>sugar</li>
               </ul>
              </ul> 
         ```
