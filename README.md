<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form>
        <fieldset>
            <h1>Registration Form</h1>
            <fieldset>
                <legend>User personal information</legend>
                <label for="name">Enter your full name</label><br>
                <input type="text" id="name" name="name"><br>
                <label for="email">Enter your email</label><br>
                <input type="email" id="email" name="email"><br>
                <label for="password">Enter your password</label><br>
                <input type="password" id="password" name="password"><br>
                <label for="password">Confirm your password</label><br>
                <input type="password" id="password" name="password">
                <div><br>
                    <label for="continent">Choose your continent</label><br>
                    <select name="continent" id="continent">
                        <option value="asia">Asia</option>
                        <option value="africa">Africa</option>
                        <option value="europe">Europe</option>
                        <option value="north america">North America</option>
                        <option value="south america">South America</option>
                        <option value="australia">Australia</option>
                        <option value="antarctica">Antarctica</option>
                    </select>
                </div>
                <div><br>
                    <label for="interest">Choose your interest</label>
                    <input type="checkbox" id="music" name="music" value="music">
                    <label for="music">Music</label>
                    <input type="checkbox" id="dance" name="dance" value="dance">
                    <label for="dance">Dance</label>
                    <input type="checkbox" id="game" name="game" value="game">
                    <label for="game">Game</label>
                    <input type="checkbox" id="reading" name="reading" value="reading">
                    <label for="reading">Literature</label>
                    <input type="checkbox" id="others" name="others" value="others">
                    <label for="others">Others</label><br>
                </div>
                <div><br>
                    <label for="gender">Enter your gender</label><br>
                    <input type="radio" id="gender" name="gender" value="male">Male <br>
                    <input type="radio" id="gender" name="gender" value="female">Female <br>
                    <input type="radio" id="gender" name="gender" value="other">Other <br>
                </div>
                <div><br>
                    <label for="textarea">Enter your Address</label><br>
                    <textarea id="textarea" cols="16" rows="3"></textarea><br>
                </div>
                <div>
                    <input type="submit" value="Sign-up">
                </div>
            </fieldset>
        </fieldset>
        
        
    </form>
    
</body>
</html>
