<!DOCTYPE html>
<html lang="en">
  
<head>
    <title>
        Build a Survey Form
    </title>
 
    <style>
 
        /* Styling the Body element i.e. Color,
        Font, Alignment */
        body {
            font-family: Arial black;
            text-align: center;
        }
 
        /* Styling the Form (Color, Padding, Shadow) */
        form {
            background-color: #fff;
            max-width: 500px;
            margin: 50px auto;
            padding: 30px 20px;
           box-shadow: 2px 5px 10px rgba(203, 187, 187, 0.5);
        }
 
        /* Styling form-control Class */
        .form-control {
            text-align: left;
            margin-bottom: 25px;
        }
 
        /* Styling form-control Label */
        .form-control label {
            display: block;
            margin-bottom: 10px;
        }
 
        
        .form-control input,
        .form-control select,
        .form-control textarea {
            border: 1px solid #777;
            border-radius: 2px;
            font-family: inherit;
            padding: 10px;
            display: block;
            width: 95%;
        } 
 
        /*Styling form-control Radio
        button and Checkbox */
        .form-control input[type="radio"],
        .form-control input[type="checkbox"] {
            display: inline-block;
            width: auto;
        }
        button {
            background-color: #05c46b;
            border: 1px solid #777;
            border-radius: 2px;
            font-family: inherit;
            font-size: 21px;
            display: block;
            width: 100%;
            margin-top: 50px;
            margin-bottom: 20px;
        }
    </style>
</head>
  
