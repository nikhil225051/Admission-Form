# Admission-Form
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="image/WCC3.jfif" width="10" height="10">
    <link rel="shortcut icon" href="" width="10" height="10">
    <title>CGC Login form:</title>
    <style type="text/css">
        #ik{ background-color: rgba(134, 213, 235, 0.986);}
        p{align-items: center;}
       
    </style>
</head>
<body>
    <p><img src="https://s3-us-west-2.amazonaws.com/issuewireassets/primg/54371/chandigarh-group-of-colleges-landran1865648758.png" width="1200" height="250"/></p>
    <div id="ik"><form action="mailto:nikhil7352466976@gmail.com" method ="post" enctype="text/plain">
        <fieldset>
        <legend><b>Applicant's Details:</b></legend>
        <label><b>Name of Applicant:</b> <input type="text" name="name" size="15" maxlength="30" required/></label><br/>
        <label><strong>Father's Name:</strong> <input type="text" name="father" size="15" maxlength="30" required/></label><br/>
        <label><b>Mother's Name:</b><input type="text" name="mother" size="15" maxlength="30" required/></label><br/>
        <label><b>Gender:</b><select name="gender" required>
            <option></option>
            <option value="male">Male</option>
            <option value="Female">Female</option>
            <option value="other">Other</option>
        </select></label><br/>
        <label><b>Relationship Status:</b><select name="Status">
            <option></option>
            <option value="Married">Married</option>
            <option value="Unmarried">Unmarried</option>
            <option value="Single">Single</option>
         </select></label><br/>
         <label><b>Nationality:</b><input type="text" name="country" size="10" required/></label><br/>
        <label><b>Place of Residence:</b><input type="text" name="place" size="10" maxlength="20"/></label><br/>
        <label><b>Residencial address:</b><input type="text" name="address" size="30" maxlength="50" required/></label><br/>
        <label><b>Contact no.:</b><input type="text" size=""10 required/></label><br/>
        <label><b>E-mail:</b> <input type="Email" name="email" size="15"/></label><br/>
    </fieldset>
    <fieldset>
        <legend><b>Acadmics Details:</b></legend>
        <label><b>Name of College:</b></label>
        <label for="second2">
            <input type="radio" name="college" value="CEC"  id="second2" required/>Chandigarh Engineering College </label>
        <label for="first1">
            <input type="radio" name="college" value="COE" id="first1" required/>College of Engineering
        </label><br/>
        <label><b>Campus:</b>
        <input type="checkbox" name="campus" value="Landran" />Landran(Mohali)
        <input type="checkbox" name="campus" value="Jhanjeri" />Jhanjeri
    </label><br/>
        <label><b>Course:</b><select name="course">
            <option value="b.tech">B.Tech</option>
            <option value="mba">MBA</option>
            <option value="bca">BCA</option>
            <option value="mca">MCA</option>
            <option value="pharmacy">Pharmacy</option>
            <option value="hmt">Hotel Management</option>
        </select></label><br/>
        <label><b>Branch:</b><input type="text" name="branch" size="10"/></label><br/>
        <label><b>Section:</b><input type="text" name="section" size="5" maxlength="2"/></lable><br/>
        <lable><b>CC Name:</b><input tupe="text" name="cc" maxlength="15"/></label><br/>
        <label><b>10th passing year:</b><input type="text" name="10th" maxlength="15" required/></lable>
        <label><b>Uplord 10th Marks sheet:<input type="file" name="10th marks" required/></b></label><br/>
        <label><b>12th passing year:</b><input type="text" name="passingyear" maxlength="10" required/></label>
        <label><b>Uplord 12th Marks Sheets:</b><input type="file" name="12th marks" required /></label><br/>
        <label><b>Date of Birth:</b><input type="date" name="birth" required/></label><br/>
        <label><b>Year of Addmission:</b><input type="text" name="addmission" maxlength="6"/></label>
        <label><b>Year of Passing:</b><input type="text" name="passing" maxlength="8"/></label>
    </fieldset>
|<fieldset >
    <legend><b>Reviews:</b></legend>
    <label><p><b>How is your Experience in college:</b></p><textarea name="comments" col="50" row="10">Comments:</textarea> <label>
</fieldset>
<p><input type="submit" name="Subscribe" value="Submit" required/></p>
</form>
<p><b>Pridict your name:</b>
<label for="f1">
    <input type="radio" name="pridict" value="Aman" id="f1"/>Aman</label>
<label for="f2">
    <input type="radio" name="pridict" value="Nikhil" id="f2" />Nikhil </label></p>
</div>

    
</body>
</html>
