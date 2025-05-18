
# Food Ordering Application 🍔📱

This is a simple **Food Ordering System** implemented using Python's socket programming over TCP. It demonstrates a basic **client-server architecture**, where the client can view a menu and place orders, and the server receives and processes the orders.

## 📌 Features

- Simple menu-driven interface for ordering food
- TCP-based client-server communication
- Menu selection and order confirmation
- Written in Python using socket programming

## 🛠 Technologies Used

- Python 3.x
- Socket Programming (TCP)

## 📁 File Structure

```

Food-Ordering-application/
│
├── CLIENT.PY      # Client-side script
├── SERVER.PY      # Server-side script
└── README.md      # Project documentation

````

## 🚀 How to Run

Follow these steps to get the application up and running on your local machine:

### 1. Clone the Repository

```bash
git clone https://github.com/Sachin8347/Food-Ordering-application.git
cd Food-Ordering-application
````

### 2. Run the Server

Open a terminal window and run:

```bash
python SERVER.PY
```

The server will start and wait for incoming connections on a specified port.

### 3. Run the Client

In a new terminal window (or on a different machine in the same network), run:

```bash
python CLIENT.PY
```

Follow the on-screen instructions to:

* View the menu
* Select food items
* Confirm the order

> ⚠️ Make sure the server is running **before** starting the client. Also, ensure the IP address and port in `CLIENT.PY` match those of the server.

## 📸 Sample Screenshots

> (You can add screenshots here for both client and server terminals.)

## ✨ Future Enhancements

* Add GUI using Tkinter or PyQt
* Store orders and menus using SQLite or MySQL
* Handle multiple clients with threading or multiprocessing
* Add user authentication and session tracking
* Add order history, cancelation, and feedback support

## 🙌 Contributing

Feel free to fork this repository, submit issues, and send pull requests to enhance the project!

## 📄 License

This project is licensed under the MIT License.

---

**Author:** [Sachin8347](https://github.com/Sachin8347)





