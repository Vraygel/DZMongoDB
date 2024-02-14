# DZMongoDB
DZMongoDB

db.books.insertMany([
  {
    title: "Книга 1",
    description: "Описание книги 1",
    authors: "Автор книги 1"
  },
  {
    title: "Книга 2",
    description: "Описание книги 2",
    authors: "Автор 2"
  }
])


db.books.find({ title: "Книга 1" })



db.books.updateOne(
  { _id: ObjectId("id_Первой_книги") },
  { $set: { description: "Новое описание", authors: "Новый автор" } }
)

