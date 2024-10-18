# HTML : Forms and Tables

## HTML Forms

HTML forms are used to collect user input, which is then sent to a server for processing. They provide a way for users to interact with a website by entering data such as text, selecting options, or uploading files. Forms are created using the `<form>` element and contain various input elements like text fields, checkboxes, radio buttons, and submit buttons.

```html
<form action="/submit" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name"><br><br>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>

  <label for="age">Age:</label>
  <input type="number" id="age" name="age"><br><br>

  <input type="submit" value="Submit">
</form>
```

### Key attributes:
`action`: Specifies where the form data will be sent.
`method`: Defines how the data will be sent (`GET` or `POST`).
`<input>`: A versatile tag used for various input types like text, email, password, etc.

## HTML Tables

HTML tables are used to display tabular data in rows and columns. They are created using the `<table>` element and include other elements like `<tr>` (table row), `<th>` (table header), and `<td>` (table data).

```html
<table border="1">
  <thead>
    <tr>
      <th>Name</th>
      <th>Age</th>
      <th>Email</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>John</td>
      <td>28</td>
      <td>john@example.com</td>
    </tr>
    <tr>
      <td>Jane</td>
      <td>24</td>
      <td>jane@example.com</td>
    </tr>
  </tbody>
</table>
```

### Key elements:
`<table>`: Defines the table.
`<tr>`: Defines a row within the table.
`<th>`: Defines a header cell.
`<td>`: Defines a standard data cell.