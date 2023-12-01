# open-library.com.np.


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Library Management System</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #2c3e50;
            color: #ecf0f1;
            text-align: center;
            padding: 1em;
        }

        section {
            margin: 20px;
        }

        form {
            max-width: 400px;
            margin: 0 auto;
            background-color: #ecf0f1;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        label {
            display: block;
            margin-bottom: 8px;
            color: #333;
        }

        input, button {
            width: 100%;
            padding: 10px;
            margin-bottom: 16px;
            box-sizing: border-box;
            border: 1px solid #bdc3c7;
            border-radius: 4px;
        }

        button {
            background-color: #3498db;
            color: #fff;
            cursor: pointer;
        }

        button:hover {
            background-color: #2980b9;
        }

        .book-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .book {
            max-width: 200px;
            margin: 16px;
            padding: 16px;
            background-color: #ecf0f1;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s ease;
        }

        .book:hover {
            transform: scale(1.05);
        }

        .book img {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
        }

        h3 {
            margin-top: 0;
            color: #3498db;
        }

        p {
            margin: 8px 0;
            color: #7f8c8d;
        }
    </style>
</head>
<body>

    <header>
        <h1>Library Management System</h1>
    </header>

    <section>
        <form>
            <label for="bookTitle">Book Title:</label>
            <input type="text" id="bookTitle" name="bookTitle" required>

            <label for="author">Author:</label>
            <input type="text" id="author" name="author" required>

            <label for="isbn">ISBN:</label>
            <input type="text" id="isbn" name="isbn" required>

            <button type="submit">Add Book</button>
        </form>
    </section>

    <section class="book-container">
        <div class="book">
            <img src="book1.jpg" alt="Book 1">
            <h3>Book Title 1</h3>
            <p>Author: Author Name</p>
            <p>ISBN: 1234567890</p>
        </div>

        <div class="book">
            <img src="book2.jpg" alt="Book 2">
            <h3>Book Title 2</h3>
            <p>Author: Author Name</p>
            <p>ISBN: 2345678901</p>
        </div>

        <!-- Add more books as needed -->
    </section>

</body>
</html>
