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

---

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
   <input type="number"  min="1" max="100" placeholder="5">
   <input type="submit">
</form>

---

1. Checkbox

<form>
   <h4>Checkbox</h4>
   <input type="Checkbox">
   <label>Language</label>
   <input type="Checkbox">
   <label>Language</label>
   <input type="Checkbox">
   <label>Language</label>
   <input type="submit">
</form>

---

1. Calender / Calender Box

<input type="date">

1. Dropdown Box / Select Box

<select name="cars" id="cars" >
<option value="volvo">Volvo</option>
<option value="saab">Saab</option>
<option value="mercedes">Mercedes</option>
<option value="audi">Audi</option>
</select>

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
