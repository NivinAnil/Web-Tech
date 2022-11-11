# Form in HTML

## Form Elements/ Fields

![](Form%20Elements.PNG)
![](Form%20Elements2.PNG)
![](Form%20Elements3.PNG)

---

## Text Box

1.  Input tag is used to create textbox in the webpage.
1.  In the input tag we have specify the value of the "type" attribute as "text", o create the text box.
1.  "placeholder" attribute is used to add the placeholder to the text box or any field which is created using \<input>.
1.  "required" attribute is used to make the text box input as compulsory.
1.  "pattern" attribute is used to do the validation of the field based on the given pattern.
1.  "title" attribute is used to display the warning message based on the "pattern" attribute

#### Example I

---

<form>
   <h4>Text Box</h4>
   <label>Name</label>
   <input type="text" placeholder="First Name">
   <input type="submit">
</form>

---

#### Example II

---

<form>
   <h4>Text Box</h4>
   <label>Name</label>
   <input 
   type="text" 
   placeholder="First Name" 
   required 
   >
   <input type="submit">
</form>

---

#### Example III

---

### Pattern

- [ ] => Characters or number
- {min,max} => min and max count
- \- => one or more condition
- ^ => match the beginning
- $ => match the end

  ### Phone Number

  1.  Must be 10 digits
  1.  1<sup>st</sup> digit must be within 6 tag and the remaining 9 digit must be within in 0-9.

      ```
      "^[6-9]{9}[0-9]{9}$"
      ```

  ### example

  ```html
  <form>
    <h4>Text Box</h4>
    <label>Name</label>
    <input
      type="text"
      placeholder="First Name"
      required
      pattern="[a-zA-Z]{5,13}"
    />
    <input type="submit" />
  </form>
  <!-- phone form -->
  <form>
    <h4>Text Box : Phone Number</h4>
    <label>Ph no. : </label>
    <input
      type="text"
      placeholder="First Name"
      required
      pattern="^[6-9]{1}[0-9]{9}$"
      title="Invalid Phone Number"
    />
    <input type="submit" />
  </form>
  ```

   <form>
      <h4>Text Box</h4>
      <label>Name</label>
      <input 
      type="text" 
      placeholder="First Name" 
      required 
      pattern="[a-zA-Z]{5,13}"
      >
      <input type="submit">
   </form>
   <form>
      <h4>Text Box</h4>
      <label>Ph no. : </label>
      <input 
      type="text" 
      placeholder="First Name" 
      required 
      pattern="[6-9]{1}[0-9]{9}"
      >
      <input type="submit">
   </form>

  ***

## Email Box

<form>
   <h4>Email Box</h4>
   <label>Email : </label>
   <input 
   type="email" 
   placeholder="abc@email.com" 
   required
   >
   <input type="submit">
</form>

---

## Password Box

---

<form>
   <h4>Password Box</h4>
   <label>Password : </label>
   <input 
   type="password" 
   placeholder="" 
   required
   >
   <input type="submit">
</form>

---

## Number Box

---

<form>
   <h4>Number Box</h4>
   <label>Age : </label>
   <input type="number"  min="18" max="60"  >
   <input type="submit">
</form>

- The up arrow of the spin control in the number box will start from 1.
- The down arrow of the spin control in the number box will start from -1.
- "min" attribute is used to set the minimum count in the number box."max" attribute is used to set maximum count in the number box. spin control will set the min and max value based on the min and max attribute.
- "step" attribute is used to set the step count or incrementing and decrementing count in the number box. By default step will be 1 for incrementing and -1 for decrementing.

#### Step attribute

---

   <form>
   <h4>Number Box</h4>
   <label>Age : </label>
   <input type="number"  min="18" max="60"  step=3>
   <input type="submit">
   </form>

---

## Checkbox

---

<form>
   <h4>Checkbox</h4>
   <input type="Checkbox"><label>Java</label>
   <input type="Checkbox"><label>C</label>
   <input type="Checkbox"><label>Python</label>
   <input type="submit">
</form>

---

## Calender / Calender Box

- In the input tag "type" attribute must be specified as "date" to create "calender box" in the form.
- By default calender box will display the date in dd-mm-yyyy format.
- Using "mint' and "max" attribute we can set the minimum and maximum dates to be displayed in the calender.
- While specifying the value for min and max attribute "yyyy-mm-dd" format must be used.

  <input type="date">

### Min Max format

```html
"yyyy-mm-dd"
```

#### Example

   <input type="date" min="1999-01-01" max="2010-01-01">

---

1. Dropdown Box / Select Box
<form>
<h4>Select Country: </h4>
<label>Country</label>
<select  required >
<option >Select</option>
<option >India</option>
<option >Japan</option>
<option >UK</option>
<option >USA</option>
</select>
<input type="submit">
</form>

1. Radio Button

<input type="radio"><label>Male</label>
<input type="radio"><label>Female</label>

1. Reset Button

<input type="reset">

1. Submit Button

<input type="submit">

1. File Button

<input type="file">

1. TextArea Box

<textarea rows="4" cols="50">
This is a TextArea
</textarea>

1. Search Box

<input type="search">

1. Range Box

<input type="range" max="200" min="10">

1. Color Box

   <input type="color" >
