# js-lab-162
### Lab 162 ES6: ฟังก์ชันตรวจสอบอายุ
จงเขียนฟังก์ชันตรวจสอบอายุ โดยรับข้อมูล user ที่อยู่ใน object ที่มี keys เป็น firstName lastName และ age โดยถ้า user มีอายุมากกว่า 18 ให้แสดงผลเป็นการทักทายแล้วตามด้วยชื่อ-นามสกุล ในกรณีที่มีอายุน้อยกว่าหรือเท่ากับ 18 ให้แสดงผลว่า ไม่มีสิทธิ์เข้าใช้งาน (ใช้ destructuring)

```JavaScript
const user1 = { firstName: "John", lastName: "Doe", age: 20 };
checkAge(user1); // Hello, John Doe!

const user2 = { firstName: "Alice", lastName: "Smith", age: 17 };
checkAge(user2); // Access denied: You are not eligible to use this service.
```
