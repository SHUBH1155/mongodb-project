# mongodb-project
This project is based on designing a MongoDB database for the ** Zen Class Programme ** and writing queries to solve the given problem statements using ** MongoDB Compass **.
Problem Statements & Queries

$$ 1. Find all the topics and tasks which are taught in the month of October
- Query written using `taught_date` and `assigned_date`
- Date range: `01-10-2020` to `31-10-2020`

$$ 2. Find all the company drives between 15-Oct-2020 and 31-Oct-2020
- Filter based on `drive_date`

$$ 3. Find all the company drives and students who appeared for placement
- Uses `students_appeared` array

$$ 4. Find the number of problems solved by the user in Codekata
- Uses `problems_solved` field

$$ 5. Find all mentors with mentees count more than 15
- Filter using `mentees_count > 15`

$$ 6. Find number of users who are absent and task is not submitted between 15-Oct-2020 and 31-Oct-2020
- Uses `attendance.status = "absent"`
- Uses `tasks.submitted = false`
- Date range filter applied

Tools Used

- MongoDB
- MongoDB Compass
- Git & GitHub

 $$ -- Screenshots

All screenshots of collections and query results are available in the ** screenshots ** folder for verification.


$$ -- Conclusion

This project demonstrates:
- MongoDB database design
- Proper collection structure
- Date-based filtering
- Real-world query handling using MongoDB Compass
