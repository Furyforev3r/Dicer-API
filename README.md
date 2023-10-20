![Dice Roller API](https://github.com/Furyforev3r/Dice-Roller-API-ExpressJS/assets/88341564/a172c9ac-47fd-46fb-ac93-fde99097416f)
# 🎲 | Dice-Roller-API-ExpressJS
**A dice rolling API done in Typescript using ExpressJS!**
**Running on: https://dice-roller-api-express-js.vercel.app/**
## :grey_question: How does it work?
**The API operates on the "REST API" model, returning a JSON as an HTTP GET response.**
## :desktop_computer: How to use?
**From GET requests with the parameter of the dice rolling operation, you will receive a JSON with the information generated from the parameter.**
**Example:** 
```python
requests.get("https://dice-roller-api-express-js.vercel.app/10d20+15")
```
# 📥 Installation
**Clone the repository:**
```bash
git clone https://github.com/Furyforev3r/Dice-Roller-API-ExpressJS.git
```
**Install dependencies:**
```bash
npm install
```
# 🖥️ How to Run
**Run the command:**
```bash
npm start
```
 **Acess the application in the browser: `http://localhost:PORT` or `http://localhost:3000`**
## 🗃️ **What can I put in the main parameter?**
**Common dice operations (Example: 1d20) and sum modifiers in operations (Example: 1d20+15).**
**It is also possible to roll several separate dice at once (Example: 1d20+10d6+15+15+1d100).**
