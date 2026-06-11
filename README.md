<!DOCTYPE html>
<html>

<head></head>

<body>
    <h1>Student Registration Form</h1>
    <form>
        <table border="2" align="center">
            <tr>
                <td><label for="sno">Student Number</label> </td>
                <td><input type="number" name="sno" placeholder="Enter Student Number"></td>
            </tr>
            <tr>
                <td><label>Student Name</label><br></td>
                <td><input type="text" name="Studentname" placeholder="Enter Student Name"><br><br></td>
            </tr>
            <tr>
                <td><label>Student Email</label><br></td>
                <td><input type="email" name="Email" placeholder="Enter gmail"><br></td>
            </tr>
        </table>
        <label for="Gender">Gender</label><br>
        <input type="radio" name="Gender" value="Male">Male
        <input type="radio" name="Gender" value="Female">Female
        <input type="radio" name="Gender" value="other">Other<br><br>
        <label for="qualification">Qualification</label><br><br>
        <input type="checkbox" name="10th" Value="10th">10th
        <input type="checkbox" name="Diploma" Value="Diploma">Diploma
        <input type="checkbox" name="B-tech" Value="B-tech">B-tech<br><br>
        <label for="Caste">Caste</label><br><br>
        <select name="Caste">
            <option value="General">General</option>
            <option value="OBC">OBC</option>
            <option value="SC">SC</option>
            <option value="ST">ST</option>
        </select><br><br>
        <label for="Address">Address</label><br>
        <textarea name="Address" rows="4" columns="50" placeholder="Address"></textarea><br><br>
        <input type="Submit" value="Submit">

    </form>
</body>

</html>
