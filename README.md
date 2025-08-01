# Bluetooth Attendance app
Our project is a Bluetooth attendance system that can be used to take attendance in classes instantly. It uses [Nearby Connections API](https://developers.google.com/nearby/connections/overview) to discover nearby devices and mark attendance on the database. The communication model used is an advertise-discover communication model in which the teacher acts as the advertiser and the students discover the advertiser, i.e the teacher. This is a 1 to N connection.

The teacher has to select the semester, subject and slot for which they are taking attendance and click the submit button. Now the device starts advertising. 
On the student's view they just click a button to start discovering. And once the faculty is detected, the data is verified, and the attendance is recorded.
The teacher can also export the attendance data for any date as a CSV file.
## Workflow
### Student Registration and login
<div>
  <img src="https://user-images.githubusercontent.com/74052417/230736620-a493c671-fa2d-4062-8296-150b9b3ae99d.jpg" alt="Registration page" width="200" height="450">
  <img src="https://user-images.githubusercontent.com/74052417/230736873-a1406d2c-a0fa-4f61-88c0-1703e3b37b39.jpg" alt="Login" width="200" height="450">
</div>

### Student / Discoverer
<div>
  <img src="https://user-images.githubusercontent.com/74052417/230737022-a9a67eac-340f-4b2c-a753-dd2bc2ef96c2.jpg" alt="Bluetooth" width="200" height="450">
  <img src="https://user-images.githubusercontent.com/74052417/230737028-adacf3c9-0203-4704-97f6-4e50ea951e2c.jpg" alt="Discovering" width="200" height="450">
  <img src="https://user-images.githubusercontent.com/74052417/230737032-c8c3f53b-cbcc-46cc-a824-9eabd52a7e8e.jpg" alt="Attendance recorded" width="200" height="450">
</div>
