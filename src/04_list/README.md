# 04. List

HTML oﬀers three ways for specifying lists: ordered lists, unordered lists, and description lists. Ordered lists use
ordinal sequences to indicate the order of list elements, unordered lists use a deﬁned symbol such as a bullet to list
elements in no designated order, and description lists use indents to list elements with their children.

- ## Unordered List

    ```html
    <body>
        <h2>This is an unordered list</h1>
        <ul>
            <li>list 1</li>
            <li>list 2</li>
            <li>list 3</li>
        </ul>

        <h3>Change list type</h3>
        <ul type="square">
            <li>list 1</li>
            <li>list 2</li>
            <li>list 3</li>
        </ul>
        <ul type="disc">
            <li>list 1</li>
            <li>list 2</li>
            <li>list 3</li>
        </ul>
        <ul type="circle">
            <li>list 1</li>
            <li>list 2</li>
            <li>list 3</li>
        </ul>
    </body>
    ```

    *[Click here to see the output](./01list-ul.html)*

- ## Ordered List

    ```html
    <body>
        <h2>This is an ordered list</h2>
        <ol>
            <li>List 1</li>
            <li>List 2</li>
            <li>List 3</li>
        </ol>

        <h3>Manually changing number</h3>
        <ol start="3">
            <li>list 1</li>
            <li>list 2</li>
            <li>list 3</li>
        </ol>

        <ol>
            <li>List 1</li>
            <li>List 2</li>
            <li>List 3</li>
            <li value="1">Reset</li>
            <li>List 5</li>
            <li>List 6</li>
        </ol>

        <h3>Change list type</h3>
        <ol type="A">
            <li>List 1</li>
            <li>List 2</li>
            <li>List 3</li>
        </ol>
        <ol type="a">
            <li>List 1</li>
            <li>List 2</li>
            <li>List 3</li>
        </ol>
        <ol type="i">
            <li>List 1</li>
            <li>List 2</li>
            <li>List 3</li>
        </ol>
        <ol type="I">
            <li>List 1</li>
            <li>List 2</li>
            <li>List 3</li>
        </ol>
        <ol type="1">
            <li>List 1</li>
            <li>List 2</li>
            <li>List 3</li>
        </ol>
    </body>
    ```

    *[Click here to see the output](./02list-ol.html)*

- ## Nested List

    ```html
    <body>
        <h2>Nested Unordered List</h2>
        <ul>
            <li>list 1</li>
            <li>list 2</li>
                <li>sub-list 1</li>
                <li>sub-list 2</li>
                <li>sub-list 3</li>
            <li>list 3</li>
        </ul>

        <h2>Nested Ordered List</h2>
        <ol>
            <li>list 1</li>
            <li>list 2</li>
                <li>sub-list 1</li>
                <li>sub-list 2</li>
                <li>sub-list 3</li>
            <li>list 3</li>
        </ol>
    </body>
    ```

    *[Click here to see the output](./03list-nested.html)*

- ## Description List

    A description list or definition list, as it was called before HTML5

    ```html
    <body>
        <h2>This is a Description List</h2>
        <dl>
            <dt>name 1</dt>
            <dt>name 2</dt>
            <dd>value for 1 and 2</dd>
            
            <dt>name 3</dt>
            <dd>value for 3</dd>
            <dd>value for 3</dd>
        </dl>
    </body>
    ```

    *[Click here to see the output](./04list-desc.html)*
