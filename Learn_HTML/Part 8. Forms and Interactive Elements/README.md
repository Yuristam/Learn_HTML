# Forms and Interactive Elements

## Forms

> **&lt;form&gt;** - is used to collect user input.

```
<body>
    <main>
        <form action="success.html" method="get">
            <label>Name</label>
            <input name="name">
            <label>Email</label>
            <input name="email">
            <button>Sign Up</button>
        </form>
    </main>
</body>
```

---

> **value** - this attribute is used to put default value for field

```
<label for="name">Name</label>
<input name="name" id="name" type="text"
       value="Your Name">
```

---

> **placeholder** - this attribute specifies a hint that describes the expected value of an input field
> **required** - required value

```
<label for="email">Email</label>
<input name="email" id="email" 
       type="email" required
       placeholder="me@example.com">
```

---

> **type="password"** - hides entered value in input field

```
<label for="password">Password</label>
<input id="password" name="password"
       type="password">
```

---

> **&lt;textarea&gt;** - is used to add a lot of text
> **cols** and **rows** - the size of *textarea* attribute

```               
<label for="textarea">Text Area</label>
<textarea id="textarea" name="textarea"
          cols="30" rows="15"></textarea>
```

---

> **type="file"** - this type is used to add *files*
> **accept="image/*"** - this attribute specifies the type of file
> **multiple** - allows to add multiple files  

```
<label for="file">File</label>
<input id="file" name="file" type="file"
       accept="image/*" multiple>
```

---

> **checked** - means that checkbox is checked

```
<label for="checkbox">checkbox</label>
<input id="checkbox" name="simplecheckbox"
       value="The checkbox is checked"
       type="checkbox" checked>
```

---

> **&lt;select&gt;** - is used to create a drop-down list
> **&lt;option&gt;** - tag defines an option in a select list.

```
<label for="selectlist">Choose one</label>
<select id="selectlist" name="selectlist">
    <option>First Option</option>
    <option>Second Option</option>
    <option>Third Option</option>
</select>
```

> **&lt;optgroup&gt;** - is used to group related options in a *&lt;select&gt;* element (drop-down list).

```
<label for="cars">Choose a car:</label>
<select id="cars">
  <optgroup label="Swedish Cars">
    <option value="volvo">Volvo</option>
    <option value="saab">Saab</option>
  </optgroup>
  <optgroup label="German Cars">
    <option value="mercedes">Mercedes</option>
    <option value="audi">Audi</option>
  </optgroup>
</select>
```

---

### Fieldset and legend

> **&lt;fieldset&gt;** - tag is used to group related elements in a form (draws a box around the related elements)
> **&lt;legend&gt;** - tag is used to define a caption for the *&lt;fieldset&gt;* element.

```
<fieldset>
    <legend>Checkboxes in a fieldset</legend>
    <input id="thischeck" name="checkboxlist" type="checkbox" value="This" checked>
    <label for="thischeck">This</label>
    <input id="orcheck" name="checkboxlist" type="checkbox" value="And Or">
    <label for="orcheck">And/Or</label>
    <input id="thatcheck" name="checkboxlist" type="checkbox" value="That">
    <label for="thatcheck">That</label> 
</fieldset>
```

---

## Some Input Types

`<input type="color">` - is used for input fields that should contain a color.

`<input type="checkbox">` - defines a checkbox.

`<input type="reset">` - defines a reset button that will reset all form values to their default values

`<input type="radio">` - let a user select ONLY ONE of a limited number of choices

`<input type="date">` - is used for input fields that should contain a date.

`<input type="email">` - is used for input fields that should contain an e-mail address.

`<input type="hidden">` - defines a hidden input field (not visible to a user).

`<input type="number">` - defines a numeric input field.

`<input type="range" min="0" max="50">` - defines a control for entering a number whose exact value is not important (like a slider control). Default range is 0 to 100. However, you can set restrictions on what numbers are accepted with the min, max, and step attributes.

`<input type="search">` - is used for search fields (a search field behaves like a regular text field).

`<input type="tel" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}>` - is used for input fields that should contain a telephone number.

`<input type="time">` - allows the user to select a time (no time zone).

`<input type="url">` - is used for input fields that should contain a URL address. Depending on browser support, the url field can be automatically validated when submitted. Some smartphones recognize the url type, and adds ".com" to the keyboard to match url input.
