# Forms `<form>`
- Uses form tags, `<form>`
- form attributes need to be filled in
    - action, after form is submitted, where should it be sent to?
        - usually `.php` file
    - method attribute
        - specifies if `GET` or `POST` request
        - `POST` is used for confidential information (ex, username password)
        - `GET` is for insensitive data
- Elements in form:
    - **textbox**, self closing `<input>` tag
        - text is default
        - other types such as passwords, emails, numbers
    - **`<label>`** can be used to let user know what should go in the input box
    - **for** attribute is helpful for visualally impaired users
        - Additionally, when clicking the **label** curser moves to the text box
            - needs mattching id attribute withint input tag (*needs to be the same as the for tag)
        - ```
            <label for="Username">Username:</label>
            <input type="text" id="Username">
            ```
    - Creating a **submit** button
        - ```
            <input type="submit">
            ```
    
    - More attributes can be used such as **max/minimum length** and if input is **required**
        - ```
            <input type="text" id="Username" minlength="6" maxlength="15" required>
    - **Resetting**
        - ```
             <input type="reset">
            ```
    - **Placeholder**
        - used to give a guide to the user (ex, following the formatt required)
            - ```
                <input type="text" id="Username" placeholder="Spongebob" minlength="6" maxlength="15" required>
                ```
    - **Password**
        - follows the same concept as username
        - when typing password, input is hidden
            - ```
                <label for="password">password:</label> 
                <input type="password" id="password">
                ```
    - **Email** and **Phone Number**
        - Email and Phone Number follow the same format as password and username.
        - In Phone Number
            - uses "tel" as input type
                - `<input type="tel">`
            - you can use a **pattern** attribute to follow a certain or required format. For example, phone numbers in the US use 6 digits following the pattern 3 digits - 3 digits - 4 digits
            - ```
                <label for="phone">Phone #:</label>
                <input type="tel" id="phone" placeholder="123-456-7890" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}">
                ```
    - **Date/Birthdate**
        - uses "date" as input type
            - `<input type="date">`
        - interative calendar is displayed
        - ```
            <label for="birthdate">Birthdate</label>
            <input type="date" id="birthdate">
            ```
    - **Number** (Quantity)
        - uses "number" as input type
            - `<input type="number">`
        - interactive arrows are shown to display amount (up for increase, down for decrease)
        - since number can go into negatives, a condition can be added for the **maximum** or **minimum** 
            - ```
                <label for="quantity">Quantity:</label>
                <input type="number" id="quantity" min="0" max="99">
                ```
    - **Radio**
        - these are used to select from a list, for example, the title of a person (Mr., Mrs., Miss, etc.)
        - A label is created followed by the input type "radio"
            - ```
                <label for="title">Title:</label>

                <input type="radio" id="Mr." value="Mr." name="title">
                <label for="Mr.">Mr.</label>

                <input type="radio" id="Mrs." value="Mrs." name="title">
                <label for="Mrs.">Mrs.</label>

                <input type="radio" id="PhD" value="PhD" name="title">
                <label for="PhD">PhD</label>
                ```
    - **Dropdown**
        - 