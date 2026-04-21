curl -X POST "http://127.0.0.1:5000/addstudent" -H "Content-Type: application/json" -d "{\"name\":\"Alice\",\"rollno\":\"101\"}"
curl -X POST "http://127.0.0.1:5000/deletestudent" -H "Content-Type: application/json" -d "{\"id\":101}"
curl "http://127.0.0.1:5000/getstudents"