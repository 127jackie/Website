# Tables `<table>`


- Uses table tags: `<table>`
    - then Table Row: `<tr></tr>`
        - use `<tr>` for each individual table row
    - Table Header: `<th></th>`
    - Table Data: `<td>`

    ```
    <table>

        <tr>
            <th>Sunday</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>

        <tr>
            <td>Closed</td>
            <td>9-5</td>
            <td>0-5</td>
            <td>9-5</td>
            <td>9-5</td>
            <td>9-5</td>
            <td>10-2</td>
        </tr>
    </table>
    ```
    - To add a black border, in the table tag, use:
        - ```
            <table border="1" style="background-color: black;">
            ```

    - To center text and make 1st row light blue, you can use the align attribute such as 
        - ```
            <tr align="center" style="background-color: lightblue;">
            ```

    - Apply the same concept to following rows to change color

## Index Created
- [index.html](https://github.com/127jackie/Website/blob/main/week%201/Tables/index.html)

