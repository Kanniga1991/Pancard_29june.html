# Pancard_29june.html
the pan card form application using html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pan_Card Application Form</title>
    <style>
span{
    color:red;
}
table,th,td{
    border: 1px solid black;
    border-collapse: collapse;
}
*{
    margin:0px;
}

    </style>
    


</head>

<body>
  <div style = "background-color: rgb(204, 204, 146);">
  <div style = "background-color: orange; color:white;">
    <h4 style="text-align: center;">Request for New Pan Card /and Changes or Correction in Pan Data</h4>
    <p style="font-style: italic;font-weight: lighter; text-align: center;">Fields marked with <span>*</span>(asterik) are mandatory. To avoid mistakes please refer <span>guidelines and instructions</span></p>
</div>

<div style = "font-weight: bold;">
    <table width="100%">
        <tr>
            <td></td>
            <td>
            <span>*</span>Whether Citizen Of India
            <label for="ye" style="padding-left: 90px;font-weight: lighter;">Yes</label>
            <input type="radio" name ="" id = "ye">
            <label for="na" style="padding-left: 30px;font-weight: lighter;">No</label>
            <input type="radio" name ="" id = "na">
            </td>
        </tr>
        <tr>
            <td style="width:1% ;padding : 5px;"><input type="checkbox" name="" id=""></td>
            <td> 
            1. Name
            </td>
        </tr>
        <tr>
            <td></td>
            <td>
                Title 
                <label for="mr" style="padding-left: 40px;font-weight: lighter;">Shri/Mr</label>
                <input type="radio" name ="" id="mr">
                <label for="mrs" style="padding-left: 40px;font-weight: lighter;">Smt/Mrs</label>
                <input type="radio" name ="" id="mrs">
                <label for="ms" style="padding-left: 40px;font-weight: lighter;">Kumari/Ms</label>
                <input type="radio" name ="" id="ms">
            </td>
        </tr>
        <tr>
            <td></td>
            <td>
                <div style="width: auto;">
                <div style="display: inline-block;">
                    <label for="surname"> Last Name/Surname</label><br>
                    <input type="text" name = "" id="surname" >
                </div>
                <div style="display: inline-block; padding-left: 300px;">
                    <label for="firstname" > First Name</label><br>
                    <input type="text" name = "" id="firstname" >
                </div>
                <div style="display: inline-block; padding-left: 300px;">
                    <label for="midname" > Middle Name</label><br>
                    <input type="text" name = "" id="midname" >
                </div>
                </div>
             </td>
        </tr>
        <tr>
            <td></td>
            <td>
                <label for="nameoncard" > <span>*</span>Name as you would like it printed on the card
                <label for ="nameoncard" style="color: blue;">(Prefix like Shri, Smt, Kumari, Late, Dr, CA, Ms, Mr, Mrs, M/s, Alias etc are not allowed)</label><br>
                <input type="text" name = "" id="nameoncard"style="padding-left: 150px;" > 
            </td>
        </tr>
        <tr>
            <td></td>
            <td>
                Details of the Parents.
                <label for ="parentdetails" style="color: blue;">(Prefix like Shri, Smt, Kumari, Late, Dr, CA, Ms, Mr, Mrs, M/s, Alias etc are not allowed)</label><br>    
            </td>
        </tr>
        <tr>
            <td></td>
            <td>
                Whether mother is single parent and you wish to apply for PAN by furnishing the name of your<br> 
                mother only
            </td>
            <td>
                <label for="ye">Yes</label>
                <input type="radio" name = "" id="ye">
                <label for="na">No</label>
                <input type="radio" name = "" id="na">
                
            </td>
        </tr>
        <tr>
            <td style="width:1% ;padding : 5px;"><input type="checkbox" name="" id=""></td>
        <td>
            <span>*</span>Father's Name
            <label for="fathername" style="color: blue;">(Mandatory field. Even married women should give fathers only)
        </td>
        </tr>
        <tr>
            <td></td>
            <td>
                <div style="width: auto;">
                    <div style="display: inline-block;">
                        <label for="surname"> Last Name/Surname</label><br>
                        <input type="text" name = "" id="surname">
                    </div>
                    <div style="display: inline-block; padding-left: 300px;">
                        <label for="firstname" > First Name</label><br>
                        <input type="text" name = "" id="firstname" >
                    </div>
                    <div style="display: inline-block; padding-left: 300px;">
                        <label for="midname" > Middle Name</label><br>
                        <input type="text" name = "" id="midname" >
                    </div>
                    </div>
            </td>
        </tr>
        <tr>
            <td style="width:1% ;padding : 5px;"><input type="checkbox" name="" id=""></td>
        <td>
            <label for="mothersname" style="color: blue;">Mother's Name(This field is Optional)</label>
        </td>
        </tr>
        <tr>
            <td></td>
            <td>
                <div style="width: auto;">
                    <div style="display: inline-block;">
                        <label for="surname"> Last Name/Surname</label><br>
                        <input type="text" name = "" id="surname">
                    </div>
                    <div style="display: inline-block; padding-left: 300px;">
                        <label for="firstname" > First Name</label><br>
                        <input type="text" name = "" id="firstname" >
                    </div>
                    <div style="display: inline-block; padding-left: 300px;">
                        <label for="midname" > Middle Name</label><br>
                        <input type="text" name = "" id="midname" >
                    </div>
                    </div> 
            </td>
        </tr>
        <tr>
            <td></td>
            <td>
                <span>*</span>4. Select Parent name which is to be printed on the card<br>
                <label for ="par" style="color: blue;">(In case no option is provided then PAN card will be issued with Father's Name)</label>
            </td>
            <td>
                <label for="dad">Father's Name</label>
                <input type="radio" name=" " id="dad">
                <label for="mom" style="padding-left: 30px;">Mother's Name</label>
                <input type="radio" name=" " id="mom">
            </td>
        </tr>
        <tr>
            <td style="width:1% ;padding : 5px;"><input type="checkbox" name="" id=""></td>
            <td>
               <span>*</span>5. Date of Birth / Incorporation / Agreement / Partnership<br>
               or Trust Deed / Formation of Body of Individuals /<br>
               Association of Persons
            </td>
            <td>
                <label for = "dob" >MM DD YYYY</label><br>
                <input type="date" name ="" id="dob">
            </td>
        </tr>
        <tr>
            <td style="width:1% ;padding : 5px;"><input type="checkbox" name="" id=""></td>
            <td>
                <span>*</span>6. Gender
            </td>
            <td>
                <label for="male">Male</label>
                <input type="radio" name=" " id="male" >
                <label for="female" style="padding-left: 20px;">Female</label>
                <input type="radio" name=" " id="female">
                <label for="trans" style="padding-left: 20px;">TransGender</label>
                <input type="radio" name=" " id="trans">
            </td>
        </tr>
        <tr>
            <td style="width:1%; padding : 5px;"><input type="checkbox" name="" id=""></td>
            <td>
                7. Photo Mismatch
            </td>
        </tr>
    </tr>
    <tr>
        <td style="width:1%; padding : 5px;"><input type="checkbox" name="" id=""></td>
        <td>
            8. Signature Mismatch
        </td>
    </tr>
    <tr>
        <td style="width:1%; padding : 5px;"><input type="checkbox" name="" id=""></td>
        <td>
            <span>*</span>9. Address for Communication
        </td>
        <td>
            <label for="home">Residential</label>
            <input type="radio" name=" " id="home" >
            <label for="off" style="padding-left: 20px;">Office</label>
            <input type="radio" name=" " id="off">
        </td>
    </tr>
    <tr>
        <td></td>
        <td>
            <label for ="officename">Office Name <i>(to be filled only in case of Office Address)</i></label>
               
        </td>
        <td>
            <input type = "text" name =" " id="officename">
        </td>
    </tr>
    <tr>
        <td></td>
        <td>
            <label for ="address">Flat / Door / Block No.</label> 
        </td>
        <td>
            <input type = "text" name =" " id="address">
        </td>
    </tr>
    <tr>
        <td></td>
        <td>
            <label for ="area">Name of Premises / Building / Village</label> 
        </td>
        <td>
            <input type = "text" name =" " id="area">
        </td>
    </tr>
    <tr>
        <td></td>
        <td>
            <label for ="street">Road / Street / Lane /Post Office</label> 
        </td>
        <td>
            <input type = "text" name =" " id="street">
        </td>
    </tr>
    <tr>
        <td></td>
        <td>
            <label for ="taluk">Area / Taluk / Locality / Sub-Division </label> 
        </td>
        <td>
            <input type = "text" name =" " id="taluk">
        </td>
    </tr>
    <tr>
        <td></td>
        <td>
            <label for ="city">Town / City / District</label> 
        </td>
        <td>
            <input type = "text" name =" " id="city">
        </td>
    </tr>
    <tr>
        <td></td>
        <td>
            <label for ="state">State / Union Territory</label> 
        </td>
        <td>
            <input type ="text" name =" " id="State">
        </td>
    </tr>
    <tr>
        <td></td>
        <td>
            <label for ="pin">PIN <i>(indicating PIN is Mandatory)</i> </label> 
        </td>
        <td>
            <input type ="text" name =" " id="pin">
        </td>
    </tr>
    <tr>
        <td></td>
        <td>
            <label for ="country">Country</label> 
        </td>
        <td>
            <input type ="select" name =" " id="country">
        </td>
    </tr>
    <tr>
        <td></td>
        <td>
            <label for ="zip">Zip</label> 
        </td>
        <td>
            <input type ="text" name =" " id="zip">
        </td>
    </tr>
    <tr>
        <td style="width : 1px;padding : 5px;"><input type="checkbox" name= " " id=" "> </td>
        <td>
            10. If you desire to update your other address, give required details and submit proof of other address also.
        </td>
    </tr>
    <tr>
        <td style="width : 1px;padding : 5px;"><input type="checkbox" name= " " id=" "> </td>
        <td>
            <span>*</span> 11. Telephone Number<br>(Country code is compulsory)
        </td>
        </tr>


        
    </table>
</div>
