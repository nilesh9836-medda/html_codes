# 05. Tables

*The HTML &lt;table&gt; element allows web authors to display tabular data (such as text, images, links, other tables, etc.) in a two dimensional table with rows and columns of cells.*

- ## Simple Table

    ```html
    <body>
        <table>
            <tr>
                <th>Heading 1/Column 1</th>
                <th>Heading 2/Column 2</th>
            </tr>
            <tr>
                <td>Row 1 Data Column 1</td>
                <td>Row 1 Data Column 2</td>
            </tr>
            <tr>
                <td>Row 2 Data Column 1</td>
                <td>Row 2 Data Column 2</td>
            </tr>
        </table>
    </body>
    ```

    *[Click Here to see the output](./simple-table.html)*

- ## Spanning columns or rows

    ```html
    <body>
        <table>
            <tr>
                <td>row 1 col 1</td>
                <td>row 1 col 2</td>
                <td>row 1 col 3</td>
            </tr>
            <tr>
                <td colspan="3">This second row spans all three columns</td>
            </tr>
            <tr>
                <td rowspan="2">This cell spans two rows</td>
                <td>row 3 col 2</td>
                <td>row 3 col 3</td>
            </tr>
            <tr>
                <td>row 4 col 2</td>
                <td>row 4 col 3</td>
            </tr>
        </table>
    </body>
    ```

    *[Click Here to see the output](./table-spanning.html)*

- ## Table with thead, tbody, tfoot, and caption

    ```html
    <body>
        <table>
            <caption>Table Title</caption> <!--| caption is the first child of table |-->
            <thead> <!--======================| thead is after caption |-->
                <tr>
                    <th>Header content 1</th>
                    <th>Header content 2</th>
                </tr>
            </thead>
            <tbody> <!--======================| tbody is after thead |-->
                <tr>
                    <td>Body content 1</td>
                    <td>Body content 2</td>
                </tr>
            </tbody>
            <tfoot><!--| tfoot can be placed before or after tbody, but not in a group of tbody. |-->
            <!--| Regardless where tfoot is in markup, it is rendered at the bottom. |-->
                <tr>
                    <td>Footer content 1</td>
                    <td>Footer content 2</td>
                </tr>
            </tfoot>
        </table>
    </body>
    ```

    *[Click Here to see the output](./Table.html)*

- ## Heading scope

    ```html
    <body>
        <table>
            <thead>
                <tr>
                    <td></td>
                    <th scope="col">Column Heading 1</th>
                    <th scope="col">Column Heading 2</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <th scope="row">Row Heading 1</th>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <th scope="row">Row Heading 1</th>
                    <td></td>
                    <td></td>
                </tr>
            </tbody>
        </table>
    </body>
    ```

    *[Click Here to see the output](./heading-scope.html)*
