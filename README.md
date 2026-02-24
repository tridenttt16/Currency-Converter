# Currency-Converter
Here is the latest version of Currency convertor using java:


# 💱 Advanced Currency Converter (Java)

A professional **Currency Converter Desktop Application** built using **Java (Swing)** with real-time exchange rate support and clean architecture.

This project demonstrates strong understanding of:

* Object-Oriented Programming (OOP)
* REST API Integration
* JSON Parsing
* Java Swing GUI Development
* Exception Handling
* Design Patterns (Singleton)
* Localization using ResourceBundle


## 🚀 Features

* 🌍 Convert between multiple international currencies
* 🔄 Real-time exchange rate support (API-based)
* 🖥️ Responsive Swing-based GUI (LayoutManager implemented)
* 🌐 Localization support (multi-language ready)
* 🧠 Singleton pattern for window management
* 🔗 Clickable hyperlinks inside application
* 🛡️ Robust exception handling
* 📦 Clean modular structure


## 🛠️ Tech Stack

* Java (JDK 11+ recommended)
* Java Swing
* HttpClient / HttpURLConnection
* JSON Parsing (Gson / org.json)
* ResourceBundle (Localization)
* MVC-inspired structure

## 📂 Project Structure

```
CurrencyConverter/
│── src/
│   ├── currencyConverter/
│   │      ├── Main.java
│   │      ├── CurrencyService.java
│   │      ├── ApiClient.java
│   │      ├── AboutWindow.java
│   │      └── ConversionHistory.java
│   │
│   └── localization/
│          └── translation.properties
│
│── README.md
```

## ⚙️ How It Works

1. User selects:

   * Base Currency
   * Target Currency
   * Amount

2. Application fetches exchange rate from API.

3. JSON response is parsed.

4. Conversion formula applied:

```
Converted Amount = Amount × Exchange Rate
```

5. Result displayed in GUI.


## ▶️ How to Run

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/currency-converter-java.git
```

### 2️⃣ Open in IDE

Open with:

* IntelliJ IDEA
* Eclipse
* VS Code

### 3️⃣ Compile & Run

```bash
javac Main.java
java Main
```

If using external JSON library:

```bash
javac -cp ".;gson.jar" Main.java
java Main
```

## 🌐 API Integration

Example API format:

```
https://api.exchangerate-api.com/v4/latest/USD
```

You may need to:

* Add your API key
* Store it in configuration file
* Handle API exceptions



## 📸 Application Preview


------------------------------------
|        Currency Converter        |
------------------------------------
| Amount: [ 100 ]                  |
| From:   [ USD ▼ ]                |
| To:     [ INR ▼ ]                |
|                                  |
|        [ Convert ]               |
|                                  |
| Result: 8312.00 INR              |
------------------------------------




##  Concepts Demonstrated

* Clean UI using LayoutManager (no null layout)
* Event-driven programming
* HTTP communication
* JSON parsing
* Singleton design pattern
* Localization
* Error handling best practices


## 📜 License

GNU GPL v3.0


## 👩‍💻 Author

**Ikshita Bhatnagar**
Java Developer | Software Enthusiast
India 🇮🇳



