# 🌌 Solar System Stock Index
A fun Java web application built with Maven and deployed as a WAR file on Apache Tomcat.
This app simulates a stock ticker where planetary systems are represented as stock indices.

---

# 🚀 Features
- 5 Planetary Indices: Earth, Mars, Venus, Jupiter, Saturn
- Stock names inspired by moons, asteroids, and celestial objects
- Random stock index movement (up/down every refresh)
- Color-coded ticker: 🟢 Green for gains, 🔴 Red for losses
- Auto-refresh every 3 seconds for a real-time feel
- Interactive buttons: click on a planet to view its stock index
- Date & Time display
- Marquee ticker at the bottom like real stock exchanges
- Session GUID stored in cookies – persists for the user session (future-ready for Kubernetes/replica sets)

---

# ⚙️ How to Build & Run
Clone the repo
```sh
git clone https://github.com/annkur-sharma-devops/solar-system-stock-index-1.git
cd solar-system-stock-index-1
```

Build with Maven
```sh
mvn clean package
```

---

# Deploy WAR to Tomcat
Copy target/solar-system-stock-index.war to Tomcat’s webapps/ folder

---

# Start Tomcat
Access at: http://localhost:8080/solar-system-stock-index/

Note: Update port to Apache Tomcat port, if it is different than 8080.

---

# 🌍 Future Roadmap
- Kubernetes deployment with GUID tracking across replicas
- CI/CD pipeline (Jenkins / GitHub Actions)
- REST APIs for stock data
- Containerization with Docker