<body>
    <h1>Intership YOSHOPS Survey Form</h1>
  
    <!-- Create Form -->
    <form id="form">
        <div class="form-control">
            <label for="name" id="label-name">
                1. Name
            </label>
            <input type="text"
                   id="name"
                   placeholder="Enter your name" />
        </div>
  
        <div class="form-control">
            <label for="location" id="label-location">
                2. location
            </label>
            <input type="text"
                   id="location"
                   placeholder="Enter your location, city" />
        </div>
  
        
        <div class="form-control">
            <label for="role" id="label-role">
                3. What class do you study in ?
            </label>
             
            <!-- Dropdown options -->
            <select name="role" id="role">
                <option value="lkg to std5">LKG to STD 5</option>
                <option value="std 6 to std 10">STD 6 to STD 10</option>
                <option value="11th and 12th JEE preparation">11th and 12th JEE preparation </option>
                <option value="Graduation">Graduation</option>
                <option value="Post Graduation">Post Graduation</option>
            </select>
        </div>
  
        <div class="form-control">
            <label>
                4. Which Price range for Online Tution for LKG to PG Monthly Fees You like must
            </label>
 
            <!-- Input Type Radio Button -->
            <label for="5k to 10k">
                <input type="radio"
                       id="5k to 10k"
                       name="range of fee">5000 to 10000</input>
            </label>
            <label for="10k to 20k">
                <input type="radio"
                       id="r10k to 20k"
                       name="range of fee">10000 to 20000</input>
            </label>
            <label for="20k+">
                <input type="radio"
                       id="20k+"
                       name="range of fee">20000+</input>
            </label>
        </div>
        <div class="form-control">
            <label>
                5. Laptop and Mobile which Price range you like most
            </label>
 
            <!-- Input Type Radio Button -->
            <label for="recommed-1">
                <input type="radio"
                       name="range of price">5000 to 15000</input>
            </label>
            <label for="recommed-2">
                <input type="radio"
                       name="range of price">15000 to 30000</input>
            </label>
            <label for="recommed-3">
                <input type="radio"
                       name="range of price">31000 to 50000</input>
            </label>
            <label for="recommed-3">
                <input type="radio"
                       name="range of price">51000 to 100000</input>
            </label>
        </div>
        <div class="form-control">
            <label>
               6. Which is your Favourite food biryani essay?
            </label>
 
            <!-- Input Type Radio Button -->
            <label for="recommed-1">
                <input type="radio"
                       name="recommed">Veg biryani</input>
            </label>
            <label for="recommed-2">
                <input type="radio"
                       name="recommed">chicken biryani</input>
            </label>
            <label for="recommed-3">
                <input type="radio"
                       name="recommed">Mutton biryani</input>
            </label>
            <label for="recommed-3">
                <input type="radio"
                       name="recommed">others</input>
            </label>
        </div>
        <div class="form-control">
            <label for="role" id="label-price">
                7. What is Price Rang for 1kg Biryani( 2 Person Eat) you like must
            </label>
             
            <!-- Dropdown options -->
            <select name="role" id="role">
                <option value="99">99</option>
                <option value="149">149</option>
                <option value="199">199</option>
                <option value="249">249</option>
                </select>
        </div>
        <div class="form-control">
            <label>
                8. Which Financial products you like most
            </label>
 
            <!-- Input Type Radio Button -->
            <label for="recommed-1">
                <input type="checkbox"
                       name="recommed">Mutual Fund SIP (ROI 12%)-1yr
                    </input>
            </label>
            <label for="recommed-2">
                <input type="checkbox"
                       name="recommed">Company Stock IPO(ROI 15%)-1yr
                    </input>
            </label>
            <label for="recommed-3">
                <input type="checkbox"
                       name="recommed">Yoshops Franchise Investment(ROI 16%)-1yr
                    </input>
            </label>
            <label for="recommed-3">
                <input type="checkbox"
                       name="recommed">Bank FD(Rate of Interest- 7%)-1yr
                    </input>
            </label>
        </div>
        <div class="form-control">
            <label>
                9. Are you interested in Yoshops Finance  Product.
            </label>
 
            <!-- Input Type Radio Button -->
            <label for="yes">
                <input type="radio"
                       id="yes"
                       name="yes">Yes</input>
            </label>
            <label for="no">
                <input type="radio"
                       id="no"
                       name="No">No</input>
            </label>
            <label for="May be">
                <input type="radio"
                       id="May be"
                       name="May be">May be</input>
            </label>
        </div>
        <div class="form-control">
            <label for="internship name" id="label-internship">
                10. Which Unpaid Training Internship are you interested for six Months ?
            </label>
            <input type="text"
                   id="internship" />
        </div>
        <div class="form-control">
            <label>
                11. How much you pay training fees per month for online training with internship?
            </label>
 
            <!-- Input Type Radio Button -->
            <label for="500">
                <input type="radio"
                       id="500"
                       name="500">500</input>
            </label>
            <label for="1000">
                <input type="radio"
                       id="1000"
                       name="1000">1000</input>
            </label>
            <label for="1500">
                <input type="radio"
                       id="1500"
                       name="1500">1500</input>
            </label>
            <label for="above 1500">
                <input type="radio"
                       id="above 1500"
                       name="above 1500">above 1500</input>
            </label>
        </div>
        <div class="form-control">
            <label for="suggesion" id="label-suggesion">
                12. Any IDEA or Suggestions for Yoshops Startup
            </label>
            <input type="text"
                   id="suggesion" />
        </div>
        <div class="form-control">
            <label>
                13. Do you want to get a free Gift and Refferal Amount Rs.100 by reffer friends to Training Internship and Online Tituation
            </label>
 
            <!-- Input Type Radio Button -->
            <label for="yes">
                <input type="radio"
                       id="yes"
                       name="yes">Yes</input>
            </label>
            <label for="no">
                <input type="radio"
                       id="no"
                       name="No">No</input>
            </label>
        </div>
        <div class="form-control">
            <label for="rating" id="label-rating">
                14. How would you rate Yoshops Training Internship and Products & Service
            </label>
             
            <!-- Dropdown options -->
            <select name="rating" id="rating">
                <option value="1">1</option>
                <option value="2">2</option>
                <option value="3">3</option>
                <option value="4">4</option>
                <option value="5">5</option>
                </select>
        </div>
  
        <!-- Multi-line Text Input Control -->
        <button type="submit" value="submit">
            Submit
        </button>
    </form>
</body>
  
</html>
