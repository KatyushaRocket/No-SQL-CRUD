# No-SQL-CRUD
Nama : Muh Alfiansyah Akbar
NIM : D0222326
#Create
db.users.insertOne({
  name: "Alice",
  age: 25,
  email: "alice@example.com"
});
#Read
db.users.find({ name: "Alice" });
#Update
db.users.updateOne(
  { name: "Alice" },
  { $set: { age: 26 } }
);
#delete
db.users.deleteOne({ name: "Alice" });
